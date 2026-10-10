# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Deemah alghuribi] |
| **Student ID** | [446051656] |
| **University Email** | [446051656@std.psau.edu.sa] |
| **GitHub Username** | [Deemaalghuribi] |
| **Repository Link** | [(https://github.com/Deemaalghuribi/OS-Assignment1-Deemah-Alghuribi)] |
 
---

## 🎥 Video Link

**Video Link**: [(https://drive.google.com/file/d/1mWasvs3DMHb6rPmrVXCyWi6azfvW2aMG/view?usp=sharing)]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 5, 2026, 4:15 PM]
**What I did**: Forked the repository, set up my environment, and added my student ID.

**Details**:
- Forked the starter repo to my GitHub account and kept it public.
- Cloned it locally using VS Code.
- Changed the student ID to 446051656 to seed the random generation.
- Ran the initial simulation to observe the default behavior.

**Challenges**: The terminal was throwing git configuration errors when trying to commit.

**Solution**: I used the terminal to manually set `git config --global user.name` and `user.email`.

**Time spent**: 45 minutes

---

### Entry 2 - [October 7, 2026, 6:30 PM]
**What I did**: Implemented Feature 1 (Process Priority).

**Details**:
- Added a `priority` integer variable to the `Process` class.
- Initialized it in the constructor using `Math.random()` to generate a value between 1 and 10.
- Created a getter method `getPriority()`.
- Updated the `addProcessToQueue()` print statement to display the priority.

**Challenges**: The output wasn't updating when I ran `java SchedulerSimulation`.

**Solution**: Realized the file wasn't saved properly. Started using `File > Save` manually and clearing the terminal before recompiling.

**Time spent**: 1 hour

---

### Entry 3 - [October 8, 2026, 5:00 PM]
**What I did**: Implemented Feature 2 (Context Switch Counter).

**Details**:
- Declared a `public static int contextSwitches = 0;` variable above the `main` method.
- Found the exact location where a process starts execution in the queue loop.
- Incremented the counter right before `currentThread.start()`.
- Printed the total context switches at the end of the simulation.

**Challenges**: Deciding exactly where to increment the counter to accurately reflect context switches.

**Solution**: Read the `while` loop logic carefully and placed the increment before the thread starts its quantum.

**Time spent**: 45 minutes

---

### Entry 4 - [October 9, 2026, 8:00 PM]
**What I did**: Implemented Feature 3 (Waiting Time Tracking).

**Details**:
- Added `arrivalTime` and `waitingTime` variables to the `Process` class.
- Recorded `System.currentTimeMillis()` in the constructor.
- Calculated waiting time as `(System.currentTimeMillis() - arrivalTime) - burstTime`.
- Updated print statements in both `run()` and `runToCompletion()` methods.

**Challenges**: Ensuring the waiting time calculation was mathematically correct and didn't output negative numbers.

**Solution**: Used `Math.max(0, ...)` to prevent any negative values due to minor thread execution delays.

**Time spent**: 1 hour

---

### Entry 5 - [October 10, 2026, 2:00 PM]
**What I did**: Finalized documentation and verified all features.

**Details**:
- Ran the full program to ensure all features work together flawlessly.
- Filled out the `MY_WORK.md` development log.
- Answered the reflection and technical questions based on my code execution.
- Prepared for recording the video demonstration.

**Challenges**: Formulating concise and accurate technical answers.

**Solution**: Re-read the specific functions in the code and matched them with the theoretical concepts learned in class.

**Time spent**: 1.5 hours

---

## Development Log Summary

**Total time spent on assignment**: 5 hours

**Most challenging part**: Debugging the terminal outputs and managing git configurations directly from VS Code.

**Most interesting learning**: Seeing how `Thread.sleep()` and `Thread.join()` actually pause and manage execution time visually in the terminal.

**What I would do differently next time**: I would configure Auto-Save in my IDE from the very beginning to avoid compiling old code.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[I learned how Java implements multithreading using the `Runnable` interface and the `Thread` class. It was fascinating to see how `Thread.start()` actually begins the execution of the `run()` method concurrently. I also learned how `Thread.sleep()` is used to simulate processing time by temporarily pausing a thread's execution. Furthermore, the use of `Thread.join()` showed me how the main program scheduler waits for a specific thread to finish its time quantum before moving to the next one. Overall, it clarified how multiple tasks share CPU time efficiently without blocking the entire system.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was configuring the GitHub integration and ensuring my commits were tracked correctly. Initially, I faced errors when trying to commit my changes directly from the Source Control panel because my Git `user.name` and `user.email` were not globally set up on my machine. It was also slightly tricky to figure out exactly where to place the new variables inside the existing `SchedulerSimulation.java` structure, especially ensuring the `contextSwitches` counter was incremented at the precise moment.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame these challenges by taking a step-by-step approach instead of rushing. Whenever I hit a Git error, I used the terminal to manually input the correct `git config` commands with my university email. To fix code and compilation issues, I learned to save my files manually from the top menu and use the `clear` command in the terminal before running `javac` and `java` again. This prevented me from confusing outdated output with new changes.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading concepts are essential in almost every modern application to maintain responsiveness. For example, when I am listening to a playlist on Spotify, one thread handles streaming the audio seamlessly, while another updates the UI and responds to my clicks. Without multithreading, the app would freeze every time it downloaded the next chunk of the song. Similarly, background tasks like downloading files or sending push notifications rely heavily on threads to keep the main application running smoothly for the user.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[A process is an independent program in execution with its own dedicated memory space, while a thread is a lightweight unit of execution within a process that shares the same memory. We used threads in `SchedulerSimulation.java` (specifically via `Thread thread = new Thread(process);`) because creating actual OS processes is highly resource-intensive and has a massive creation overhead. Threads allow us to simulate concurrent execution much faster, with minimal memory overhead, and they communicate with each other seamlessly within the same Java Virtual Machine.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, if a process doesn't finish its burst time within the allocated time quantum, it is preempted, removed from the CPU, and placed back at the end of the ready queue. Re-queueing ensures absolute fairness so that no single long process monopolizes the CPU, allowing shorter processes a chance to run. In my output, a process with a large burst time had to be re-queued multiple times before its remaining time finally reached zero.]

Example from my output:
```[⏸ P10 completed quantum 5000ms │ Overall progress: [███████████████████░] 99%
     Remaining time: 81ms
  ↻ P10 yields CPU for context switch

  ➕ P10 (Priority: 2) added to ready queue │ Burst time: 10081ms]
```

**Explanation of example:**
[In this snippet, process P10 executed for its full time quantum of 5000ms, but it still had 81ms of execution time left. Because of the Round-Robin policy, it yielded the CPU (triggering a context switch) and was placed back into the ready queue to wait for another turn to finish its remaining 81ms.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 is in the New state when we create its thread object via `new Thread(process)` inside the `addProcessToQueue()` method.
2. **Runnable**: P1 becomes Runnable when it is added to the `processQueue`, waiting for the CPU to become available.
3. **Running**: P1 enters the Running state when the scheduler loop pulls it from the queue and calls `currentThread.start()`.
4. **Waiting**: P1 goes into a timed waiting state when `Thread.sleep()` is called inside `run()` to simulate work. The main thread also waits when calling `currentThread.join()`.
5. **Terminated**: P1 is Terminated when its `remainingTime` reaches 0 and the `run()` or `runToCompletion()` method completely finishes execution.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): Modern OS CPU Scheduler
**Description**: The operating system scheduler manages multiple background services, system processes, and user applications running simultaneously on a single CPU core.
**Why Round-Robin works well here**: It provides high responsiveness and fairness, ensuring that no single heavy application freezes the entire system, giving the user the illusion that everything is running at the exact same time smoothly.

### Example 2: Event Hospitality POS System (Rafad)
**Description**: A digital ordering system for an event hospitality service like Rafad, where multiple customers are placing orders simultaneously at different stations (V60 coffee, matcha, crepe, etc.).
**Why Round-Robin works well here**: It ensures fairness and predictable wait times. Every customer's order gets processed sequentially in small increments without one massive bulk order completely blocking the entire queue and halting the service flow.

## Summary

**Key concepts I understood through these questions:**
1.
2.
3.

**Concepts I need to study more:**
1.
2.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
