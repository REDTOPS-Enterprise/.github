# 📜 The REDTOPS Contribution

So, you want to contribute to a REDTOPS project? Good. We need more hands on the keyboard and fewer people talking about "best practices" in the cafeteria. 

At **REDTOPS Enterprise**, we have a specific way of doing things. We call it **The Vibe Protocol**. Follow it, and we’ll get along fine. Ignore it, and you’ll be demoted to "Manual Documentation Entry" for a month.


---

## 🎭 Culture & Stability (The "Human" Element)

One thing we should take note on, we’re sometimes serious about performance, but we aren't boring. You might find jokes in the comments, weird variable names in the experimental branches, and a general lack of "corporate stiffness." Most of us at **REDTOPS** like to keep things light while we’re pushing software to its limit.

**A Note on Stability:**
Because we move fast and shit the code hard, things might get... shaky. If you’re the type of developer who enjoys taking our high-speed chaos and finding ways to **stabilize** it without killing much of the performance, we love you. Seriously. If you can make our mad-scientist experiments actually survive a production environment, you’re doing the Lord’s work. We thank you, and the hardware thanks you.

---

## How to Contribute?
But anyway with all that out of the way there is 5 simple steps when working or voluteering with us.

1.  **Identify a Bottleneck:** If something is slow, it’s an insult to the brand. Fix it.
2.  **Fork and Hammer:** Grab the repo, create a branch or work with someone, and start coding. 
3.  **Test your code:** Before you submit a Pull Request, run the code. If it smokes the CPU but completes the task in record time, you’re on the right track.
4.  **Verify the Logic:** If you used a tool to help you, double-check the math. We don't ship "hallucinations."
5.  **Communication:** Communication is key! Use it, it helps out a lot in the long run!

---

## ⚠️ The Do's and Don'ts

### ✅ DO:
* **Prioritize Performance:** If you can save 2ms by writing a slightly "unreadable" bit of assembly, do it. We might just hire someone to read it later.
* **Be Bold:** If a feature in AmberLink or REDLINE is "stable" but boring, make it "unstable" but revolutionary. (We're kidding of course careful with instablities!)
* **Document the "Why":** We can see *how* the code works by looking at it. Tell us *why* you decided to ignore the memory safety warnings for the sake of speed.

### 🛑 DON'T:
* **Don't Ship Bloat:** If your PR adds a 20gb dependency just to sort a list, we will find you.
* **Don't "Clean Code" us to Death:** If you rewrite a high-speed function into three "cleaner" nested functions but runs 70% slower, your PR will be closed immediately.
* **Don't Ask to ask, just do it:** If you see a way to make Amberlink 2x faster, don't open an issue asking if you should. **Do it.** Then show us the benchmark. However if you really need to ask, then feel free to message us.

---

## Submission Guidelines

When you open a Pull Request, keep the description short:
1.  **What it does.**
2.  **How much faster it is (Show us the benchmarks!).**
3.  **Contributors:** The person who's making the PR, please write down who worked with you. (leave blank if done sololy)

---

## Pull Request Template (feel free to make ur own varient)

PRODUCT:
VERSION NUMBER:
CONTRIBUTORS:
PERFORMANCE OR STABILITY?:

[ Insert details here ]

[ Insert Performance Details here ]


---

**REDTOPS Enterprise: Breaking things so you don't have to.**
