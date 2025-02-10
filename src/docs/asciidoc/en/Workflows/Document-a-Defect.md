---
Title: Document a Defect
author: Jonathan Zollinger
Description: HQ WF for addressing Help Requests in JustServe
---

# Defect Reports

Defects are reported in Jira which link is not documented in this public doc. Reach out to Jonathan or look in teams for the link. 

<details><summary> Why Detailed Defect Reports Are Crucial </summary>

Accurate and detailed defect reports are essential for our team to effectively diagnose and resolve issues.  The information you provide directly impacts whether a defect is understood by the dev team or if they have to ask for context. the time it takes to ask for context introduces days worth of wasted time.

</details>

## 1. Expected Behavior

**Why it matters:** This tells us what *should* happen. It's the baseline for comparison. Without knowing the intended behavior, we can't determine if something is truly a defect.

**How to describe it:** Be clear and specific.  Think of it as writing instructions for someone who has never used the feature before.

**Example:** "When a user clicks the 'Submit' button on the volunteer opportunity form, they should be redirected to a confirmation page displaying a success message."

## 2. Current Behavior

**Why it matters:** This describes what is *actually* happening.  It highlights the deviation from the expected behavior and pinpoints the problem.

**How to describe it:** Be precise and objective. Describe what you observe, not what you assume. Include any error messages you see.

**Example:** "When a user clicks the 'Submit' button, the form appears to freeze, and a spinning wheel is displayed. After a few minutes, a generic error message appears: 'An error occurred. Please try again later.'"

## 3. Steps to Reproduce

**Why it matters:** This allows us to recreate the issue consistently.  If we can't reproduce the problem, we can't fix it.  Think of it as providing a recipe for the bug!

**How to describe it:** Be step-by-step and detailed. Include every action you took, even if it seems insignificant.  The more detail, the better.

**Example:**

1. Log in to JustServe.
2. Navigate to the 'Volunteer Opportunities' page.
3. Click on the 'Create New Opportunity' button.
4. Fill out all required fields in the form.
5. Click the 'Submit' button.

## 4. Environment

**Why it matters:** Defects can be specific to certain browsers, operating systems, or devices.  Knowing the environment helps us narrow down the cause.

**How to describe it:** Provide as much detail as possible about the environment where you encountered the issue.

**Example:**

* **Browser:** Chrome (Version 114.0.5735.199)
* **Operating System:** Windows 11
* **Device:** Desktop Computer
* **JustServe App Version:** (If applicable)  Provide the app version number.

## The Impact of Your Contribution

By providing thorough and accurate defect reports, you directly contribute to the quality and stability of JustServe.  Your attention to detail helps our development team quickly identify and resolve issues, leading to a better experience for all users.  Thank you for your help in making JustServe the best it can be!
