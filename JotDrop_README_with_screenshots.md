# JotDrop

**Get it out of your head. Get it into your calendar.**

> **Status: Currently in Development**  
> JotDrop is a working prototype that I use with my own Google accounts. It works the way I want for personal use, but it isn't ready to share publicly yet. Connecting another account currently requires extra technical steps, including creating and importing Google Apps Script code and configuring authentication IDs and permissions. I'm working on making that process easier before releasing it for others to use.

## Why I Built It

Recently, I've caught myself texting reminders to myself or a friend just so I don't forget them. I usually write them out on separate lines, something like:

```text
Fill out applications
Complete new project and document it for project portfolio
Dance like crazy
```

One morning, I remember thinking, *"I wish I could just copy and paste these messages directly into Google Calendar and Tasks to save myself some time."*

I don't enjoy spending a lot of time organizing calendars and to-do lists. But as someone with ADHD, I find it nearly impossible to keep track of everything unless I carefully write it down. The catch is that transferring those thoughts into Google Calendar and Google Tasks takes time, especially when I have a bunch of things to add at once.

That's the problem I made **JotDrop** to solve. I wanted to keep writing reminders the way I naturally do, then have a way to organize them without entering each one individually.

## What I Made

JotDrop gives me one place to paste a message or jot down everything on my mind. I prefer putting each task or event on its own line, but I can include notes and additional details too. The app processes what I've written, separates the individual entries, and lets me review them before adding everything to Google Calendar and Google Tasks with one button.

### 1. Quick Notes and Multiple Entries

I can paste the kind of list I'd normally send in a text message, with each reminder on its own line. I can include notes in the input without having to open a separate form for every thought.

**Screenshot slot: Notes input**

<!-- After uploading screenshots/notes-input.png to the repository, remove the comment markers around the line below. -->
<!-- ![JotDrop notes input with multiple line-separated reminders](screenshots/notes-input.png) -->

### 2. Automatic Separation and Review

JotDrop sorts through what I wrote and separates it into entries I can review before sending them to Google Calendar and Google Tasks.

**Screenshot slot: Organized entries and review screen**

<!-- ![JotDrop separating notes into individual entries for review](screenshots/entry-review.png) -->

### 3. One-Button Calendar and Tasks Upload

Once I'm satisfied with the entries, I can add them to Google Calendar and Google Tasks in one workflow rather than creating them individually.

**Screenshot slot: Add/upload action**

<!-- ![JotDrop button for adding entries to Google Calendar and Tasks](screenshots/bulk-upload.png) -->

### 4. Duplicate Calendar Events as Tasks

I added an option to **duplicate Google Calendar events as Google Tasks**. That way, I can see an event on my schedule and have a matching to-do item I can check off when it's done.

**Screenshot slot: Calendar-to-Tasks duplication option**

<!-- ![JotDrop option to duplicate calendar events as tasks](screenshots/duplicate-as-tasks.png) -->

### 5. Customizable Themes and Colors

I wanted the interface to feel personal, so I built customizable UI themes and color combinations. I can change the look of the app to suit my preferences.

**Screenshot slot: Theme customization**

<!-- ![JotDrop theme and appearance customization](screenshots/themes.png) -->

### 6. Color-Coded Priority Flags

I also added priority flags with different color combinations so important entries are easier to recognize at a glance.

**Screenshot slot: Priority flags and colors**

<!-- ![JotDrop entries with color-coded priority flags](screenshots/priority-flags.png) -->

## How I Built It

I built a lightweight web interface for writing, sorting, and reviewing entries. The backend is a **Google Apps Script** I wrote to connect JotDrop with Google Calendar and Google Tasks.

The prototype is shaped around how I already capture reminders: quick messages, separate lines, and occasional notes, followed by a single review-and-add workflow.

## Current Status and What's Next

Right now, JotDrop supports **Google Calendar and Google Tasks**, and the prototype works for my personal use. My immediate goal is to refine the Google version and make it easier for other people to connect their own accounts without manually setting up scripts or authentication credentials.

Once the Google version is in good shape, I'd like to expand JotDrop to **Microsoft environments** as well.

For now, this repository documents a personal productivity problem and the tool I built to address it.

---

<!--
SCREENSHOT CHECKLIST (for me while editing the README):
Upload these images into a screenshots/ folder at the root of this repository:
- screenshots/notes-input.png
- screenshots/entry-review.png
- screenshots/bulk-upload.png
- screenshots/duplicate-as-tasks.png
- screenshots/themes.png
- screenshots/priority-flags.png

Then remove the surrounding <!-- and --> from each Markdown image line above.
You can use .jpg or .webp instead of .png, but change the image paths to match.
Remove this checklist once the screenshots are in place.
-->
