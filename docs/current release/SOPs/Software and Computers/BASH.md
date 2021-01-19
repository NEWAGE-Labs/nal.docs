# Standard Operating Procedure - BASH

>Most recently edited by: *Paul VanderWeele*  
>Most recent edit date: *Jan 2nd, 2021*  
>Edits were authorized by:  

## Purpose and Scope

The Bourne-Again Shell (BASH) is a [TTY](#TTY) software that comes pre-installed on [Ubuntu](Ubuntu.md), and is one of the [CLIs](#cli) used in NAL along with [Powershell](Windows.md#additional-information-and-tools). This procedure outlines basic usage, and references the official documentation page.

## Terms and Definitions

### TTY

> A Teletype Terminal (TTY) is a software  used to allow human users to enter English or other natural language characters into a computer system.

### CLI
> A Command-Line Interface (CLI) is a software that process single lines of texts as machine operating instructions. Command words are delimited and executed based on syntax rules.

### CWD

> The Current Working Directory (CWD) is a directory location within a filesystem that a software is actively working in.

# Usage

In order to use BASH, it must be installed on the computer. Using BASH on [Windows](Windows.md) is complicated, but it is the default [CLI](#CLI) in [Ubuntu](Ubuntu.md) and other Linux variants. To open BASH, either select the icon from the application list, or press **CTRL+ALT+T**.

The commands that can be executed from BASH are nearly limitless depending on the specific software installed on the machine. However, some of the most useful commands are listed below. The `$` symbol is used to denote independent lines, and is the same syntax convention used within BASH itself.

```
$ ls - List Directory Contents
$ mv - Move file or folder
$ rm - Remove file or folder
$ cd - Change CWD
$ man <command> - Displays instructions on the usage of a command
```

Additional information on using BASH and BASH commands can be found on the [GNU Website](www.gnu/software/bash/).
