+++
date = '2021-11-01T12:00:00Z'
draft = false
title = 'Incident Management: Turning Problems into Improvements'
readingTime = '7 min'
+++

# Incident Management: Turning Problems into Improvements

**Published: November 2021 | Reading Time: 7 minutes**

---

## The Wednesday That Kept Happening

It was November 2021 at Exclusive IT Solutions. We had a recurring problem.

Every Tuesday at approximately 10:15 AM, our payment processing system would slow down. Transactions that should take 2 seconds were taking 30 seconds.

We responded every time:
- Investigated the issue
- Restarted the payment gateway service
- Cleared the cache
- Confirmed everything was working again

We were good at responding. We were fast. We were effective.

But here's the thing: **it happened every Tuesday. Same problem. Same response. Fixing it over and over.**

After 8 weeks of this, I realized something: we weren't managing incidents. We were just putting out fires.

## The Metaphor: The Firefighter vs. The Fire Prevention Officer

Let me explain with a metaphor that transformed my approach to incidents.

**Incident response is like firefighting.** Something is burning. You rush in, you put out the fire, you save what you can. It's heroic, it's necessary, and everyone appreciates it.

**But what if the same fire keeps starting in the same place every week?**

A firefighter would keep putting it out every time. They'd get faster at it. They'd be efficient. They'd be celebrated for their quick response.

But a fire prevention officer would ask: *Why is this fire starting every week? What's causing it? How do we prevent it?*

We were being firefighters—putting out the same fire every week. We needed to become fire prevention officers—finding and eliminating the cause.

## The Struggle: The "We're Good at Responding" Trap

I'll be honest: it felt good to be good at incident response.

When the payment system slowed down, I would jump into action. I'd investigate. I'd diagnose. I'd fix. Stakeholders would thank me.

I felt valuable. I felt skilled. I felt like I was making a difference.

Then I looked at the data: 8 weeks of the same incident. 8 weeks of the same response. 8 weeks of the same fix.

We weren't making a difference. We were just being efficient at the same thing over and over.

## The Transformation: From Incident Management to Problem Management

I implemented a shift in our approach. We didn't stop responding to incidents—we added problem management.

**Incident management: Fix the problem**
**Problem management: Find and eliminate the cause**

### The "Root Cause" Framework

I developed a framework that ensured every incident led to a problem investigation.

#### Principle 1: Not All Incidents Are Created Equal
**Level 1 Incidents (Recurring or High Impact):** Trigger full problem management investigation
**Level 2 Incidents (Unique or Low Impact):** Document and monitor, no full investigation needed

**Why:** You can't investigate everything. Focus on what matters.

#### Principle 2: Every Incident Gets Documented
Every incident, regardless of level, gets documented in a standard format:

- What happened?
- When did it happen?
- Who was affected?
- What did we do to fix it?
- What was the immediate cause?

**Why:** Data is your friend. Without it, you can't see patterns.

#### Principle 3: Recurring Incidents Trigger Investigation
If an incident happens more than once, it triggers a full problem management investigation:

- What is the root cause?
- Why didn't we find it before?
- What prevents this from happening again?
- How do we verify the fix works?

**Why:** Recurring incidents are symptoms, not the problem. Find the problem, eliminate the symptom.

#### Principle 4: Investigation Happens During, Not After, Incidents
Don't wait for things to calm down to investigate. Investigate while the incident is happening or immediately after.

**Why:** Evidence is fresh. People remember details. The cause is still visible.

#### Principle 5: Every Problem Needs a Verified Fix
Finding the cause isn't enough. You need to implement a fix and verify it works.

**Why:** You don't want to "fix" something only to discover it wasn't the real fix.

## The Real-World Example: The Tuesday Payment Slowdown

Let me share how this framework transformed our approach to the recurring payment system slowdown.

### Week 1: First Incident
**What happened:** Payment system slowed at 10:15 AM on Tuesday
**Who was affected:** 250 customers trying to make payments
**What we did:** Restarted payment gateway service, cleared cache
**Fix confirmed:** System working normally
**Documentation:** Created

### Week 2: Second Incident
**What happened:** Payment system slowed at 10:18 AM on Tuesday
**Who was affected:** 280 customers trying to make payments
**What we did:** Restarted payment gateway service, cleared cache
**Fix confirmed:** System working normally
**Documentation:** Updated (noted pattern: Tuesday mornings)

### Week 3: Third Incident
**What happened:** Payment system slowed at 10:12 AM on Tuesday
**Who was affected:** 310 customers trying to make payments
**What we did:** Restarted payment gateway service, cleared cache
**Fix confirmed:** System working normally
**Documentation:** Updated (noted recurrence pattern - trigger problem management)

### Week 4: Problem Management Investigation
**Root Cause Investigation:**
- Why Tuesday mornings? Checked scheduled processes. Found: Weekly customer report generation runs at 10:00 AM on Tuesdays.
- Why does report generation slow payments? Found: Report generation queries the same customer tables as payment processing.
- Why does this cause slowdown? Found: Report generation queries are not optimized and lock tables, blocking payment queries.

**Root Cause:** Weekly report generation at 10:00 AM Tuesdays locks customer tables, blocking payment queries.

**Why didn't we find this before?**
- Incidents were always responded to by fixing symptoms (restart service), not investigating cause
- Reports and payments were managed by different teams, so the connection wasn't obvious

**Fix Implemented:**
1. Optimized report generation queries (added indexes)
2. Changed report generation time to 2:00 AM (off-peak)
3. Implemented table partitioning so reports and payments query different partitions

**Fix Verified:**
- Week 5: No payment slowdown
- Week 6: No payment slowdown
- Week 7: No payment slowdown

## The Results: Measurable Impact

### Incident Volume
**Before problem management:** 3 incidents per week (average)
**After problem management:** 1 incident per week (average)
**Reduction:** 67% fewer incidents

### Time Spent on Incidents
**Before problem management:** 12 hours per week (responding to the same incident repeatedly)
**After problem management:** 3 hours per week (responding to unique incidents)
**Reduction:** 75% less time spent on incidents

### Customer Impact
**Before problem management:** 280 customers affected per week (average)
**After problem management:** 95 customers affected per week (average)
**Reduction:** 66% fewer customers affected

### Team Effectiveness
**Before problem management:** Firefighting—responding to the same problems
**After problem management:** Problem prevention—eliminating causes of problems

## The Metaphor: The House Repairs

I like to explain this with another metaphor:

**Imagine you have a leaky pipe.**

Every Tuesday, it leaks. You clean up the water. You patch the pipe. You feel good about fixing it.

Next Tuesday, it leaks again. You clean up the water. You patch the pipe. You're getting faster at patching. You feel accomplished.

But the pipe is still leaking. You're just getting better at cleaning up the same mess.

**Incident response is cleaning up the water.**
**Problem management is fixing the pipe.**

You need both. Sometimes you need to clean up water (respond to emergencies). But if you never fix the pipe, you'll just keep cleaning up water forever.

## The Framework: Implementing Problem Management

If you want to shift from incident management to incident + problem management:

### Step 1: Document Every Incident
Create a standard template. Use it every time.

### Step 2: Track Patterns
Review incidents monthly. Look for:
- Same problem happening repeatedly
- Same systems involved
- Same times/days
- Similar root causes

### Step 3: Trigger Investigations
For recurring incidents, trigger full problem management:
- What is the root cause?
- Why didn't we prevent this?
- What prevents recurrence?

### Step 4: Implement and Verify Fixes
Don't just propose a fix. Implement it and verify it works.

### Step 5: Close the Loop
Every problem needs a documented resolution:
- Root cause identified
- Fix implemented
- Fix verified
- Lessons learned documented

## Common Mistakes to Avoid

### Mistake 1: Confusing Incidents with Problems
**The Problem:** Treating the symptom (incident) as the problem

**The Fix:** The incident is the symptom. The problem is the cause. Fix the problem, eliminate the incident.

### Mistake 2: Never Investigating Root Causes
**The Problem:** Fixing incidents without understanding why they happened

**The Fix:** Every recurring incident gets a root cause investigation.

### Mistake 3: Implementing Fixes Without Verification
**The Problem:** "We fixed it" but it happens again

**The Fix:** Verify fixes. If it happens again, you didn't fix the real cause.

### Mistake 4: Not Sharing Learnings
**The Problem:** Each team solves their own problems, nobody learns from anyone else

**The Fix:** Document and share problem resolutions. Learn from each other.

### Mistake 5: Treating Problem Management as Optional
**The Problem:** We're too busy responding to incidents to investigate problems

**The Fix:** Problem management reduces incident volume long-term. It's not optional, it's essential.

## The Hard Truth

The best incident management is incident + problem management.

I've seen teams that are incredible at responding to incidents. They're fast, they're skilled, they're heroic. But they keep responding to the same problems over and over.

I've seen teams that are good at responding and excellent at problem management. Over time, they have fewer incidents to respond to. Their time shifts from firefighting to improving systems.

**Firefighting feels heroic. Fire prevention feels boring. But fire prevention is what makes a real difference.**

## A Framework for Your Team

If you're implementing this approach:

### Week 1: Start Documenting Every Incident
Use a standard template. Make it non-negotiable.

### Week 2-3: Track Patterns
Review incident logs weekly. Look for recurring problems.

### Week 4: Trigger First Problem Investigation
Pick the most impactful recurring incident. Investigate fully.

### Week 5-6: Implement and Verify Fix
Don't just identify the problem. Fix it and verify the fix works.

### Week 7+: Scale the Approach
Make problem management standard for all recurring incidents.

## The Inspiration

After implementing problem management, our team lead came to me.

"You know what I realized?" she said. "We used to feel like firefighters—always rushing to put out fires. Now we feel like engineers—preventing fires from starting."

That's exactly right.

Firefighters are essential. But engineers who prevent fires are even more valuable.

**Incident management is necessary. Problem management is transformative.**

---

## Quick Incident Documentation Template

```
INCIDENT REPORT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

INCIDENT DETAILS
Date/Time: ________________________
Reporter: ________________________
Severity: ___ / 10
Systems affected: ________________________

INCIDENT DESCRIPTION
What happened?
___________________________________________________________________________

Who was affected?
___________________________________________________________________________

What was the immediate impact?
___________________________________________________________________________

RESPONSE ACTIONS
What did we do to resolve?
___________________________________________________________________________

When was service restored?
___________________________________________________________________________

ROOT CAUSE (if identified)
What caused this incident?
___________________________________________________________________________

PATTERN DETECTION
Has this happened before? [ ] Yes [ ] No
If yes, when? ________________________

PROBLEM MANAGEMENT
[ ] Trigger full investigation? [ ] No investigation needed (explain why)
___________________________________________________________________________

LESSONS LEARNED
What should we do differently?
___________________________________________________________________________

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

**What's your approach to incidents? Do you just respond, or do you also solve problems?**

*#IncidentManagement #ProblemManagement #ContinuousImprovement #ITSupport #OperationalExcellence*
