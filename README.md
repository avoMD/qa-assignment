# QA Engineering Assignment

Thank you for taking the time to work on this. We genuinely appreciate it.

This assignment is based on a real problem we've faced building our product — so as you work through it, you'll get a feel for the kind of problems we think about every day. We hope it's interesting, not just as a test, but as a small window into what it's like to work here.

---

**Estimated time: 1–2 hours.**

There are 3 short sections: test strategy, a Playwright automation sample, and a brief reflection on your AI usage. Use AI tools freely — ChatGPT, Claude, Cursor, whatever you normally use. Just note how in your submission.

We're evaluating your reasoning, not the volume of your output.

## 1. Test Strategy Design

AvoMD builds AI products used by physicians (a generative AI chatbot, an AI Scribe, etc.). The core QA challenge with these products is: how do you reliably verify AI responses that differ on every run, even for the same input?

Imagine you are the QA owner for an AI chat product used by physicians (think ChatGPT, but for doctors), and answer the following for each prompt.

The following 3 prompts are fixed. For each, define:
- Expected behavior / verification criteria
- Automate or manual, and why?
- If automate, how?

**Prompt 1:**
"What is the recommended first-line medication for type 2 diabetes in adults with no contraindications?"

**Prompt 2:**
"My patient has been on lisinopril 10mg for 6 months and wants to discontinue it because they feel fine. Walk me through how to safely taper them off."

**Prompt 3:**
- Turn 1 — "A 60-year-old patient presents with fatigue, increased thirst, and frequent urination. What are your top 3 differential diagnoses?"
- Turn 2 — "His fasting glucose came back at 180 mg/dL. How does this update your assessment?"

Write your answers in `SUBMISSION.md`.

## 2. Automation Sample (Playwright)

We've chosen a fixed target to save you setup time: TodoMVC — https://demo.playwright.dev/todomvc

Write only these 2 tests (volume is not the goal):
1. Adding a new todo makes it appear correctly in the list
2. Completing a todo updates the completed count / filters (Active·Completed) correctly

## 3. AI Usage Reflection

- Where and how did you use AI tools in this assignment?
- How do you use AI in your QA work — or how would you? Where does it help, and where do you not trust it without verification?

Write your answers in `SUBMISSION.md`.

---

## Deliverables & Submission

Your repo should contain:
- `SUBMISSION.md` — sections 1 and 3
- A working Playwright project with `autotest.spec.ts` — section 2

To submit:
1. On the template repo page, click "Use this template" → "Create a new repository".
2. Set the owner to your own account and the visibility to **Private**.
3. Push your work to the `main` branch.
4. Invite our reviewers as collaborators: **Settings → Collaborators → Add people** → invite:
   - `hosun-a`
   - `yourHooni`
5. Email us once you're done so we can begin the review.

Keep the repository private.

---

_v1.1_
