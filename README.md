# Claude Code for Non-Technical People: Getting Started

A guide to getting started with Claude Code for non-technical people.

## Tip 0: Setting Up on Windows

I'm more familiar with Mac (and Linux to some extent), so here's my interview with Scott Hanselman (VP of Developer Community at Microsoft) on setting up a Linux-based development environment on Windows.

- Video: [Coding on Windows (and Linux)](https://www.youtube.com/watch?v=MNN--Ml9XJg)

Once you have your terminal set up, install Claude Code by following the [official setup guide](https://docs.anthropic.com/en/docs/claude-code/setup).

Most of the following tips work on Mac, Linux, and Windows (with WSL).

## Tip 1: Talk to Claude Code with Your Voice

You can communicate much faster with your voice than typing. Using a voice transcription system on your local machine is really helpful for this.

On Mac, I've tried a few different options:
- [superwhisper](https://superwhisper.com/)
- [MacWhisper](https://goodsnooze.gumroad.com/l/macwhisper)
- [Super Voice Assistant](https://github.com/ykdojo/super-voice-assistant) (open source, I built it with Claude Code)

Even when there are mistakes in the transcription, Claude is smart enough to understand what you're trying to say.

Think of it like communicating with a friend - you can text, but a quick voice message is often faster.

## Tip 2: Basic Terminal Navigation

Before using Claude Code, you need to understand the terminal basics:

- `pwd` - Print working directory (shows where you are)
- `ls` - List files in the current directory
- `cd` - Change directory (navigate folders)
  - `cd folder-name` to go into a folder
  - `cd ..` to go back up one level
- `mv` - Move or rename files
- `cp` - Copy files
- `Ctrl+C` - Stop/exit running processes

These six concepts are enough to get started.

## Tip 3: Git and GitHub Basics

Version control is essential. Learn to save your work and track changes.

- **Git**: Version control system that tracks changes to your code
- **GitHub**: Website that hosts Git repositories online
- **GitHub Desktop**: Visual app that makes Git easier for beginners
- **gh CLI**: GitHub's command line tool (Claude Code uses this a lot)

Here's my video on open source contribution basics - it covers Git and GitHub fundamentals.

- Video: [How to Get Started with Open Source | A Beginner-Friendly Guide](https://www.youtube.com/watch?v=MkaIrwOlP6Y)

Key concepts:
- Commits = saving snapshots of your work
- Branches = working on different versions
- Push/Pull = syncing with GitHub
- Cloning = downloading a copy of a project from GitHub to your computer
- Forking = creating your own copy of someone else's project on GitHub (unlike a branch, a fork is a completely separate copy you own)
- Pull Requests (PRs) = proposing changes to a project for review before they get merged in

## Tip 4: Automating Simple Tasks

Claude Code excels at automating repetitive tasks:

- **Image processing**: Resize, convert formats, batch rename
- **File conversions**: Convert between file types
- **Transcription**: Convert audio/video to text (more advanced but possible)
- **Data processing**: Go through CSV files, organize folders

Just describe what you want to do, and Claude Code will figure out the commands.

## Tip 5: Research

Claude Code is an amazing research tool. Just ask any question:

- Research topics across the web
- Analyze documents and PDFs
- Explore public information
- Get summaries of complex topics

The key is giving it the right context and access to information. It can search the web, read files, and synthesize information from multiple sources.

## Tip 6: Writing

Claude Code makes an excellent writing assistant:

- Give it context about what you're writing
- Use your voice to dictate detailed instructions
- Go through drafts line by line together
- Ask for specific changes and improvements

Works great for blog posts, documentation, LinkedIn posts, emails - anything text-based.

## Tip 7: Getting Outputs Out of Your Terminal

Once Claude Code creates something, you need to get it out:

- **`/copy` command**: Type `/copy` to copy Claude's last response to your clipboard as markdown
- **Clipboard**: Ask Claude to use `pbcopy` (Mac) to copy directly
- **Write to file**: Have it save content to a file, then open in VS Code
- **Open URLs**: Ask Claude to open links in your browser
- **GitHub Desktop**: Ask it to open the repo in GitHub Desktop to see changes

## Tip 8: The Cmd+A / Ctrl+A Trick

Sometimes Claude Code can't access a URL directly - maybe it's a private page, or a site that blocks automated access. The workaround is simple:

1. Open the page in your browser
2. Select all the content (Cmd+A on Mac, Ctrl+A on Windows/Linux)
3. Copy it (Cmd+C or Ctrl+C)
4. Paste it directly into Claude Code

Claude Code is smart enough to work with raw pasted content. This works great for terminal output too - if you have output from another tool or another Claude Code session, just select all, copy, and paste it back.

Some pages don't lend themselves well to select all by default, but there are tricks. For example, with Gmail threads, click Print All to get the print preview (but cancel the actual print). That page shows all emails in the thread expanded, so you can select the entire conversation cleanly.

## Tip 9: Be Fearless in the Unknown

This is the overarching theme. Don't be intimidated by:

- **Unfamiliar codebases**: Even if it's your company's code, just ask Claude Code to explain it
- **Long PDF files**: Claude can read and summarize them
- **Bugs and errors**: Paste the error message and ask for help
- **New technologies**: Claude Code can guide you through anything
- **Quick prototyping**: Want to build something? Just describe it and start

The key insight: you don't need to know everything. Claude Code can help you navigate the unknown. Be brave and start exploring.

---

For more tips to truly become an expert at Claude Code, check out [40+ Claude Code Tips: From Basics to Advanced](https://github.com/ykdojo/claude-code-tips).
