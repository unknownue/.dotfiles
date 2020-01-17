# Git Commit Message Guide

This guidence is modifed from http://udacity.github.io/git-styleguide/.

## Introduction

This style guide acts as the official guide to follow in this repo. This guidence is not mandatory.

You can use your own style of commit message if you prefer.

## Commit Messages

### Message Structure

A commit messages consists of three distinct parts  separated by a blank line: the title, an optional body and an optional  footer. The layout looks like this:

```
type_emoji subject

body

footer
```

The title consists of the type of the message and subject.

### The Type

The type is contained within the title and can be one of these types:

| Type     | emoji                       | code                          | function                                                     |
| -------- | --------------------------- | ----------------------------- | ------------------------------------------------------------ |
| init     | :seedling:                  | `:seedling:`                  | Initial commit or create sub module                          |
| fix      | :chipmunk:    | `:chipmunk:`      | Bug fix                        |
| format   | :butterfly: | `:butterfly:` | Formatting, missing semi colons, etc; no code change |
| docs     | :books:        | `:books:`  | Changes to the documentation (readme, API docs, etc.)        |
| remove   | :fire:                      | `:fire:`                      | Remove features or files                                     |
| refactor | :fox_face:            | `:fox_face:`              | Refactoring production code or Changing file structure       |
| license  | :dove: | `:dove:` | Add or modify license                                  |
| shell | :shell: | `:shell:` | Add or modify shell scripts |
| package | :package:                   | `:package:`                   | Updating build tasks, package manager configs, etc; no production code change |
| docker   | :whale:                   | `:whale:`       | Configure docker environment                                 |
| rewind   | :rewind:                    | `:rewind:`                    | Reverting changes                                            |
| merge    | :twisted_rightwards_arrows: | `:twisted_rightwards_arrows:` | Merging branches                                             |

### The Subject

Subjects should be no greater than 50 characters, should begin with a capital letter and do not end with a period.

Use an imperative tone to describe what a commit does, rather than what it did. For example, use **change**; not changed or changes.

### The Body

Not all commits are complex enough to warrant a body,  therefore it is optional and only used when a commit requires a bit of  explanation and context. Use the body to explain the **what** and **why** of a commit, not the how.

When writing a body, the blank line between the title and  the body is required and you should limit the length of each line to no  more than 72 characters.

### The Footer

The footer is optional and is used to reference issue tracker IDs.

### Example Commit Message

```
feat: Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequenses of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: #123
See also: #456, #789
```

