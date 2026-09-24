---

layout: essay
type: essay
title: "Coding Standards Are Helpful (Until the Clock Starts)"
date: 2026-09-23
labels:

* Software Engineering
* Coding Standards

---

# Coding Standards Are Helpful (Until the Clock Starts)

The first time I used ESLint in VS Code, I understood why people like coding standards and why they can drive beginners a little crazy. I would still be halfway through writing a line, and an error would already appear. Sometimes it caught something useful. Other times, it seemed deeply concerned that I hadn't added a new line at the very end of my file. I was thinking about what my program was supposed to *do*, while ESLint was thinking about how I ended the document.

## The useful kind of interruption

Despite that frustration, I like having ESLint around. When I'm learning TypeScript, it's easy to overlook a small mistake while concentrating on the bigger problem. An error highlighted in VS Code gives me somewhere specific to look instead of leaving me to wonder why the program isn't working. Fixing those errors can also teach me the expectations of the language and the project. After seeing the same warning a few times, I start to recognize the pattern myself.

VS Code has made this experience better overall. I used the TypeScript Playground before, and it was convenient for trying out small pieces of code. But VS Code feels more useful when a project has multiple files. I can move between those files, use the terminal, and see problems in the editor where I'm working. It's a pretty user-friendly setup once I know where everything is.

## When every warning feels urgent

My opinion of coding standards changes a little during a timed Workout of the Day, or WOD. I'm already trying to understand the problem, choose an approach, write the code, and check whether it works before time runs out. Adding a list of ESLint errors makes it feel like there's one more task competing for my attention. The warnings that appear while I'm still typing are especially distracting because I haven't even finished expressing the idea yet.

The new-line-at-the-end-of-the-file rule is a good example of why beginners can find this frustrating. I can accept that a team wants its files to follow a consistent format. But when I'm racing against a clock, that warning doesn't feel as urgent as getting the program to produce the right result. Having both kinds of issues presented as errors can make it harder for me to decide what to focus on first.

## Why I still want standards

Outside a timed exercise, I think coding standards are awesome. If several people work on the same project, shared guidelines make the code easier to read and maintain. I don't want to spend time figuring out each person's preferred formatting before I can understand what their code does. Consistency also helps me revisit my own work later without feeling like every file was written by a different person.

So, do coding standards help someone learn a programming language? I think they can. ESLint gives me immediate feedback and pushes me to notice habits I might otherwise miss. But that feedback works best for me when I have enough time to understand *why* a rule exists. Under time pressure, I can end up fixing a warning just to make it disappear. When I can slow down, the same warning becomes a chance to learn.

I don't love every rule, and I definitely don't love seeing errors before I've finished typing. Still, after my first week with ESLint and VS Code, I would rather have those tools than go without them. The challenge for me is learning which messages point to a real problem with my code, which ones are about consistency, and when to deal with each. That feels like a useful software engineering skill in itself.

*AI use: I shared my own experiences and opinions about ESLint, VS Code, TypeScript Playground, and timed WODs with ChatGPT. It helped turn those ideas into an essay draft. I reviewed and edited the final wording before publishing.*
