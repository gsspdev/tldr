# jdupes

> A powerful duplicate file finder and an enhanced fork of fdupes.
> More information: <https://codeberg.org/jbruchon/jdupes#usage>.

- Search a single directory:

`jdupes {{path/to/directory}}`

- Search multiple directories:

`jdupes {{directory1}} {{directory2}}`

- Search all directories recursively:

`jdupes --recurse {{path/to/directory}}`

- Search directory recursively and let user choose files to preserve:

`jdupes --delete --recurse {{path/to/directory}}`

- Search multiple directories and follow subdirectores under directory2, not directory1:

`jdupes {{directory1}} --recurse: {{directory2}}`

- Search multiple directories and keep the directory order in result:

`jdupes -O {{directory1 directory2 directory3 ...}}`
