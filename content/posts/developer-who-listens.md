+++
date = '2017-03-01T12:00:00Z'
draft = false
title = 'The Developer Who Listens: Why Stakeholder Engagement Changes Everything'
readingTime = '7 min'
+++

# The Developer Who Listens: Why Stakeholder Engagement Changes Everything

**Published: March 2017 | Reading Time: 7 minutes**

---

## The Project That Should Have Been Easy

It was early 2017. I had just joined i4cus Nigeria Limited as a Software Engineer / Business Analyst. We had what seemed like a straightforward project: build a student information system for a local college.

Requirements were clear. We had a detailed specification document. We had a 4-month timeline. We had a capable development team.

Six weeks in, the college's registrar came to our office. She looked exhausted.

"I don't want to be rude," she said hesitantly, "but this system won't work for us."

I was defensive immediately. "We're following the requirements document. The college approved everything."

She sighed. "The document says we need to track student attendance. That's correct. But the way you're building it means a teacher has to enter attendance manually for every student, every class, every day. Our teachers have 200 students each. That's 200 entries per day. They'll never do it."

Silence in the room.

I looked at the requirements document. It said: *"System shall capture and store student attendance."*

That was technically accurate. And completely wrong.

**We were building exactly what was specified. And we were building exactly what wouldn't be used.**

## The Hard Realization

That meeting was a wake-up call for me.

I had spent years thinking my job was to execute requirements. Give me a specification, I'll build the system. Tell me what you want, I'll deliver it.

But the student information system taught me something profound:

**The best system is the one that's actually used.**

And people only use systems that fit into how they actually work—not how we think they should work.

## The Struggle: Unlearning "Execution Mindset"

I want to be honest about how hard this was for me.

I was proud of my technical abilities. I could write clean code. I could design elegant architectures. I could deliver exactly what was specified.

But this new way of working—spending time understanding stakeholders before building anything—felt inefficient. It felt like slowing down. It felt like I wasn't being a "proper" engineer.

Then I had a conversation with one of my mentors that shifted everything.

"Omeiza," he said, "you can build the perfect system. But if people don't use it, it's worthless. You can build a good-enough system that fits how people work. And they'll use it every day. Which would you rather deliver?"

I wanted to deliver the second. But I didn't know how.

## The Transformation: Learning to Listen

I decided to change my approach completely. Before writing a single line of code for the student information system, I would spend time understanding.

### What I Did Differently

#### 1. I Went Where the Work Happens
Instead of meeting in conference rooms, I visited the college. I watched teachers in classrooms. I watched registrars in their offices. I watched students enroll.

I saw things no requirements document would have captured:
- Teachers taking attendance on paper during class, then having no time to enter it into systems later
- Registrars using sticky notes to track urgent student issues because the current system was too slow
- Students lining up in person because the online portal wasn't mobile-friendly

#### 2. I Asked "Why" Not "What"
Instead of asking "what features do you want?" I started asking "why do you do it this way?"

The registrar's answer about attendance: "We need attendance records for government funding. But we don't have time to enter it. The teachers are overwhelmed already."

The hidden requirement: It's not about capturing attendance. It's about capturing attendance without adding work.

#### 3. I Observed Workarounds
I learned that every system has workarounds. And workarounds are goldmines of hidden requirements.

- Teachers taking photos of paper attendance to enter later (they never did)
- Staff using WhatsApp to share urgent student updates because the system was too slow
- Students calling the office because the online portal wasn't working on their phones

#### 4. I Involved Users in Design
I didn't just interview stakeholders. I brought them into the design process. I showed them mockups. I watched them try to use prototypes.

When the registrar tried our prototype, she said: "This screen is too complex. I need to see at a glance which students have missing documents. I don't have time to click into each student record."

We redesigned based on her feedback. The second prototype worked better. The third prototype worked even better.

## The Result: A System People Actually Used

Six months later, we delivered the student information system.

Here's what made it different:

### Feature 1: Mobile-First Attendance
Instead of requiring teachers to log into a desktop system, we built a mobile app. They could mark attendance during class with a few taps. No extra work after class.

**Usage:** 95% of teachers used the mobile app within first week.

### Feature 2: Automated Funding Report
Instead of requiring manual work to generate government funding reports, the system automatically generated them based on the attendance data.

**Result:** The college received full government funding because attendance records were accurate.

### Feature 3: Simple Dashboard
Instead of complex navigation, we built a simple dashboard that showed what each user needed to see at a glance. Registrars saw urgent student issues. Teachers saw today's classes. Administrators saw overview metrics.

**Feedback:** "It just shows me what I need to know. I don't have to search for it."

## The Metrics That Mattered

Three months after launch, I tracked adoption:

### Traditional System (Previous College System)
- Feature usage: 40% (most features went unused)
- User satisfaction: 3.2/5
- Time to complete common tasks: 15 minutes average
- Manual workarounds still in use: Yes

### Our New System
- Feature usage: 87% (features were actually used)
- User satisfaction: 4.7/5
- Time to complete common tasks: 3 minutes average
- Manual workarounds in use: None

We hadn't built a more technically complex system. We had built a system that fit how people worked.

## The Framework I Use Now

Since the student information system project, I've refined my approach into a deliberate practice.

### The "Listen First" Framework

#### Phase 1: Observation (1-2 weeks)
**Goal:** Understand actual workflows, not described workflows.

- Visit where the work happens
- Watch people do their actual work
- Note workarounds and shortcuts
- Identify pain points and frustrations

#### Phase 2: Deep Inquiry (1 week)
**Goal:** Understand the "why" behind requirements.

- Ask "why do you do it this way?" repeatedly
- Understand the business purpose behind each task
- Identify what success looks like
- Discover what's not working about current approaches

#### Phase 3: Co-Design (1-2 weeks)
**Goal:** Design with users, not for users.

- Create rough mockups or prototypes
- Watch users try to use them
- Ask "what's confusing?" and "what would make this better?"
- Iterate based on real feedback

#### Phase 4: Validation (Ongoing)
**Goal:** Ensure you're building the right thing.

- Test early prototypes with real users
- Get honest feedback—it's okay if they say it's wrong
- Be willing to change direction
- Measure whether workflows actually improved

## Real-World Example: Healthcare Logging System

Fast forward to 2024. I'm working at Canaries Solutions on a healthcare support logging system.

Old approach would have been: "Give me the requirements, I'll build it."

My approach:

### Observation
I spent two days in the healthcare facility. I watched operational staff log incidents. I saw:
- They used paper notebooks because the previous digital system was too slow
- They forgot details by the time they got to the system
- They couldn't find previous incidents to reference

### Deep Inquiry
I asked "why do you need to log incidents?"

The answer wasn't about compliance or audit trails. It was: *"So we can fix recurring problems before they harm patients."*

### Co-Design
We built a mobile-first system that captured incidents as they happened. We added a feature to detect patterns and flag recurring issues.

### Result
40% improved issue visibility. 35% faster resolution times.

But more importantly: Staff actually used it.

## The Common Mistakes I See

### Mistake 1: Building to Specifications Instead of People
**The Problem:** "The requirements document says X, so I'm building X."

**The Fix:** Specifications capture what people think they need. Observation reveals what they actually need.

### Mistake 2: Assuming You Understand the Work
**The Problem:** "I know how this should work. I've built similar systems."

**The Fix:** Every context is different. What works in one environment might fail in another. Don't assume—observe.

### Mistake 3: Talking More Than Listening
**The Problem:** "Here's how we're going to solve this problem."

**The Fix:** Ask more questions than you answer. "What would make this work better for you?" is more powerful than "Here's my solution."

### Mistake 4: Focusing on Features Instead of Workflows
**The Problem:** "We're adding these 5 great features."

**The Fix:** Features don't matter if they don't fit workflows. Focus on how the work actually gets done, then design features to support it.

## The Impact: How This Changed Everything

Since learning to listen before building, I've seen consistent results:

### Projects Deliver on Time
We don't waste time building the wrong thing. We build the right thing, which means we don't have to rebuild it later.

### User Adoption Is High
When people help design the system, they feel ownership. They use it. They advocate for it.

### ROI Is Higher
A system that's used delivers ROI. A system that's not used wastes money.

### My Career Has Grown
I've moved from "the developer who builds what you tell him" to "the person who helps you figure out what you actually need." That's a very different—and much more valuable—role.

## The Hard Truth

Technical skills are essential. But the ability to understand and engage with stakeholders is what separates good developers from great ones.

I've worked with brilliant engineers who built technically perfect systems that nobody used. I've worked with competent engineers who built technically adequate systems that transformed organizations.

The difference wasn't code quality. The difference was understanding people.

## A Challenge for You

If you're a developer, business analyst, or anyone who builds systems:

1. What was the last system you built where you spent more time listening than coding?
2. When was the last time you visited where the work actually happens?
3. When was the last time you changed your design based on user feedback?

If the answer is "I don't remember" or "never"—you're missing something important.

## The Inspiration

I used to think listening was soft skills. Weak skills. Skills for people who weren't technically strong.

I was wrong.

Listening is the hardest technical skill I've learned. It requires humility. It requires admitting you don't have all the answers. It requires being willing to be wrong.

But it's also the most rewarding skill I've learned.

When you build systems that people actually use—when you see your work making a real difference in their day—that's the best feeling in the world.

**Start listening. Your stakeholders will thank you. Your users will thank you. And your future self—the one who doesn't have to rebuild systems nobody uses—will thank you too.**

---

**What's your experience with stakeholder engagement? Have you built the perfect system nobody used?**

*#RequirementsGathering #StakeholderEngagement #BusinessAnalysis #SoftwareEngineering #UserCentricDesign #ProductManagement*
