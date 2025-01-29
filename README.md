Created readme file and added some text.

- Created new folder.
- Created git repository.
- Added readme file.
- Staged and committed.

- Created project/src and project/docs folders.
- Added .txt, .log, .js, .md files to each subfolder.
- Added `*.log   /project/docs/` into .gitignore file.
- Added `index.log` into /project/src/.gitignore.
- While adding the files using `git add .` the files mentioned in the .gitignore file aren't added. Confirmed it using `git status`.
- Git allows to have multiple .gitignore files in different directories. The root-level .gitignore is used to include files from entire project. The directory-level .gitignore is used to include files from that particular directory or folder. If multiple .gitignore files have different rules for a particular file, then the directory-level .gitignore file's rules are applied overriding the parent and root directory rules.
- Tried `git log` which showed the history of commits.
- Tried `git log --oneline` which showed history of commits in short format with just commit hash and commit message.
- Executed `git log --graph` which showed the history of commits, diverging and merging in tree format.
- Also tried `git log --graph --oneline` which showed the history in short tree and more readable format.
