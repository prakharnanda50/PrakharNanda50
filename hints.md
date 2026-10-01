# DecodeX — Progressive Hints

> Read `[README.md](README.md)` first for the event details, objective, and rules.

---

## Before you begin

These hints are **entirely optional**. DecodeX is designed to be solved by
exploration, and a team that never opens this file has done the challenge
properly.

A few things worth knowing about how these hints work:

- **They are arranged in levels.** Start at the top and stop reading the moment
  you have what you need.
- **Try the challenge first.** Independent exploration teaches you the
  navigation skills better than a hint will.
- **Stronger hints shrink the search space; they do not hand you the answer.**
  A Level 3 hint may tell you *which kind of surface* matters. It will not tell
  you what it says.
- **These hints guide exploration, not discovery.** Nothing here solves the
  challenge for you.

If you are truly stuck at Level 3, ask an organizer. That is what they are for.

---

## Level 0 — Gentle nudges

- The repository is more than its README. The landing page is a starting point, not a summary.
- A visible file may exist only to point somewhere else. Read what it points *to*.
- A single clue may be split across several unrelated GitHub features.
- Do not assume everything useful lives on the default branch.
- If something looks like housekeeping — a note, a log, a config line — read it anyway. That is exactly what housekeeping usually is in a hunt like this.
- The answer is already written down somewhere. You are looking for text that describes a problem to be solved, not code that solves it.

---

## Level 1 — Exploration hints

### Issues

- Issues carry more than their titles suggest.
- The comment thread under an issue is a separate space from the description above it. Read one and then read the other.
- An issue's state and labels can indicate whether its content is live or historical.

### Pull requests

- Pull requests behave like issues with a diff attached.
- The conversation around a change is often more informative than the change itself.
- A branch name is written by a human and is meant to be read.

### Releases

- A release is more than a version number and a tag.
- Release notes are prose written for readers, and are worth reading in full.
- Release notes may point at other files or records in the repository.

### GitHub Actions

- A workflow file is only half of what a workflow is.
- Workflows communicate through what they *produce* when they run.
- The repository's workflow list shows more than its file tree does.

### Configuration and dotfiles

- Configuration files are read constantly and skimmed rarely.
- A file that ignores paths is still a file with readable contents.
- Comments inside configuration are not decoration.

---

## Level 2 — Connection hints

- **Follow references between files and GitHub features.** The clue you need may live on the other end of a link found in an unrelated place.
- **Inspect the destination of every link in a configuration file.** A filename in a config file is an address, not a comment.
- **Ask whether a workflow output or a release note contains more than ordinary project information.** Generated output often carries text that the source configuration only passes through.
- **Compare clues across different areas.** If two unrelated surfaces mention the same record, subject, or code, that overlap is deliberate.
- **Check whether a resource points to another resource.** Some entries in this repository are pure pointers; the content is one hop away.
- **Consider that the same underlying subject may be described in two different ways.** If a document describes a project without naming it plainly, that project may be the thing you are tracking.

---

## Level 3 — Stronger hints

- A discussion thread may contain information that the main description does not.
- A release can carry more context than its version number.
- Some configuration files describe what should be ignored, but their contents may still deserve attention.
- A workflow can communicate through its outputs, not only through its YAML definition.
- A reference is useful only when you follow it to its destination.
- Text that describes a problem to be solved — its title, theme, difficulty, description, and key features — is the kind of text you are looking for. It reads like a brief, not like documentation.
- Not every problem statement is stored the same way. Some sit inside ordinary repository content; some are produced by a tool that runs against the repository.
- When a record in this repository is described as archived, withdrawn, or retained, that status language is often adjacent to the material you need.

---

## Feature-specific hints

### GitHub Issues

- Read the issue list, not just the landing page.
- Open every issue and read past the description into the comments.
- A comment that begins with a housekeeping remark may continue into something else entirely.

### Pull Requests

- Open every pull request, including closed ones.
- Read the review and comment discussion on each.
- Branch names are part of the evidence; record them.

### Releases

- Open the Releases page directly rather than relying on links from files.
- Read every release note in full, including short ones.
- Note that a release may be described as an export or a companion record — the framing is not the content.

### GitHub Actions

- List the workflows and run them if they are dispatchable; read the resulting job summary and any artifacts.
- Read the workflow definition too, but expect the interesting text to appear where the run *outputs* it.
- An environment variable or config block inside a workflow is content, not plumbing.

### `.gitignore` and linked files

- Open `.gitignore` and read every line, including comments.
- A comment in an ignore file is unusual and therefore worth reading closely.
- If a configuration file names a file, that file is probably worth opening — even though the reference does not say why.

### Packages

- If a package has been published for this repository, its registry page and any attached README may hold material that the repository tree does not.
- Package metadata is inspectable without installing anything; you do not need to run or depend on published code to read its description.
- If you find no packages published, note that as a checked and cleared avenue rather than assuming it was overlooked.

### Branches and tags

- List all branches and all tags. The default branch is rarely the whole repository.
- Tags are often named after records and dates in a way that is meant to be decoded.
- Commit history on a non-default branch can hold material that never reached the main line.

---

## Hint usage guide

1. **Start at Level 0.** Do not skip ahead because the levels are tempting.
2. **Move up one level only when genuinely stuck**, and only as far as you need.
3. **Record what you have already inspected.** A written list of checked locations prevents re-searching and shows you the pattern of what is left.
4. **Do not re-check the same location without a new reason.** If you have already read it carefully, reading it again will not change it.
5. **Verify against the original source.** Every recorded discovery should point at the exact place you found it, so it can be re-checked later.

---

## Final reminder

The most reliable discoveries in DecodeX did not come from staring harder at one
place. They came from noticing that two ordinary-looking pieces of information
— in two different corners of a repository — were describing the same thing.

Follow the thread. Connect the two. That is the whole trick.

Good luck.

---

**DecodeX** · Organized by **AWS Student Builder Group, SUIIT** · 6 October 2026
