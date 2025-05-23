# exa

> A modern replacement for `ls` (List directory contents).
> More information: <https://github.com/ogham/exa>.

- List files one per line:

`exa --oneline`

- List all files, including hidden files:

`exa --all`

- Long format list (permissions, ownership, size and modification date) of all files:

`exa --long --all`

- List files with the largest at the top:

`exa --reverse --sort={{size}}`

- Display a tree of files, three levels deep:

`exa --long --tree --level={{3}}`

- List files sorted by modification date (oldest first):

`exa --long --sort={{modified}}`

- List files with their headers, icons, and Git statuses:

`exa --long --header --icons --git`

- Don't list files mentioned in `.gitignore`:

`exa --git-ignore`
