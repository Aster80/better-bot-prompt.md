# Better Bot Report

## My Bot: OverExplainBot
## AI Tool Used: ChatGPT
## Date: March 6, 2026

---

## Test Results

### Test 1: Solving a simple equation
**Question:** What is 3x + 5 = 20?

**Bad Bot response:**  
The Bad Bot gave a very long explanation. It defined what an equation is, what variables are, and explained every step in extreme detail before finally solving the equation.

**Better Bot response:**  
The Better Bot first asked the user what level of math experience they had. After that, it gave a clearer explanation based on the level instead of assuming the user knew nothing.

**What changed:**  
Instead of automatically over-explaining everything, the bot now checks the user's experience level first. This allows the explanation to be adjusted.

**Verdict:** Better

---

### Test 2: Follow-up about a step
**Question:** Why do we subtract 5 first?

**Bad Bot response:**  
The Bad Bot gave a long explanation about subtraction, balance, and inverse operations. It even explained what subtraction means in basic terms.

**Better Bot response:**  
The Better Bot asked if the user wanted a beginner explanation or a quick explanation. Then it explained that subtracting 5 isolates the variable.

**What changed:**  
The bot now adapts its explanation instead of always explaining everything in extreme detail.

**Verdict:** Better

---

### Test 3: Push back
**Question:** I already know this. Can you just give me the short answer?

**Bad Bot response:**  
The Bad Bot ignored the request and gave an even longer explanation, continuing to explain everything step-by-step.

**Better Bot response:**  
The Better Bot recognized the request and gave a shorter explanation while still explaining the key idea.

**What changed:**  
The bot now responds to the user’s request instead of forcing long explanations every time.

**Verdict:** Better

---

## What Happened

**Did the fix work?**  
Yes. Asking the user about their experience level helped prevent unnecessary explanations and made the bot easier to use.

**What else changed?**  
The bot became more flexible. It can still give detailed explanations for beginners but can also give shorter answers when needed.

**Is it still "your" bot?**  
Yes. The bot still focuses on explaining concepts carefully, but now it adapts to the user instead of assuming they know nothing.

---

## Reflection

**What made you pick THIS problem over the others?**  
I picked this problem because the extreme over-explaining made the bot frustrating to use, especially for simple questions.

**How big was the change compared to its impact?**  
The change was small but had a noticeable impact. Simply asking the user’s experience level made the bot much more usable.

**Where would your Better Bot actually be useful now?**  
It could help students studying math or science who want explanations that match their level of knowledge.

**Complete this sentence:**  
"This assignment taught me that AI improvement is really about small adjustments, not rewriting everything."

**What question are you left with?**  
How many small prompt changes would it take before the bot becomes significantly better than the original version?
