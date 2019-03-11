# gitignore_preprocessor
preprocessor for .gitignore file (used by git) for RegEx support and more

written in AutoHotkey. in long term maybe written in nodeJs.

AutoHotkey is a free, open-source scripting language for Windows that allows users to easily create small to complex scripts for all kinds of tasks such as: form fillers, auto-clicking, macros, etc.


# examples for using preprocessor for .gitignore :



# ignore 3 digits:
\d{3}

# ignore 3 words case insensitive:
i)\w{3}

# ignore 3 words lowercase:
\w{3}

# ignore words lowercase and then case insensitive:
\w{1}i)\w{1}

# ignore amount of 1-3 digits:
\d{1,3}

# ignore amount of 1-4 letters:
\w{1,4}

# same with text around:
hello\d{1,3}world

# ignore amount of 2-3 digits:
\d{2,3}

# ignore for eg 3 digits:
[0-9][!a-z][0-9]
