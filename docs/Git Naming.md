# Git Naming
### Branch naming
-   In the very beggining is version of app. Contains 3 digits: {Major}.{Minor}.{Patch}; 
-   Version follows with colon after which goes shortly explanation of work to be done (Except Major versions);
### Example of branch naming: 
-   1.0.0: Stable release;
-   0.1.0: Music player implementation;
-   0.1.1: Fix issues with audio visualization;
### Exceptions:
#### Branches, not directly related to app improvement, can deviate from rule of naming. Examples: docs, github-pages, etc.
---
### Prefixes in commit messages:
-   doc: – Documentation commits. Ex: 'doc: Add endpoints documentation for authorization';
-   ft: – Implementation of new feature. Ex: 'ft: Add audio visualization';
-   bf: – Bugfix, contains issue, discribing bug been fixed. Ex: 'bf: [fix/resolve] issue #10';
-   rf: - Refactoring of code, includes optimization, can also be attached to the issue. Ex: 'rf: Improved perfomance of audio visualization. [fix/resolve] issue #10'; 
---
### Pull Requests naming:
-   Name of pullrequest as well as commit message must begin with prefix, which is applicable to the work done.
-   If PR assigned to an issue, it must ends with [close] issue #{issue_num};
### Example:
-   ft: Complete music player
-   bf: Fix playback UI undefined behaviour. Close issue #10
### All Pull Requests merged using 'Squash and Merge' option.