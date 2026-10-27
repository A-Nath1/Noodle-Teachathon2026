# Noodle-Teachathon2026 User Guide
# https://noodle-react.vercel.app/
# 140 Signed Up Users!
Notes, unravelled.

Noodle turns your lecture notes into games. You add notes, slides, a textbook or a lecture transcript, and Noodle cooks them into flashcards, quizzes, a mini podcast, a mind-map puzzle and more. Everything you play earns XP, which fills a bowl of ramen, builds a daily streak and unlocks things to customise.

This guide is for people using Noodle. If you are building or running it, read [README.md](README.md) instead. Last checked against the app in October 2026.

## Contents

1. [Quick start](#1-quick-start)
2. [Signing in with Google](#2-signing-in-with-google)
3. [Making a study set](#3-making-a-study-set)
4. [Your home page and subjects](#4-your-home-page-and-subjects)
5. [The study set page](#5-the-study-set-page)
6. [The activities](#6-the-activities)
7. [Teach Noodly](#7-teach-noodly)
8. [Still Tangled: explain it through your interests](#8-still-tangled)
9. [Textbook, lecture and references](#9-textbook-lecture-and-references)
10. [Annotated slides](#10-annotated-slides)
11. [Fusion: mixing topics](#11-fusion-mixing-topics)
12. [Cheat sheets, practice papers and Anki export](#12-cheat-sheets-practice-papers-and-anki-export)
13. [Showdown: live quizzes](#13-showdown-live-quizzes)
14. [Lecture rooms: annotate with classmates](#14-lecture-rooms)
15. [Friends and study groups](#15-friends-and-study-groups)
16. [XP, levels, streaks and your bowl](#16-xp-levels-streaks-and-your-bowl)
17. [Customise: avatar, wallpapers, sounds, codes](#17-customise)
18. [Music player](#18-music-player)
19. [Settings and accessibility](#19-settings-and-accessibility)
20. [Keyboard shortcuts](#20-keyboard-shortcuts)
21. [Where your data lives and privacy](#21-where-your-data-lives-and-privacy)
22. [Limits to know about](#22-limits-to-know-about)
23. [Troubleshooting](#23-troubleshooting)
24. [Words you will see](#24-words-you-will-see)

---

## 1. Quick start

1. Open Noodle and press **Start studying** on the landing page, or **Try sample notes** to jump straight in. Choose **Continue as guest** or **Continue with Google**.
2. Press **New study set**.
3. Paste notes into the box, or press **Upload file** and pick a PDF, PowerPoint or text file.
4. Under **Start with**, pick an activity such as **Flashcards**, then press **Cook it**.
5. Play. Your XP is added when you finish, and you will see it fill your bowl on the home page.

Next time, open the set from your home page and pick any other activity. Noodle remembers what it has already cooked.

---

## 2. Signing in with Google

Choose **Continue as guest** to start without Google, with a 50p lifetime AI trial shared across your network. Choose **Continue with Google** for your own £5 monthly AI allowance, and from then on your sets, XP, streak and bowl are saved to that account and follow you to every device. When cloud sync is off (a local copy of the app with no Supabase), there is nothing to sign in to and progress stays in this browser.

### The sign-up gift

When you sign up, a **Welcome gift unlocked** box lists what you got: **10 random avatar items and 10 random wallpapers**, with **Take a look** to open Customise.

### Keeping your guest progress

Your guest session is remembered in this browser. Returning guests can continue studying without Google. In Settings, add your Google account to keep your guest sets and XP and unlock the signed-in allowance. If that Google account already has a Noodle account, choose **I already have a Noodle account** instead. That opens it, and it does not merge the guest progress into it.

### Questions

The home page has a **Got a question?** card with a **Join the community** button, which opens the Noodle WhatsApp community.

### Signing out

Press **Sign out** in Settings. Choose Google or **Continue as guest** when you return. A remembered guest is restored when its session is still valid; clearing browser data can lose access to guest progress, but does not reset the network trial.

**Your username.** After your first Google sign-in, Settings asks you to choose a username once. It appears on your bowl and on leaderboards. You can change it later in Settings.

---

## 3. Making a study set

A **study set** is a title, your notes and an optional focus. Each set can hold one saved copy of each activity.

### Adding notes

- **Paste** into the **Notes** box, or
- **Upload file**: `.txt`, `.md`, `.csv`, `.rtf`, `.pdf` or `.pptx`.

Things to know:

- Files are read in your browser. PDFs need selectable text, unless you tick **Read pictures and diagrams too** before you upload (see [Pictures and diagrams](#pictures-and-diagrams)).
- You need at least 50 characters.
- Games use the first 60,000 characters. Cheat sheets read everything.
- Slides that are about running the course (agenda, deadlines, contacts, reading lists, "any questions?") are skipped automatically, so a quiz never asks who the lecturer is. The status line under your file says how many were skipped.
- After you upload, the notes box becomes **Extra notes (optional)**. Use it to add anything the file lacks.

### Adding more later

Open the set and use **Add extra notes & material**. Paste text, or choose one or more `.txt`, `.md`, `.csv`, `.rtf`, `.pdf` or `.pptx` files, then press **Add to study set**. Your original notes stay, and the new text is added after them. A set can hold 60,000 characters in all, and the panel shows how close you are. Activities you already cooked, cheat sheets and lecture rooms stay as they were, so press **Cook a fresh batch** in an activity to include the new material.

### Pictures and diagrams

Tick **Read pictures and diagrams too** beside **Upload file**, before you choose the file, and Noodle reads the pictures as well as the text. It works on:

- **Scanned PDFs and photos of pages** (PNG, JPEG or WebP), which have no text of their own. Noodle reads the writing off them, handwriting included. Words it cannot make out are marked [unclear].
- **Diagrams, graphs, tables and figures inside a PDF.** Noodle writes each one into the page's text in square brackets, like `[Figure: a graph of speed against time ...]`, with its labels, axes, values and what connects to what. Games, summaries, cheat sheets and practice papers then know about it.

Each page is drawn in your browser and sent to the AI as a picture. It is free: it runs on a free University-hosted model, so it does not use your AI allowance, for up to 30 pages of each file. Pages after the 30th keep their text only. It is off by default, on the practice paper page as well as for new study sets, so no picture is read unless you tick it. Tick it before you add the files. A PowerPoint's pictures are not read, so save it as a PDF first if the pictures matter.

Noodle can misread a diagram, such as which way an arrow points or a value on a crowded graph, so check anything that matters against the original. If a page cannot be read, it keeps whatever text it had, and a line under the file says how many pages were read and how many were not. If your allowance runs out partway, the pages already read are kept.

### The other fields

- **Anything to focus on?** A short instruction, such as "focus on the Calvin cycle" or "explain it like I'm new".
- **Subject** (optional). Type a course name like `Biology 101`. Sets with the same subject are grouped on your home page and can be fused. Existing subjects are suggested as you type, so you spell them the same way each time.

### Textbook and lecture (optional)

Add the course textbook and a lecture transcript here. Noodle then says where each answer is covered. Full details are in [section 9](#9-textbook-lecture-and-references).

### Start with

Pick what to make first:

- **Just save it** keeps your notes and files without generating anything. This is the default when you upload a file. Open the set later and choose.
- **Annotated slides** (only for a PDF or PowerPoint). See [section 10](#10-annotated-slides).
- Any activity from [section 6](#6-the-activities). Each shows its own options (how many cards, difficulty, level of detail).

### Your upload: keep or delete

When you add files you choose:

- **Keep it for later** (default). The set and your files stay until you delete them.
- **Delete when I leave**. The set, its files and anything made from it are removed once you close Noodle. A reload never deletes anything. You can press **Keep it instead** on the set page first.

### Cooking time

Cooking asks the AI, which can take from a few seconds to about a minute. With the free AI, big jobs are slower. You can press **Cancel** at any time. While you wait you will see a little ramen being made.

---

## 4. Your home page and subjects

The home page has:

- A greeting and today's progress toward your daily goal.
- **Your study sets**, with buttons for **Join a room**, **Fuse topics** and **New study set**.
- **Lecture rooms** you are in, and saved copies of rooms that have closed.
- **AI allowance**: how much AI is left. Signed-in accounts see their monthly reset date; guests see their remaining lifetime trial and a Google sign-in prompt. See [section 22](#22-limits-to-know-about).
- **Invitations** from friends, along the top of every page. See [section 15](#15-friends-and-study-groups).
- Your bowl, a 7-day flame strip, and a leaderboard of you and your friends (top 10, plus your own place).
- **Noodle in numbers**, a small panel showing total noodlers and an **I'm interested** button to express interest.

### Subjects work like courses

Your sets are grouped by **subject**, like the courses on Blackboard.

- Each subject is a header showing how many sets it has. Press it to fold the group away or open it. Noodle remembers which ones you folded.
- Sets with no subject sit together under **No subject yet**.
- If none of your sets has a subject, you see a plain list and a hint to add one.
- **To put a set in a subject:** open the set and use the **Subject** box under its title. Type a new one or pick an existing one. It saves when you click away or press Enter.
- Fusions (see [section 11](#11-fusion-mixing-topics)) sit under the subject of the sets they were made from.

### Your friends leaderboard

The card shows you and your friends by XP. **Add friends** (or **N requests** when someone is waiting) and **Groups** take you to Social.

---

## 5. The study set page

Open a set to reach everything you can do with it. From top to bottom:

- **Title, Delete set, Subject.** **Delete set** removes the set and everything cooked from it. It cannot be undone.
- **Show notes** opens a viewer for your file, or the text Noodle read.
- **Add extra notes & material** adds more text or files to the set without replacing your original notes (see [Adding more later](#adding-more-later)).
- **Teach Noodly** ([section 7](#7-teach-noodly)).
- **Instant Ramen**.
- **Annotate with classmates** (a lecture room, when cloud sync is on).
- **Personal tutor** ([section 7](#personal-tutor)).
- **Cheat sheet** (see [section 12](#12-cheat-sheets-practice-papers-and-anki-export)).
- **Practice paper** (see [Practice papers](#practice-papers)).
- **Annotated slides** (for PDF and PowerPoint sets).
- **Textbook and lecture** to add or change sources.
- **Take your cards to Anki**.
- **Learn it** and **Ramen Run**: the tiles for each activity. A tick means it is already cooked. Press a tile, set options, then **Play**, **Cook a fresh batch** or **Cook and play**.

---

## 6. The activities

If you leave a game halfway, the XP you already earned is still saved. Where an activity has options, you can choose how many (cards, pairs, questions or categories), the difficulty (easy, medium, hard) and the level of detail (brief, standard, in depth).

### Learn it

| Activity | What you do |
|---|---|
| **Summary** | Read the key ideas and key terms. **Copy summary** copies it. Finish with **I've read it** for a small XP bonus. |
| **Flashcards** | Flip a card, then choose **Still learning** or **Got it**. Missed cards come back a few cards later. Use **Hint** or **Memory hook** before flipping. A heatmap under the deck shows how many cards you reviewed each day over the last year, like Anki's, and is kept in this browser. |
| **Layered Cards** | Drag the **Pull for help** slider to reveal a hint, then the answer, then a memory hook. The less help you pull, the more XP. |
| **Noodle Radio** | A 60-second podcast where two hosts, Miso and Shoyu, talk about your notes. Press **Play**, **Pause** or **Resume**, and **Skip line**. The transcript is shown below. |
| **Untangle Canvas** | Your notes drawn as a tangled mind map. Tap a concept, say what it means, press **Show answer**, then **I knew it** if you did. Known concepts straighten out. **Build the whole map** draws it all at once and **Show all answers** reveals every answer. Your progress is saved. |

**Noodle Radio voices.** Use the **Voices** switch. **Studio voices** run an AI voice model in your browser. The first time it downloads about 90 MB, then it is cached. **Device voices** use your browser's built-in speech, and are used automatically if the studio voices cannot load. Press **I read the transcript** if you would rather read.

### Ramen Run (games)

| Activity | What you do |
|---|---|
| **Match the Strands** | Pair every term with its meaning against the clock. Combos earn bonus. Your best time is saved. |
| **Fill in the Gaps** | Type missing key terms into a summary. The check ignores case and punctuation and allows one typo in longer words. **Check answers** marks them, **Show answers** reveals them. |
| **Speed Slurp** | 60 seconds of rapid-fire multiple choice. Streaks of three or more add bonus. A review of your answers comes at the end. |
| **Target Practice** | 60 seconds of moving targets. Shoot the right answer for +10 plus a bonus for speed and streaks. A wrong target costs 8 and breaks your streak, and letting targets get away costs 3. |
| **Timed Quiz** | Multiple choice with a countdown (30, 25 or 20 seconds by difficulty). Faster answers earn more. A hint costs XP. |
| **Error Check** | A summary with exactly three false sentences hidden in it. Tap the lies. |
| **Jeopardy** | A board of categories with three clues each, easiest to hardest. Read the clue, then type the question ("What is...?"). Other wordings that mean the same are accepted. One hidden tile pays double. Hints, then analogies, cost XP. If you meant it, press **I meant that, count it** for half the XP. |

### Instant Ramen (cram)

Three minutes of the highest-yield questions with generated music and double XP. Start it from the big orange panel on a set page. Finishing one unlocks the sweet corn topping.

### XP you earn

These are the numbers you see in the app, which already include the **double XP** every game pays.

| Activity | XP |
|---|---|
| Summary | 20 for finishing |
| Flashcards | 12 per card the first time, 6 after a miss |
| Layered Cards | 20 with no help, 12 with the hint, 6 with the answer, 4 with the memory hook |
| Noodle Radio | 20 for listening to it, 10 for reading |
| Untangle Canvas | 10 per concept |
| Match the Strands | 16 to 32 per pair, more for a longer combo |
| Fill in the Gaps | 12 per gap right on the first check, 8 after |
| Speed Slurp | 8 to 14 per right answer, more for a longer streak |
| Instant Ramen | 16 to 28 per right answer |
| Target Practice | About half your final score |
| Timed Quiz | Up to 30 per question, less with a hint |
| Error Check | 24 with no false alarms, 16 otherwise |
| Jeopardy | 8, 12 or 16 by row, minus 4 for each hint or analogy, doubled on the hidden tile |
| Fusion | 24 with no help, less for each hint or analogy |
| Teach Noodly | Up to 70 (see [section 7](#7-teach-noodly)) |
| Annotated slides | 2 for each slide annotated for the first time, up to 100 for one run (see [section 10](#10-annotated-slides)) |
| Showdown | 8 per right answer, plus placement (see [section 13](#13-showdown-live-quizzes)) |

Teach Noodly, annotated slides and Showdown are not doubled.

### Where you see the answer's source

If you added slides, a textbook or a transcript, answers show small chips like **Slide 12** or **Textbook p. 42**. See [section 9](#9-textbook-lecture-and-references).

---

## 7. Teach Noodly

Teaching is one of the best ways to find out what you really know.

1. Open a set and press **Start teaching**.
2. Type a concept (for example "photosynthesis") or pick one from **From this set**. **Pick one for me** chooses one at random.
3. Explain it in your own words, as if to a friend who has never heard of it. Do not copy from your notes.
4. Noodly plays a confused student and asks questions about the parts you skipped or got wrong.
5. You can explain up to **five times**. Press **I'm done** (or **Send and finish**) at any point after the first.
6. Noodly gives a verdict: how much of the idea in your notes came across, what you explained well, what you missed, and anything you said that your notes contradict, with the right version.
7. Press **Collect XP**.

**XP:** 60% of your understanding score, plus 10 more if it reaches 80 or above. That is up to 70 XP.

Press **Ctrl+Enter** to send. Noodly only judges against your own notes and never gives you the answer.

---

### Personal tutor

The **Personal tutor** card on a set page opens your whiteboards. Nothing on them is shared with a room.

**Choosing a board.** The first screen lets you start **New blank board**, or a new board on **Notebook lines**, **Squared paper** or **Dots**. Under **Your whiteboards** are the boards you have saved: **Edit** opens one again, **PNG** and **PDF** export it, and the bin deletes it.

**Saving.** Boards are kept on this device only. Press **Save** (or Ctrl+S) to keep one; the first time you give it a name. When you close a board, or go to any other page, with changes that are not saved, Noodle asks whether to **Save**, **Do not save** or **Keep editing**.

**Working a question.**

1. Choose your **Subject** in the tutor panel. It starts as the set's subject. Maths, Physics, Chemistry, Biology, Computer science and Economics each get their own way of helping (for example, Physics asks what is given and which principle applies before any numbers, and Chemistry balances the equation and goes through moles). **Something else** lets the tutor work out the subject from the question.
2. Copy a question as a picture (a screenshot or a photo works) and press **Ctrl+V**. The picture lands on the board. Drag its title bar to move it, or the circle on its corner to make it bigger. **Paste from clipboard** and **Choose a picture** do the same if your browser will not paste.
3. Work it out on the board beside the question. The tools are in a column down the left edge: move, pen, marker, shapes, eraser, then colour, thickness and style, undo, redo and erase. **Ctrl+Z** undoes and **Ctrl+Y** redoes. The wheel zooms, and the space bar or the middle button moves around.
4. Press **Hint** when you are stuck. The tutor looks at the question and at what you have drawn since you pasted it, and explains the next move without giving the answer. It says where it thinks your working has got to, and points out a line that has a slip. Everything it writes is typeset like LaTeX, with formulas and chemical equations set properly.
5. Press **Another hint** if you still need more. Each hint is more concrete than the last: first which idea to try, then what to do to the first step, then that step worked through. The hints scroll inside the panel.
6. Press **Show the answer** (it appears after your first hint) when you do not want any more hints. The tutor works the whole question through, step by step with the reason for each step, and says where your working went wrong if it did.

**The tutor can step in.** While you work, the tutor looks over your board when you pause, and speaks up only if something is really wrong and will send you the wrong way, such as the wrong method or a mistake early on that spoils everything after it. It waits at least 15 seconds after you stop writing. It stays quiet for ambiguous handwriting, unfinished substitutions, crossed-out work, valid alternative methods, and small slips you will probably catch yourself. A proposed interruption must include a readable, completed line and a specific substantive error; a second fresh check must independently identify the same line and error before anything appears. Uncertain, disagreeing or failed checks stay quiet. When it does, a card headed **The tutor stepped in** asks you to **Check this step**, quotes the particular line it read and gives a short nudge without giving the answer. It can still misread handwriting, so compare the quoted line with your actual work. It checks at most once every 15 seconds, only after you have written a few new marks, and no more than 8 times for one question. Use the **Tutor can step in** switch at the top of the tutor panel to turn it off or on. It is remembered on this device, and turning it off cancels a check that is already running. With it off, the tutor only answers when you press **Hint** or **Show the answer**. A **High AI usage** warning beside the toggle explains that automatic checks can use up your AI allowance quickly. Automatic checks use your AI allowance; a possible error triggers a second verification call and therefore costs more than a quiet check. Turn automatic checks off and ask for hints when needed to save usage.

If you ask for a hint while your working is heading the wrong way, the hint says so first and then points you back in the right direction. It still does not give the answer.

**Exporting.** **PNG** saves the board as a picture and **PDF** as a one-page PDF, each cropped to what is on it with the paper pattern, the question and your marks.

If the tutor writes a formula without its dollar signs, Noodle still typesets it, so you do not see raw symbols like `int_0^1` in a hint.

A hint costs a fraction of a penny of your AI allowance and has its own rate limit of 40 every 10 minutes. Paste a new picture to start another question; marks drawn before it are left out of the next hints.

## 8. Still Tangled

When a card, answer, key term or mind-map node does not click, press **Still tangled?**. Noodly explains it as an analogy from your own interests, with a table showing which part of the analogy matches which part of the real idea.

Choose up to three interests (Sports, Gaming, Music, Anime, Cooking and more) in **Settings**.

---

## 9. Textbook, lecture and references

You can add two extra sources to any set: a **course textbook** and a **lecture transcript**. Noodle then tells you where in your own material each idea is covered.

### Adding them

- **When making a set:** use the **Textbook and lecture** section on **New study set**.
- **Later:** open the set and use the **Textbook and lecture** section on its page. This works for sets you made before, and references appear in games you already cooked.
- **On annotated slides:** the same panel is on the slides page.

**Textbook.** A PDF, text or PowerPoint file. Optionally fill in **Pages to use** with a range like `42-67, 80` so Noodle only searches the chapters you need. Page numbers count pages in the file, which can differ from the numbers printed on the pages.

**Lecture transcript.** A `.txt`, `.vtt` or `.srt` file, or press **Paste text instead**. Subtitle files keep their timestamps, so references show the time.

### What you see

Under answers, explanations and summary sections, small chips appear:

- **Slide 12**: the slide that covers it.
- **Textbook p. 42**: the textbook page.
- **Lecture 23:10**: the moment in the lecture (or **Lecture, 40% in** for plain text with no times).

Press a chip to read the passage it matched, so you can check it. Press again to close.

They show in flashcards, layered cards, all the quiz-style games, Jeopardy, Error Check, the mind map, Fill in the Gaps (once answers are shown), Match (a list under the board) and the summary. Noodle Radio does not have them.

### Good to know

- References are found by matching keywords in your own browser. Nothing extra is sent to the AI, and Noodle never invents a page number.
- An idea the textbook words very differently may get no chip. That is normal.
- Scanned textbooks have no text to search.
- Your textbook and transcript stay on the device you added them on.

---

## 10. Annotated slides

Turn a PDF or PowerPoint into printed-style pages with key points hand-inked around each slide, like OneNote.

1. Upload a PDF or PowerPoint on **New study set** and pick **Annotated slides**, or open an existing set and press **Annotate my slides**.
2. Choose **Level of detail**: Brief (2 short points), Standard (2 to 4) or Thorough (4 to 6 fuller points with examples).
3. Choose **Language**: Simple terms, Standard or Advanced terminology.
4. Optionally add a textbook and transcript so points cite them (see [section 9](#9-textbook-lecture-and-references)).
5. Press **Annotate with Noodle**. Slides are written in batches. The free AI waits about 15 seconds between batches, so long decks take a while.
6. If it stops, press **Finish the last N** to continue where it left off. Results are saved after every batch. **Annotate again** starts over.
7. Press **Download PDF** for the inked slides or **Download notes** for a Markdown file.

Notes:

- Up to 60 slides are shown.
- Each point is tied to an exact phrase on the slide with an ink loop around it, and a point that comes from the textbook or lecture says so.
- Slides that are not study content are left alone.
- Annotating earns **2 XP for each slide annotated for the first time**, up to 100 XP for one run. A slide that already has notes earns nothing again, so annotating a deck twice does not pay twice.
- PowerPoint slides are redrawn simply: text and pictures, not themes, charts or effects.
- Annotations are saved on this device.

---

## 11. Fusion: mixing topics

Fusion writes questions that need ideas from several of your topics at once.

1. Give two or more sets the **same subject** (see [section 4](#4-your-home-page-and-subjects)).
2. On the home page press **Fuse topics**, or press **Fuse with other [subject] sets** on a set page.
3. Pick **2 to 4** sets, choose how many questions (6, 10 or 15) and the difficulty.
4. Press cook. The result is saved as its own set, shown under that subject.

Fusion questions list the topics they connect. If you are stuck, **hints come in steps**: first a nudge, then an everyday analogy. Each step costs XP, so try without first. After a wrong answer, **Still tangled?** explains it through your interests. Answer with keys **1 to 4** and press **Enter** for the next question.

---

## 12. Cheat sheets, practice papers and Anki export

### Cheat sheet maker

A dense one or two page exam sheet in LaTeX and PDF, made only from your slides or notes. It works for courses up to 1000 slides.

1. Open a set and press **Make a cheat sheet**.
2. Choose **Length** (1 or 2 A4 landscape pages) and **Columns** (3, 4 or 5).
3. Press **Make my cheat sheet**. Long courses are read in batches of about 25 slides, and each batch is saved, so you can stop and press **Carry on** later.
4. Changing the length or columns re-fits the sheet straight away without reading again. **Make it again** starts a fresh read.
5. Press **Download PDF**, **Download .tex** or **Copy LaTeX**.

Admin and blank slides are left out, and the page tells you how many. The sheet only uses what is in your material, so a short course may not fill the page.

> The **Cheat sheet** panel on a set page is open to everyone. It keeps going in the background if you leave the page. There is no daily limit. If you have already made a sheet in the last 24 hours, Noodle asks before starting another, and tells you roughly what it will use and how much allowance you have left, since each sheet takes far more than a game does. Making it again from scratch asks the same way.

### Practice papers

Noodle writes you a brand new practice paper from your notes, with a mark scheme to check it against. Give it your past papers and it copies their format. Give it the course specification and it follows what is covered and how it is marked. It comes as LaTeX and as a PDF.

1. Open a set and press **Make a practice paper**.
2. If your past papers are scans or rely on diagrams, tick **Read pictures and diagrams too** first (it is off to start with), so Noodle reads the pictures as well as the text. Then press **Add documents** and pick one or more PDF, PowerPoint, text or picture files at once, or press **Paste text instead**. You can add up to 10. A file Noodle cannot read is named in a message and the rest are still added.
3. Under each document, say what it is: **A past paper**, **The course specification** or **Notes**. New documents start as past papers, so change the label if you add something else.
4. Choose **What subject is it?**: Maths, Physics, Chemistry, Biology, Computer science, Economics & business, History/politics/philosophy/literature, Law, Psychology & social science or Medicine & health. Each has its own usual kind of paper, its own way of asking questions (for example linked "show that" problems in Maths, a case to advise on in Law, a clinical vignette in Medicine) and its own style of mark scheme. Leave it on **Not sure** and Noodle works the style out from your notes. A past paper or specification you add always comes before the subject's usual style.
5. Choose **How hard should it be?**: about the same as your past papers, a bit harder or a bit easier. You can also type **Anything to focus on?**, such as "mostly chapters 3 and 4".
6. Press **Make my practice paper**. Noodle plans the paper, writes its questions, then writes the mark scheme, and a picture shows how much of the paper is made: a block for every question, which fills as it is written and gets a tick once its mark scheme is done. A paper usually takes 30 to 60 seconds, and you can press **Cancel** while you wait.
7. The paper and its **Mark scheme** both appear on the page, one under the other. Each has its own **Download paper PDF** or **Download mark scheme PDF**, **Download .tex** and **Copy LaTeX** buttons, so you can take both.

**Subjects with Paper 1 and Paper 2.** If your past papers show that the exam is sat as more than one paper, Noodle writes each of them in the layout of that paper, with its own time, sections, marks and mark scheme, one after another. The second paper is told what the first asked, so it does not repeat it. If something goes wrong partway, the papers already written are kept and a **Write paper 2** button carries on from there.

What Noodle takes from each kind of document:

| You add | Noodle uses it for |
|---|---|
| **A past paper** | The format: the sections, how many questions, what kinds (multiple choice, short answer, calculations, essays), how many marks each is worth, the time allowed and how the questions are worded. It never copies a question or takes a fact from a past paper. More than one helps Noodle see what stays the same from year to year. |
| **The course specification** | What is in scope, how much each topic matters, which skills are assessed, and how the exam is set up (time and marks), when there is no past paper to copy. |
| **Notes** | More to ask about. Slides, a textbook extract or a lecture summary are used for questions, on top of the set's own notes. |

Every question has to be answerable from your set's notes and any **Notes** documents, so a topic your past papers or specification cover that those do not is left out. You need at least one document. If none of them is a past paper or the specification, Noodle writes the layout that is usual for the subject you chose, or an ordinary exam layout if you left it on **Not sure**.

**How demanding it is.** Noodle aims for the demand of a real paper, not only its topics, wherever the subject allows it. Longer questions are in linked parts, where a later part needs the result of an earlier one, and a result may be given to "show that" so the next part can still use it. Questions do not hand you exactly the numbers one formula needs: you work out intermediate quantities, choose the method and combine ideas from different topics. There are derivations and "show that" or "prove that" questions where the subject has them. The paper cannot draw, so a set-up such as a ramp, a beam or a spring is described fully in words (lengths, angles, masses, what is attached to what) so that you could draw it yourself. Early questions are short and direct, and the last ones are the longest and hardest.

The question numbers, part letters, marks, time and total marks are all printed by Noodle in one layout, so every question looks the same and the numbers are never repeated. The total on the front is added up from the questions, so it always agrees with them. When a section lets candidates choose ("answer ONE question"), only the questions they have to answer count. If the AI aimed for a different total from what its questions add up to, the page says so. If any question follows one of your past paper questions word for word, the page tells you, and **Make a new paper** writes a different one. Each mark scheme says where the marks are earned. It is written in a separate step, on a stronger model than the one that wrote the questions. It is still written by AI and could have mistakes, so the mark scheme says so at the top, in the PDF and the `.tex` file too, and you should check any answer you are unsure of against your notes.

The `.tex` file is a complete document: compile it with `pdflatex`, or paste it into Overleaf. The PDF is drawn from the same layout, so it looks the same.

Things to know:

- **Diagrams in your past papers are taken into account** when **Read pictures and diagrams too** is ticked: the new paper sets questions of the same kind. It cannot draw pictures, so each question that needs a figure gives the labels, values and layout in words or as a table instead.
- A PowerPoint's pictures are not read. Save it as a PDF first.
- The AI sometimes writes LaTeX with faults, such as every backslash doubled, a brace left open, or `\(` `\)` and `$$` instead of dollar signs. Noodle mends these before the paper is shown or written to the `.tex` file, so the formulas come out as they should. A formula it cannot mend, such as one that uses a command that does not exist, is shown as plain text instead of breaking the page or the file. If a formula arrives with no dollar signs at all, or with a command that lost its backslash (like "frac{1}{2}" for a fraction), Noodle cannot tell by rule what is maths, so it sends just those pieces of text back to the AI to be typeset, changing nothing else. If that fails or there is too little time, the text is kept as it was.
- Your documents and the paper you made stay on this device. Their text goes to the AI only when you press **Make my practice paper**.
- The subject you choose only decides the fallback style. A past paper or specification you add always comes first, so a Maths paper made from your own past paper follows that paper's layout.
- A set keeps one paper. Making another replaces it, and Noodle asks first.
- Noodle writes papers of its own. They are good practice, but they are not your real exam, so check any worked answers you are unsure of against your notes.

### Anki export

On a set page, **Take your cards to Anki** turns your cooked Flashcards, Layered Cards, Match pairs, Quiz questions and Fill in the Gaps into one text file.

1. Cook those activities for the set first.
2. Press **Download for Anki** to save the file.
3. In Anki choose **File, Import** and pick the file. It makes a deck named after the set, tagged with `noodle`, the set and the activity.

---

## 13. Showdown: live quizzes

A Kahoot-style live quiz built from one of your sets. Open **Showdown** in the navigation.

### Hosting

1. Press **Host a game**, then choose one of your sets.
2. Choose how it runs:
   - **Central host**: you run the game from a big screen and everyone answers on their phone. You press the button for the next question. You do not play.
   - **No central host**: everyone plays on their own device, you included. The leaderboard shows after each question and the next one starts by itself.
3. Choose how many questions: **10, 15, 20, 25 or 30**, limited by how many the set has.
4. Pick your avatar if you are playing.
5. Press **Host this Showdown** (or **Host with no central host**). A **4-letter code** appears. Players type it, or you press **Copy join link**. Press **Invite friends** to send the game straight to friends in Noodle (see [section 15](#15-friends-and-study-groups)).
6. Press **Start with N players** once people have joined. With no central host you need at least two players.

### Joining

1. Open **Showdown** and press **Join a game**, or open the link you were sent, which fills the code in for you.
2. Type the code, pick a name and a character, and join.
3. Wait for the host. Each question lasts 20 seconds and ends early when everyone has answered. Faster correct answers score more. Answer buttons lock when time runs out.

### Scoring and XP

- A correct answer scores 500 points plus up to 500 for speed.
- Hosts earn 15 XP. Players earn 8 XP per correct answer, plus 20 XP for first place or 10 XP for second or third.
- Your wardrobe outfit is shown next to your name.
- Players cannot see the right answer before it is revealed.

> With no cloud sync, Showdown only connects tabs on the same device. That is handy for trying it out. Anyone who knows the 4-letter code can join, so share it only with people you want.

---

## 14. Lecture rooms

Annotate a lecture together with classmates, live. Lecture rooms need cloud sync to be on.

### Starting a room

1. Open a set (a slide file works best) and press **Start a lecture room**.
2. Share the **6-character join code** or copy the link. Only people you send it to can join.
3. Classmates press **Join a room** on their home page and type the code, or open your link. The join page shows the lecture title and who is hosting, then asks for the name classmates will see.

You can also press **Invite friends** in the room to send an invitation to anyone on your friends list (see [section 15](#15-friends-and-study-groups)).

Press **New code** if you need to stop the old code working. People already inside stay in. A code can be guessed, so a person gets only 12 wrong tries per 10 minutes.

### Annotating

Choose a tool under **Annotate by**:

- **Highlighting text**: drag across words to pin a note to them.
- **Dropping a dot**: click anywhere to pin a note there.
- **Drawing**: pen, marker, line, arrow, box or circle, in any colour and thickness, with solid, dashed, dotted, neon and rainbow styles. Six quick pens are on hand, and your pen is remembered on that device.
- **Erasing**: removes whole strokes you touch. The host can erase anyone's.

Then type a note (up to 500 characters) and post it. Everyone sees it at once. Give a classmate's note a thumbs-up if it was helpful.

### Whiteboard

Switch to **Whiteboard** for a shared board with no edges. The tools are in a column down the left edge of the board: move, pen, marker, shapes, eraser, then a colour button that opens thickness and style, and undo and erase. The wheel zooms where your pointer is, a trackpad or two fingers pan and pinch, and dragging with the hand tool (**Moving around**), the space bar or the middle button moves around.

### Peer review

Anyone can ask an open question. Classmates write their own answer first, which unfolds the other answers, then thumbs-up or comment on them. Seeing answers only after answering is how the page behaves, not a secret.

### Seeing who is there

You see who is online or away, and classmates' pens move on your screen live.

### Host powers

The host can remove a member, reset the code, close the room, and delete any note.

### Saving and downloading

- **Save a copy** keeps the slides, notes and votes on this device, and keeps itself up to date as classmates add notes. Closing a room saves a copy for the host first.
- Saved copies appear on your home page and open read-only.
- Download a **PDF** (ink included) or **Markdown notes** (most helpful first).

> Your own uploaded slide file for a set stays on your device, and is only uploaded to a private store when you start a room.

---

## 15. Friends and study groups

Open **Social** in the navigation. You need to be signed in with Google, because names are shown to others. Only people you add, or groups you join, can see you.

### Friends

1. Open the **Friends** tab and search for a username.
2. Send a request. The other person accepts or declines it.
3. Friends appear on the leaderboard on your home page, showing name, XP and streak.

A number on the tab shows requests waiting for you.

### Inviting friends to a room or Showdown

In a lecture room, or on a Showdown you are hosting, press **Invite friends**. Your friends list opens with an **Invite** button beside each name. Friends already in the room are left out, and a friend you have invited shows **Invited**.

On their side, the invitation appears as a card at the top of any page: "**Name** invited you to annotate *lecture*" or "to a Showdown". Press **Join** to go straight in, or **Not now** to dismiss it. Noodle checks for new invitations about every 20 seconds while the tab is open. A Showdown invitation lasts 3 hours and a room invitation 14 days, and you can send up to 60 an hour. Friends and invitations need a Google account.

### Study groups

1. Open the **Groups** tab, type a name and press **Make group**, for your course or cohort.
2. Share its **8-character code**. Others open the same tab, type it under **Join with a code** and press **Join group**.
3. Members see a leaderboard of just the group, for **this week** or **all time**.

Limits: you can run 5 groups and join 10, with up to 100 members each. Only the person who runs a group can remove members or delete it.

---

## 16. XP, levels, streaks and your bowl

### XP and levels

- Every activity earns XP, and **every game pays double**. Teach Noodly and Showdown XP are not doubled.
- Your **level** counts lifetime XP, which never goes down. Level 2 needs 100 XP, level 3 needs 300, level 4 needs 600, level 5 needs 1,000, level 6 needs 1,500 and so on.
- Spending XP in the shop only lowers what you can spend, never your level.
- One award is capped at 400 XP.

### Daily goal

Your goal is 30, 50, 100 or 150 XP per day (change it in **Settings**, default 50). Crossing it counts as one goal day. The broth level in your bowl rises as you approach it, and steam appears when you hit it.

### Streaks

Study on consecutive days to grow your streak. Miss a full day and it resets. Days use your own time zone. The flame in the header is lit once you have studied today.

### Toppings

Toppings unlock free from achievements, or you can buy them:

| Topping | Free when you | Price |
|---|---|---|
| Scallions | Hit your daily goal once | 30 XP |
| Soft-boiled egg | Reach a 3-day streak | 60 XP |
| Naruto | Hit your daily goal 5 times | 90 XP |
| Nori | Reach level 3 | 120 XP |
| Sweet corn | Finish an Instant Ramen cram | 150 XP |
| Bamboo shoots | Hit your daily goal 10 times | 180 XP |
| Chashu pork | Reach a 7-day streak | 240 XP |
| Chili oil | Reach level 6 | 300 XP |
| Sesame seeds | Reach a 14-day streak | 360 XP |

Buying has no level or streak requirement. Do it on the **My bowl** page, which is under Customise.

### Sharing your bowl

On **My bowl**, press the share button to make a picture of your bowl. On a phone this opens the share sheet. Elsewhere it downloads.

---

## 17. Customise

Open **Customise** in the navigation. Spend your XP on how everything looks. It is meant to take a long time: items come in five rarities (common, uncommon, rare, epic, legendary), and the rarer ones cost far more and need a level, and sometimes an achievement.

| Rarity | Level needed | Typical price |
|---|---|---|
| Common | 1 | 250 to 800 XP |
| Uncommon | 3 | 650 to 2,000 XP |
| Rare | 6 | 1,500 to 4,400 XP |
| Epic | 9 | 4,200 to 8,600 XP |
| Legendary | 12 | 9,500 to 18,000 XP |

Some epic and legendary items also ask for an achievement, such as a 14-day streak, 30 daily goals or 5 Instant Ramen crams. What is missing is shown on the item.

### Wardrobe

75 avatar items in seven slots: hats, eyewear, neckwear, backdrops, frames, auras and colourways. They go on any of the eight free characters, and other players see them in Showdown.

- **Try on** any item first. Nothing is kept until you buy or wear it. **Put it all back** clears the trial.
- **Buy** an item with the button that shows its price, then press **Wear it** (or **Take off**). **Take everything off** removes your outfit.
- **Randomise my outfit** picks from what you own.

### Wallpapers

60 animated wallpapers to buy, plus the five Japanese scenes and a plain background that are free for everyone.

- **Preview** a wallpaper behind the page before buying.
- Press **Use it** to set it. A random button picks a free one for you.
- What you own also appears in Settings and in the header wallpaper shortcut.

### Sounds

12 sound packs that change the effects (tap, correct, wrong, flip, combo, level up). The sounds Noodle has always had are free. Preview a pack, buy it, then press **Use it**.

### Themes

33 themes that restyle the whole app: the buttons, cards, top bar and phone tab bar, the colours, the corners and the typeface. Some change colour only (Matcha, Blush, Lavender, Coral reef). Others change the shape too: Cloud and Bubble are soft and round, Terminal and Blueprint are monospace and square, Arcade is chunky, Old library is all serif, Neon nights and Ember glow, Frosted glass, Aurora and Holographic have see-through cards and a coloured top bar, and Graphite keeps everything grey except right and wrong answers. **High contrast** is black and white with heavy outlines. Classic Noodle, the look Noodle has always had, is free.

- Every theme has a night and a day version, so the **Light or dark** switch in the header and Settings still works.
- Each card shows a live sample. **Try it on the app** applies a theme to everything until you press **Stop trying** or leave the page. Nothing is kept until you buy or use it.
- Buy a theme, then press **Use it**. A theme you own is used on this device only, like wallpapers and sounds.
- The Noodle wordmark keeps its own typeface in every theme.

### Matching wallpaper and theme pairs

Ten of the wallpapers come with a theme of the same name and colours: Orbital Garden, Clockwork Observatory, Crystal Cavern, Paper Sea, Dream Railway, Bamboo Moon, Floating Islands, Prism Rain, Living Reef and Celestial Library. They are bought separately, one on the Wallpapers page and one on the Themes page, and each sells at the same price. On either page, the card for one of these shows **Preview matching pair**, which tries the wallpaper and theme together until you press **Stop pair preview**. Once you own both, **Use matching pair** sets them in one go.

### My bowl

Toppings and sharing (see above).

---

## 18. Music player

The small pill in the top bar opens a study music player.

- **Noodle** plays the music files provided with the app, and always has **Noodle piano**, a calm piano the browser makes up live.
- **Spotify** plays a playlist, album or song you paste a link to (in Spotify, tap Share, then Copy link). Logged out, Spotify only plays 30-second previews. You can log in from inside the player, and **Change link** switches to another.
- Controls: play and pause, previous and next, **Shuffle**, **Repeat** (off, all or one), a seek bar, volume and a queue.
- Titles come from the file names. Shuffle and repeat are on by default, and your choices and volume are remembered.
- The music keeps playing when you switch tabs. On phones, lock-screen controls work.
- Instant Ramen lowers the music while its own soundtrack plays.

---

## 19. Settings and accessibility

Open **Settings**. Everything saves automatically.

| Setting | What it does |
|---|---|
| **Username** | Your name on your bowl and leaderboards. |
| **Daily goal** | 30, 50, 100 or 150 XP. |
| **Interests** | Up to three, used for Still Tangled analogies. |
| **Light or dark** | **Night** (default) or **Day**. This works with whatever store theme you use. Your store theme is chosen on the Themes page. |
| **Sound effects** | On or off. A mute shortcut is in the header too. |
| **Animations** | Use device setting, on, or off. |
| **Dyslexia-friendly reading** | Switches the whole app to the OpenDyslexic typeface with wider letter and word spacing, taller lines and no italics. The font downloads the first time you turn it on. |
| **Text size** | Normal, Large (125%) or Extra large (150%). The whole app scales, including buttons and the top bar. |
| **Text spacing** | **Wide** adds space between letters, words and lines. Dyslexia-friendly reading has its own spacing and takes over if both are on. |
| **Keyboard focus outline** | **Thick** draws a heavy outline around whatever you have reached with Tab, in the text colour so it shows in every theme. |
| **Button and field size** | **Large** makes buttons and fields at least 44 pixels tall, an easier target on a phone or with a tremor. |
| **Solid backgrounds** | Draws cards and bars solid, without the see-through glass some themes use, so a wallpaper never shows behind words. |
| **Wallpaper** | Pick from the wallpapers you own. **See the whole wallpaper** hides the page so you can look at it. **Buy more wallpapers with XP** goes to the shop. |
| **Account** | Save progress with Google, sign in, sign out. |
| **Redeem a code** | At the very bottom of the page. Each code gives you 5 random free avatar items and 5 random wallpapers, and tells you if you already own everything it could give. You need to be signed in with Google. |

### Header shortcuts

The top bar has your streak, your level, the music pill, and quick toggles for theme, wallpaper, sound and animations, so you rarely need to open Settings for those.

### Animations

Noodle follows your device's reduced-motion setting by default. On some Windows PCs "Animation effects" is switched off, which makes every site look still. If that is you, set **Animations** to **On** in Settings.

### Screen readers and keyboards

- **Skip to main content** is the first thing Tab reaches on every page, so you can jump past the navigation.
- When you go to another page, the browser tab title changes to the page's heading and a screen reader announces it.
- The Untangle mind map has a text outline in reading order and announces progress.
- Ink on slides and whiteboards is described in words: what was drawn, colours, who by and roughly where.
- Most games work from the keyboard. See the next section.

---

## 20. Keyboard shortcuts

| Where | Keys |
|---|---|
| Flashcards | **Space** flips. After flipping, **1** is still learning and **2** is got it. |
| Timed Quiz, Speed Slurp, Instant Ramen, Fusion | **1 to 4** pick an answer. **Enter** starts or moves on. |
| Target Practice | **1 to 4** shoot a target. **Enter** starts and continues. |
| Teach Noodly | **Ctrl+Enter** sends. |
| Lecture room | **Ctrl or Cmd + Z** undoes your last stroke. |
| Whiteboard | Hold **Space** and drag to move around. |
| Pop-up boxes | **Escape** closes. |

---

## 21. Where your data lives and privacy

| What | Where |
|---|---|
| Sets, XP, streaks, profile | Your account in the cloud if sync is on, otherwise this browser |
| Uploaded PDF or PowerPoint, annotations, textbook, transcript | This device only |
| Saved copies of lecture rooms | This device only |
| Documents added for practice papers, and the paper made from them | This device only |
| Theme, wallpaper, sound and animation choices | This browser |
| Downloaded voice model | Browser cache (about 90 MB, once) |

- Pictures of your pages are sent to the AI only when you tick **Read pictures and diagrams too** for that upload, and are not kept anywhere once they have been read.
- Your notes are sent to the AI only to cook an activity, annotate slides, explain an analogy, make a cheat sheet or play Noodly. The AI is told to use only what you gave it.
- Uploads are cleaned of hidden or control characters before anything reads them.
- Leaderboards show only a display name, XP and streak.
- You can only see your own sets and the rooms or groups you belong to.
- You cannot edit your own XP or streak. They are calculated and checked on the server.

---

## 22. Limits to know about

| Thing | Limit |
|---|---|
| Notes needed | At least 50 characters |
| Notes used by games | Up to 60,000 characters are kept, and a game reads 16,000 of them, sampled evenly from start to end so a long lecture is covered throughout (cheat sheets read all) |
| Uploaded file | 100 MB, up to 1,000 pages or slides |
| Text files and transcripts | 5 MB |
| Annotated slides shown | First 60 |
| Items per activity | Flashcards 3 to 25, quiz questions 3 to 30, match pairs 4 to 12 |
| Showdown questions | 10 to 30 |
| Fusion | 2 to 4 sets of the same subject |
| Reading pictures | Up to 30 pages of each PDF, 3 pages to a request, and photos of up to a few MB each. PowerPoint pictures are not read |
| Practice papers | Up to 10 documents (past papers, the specification, notes) per set. A paper has at most 36 questions and 90 marks, so a longer past paper gives a shorter paper of the same kind. Each paper and its mark scheme use at most 15p |
| Teach Noodly | 5 explanations |
| Room notes | 500 characters |
| Study groups | Run 5, join 10, 100 members each |
| AI requests | About 20 per 10 minutes, with more for Teach Noodly (40), personal tutor hints (40), reading pictures (40) and cheat sheets (70). If you hit it, wait a few minutes. |
| AI allowance | Guests: 50p total, with no monthly reset. Signed-in accounts: £5 each month, starting again on the 1st. At most 300 AI requests a day. |
| Cheat sheets | No limit, but another one within 24 hours asks first and uses your allowance |

### What each feature costs

Everything that uses AI comes out of the 50p lifetime guest trial or the £5 monthly signed-in allowance, except reading pictures, which runs on a free University-hosted model and takes nothing from it. Guest trials are pooled server-side by network, so incognito, clearing cookies or making another guest on the same network does not create another allowance. People on shared Wi-Fi share this guest trial; signing in gives each person their own allowance. A changed network or VPN cannot reliably be identified as the same anonymous person. The home page shows how much you have left. This table shows what each feature costs, measured by running every one on a real 57 slide lecture deck (about 27,600 characters of text: "REST APIs, Exception Handling, Logging, Configuration, Actuator and Docker"). Costs are in pence at OpenAI's list prices, and what comes off your allowance can be a little lower, because when the AI re-reads the start of the same notes (for example cooking several games from one set), that repeated part is billed at a cheaper rate and Noodle counts it that way.

| Feature | AI requests | Tokens in / out | Cost | Uses in £5 |
|---|---|---|---|---|
| Flashcards (10 cards) | 1 | 3,543 / 632 | 0.11p | about 4,500 |
| Layered Cards (8 cards) | 1 | 3,556 / 836 | 0.13p | about 3,800 |
| Fill in the Gaps | 1 | 3,550 / 452 | 0.09p | about 5,300 |
| Match the Strands (6 pairs) | 1 | 3,519 / 107 | 0.06p | about 8,100 |
| Timed Quiz (10 questions) | 1 | 3,578 / 1,025 | 0.15p | about 3,400 |
| Speed Slurp (20 questions) | 1 | 3,571 / 1,043 | 0.15p | about 3,400 |
| Target Practice (20 questions) | 1 | 3,610 / 1,110 | 0.16p | about 3,200 |
| Instant Ramen (20 questions) | 1 | 3,589 / 1,166 | 0.16p | about 3,100 |
| Error Check | 1 | 3,589 / 471 | 0.10p | about 5,200 |
| Summary | 1 | 3,543 / 847 | 0.13p | about 3,800 |
| Untangle Canvas | 1 | 3,588 / 480 | 0.10p | about 5,100 |
| Noodle Radio | 1 | 3,605 / 346 | 0.09p | about 5,900 |
| Jeopardy | 1 | 3,740 / 328 | 0.09p | about 5,800 |
| Fusion (10 questions) | 1 | 3,771 / 2,145 | 0.25p | about 2,000 |
| Still Tangled (one metaphor set) | 1 | 323 / 312 | 0.03p | about 14,700 |
| Teach Noodly (each reply) | 1 | 5,657 / 90 | 0.46p | about 1,100 replies |
| Annotated slides (54 of the 57 slides) | 5 | 8,577 / 5,518 | 0.64p | about 780 decks |
| Cheat sheet (the whole deck) | 2 | 7,203 / 5,797 | 7.8p | about 64 sheets |
| Practice paper with mark scheme | about 7 for each paper | about 25,000 / 3,200 | about 5p for each paper (never more than 15p), so about 10p for a Paper 1 and Paper 2 | about 100 papers |
| Reading pictures, per page | 1 for every 3 pages | about 750 / 250 | free | no limit from the allowance |

- **The 14 games and activities average about 0.13p each**, so one study session of several games costs a fraction of a penny.
- **Annotated slides** leaves out obvious admin slides (3 of the 57 here) before any AI is used, and sends the rest 12 at a time.
- **Teach Noodly** costs more per reply because the AI reads your notes again every time, but a whole 5 reply session is still about 2.3p.
- **Cheat sheets** use a stronger model so they are accurate, which is why they cost the most. If you make another within 24 hours, Noodle tells you roughly what it will cost before it starts.
- **Reading pictures** is free, since it runs on a University-hosted model that costs nothing to run. It is still limited to 40 requests every 10 minutes (3 pages to a request), so a long PDF takes a little while.
- **A practice paper** was measured on a 60 mark, 9 question paper made from two long past papers and about 11,000 characters of notes. Planning it cost 0.7p and writing its questions 1.2p, both on `gpt-5.6-luna`. Its mark scheme is written on the strongest model, `gpt-5.6-terra`, because a wrong answer in a mark scheme teaches the wrong thing, and that cost 3.3p, 5.2p in all. It reads a fixed amount of your documents and notes, so it costs about the same for any course. Noodle adds up what each step actually cost, and will not start a step that could take the paper past 15p, so the page can stop with a message rather than spend more. When some maths needs typesetting (see Practice papers), that one extra small request on the cheaper model costs a fraction of a penny and is counted in the same total.
- A bigger deck costs more in proportion for annotated slides and cheat sheets (a 1000 slide cheat sheet is roughly £1.40), but games always read at most 16,000 characters, so they cost about the same for any course.
- Guests who use their 50p trial must sign in with Google for the default free allowance. The guest trial never resets, including after an upgrade or account deletion. If allowance checking is unavailable, new AI requests pause until it recovers.
- Guests on one network generate one request at a time. If another guest request is running, wait and retry. Usage is recorded when an AI response finishes, so the last request can take the total slightly over the allowance before further requests stop.
- If you reach your monthly allowance, new AI requests are switched off until the 1st. What you already made still works.

---

## 23. Troubleshooting

**"That batch did not cook" or it is very slow.**
The free AI is rate limited and can cut long replies short. Press **Try again**, or cook a smaller set (fewer cards or questions). Shorter notes help too.

**My PDF says it has no text.**
Scanned PDFs have images of text, not text. Tick **Read pictures and diagrams too** before you upload the file and Noodle reads the pages as pictures, or use a PDF with selectable text, or paste the notes.

**The textbook or transcript is not showing references.**
Check that it was added (the set page's **Textbook and lecture** section shows its name). References only appear when at least two keywords match, so a loosely related item may have none. If you set **Pages to use**, only those pages are searched.

**My progress disappeared.**
Google-linked progress is saved to your account. Guest progress depends on keeping access to the guest session in this browser. Without cloud sync it lives in one browser, and clearing site data removes it.

**Lecture rooms or Showdown only work in my own tabs.**
Cloud sync is off, so they can only connect tabs on this device.

**Friends or groups are missing.**
They need a Google account. Sign in from Settings.

**I cannot redeem a code.**
Codes need a Google account. Sign in under **Account** in Settings first, then use **Redeem a code** at the bottom of that page.

**Everything looks frozen.**
Set **Animations** to **On** in Settings (see [section 19](#19-settings-and-accessibility)).

**A set vanished.**
It may have been made with **Delete when I leave**. Those are removed after the tab that made them closes. Choose **Keep it for later** next time, or press **Keep it instead** on the set page.

**I want to delete a set.**
Open it and press **Delete set**. This also deletes everything cooked from it and cannot be undone.

**There is no cheat sheet button.**
Everyone can make cheat sheets. Once one starts it carries on in the background while you use the rest of Noodle (keep the tab open), and the panel on the set page shows how far it has got and opens it when it is ready. If you close the tab, what was read so far is saved, and **Carry on** picks up from there without counting as another sheet.

---

## 24. Words you will see

| Word | Meaning |
|---|---|
| **Noodly** | The noodle mascot. It plays the confused student in Teach Noodly and explains analogies in Still Tangled. |
| **Cook it** | Ask the AI to generate an activity from your notes. |
| **Ramen Run** | The group of timed games. |
| **Instant Ramen** | The 3-minute cram with music and extra XP. |
| **Showdown** | The live multiplayer quiz. |
| **Untangle Canvas** | The mind map you straighten by recalling concepts. |
| **Still Tangled** | The button that explains something through your interests. |
| **Bowl and toppings** | Your progress picture and what you unlock. |
| **Study set** | Your notes plus everything cooked from them. |
| **Subject** | The course a set belongs to, used for grouping and Fusion. |
| **Tokyo Night** | The default dark theme. |
