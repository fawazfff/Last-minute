# LastMinute

**When you have too much to do and not enough time.**

[**Open LastMinute →**](https://fawazfff.github.io/Last-minute/)

**Live demo:** https://fawazfff.github.io/Last-minute/

## What is LastMinute?

Imagine you have homework, a presentation, a project, and studying to do before tomorrow.

All the work will take **8 hours**, but you only have **5 hours**.

A normal to-do list can put the tasks in a nice order, but you still have 8 hours of work and only 5 hours to do it.

**That is the problem LastMinute solves.**

LastMinute looks at:

- what you need to finish
- when you need to finish it
- how much time you really have
- how long each task may take

Then it checks if everything can actually fit before your deadline.

If there is not enough time, LastMinute helps you make a smaller plan that can actually work.

It puts your tasks into four simple groups:

### MUST
Things you need to do or the main goal may fail.

Example: If you are submitting an app, making sure the app works is a MUST.

### REDUCE
Things you should still do, but you can make them smaller or quicker.

Example: Instead of spending 1 hour writing a long README, write a shorter useful one in 20 minutes.

### DEFER
Things that are useful, but can wait until after the deadline.

Example: Adding an extra feature that is not needed for your submission.

### KILL
Things you should stop doing because they are taking time away from more important work.

Example: Spending an hour changing a logo when your main project is still broken.

LastMinute then gives you a realistic plan and tells you what to work on first.

## A simple example

You have **5 hours** before a hackathon deadline.

But your list looks like this:

- Finish the main app: 2 hours
- Add login: 1 hour 30 minutes
- Test the app: 45 minutes
- Make a logo: 45 minutes
- Record the demo: 30 minutes
- Write documentation: 1 hour
- Add animations: 1 hour

That is much more work than the time you have.

Instead of pretending you can finish everything, LastMinute may tell you:

**MUST:** Finish the app, test it, record the demo.

**REDUCE:** Write shorter documentation.

**DEFER:** Extra features that can be added later.

**KILL:** Logo polishing and animations if they do not help you submit a working project.

Now you have a plan that has a better chance of fitting into your 5 hours.

## How to use LastMinute

Using LastMinute is simple:

1. Open the [**live app**](https://fawazfff.github.io/Last-minute/).
2. Press **Make a rescue plan**.
3. Tell LastMinute what you are trying to finish. For example: `Finish my school project`.
4. Choose your real deadline.
5. Enter how much time you can actually spend working. If there are 6 hours until the deadline but you can only work for 4 of them, enter 4 hours of usable time.
6. Add every task you think you need to do and how long you think each one will take.
7. If a task is absolutely needed for the smallest successful version of your goal, mark it as required.
8. Press **Check reality**.
9. LastMinute compares your work with your available time.
10. Look at the **MUST, REDUCE, DEFER, and KILL** groups. You can change them yourself if you disagree.
11. When the plan fits, press **Build rescue plan**.
12. LastMinute shows the next task you should work on.
13. Start the timer and do that task.
14. When you finish, press **Done**.
15. If something takes longer than expected, tell LastMinute you need more time. It will check the remaining plan again and try to remove or move less important work.
16. Keep following the plan until you finish.

## Want to understand it quickly?

You do not need to create a plan from scratch.

Open LastMinute and press **Try the 30-second demo**.

The demo gives LastMinute an impossible list with more work than available time. You can immediately see how it decides what should stay and what should go.

[**Try the live demo →**](https://fawazfff.github.io/Last-minute/)

## Why I built it

I built LastMinute because I had this exact problem during the MobileCodeAI hackathon.

I had many things I wanted to build and improve, but I had very little time left before the deadline.

I did not need another to-do list.

**I needed something to tell me what I could realistically finish.**

That became LastMinute.

## The important rule

**Reality first. AI second.**

If you have 4 hours left, LastMinute will not pretend that 8 hours of work can fit inside those 4 hours.

The important time calculations use normal, predictable math. The current hackathon version does not need an external AI API to make those calculations.

This keeps the main idea simple: **make a plan that fits the time you actually have.**

## Privacy

You do not need to create an account.

Your LastMinute plans are stored in your own browser for this hackathon version.

## For developers

LastMinute is a small static web app with no framework required for the hackathon version.

To run the JavaScript syntax check:

```bash
npm run check
```
