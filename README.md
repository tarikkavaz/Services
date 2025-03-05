# Library Services
- Tr Char Change: Workflow to change Turkish characters in files
  Character Replacements:
  ```
  space space > space
  ğĞ > g
  İı > i
  ý > i
  şŞ > s
  öÖ > o
  üÜ > u
  çÇ > c
  _ > -
  & > deletes it
  : > deletes it
  / > deletes it
  space > -
  . > -
  % > deletes it
  ( > -
  ) > -
  -- > -
  -. > -
  @.* > -
  … > -
  , > deletes it
  jpeg > jpg
  ```
- Open in iTerm2: Workflow to open selected files and folders in iTerm2 from Finder
- Open in VSCode: Workflow to open selected files and folders in VSCode from Finder
- Open in Cursor: Workflow to open selected files and folders in Cursor from Finder

## Installation
```bash
git clone git@github.com:tarikkavaz/Services.git ~/Library/Services
```

Add to ~/Library/Services folder and you'll see these workflows when selecting files.
