# Git practice: recovering the result

This agent-executed exercise records the reasoning behind the original Git lesson; it is not a learner quiz score.

- Version control keeps inspectable history; it does not fix program bugs automatically.
- A repository records committed files and history. Untracked and ignored files are not in the committed snapshot.
- Add selects content, commit records it locally, and push transfers reachable commits and updates the remote branch.
- A branch is a movable reference. The prior main commit remains unchanged until an explicit merge or ref update.
- Model checkpoint patterns apply to untracked files. Adding an ignore pattern does not untrack an existing file.

Verification: push this note to my-progress, clone that remote branch into a fresh directory, and compare both the commit SHA and this file.
A separate main-only clone is used for a local fast-forward merge; remote main is not pushed.
