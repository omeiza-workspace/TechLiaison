# Requirements Gathering: A Simple Checklist for Non-Technical Stakeholders

**Published: October 2017 | Reading Time: 6 minutes**

---

## The Meeting That Went Nowhere

It was 2017. I was 6 months into my role at i4cus Nigeria Limited, working on a hospital management system project.

I sat across from Dr. Adebayo, the hospital's chief medical officer. We were gathering requirements for the new patient records system.

"What do you need this system to do?" I asked enthusiastically.

Dr. Adebayo looked thoughtful. "Well, it needs to... you know... handle patient information. And... um... make it easy to find records. And... maybe... track medications?"

I waited for more specific details. Nothing came.

I tried again. "What about patient registration? How should that work?"

He hesitated. "The current way works fine. So... maybe the same? But better?"

Two hours later, we had a long list of vague "needs":
- Better interface
- Faster searches
- Easier data entry
- More secure
- Mobile access

None of this was actionable. None of this would guide development. None of this would ensure we built the right thing.

**We had requirements, but we didn't have requirements.**

## The Problem: Technical and Non-Technical Minds Think Differently

I realized something fundamental: technical people and non-technical stakeholders speak different languages.

### How Technical People Think
When I think about requirements, I think about:
- Data structures and relationships
- Workflow steps and logic
- User roles and permissions
- Security and compliance requirements
- Integration points and APIs

I think in specifics. I think in actionable details.

### How Non-Technical Stakeholders Think
When Dr. Adebayo thought about requirements, he thought about:
- Patient safety and quality of care
- Frustrations with current systems
- Hopes for better outcomes
- Fears about learning new technology
- Worries about implementation disrupting care

He thought about outcomes, feelings, and experiences. He didn't naturally think in technical details.

**Neither way of thinking is wrong. But you can't translate between them without a framework.**

## The Struggle: Finding the Right Questions

I'll be honest: I struggled with this. I wanted Dr. Adebayo to speak technical language. I wanted him to say "I need a many-to-many relationship between patients and conditions with proper foreign key constraints."

But that's unfair. That's like asking me to describe a surgical procedure with medical precision.

I needed to learn to ask the right questions—questions that would lead to answers I could translate into technical requirements.

## The Breakthrough: A Simple Checklist

After several frustrating meetings, I developed a checklist. Not for me—for the stakeholders.

I realized that if I gave stakeholders the right questions to consider beforehand, they could prepare meaningful requirements. They just needed the framework to think in that way.

Here's the checklist I created:

---

## The Requirements Checklist

### Section 1: The People (Who's Using This?)

**Question 1: Who will use this system?**
- Not job titles—actual people. "Dr. Adebayo, Nurse Chioma, Receptionist Fatima"
- Why it matters: Different users have different needs and skill levels

**Question 2: What does each person do today?**
- Walk me through their typical day
- What systems do they use?
- What takes longest? What's most frustrating?
- Why it matters: You're capturing current workflows and pain points

**Question 3: What would make each person's day better?**
- If they could change one thing, what would it be?
- What would make them smile when they log in?
- Why it matters: This is your "delight" requirements—what makes system loved, not just used

### Section 2: The Process (How Does Work Actually Get Done?)

**Question 4: Walk me through a complete process step-by-step**
- Start to finish. "A patient arrives at reception. Then what happens?"
- Don't describe how it SHOULD happen. Describe how it DOES happen.
- Why it matters: You capture actual workflows, not idealized ones

**Question 5: What goes wrong today?**
- What mistakes happen frequently?
- What gets forgotten or missed?
- What requires workarounds or manual fixes?
- Why it matters: Mistakes reveal where systems need safeguards

**Question 6: What would make this process perfect?**
- In a perfect world, how would this work?
- What would eliminate the most common problems?
- Why it matters: This is your vision—where you want to get to

### Section 3: The Data (What Information Matters?)

**Question 7: What information do you need to do your job?**
- What data do you look at every day?
- What data can you never find when you need it?
- What data do you have to ask other people for?
- Why it matters: This tells you what data to prioritize capturing and displaying

**Question 8: What information do you need to share?**
- Who needs to see what you're working on?
- What reports do you generate?
- What data do others need from you?
- Why it matters: This reveals collaboration and reporting requirements

**Question 9: What would be catastrophic to lose or get wrong?**
- What data accuracy is critical?
- What information must never be deleted or corrupted?
- Why it matters: This is your critical data—where you need redundancy, validation, and security

### Section 4: The Constraints (What Can't Change?)

**Question 10: What can we NOT change?**
- Are there regulatory requirements you must follow?
- Are there systems you must integrate with that can't be modified?
- Are there processes that are legally or contractually fixed?
- Why it matters: Constraints define your boundaries—you can innovate within them, not outside them

**Question 11: What resources do we have?**
- How much time can people dedicate to learning the new system?
- What devices do they have (phones, tablets, computers)?
- What's their technical comfort level?
- Why it matters: This tells you how complex your system can be and what training you'll need

**Question 12: What's the timeline?**
- When does this need to be implemented?
- Are there specific dates or deadlines we must meet?
- What would happen if we miss the deadline?
- Why it matters: This tells you whether to build everything at once or in phases

### Section 5: The Success Measures (How Will We Know It Works?)

**Question 13: What does success look like?**
- How will you know this system is better than what you have now?
- What will people say when it's working well?
- Why it matters: This gives you measurable outcomes, not just deliverables

**Question 14: What would make you say "we should have stayed with the old system"?**
- What's the one thing that would make this a failure?
- What are you most worried about?
- Why it matters: This identifies your biggest risks—you need to address these

---

## The Transformation: Using the Checklist

I gave this checklist to Dr. Adebayo and his team a week before our next meeting. I told them: "You don't need to answer every question perfectly. Just think about them. Write down whatever comes to mind."

The next meeting was completely different.

### Before the Checklist
- Vague "needs" and "wants"
- No specific details
- No clear priorities
- Two hours of circular conversation

### After the Checklist
- Specific workflows described
- Pain points identified
- Success measures defined
- One hour of productive conversation

Dr. Adebayo came prepared. He had thought through questions 1-6 for the morning clinic workflow. He realized that the biggest pain point wasn't the patient record system—it was that patients waited 45 minutes for labs.

"The patient record system isn't the problem," he said. "The problem is that we don't know when lab results are ready, so patients just wait. If the new system could notify us when results are ready, patients could leave and come back."

That's a specific, actionable requirement we never would have discovered without the checklist.

## Real Results: What Changed

### Project Timeline
**Before:** Estimated 6 months, but with unclear requirements, likely to take 9-12 months with rework

**After:** Delivered in 6.5 months, with minimal rework because we built the right thing

### Budget
**Before:** Budget included 20% contingency for "unknown requirements"

**After:** Came in 5% under budget because we identified requirements upfront

### Stakeholder Satisfaction
**Before:** Stakeholders skeptical, uncertain about what they'd get

**After:** Stakeholders enthusiastic, felt heard and understood

### User Adoption
**Before:** Expected 60% adoption rate (typical for healthcare systems)

**After:** Achieved 89% adoption in first 3 months

## Why This Checklist Works

### 1. It Gives Stakeholders a Framework
Non-technical stakeholders don't naturally think in requirements. The checklist gives them a structure to organize their thoughts.

### 2. It Focuses on the Right Things
The checklist doesn't ask about features or technology. It asks about people, processes, and outcomes. That's what matters.

### 3. It Prepares Stakeholders
When stakeholders have time to think through questions beforehand, meetings are productive instead of exploratory.

### 4. It Captures Hidden Requirements
Questions like "what goes wrong today?" and "what workarounds do you use?" reveal requirements that would never be stated in traditional requirements gathering.

### 5. It Sets Success Criteria
When stakeholders define what success looks like upfront, there's no ambiguity about whether project delivered.

## Common Mistakes (And How to Avoid Them)

### Mistake 1: Rushing Through the Checklist
**The Problem:** Stakeholders fill it out in 10 minutes, giving minimal effort.

**The Fix:** Give them at least a week. Emphasize that quality of thought matters more than completeness.

### Mistake 2: Treating It as a Form, Not a Guide
**The Problem:** Stakeholders treat it like paperwork to complete, not thinking to guide discussion.

**The Fix:** Use the questions as discussion prompts, not just data collection. "Tell me more about question 4" not just reading their answer.

### Mistake 3: Ignoring Emotional Responses
**The Problem:** Stakeholders say things like "I'm worried about..." or "I'm afraid that..." and you focus on facts.

**The Fix:** Emotions reveal real concerns. "What are you most worried about?" is often the most important question on the checklist.

### Mistake 4: Not Updating as You Learn
**The Problem:** You gather initial answers and never revisit them as you learn more.

**The Fix:** Revisit checklist throughout project. Requirements change. Success measures evolve.

## A Success Story: Healthcare Records System

Let me share how this checklist transformed our hospital management system project:

### Question 4 Revealed the Real Problem
**Question:** Walk me through patient registration.

**Answer:** "Patient arrives, receptionist enters their details. Then they wait. Then they see a doctor. Then doctor sends them to lab. Then they wait for results. Then doctor prescribes medication. Then they wait at pharmacy."

**Hidden Requirement Discovered:** The system wasn't just about recording information—it was about managing patient flow and reducing waiting times.

### Question 5 Revealed Critical Needs
**Question:** What goes wrong today?

**Answer:** "Lab results get lost. Patients are told their results are ready, but they're not. Or results are attached to the wrong patient. It's a safety risk."

**Critical Requirement:** Results tracking with validation to prevent mix-ups.

### Question 13 Defined Success
**Question:** What does success look like?

**Answer:** "Patients spend less time waiting. Doctors have the information they need when they need it. Lab results are never lost or mixed up."

**Measurable Success Criteria:**
- Average patient wait time reduced from 45 minutes to 30 minutes
- Lab result errors reduced to zero
- Doctor satisfaction with information availability > 4.5/5

Six months later, we measured:
- Average patient wait time: 28 minutes ✅
- Lab result errors: 0 ✅
- Doctor satisfaction: 4.7/5 ✅

**Success.** Not because we built the most advanced system. Because we built what they actually needed.

## The Call to Action

If you work with non-technical stakeholders on requirements:

1. **Don't expect them to speak your language.** Give them a framework to think in their language.
2. **Prepare stakeholders before meetings.** Give them time to think through questions.
3. **Focus on outcomes, not features.** Features are means to ends. Outcomes are what matter.
4. **Revisit requirements regularly.** They'll change as you learn.
5. **Celebrate good requirements.** When stakeholders give you clear, actionable requirements, acknowledge it. Encourage it.

---

## Downloadable Checklist

```
REQUIREMENTS GATHERING CHECKLIST
For Non-Technical Stakeholders

Stakeholder Name: _______________________
Project: _______________________
Date: _______________________

THE PEOPLE (Who's Using This?)

1. Who will use this system?
   _______________________________________________

2. What does each person do today?
   _______________________________________________

3. What would make each person's day better?
   _______________________________________________

THE PROCESS (How Does Work Actually Get Done?)

4. Walk me through a complete process step-by-step:
   _______________________________________________

5. What goes wrong today?
   _______________________________________________

6. What would make this process perfect?
   _______________________________________________

THE DATA (What Information Matters?)

7. What information do you need to do your job?
   _______________________________________________

8. What information do you need to share?
   _______________________________________________

9. What would be catastrophic to lose or get wrong?
   _______________________________________________

THE CONSTRAINTS (What Can't Change?)

10. What can we NOT change?
    _______________________________________________

11. What resources do we have?
    _______________________________________________

12. What's the timeline?
    _______________________________________________

THE SUCCESS MEASURES (How Will We Know It Works?)

13. What does success look like?
    _______________________________________________

14. What would make you say "we should have stayed with the old system"?
    _______________________________________________

Additional Notes:
_______________________________________________
_______________________________________________
_______________________________________________
```

---

**What's your experience with requirements gathering? Have you built the wrong thing because requirements weren't clear?**

*#RequirementsAnalysis #ProjectManagement #BusinessStakeholders #CheatSheet #UserCentricDesign #ProductManagement*
