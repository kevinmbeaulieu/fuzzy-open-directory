Fuzzy-search for, and `cd` into directories.

Uses Spotlight to search for a directory containing all the characters in the query in that order (i.e., directory name matches the regex `/^.*m.*y.*q.*u.*e.*r.*y.*$/`. Built for macOS.

I recommend creating an alias such as `alias fod=fuzzy-open-directory`.

Usage: `fuzzy-open-directory [-h] [-o] [-p <path>] query`

Options:

    -h, --help   Print this help message and exit.

    -o           Open directory in Finder.

    -p, --path   Search only within the specified path (default: ~).



Examples:

    ~$ fuzzy-open-directory myproj # cd into ~/Documents/Projects/MyProject
    
    ~$ fuzzy-open-directory gdrive # cd into Google Drive
