# **Chapter 04 — Show and Tell (Few-Shot Learning)**

## “Don’t tell the AI what you want. *Show* it.”

---

# 🧠 Why This Works

Few-shot learning is one of the most *magical* techniques in prompting.

Instead of explaining what you want, you **give the AI 1–3 examples** and let it infer the pattern.

Why does this work?

Because modern AI models are pattern-matching engines:

* If you give no examples → the model guesses your preference.
* If you give an example → the model *locks onto* your preferred style.
* If you give two examples → the model identifies the pattern.
* If you give three → the model becomes shockingly accurate.

Think of it like showing a designer screenshots instead of writing a long explanation.

**Examples speak louder than instructions.**

---

# 🧩 What Is Few-Shot Learning?

**Definition:**
Teaching the AI by providing a few sample inputs and desired outputs.

Format:

```
Example 1:
Input: [your input]
Output: [desired output]

Example 2:
Input: ...
Output: ...

Now your turn:
Input: [new input]
Output:
```

The AI learns:

* tone
* style
* depth
* structure
* formatting
* common vocabulary
* behavior boundaries

It’s like creating your own mini-dataset *on the fly*.

---

# 🔥 Real Example — Summaries Without Losing Tone

### ❌ Without examples

**Prompt:**
“Summarize this paragraph in a casual tone.”

Output:
Often generic and sometimes not casual at all.

---

### ✅ With examples (Few-Shot)

```
Example 1:
Input: "The quarterly reports were inconclusive..."
Output: "Basically, the numbers were all over the place."

Example 2:
Input: "The team will need additional resources..."
Output: "We’ll need more hands on deck to get this done."

Now your turn:
Input: "The marketing campaign performed better than expected..."
Output:
```

The AI now understands:

* casual tone
* short sentences
* simple words
* informal phrasing

You get *exactly* the tone you want.

---

# 🔥 Example — Turning Formal Text Into Simple English

```
Example:
Before: “The legislation aims to regulate…”
After: “This new law tries to control…”

Example:
Before: “The methodology utilized…”
After: “The method used…”

Now your turn:
Before: [paste text here]
After:
```

The output matches your simplicity style automatically.

---

# 🔥 Example — Create Consistent Resume Bullets

```
Example:
Input: Improved customer satisfaction.
Output: Increased customer satisfaction by 18% by redesigning survey workflows.

Example:
Input: Managed team tasks.
Output: Led a 5-member team, implementing weekly sprint planning to reduce delays.

Now your turn:
Input: [your bullet]
Output:
```

This gives AI a **format template + action verbs + metrics**, all inferred from your examples.

---

# 🪄 Few-Shot Is NOT Just for Writing

You can use it for:

### ✔ Coding

Provide one or two examples of how you want errors fixed.

### ✔ Data cleaning

Give examples of cleaned rows.

### ✔ Classification

Show “positive vs negative”, “formal vs casual”, “spam vs not spam”.

### ✔ Creative style copying

Give 2-3 poems, tweets, product descriptions, metaphors.

### ✔ Instruction-following

Show before/after transformations.

Few-shot unlocks *precision and consistency*.

---

# 🧨 The “Hidden” Power: Implicit Rules

When you give examples, the AI infers hidden patterns you didn’t spell out.

Example:

* sentence length
* punctuation style
* emotion level
* complexity
* structure
* format (bullet vs paragraph)
* grammar
* tone

This is why **even one example** often outperforms 10 lines of instructions.

---

# 🔧 Simple Template (Copy/Paste)

```
I will give you examples. Follow the same style.

Example 1:
Input: [text]
Output: [your desired transformation]

Example 2:
Input: [text]
Output: [your desired transformation]

Now your turn:
Input: [new text]
Output:
```

---

# 🧱 Advanced Template (Highly Reliable)

```
Learn from the examples below.

Your task:
- Identify the pattern in the examples.
- Preserve tone, style, and structure.
- Apply the exact transformation to new inputs.

Examples:
[Example 1]
[Example 2]

New Input:
[Your text]

Output:
```

This is the version engineers and technical writers use.

---

# ⚠️ Common Mistakes

### ❌ Giving contradictory examples

The AI becomes confused.

### ❌ Giving too many examples

3–5 is the sweet spot.
More is unnecessary and costly.

### ❌ Forgetting to separate examples

Use clear labels: “Example 1”, “Input/Output”.

### ❌ Giving incomplete transformations

AI will copy missing parts.

### ❌ Mixing different tones

Make sure all examples align emotionally.

---

# 🧠 Best Practices

### ✔ Use the shortest possible examples

Keep examples short but clear.

### ✔ If you want a specific tone, include it in examples

Don’t tell — show.

### ✔ Use 2 examples for style, 3 for accuracy

Reliable sweet spot.

### ✔ Put examples above the task

AI reads top-to-bottom and learns in order.

### ✔ Use *Before → After* transformations

AI understands this instantly.

---

# 📌 Summary

Few-shot learning is how you make AI behave *exactly* the way you want.

In this chapter, you learned:

* what few-shot is
* how it works
* why examples beat instructions
* powerful real-world use cases
* templates
* common mistakes to avoid
* best practices

This is one of the most important tools for getting consistent, predictable, high-quality results.

---

# 🎯 Practice Exercise

Give AI 2-3 examples in one of these tasks:

1. Rewrite text in a specific tone
2. Generate consistent resume bullets
3. Transform formal → simple English
4. Extract structured data the same way every time
5. Generate content in your writing style

You’ll see the quality skyrocket instantly.

---

# 🎉 You're Ready for Chapter 5

Next, we go even deeper:
**Thinking Out Loud (Chain-of-Thought)** — the technique that makes AI reason step-by-step, improving logic, accuracy, and reliability.

