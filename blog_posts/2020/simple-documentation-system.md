# The Simple Documentation System That Reduced Support Requests

**Published: July 2020 | Reading Time: 6 minutes**

---

## The Tuesday We Were Drowning

It was 2020 at i4cus Nigeria Limited. We had just launched a new student management system.

Our support team—two people, Sarah and Emeka—were overwhelmed. Phone ringing constantly. Tickets pouring in.

"What's happening?" I asked Emeka one afternoon.

"We're getting the same questions over and over," he said, exhausted. "How do I add a student? How do I generate a report? Why can't I access this module?"

"Can't users read the documentation?" I asked.

He laughed. "What documentation?"

I went to check. We had comprehensive documentation. A 50-page user manual. Detailed technical guides. Complete API reference.

It was beautiful. It was thorough. Nobody read it.

## The Problem: The Restaurant Menu Metaphor

Let me explain with a metaphor that transformed my approach to documentation.

Imagine you go to a restaurant. The waiter hands you a 50-page document.

It has:
- Every ingredient in every dish
- The cooking method for each recipe
- Nutritional information for everything
- The history of every menu item
- Photos of every dish in different lighting

It's comprehensive. It's beautiful. It's overwhelming.

You just want to know: "What's good to eat today?"

You ask the waiter. They recommend three dishes. You choose one.

**That's how your users feel about comprehensive documentation.**

They don't want to read 50 pages about how to use your system. They want to know: "How do I do this one thing?"

## The Struggle: Documentation That Nobody Uses

We had invested weeks in creating comprehensive documentation. And nobody was using it.

Users were calling support. Tickets were piling up. Sarah and Emeka were drowning.

I felt frustrated. We had documentation! We had written it carefully! Why weren't people using it?

Then I watched a user trying to solve a problem.

She opened our 50-page user manual. She scrolled for 30 seconds. She sighed. She closed it. She called support.

**She couldn't find what she needed. And she didn't have time to read 50 pages to find out.**

## The Transformation: Right-Sizing Documentation

I realized we had created wrong type of documentation. We had created "reference documentation"—comprehensive, detailed, for people who want to know everything.

What users needed was "task documentation"—focused, practical, for people who want to get something done.

I developed a new approach based on a simple principle:

**Don't document your system. Document tasks.**

## The Framework: Task-Based Documentation

### Principle 1: One Page Per Task
Every common task should have documentation. But only one page.

**Examples:**
- "How to Add a New Student" (1 page)
- "How to Generate an Attendance Report" (1 page)
- "How to Reset a User Password" (1 page)
- "How to Export Student Data" (1 page)

Each page answers:
- What is this task?
- Why would you do it?
- Step-by-step instructions
- What can go wrong?

**Not** everything about every feature involved. Just the task itself.

### Principle 2: Quick Reference First, Details Later
Every task page starts with a quick reference.

**Example: "How to Add a New Student"**

**Quick Reference:**
1. Click "Students" in menu
2. Click "Add New"
3. Fill in student information
4. Click "Save"

**That's it.** Four steps. Takes 10 seconds to read.

Then below that, detailed explanations of each field. Troubleshooting tips. Related tasks.

Most users never need to scroll past the quick reference. The few who do can find more details.

### Principle 3: Search-Friendly Titles
Use language users actually use, not technical terms.

**Wrong:** "Student Entity Creation Process"
**Right:** "How to Add a New Student"

**Wrong:** "Report Generation Functionality"
**Right:** "How to Generate an Attendance Report"

**Why:** Users search for what they're trying to do, not what your system calls it.

### Principle 4: Screenshots Over Descriptions
A picture is worth a thousand words. A screenshot is worth ten thousand.

Every task page has:
- Screenshot of starting state
- Screenshot after each key step
- Screenshot of completed task

Users can compare their screen to the screenshots. They know they're doing it right.

### Principle 5: Troubleshooting Built In
Every task page includes a "What Can Go Wrong?" section.

**Example for "How to Add a New Student":**

**Common Problems:**
- **"Save button is greyed out"** → You're missing a required field. Check for red asterisks (*).
- **"Student already exists"** → A student with that ID already exists. Use "Search" to find them first.
- **"I don't have permission"** → Your role doesn't include adding students. Contact your administrator.

Users can solve their own problems without calling support.

## What We Changed

### Before: Comprehensive Reference Documentation
- 50-page user manual
- Complete API reference
- Detailed technical guides
- Beautiful, thorough, unreadable

### After: Task-Based Quick Reference
- One-page guides for 20 common tasks
- Quick reference sections
- Screenshots for every step
- Built-in troubleshooting
- Simple, focused, usable

## The Results: Measurable Impact

### Support Request Volume
**Before:** Average 45 support requests per day
**After:** Average 32 support requests per day
**Reduction:** 29% fewer requests

### Self-Service Rate
**Before:** 15% of users solved their own problems
**After:** 52% of users solved their own problems
**Increase:** 247% more self-service

### Average Resolution Time
**Before:** 8 minutes per support request
**After:** 4 minutes per support request
**Reduction:** 50% faster (most requests now simple ones we can answer quickly)

### User Satisfaction
**Before:** 3.1/5 for documentation
**After:** 4.6/5 for documentation
**Increase:** 48% higher satisfaction

### Support Team Morale
**Before:** Sarah and Emeka were exhausted, overwhelmed
**After:** Sarah and Emeka were calm, focused on complex issues

**The most important result:** Our support team stopped drowning. They could focus on genuinely difficult problems instead of answering the same questions repeatedly.

## The Metaphor: The Signpost vs. The Map

I like to think of documentation with this metaphor:

**Comprehensive documentation is like a map.** It shows everything—every road, every landmark, every detail. It's beautiful and overwhelming.

**Task-based documentation is like a signpost.** It shows you exactly where to go for what you're trying to do right now.

When you're lost, a map is useful. But most of the time, you're not lost—you just need directions. A signpost is what you need.

Your users aren't lost. They're just trying to get somewhere. Give them signposts, not maps.

## Real-World Example: The Documentation That Saved Us

Three months after implementing task-based documentation, we had a critical system update.

We updated how student grades were recorded. It was a significant change.

### Old Approach (Comprehensive Documentation)
We would have:
- Updated the 50-page user manual
- Added a new technical guide
- Updated the API reference
- Sent an email: "Documentation has been updated—please review"

Users would have opened the 50-page manual, been overwhelmed, called support with questions.

### New Approach (Task-Based Documentation)
We:
- Updated 2 task pages: "How to Record Grades" and "How to Generate Grade Reports"
- Updated the quick references
- Added screenshots of the new workflow
- Added new troubleshooting tips
- Sent an email with links to the 2 updated pages

Users opened the 2 pages, followed the quick references, and got back to work.

**Support requests for the first week:** 8 (all simple clarifications)
**Previous major updates:** 40+ support requests in first week

## Common Mistakes to Avoid

### Mistake 1: Documenting Features, Not Tasks
**The Problem:** "This is what the grade entry module does"

**The Fix:** "How to Record Grades for a Student"

### Mistake 2: One-Size-Fits-All Documentation
**The Problem:** One long document covering everything

**The Fix:** One short document per task. Users only read what they need.

### Mistake 3: Technical Language
**The Problem:** "To instantiate the student entity, navigate to the student management interface..."

**The Fix:** "To add a new student, click 'Students' then 'Add New'..."

### Mistake 4: No Troubleshooting
**The Problem:** Documentation shows the happy path only

**The Fix:** Include "What Can Go Wrong?" with common problems and solutions.

### Mistake 5: Never Updating Documentation
**The Problem:** Documentation reflects how the system used to work, not how it works now

**The Fix:** Every feature change requires corresponding documentation update. Make it non-negotiable.

## The Hard Truth

Documentation should answer the questions people actually ask—not the questions you think they should ask.

Our comprehensive 50-page manual was impressive. But nobody read it because nobody needed to know everything.

Our one-page task guides were simple. Everyone read them because everyone needed to know how to do specific things.

**Good documentation isn't comprehensive. It's relevant.**

## A Framework for Your Documentation

If you're creating documentation:

### Step 1: Identify Common Tasks
What do users ask about? What are the most frequent support requests?

### Step 2: Create One-Page Guides
One page per task. Quick reference first. Details below.

### Step 3: Use Their Language
What terms do users use? Use those, not technical terms.

### Step 4: Add Screenshots
Show, don't just tell. A screenshot is worth a thousand descriptions.

### Step 5: Include Troubleshooting
What goes wrong? What are the common errors? Document the solutions.

### Step 6: Keep It Current
Every change updates the documentation. Make it automatic.

## The Inspiration

After implementing task-based documentation, Sarah, one of our support team, came to me.

"You know what I realized?" she said. "Good documentation is like having an extra team member. It answers questions before they even ask them."

That's exactly right.

Documentation that people actually use reduces support requests. It frees your team to focus on complex problems. It improves user satisfaction because people can solve their own problems.

**It's not about writing more documentation. It's about writing the right documentation.**

---

## Quick Documentation Template

```
TASK: [What users are trying to do]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

QUICK REFERENCE
1. [First step]
2. [Second step]
3. [Third step]
4. [Fourth step]

DETAILED INSTRUCTIONS
Step 1: [First step explanation]
[Screenshot after step 1]

Step 2: [Second step explanation]
[Screenshot after step 2]

...

WHAT CAN GO WRONG?
[Problem 1] → [Solution]
[Problem 2] → [Solution]
[Problem 3] → [Solution]

RELATED TASKS
- [Related task 1 link]
- [Related task 2 link]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

**What's your documentation strategy? Do people actually use it?**

*#KnowledgeManagement #Documentation #SupportEfficiency #ProcessImprovement #UserDocumentation*
