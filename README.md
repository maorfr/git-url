# git-url

Prints the URL of a file in a git repository from command line, so it is easier to share links to files in git repositores.

## Usage

```sh
$ git url <path_to_file> [remote]
```

## Example

```sh
$ git clone git@github.com:maorfr/git-url.git && cd git-url
Cloning into 'git-url'...

$ git url README.md
https://github.com/maorfr/git-url/blob/master/README.md
```

# Install

1. Clone this repository.
2. Copy `git-url` to your $PATH.
3. Add git alias - `git config --global alias.url '!git-url'`.
