# Building a Minion DFIR playbook

This repository contains a starter `rules` file for using [Minion](https://gitlab.com/CinCan/minion) for DFIR work.

This initial version will cover a basic Windows memory foresics basic playbook that hopefully other people can then build upon and get to know the tool.

You should definitely go read Minion's own documentation to unleash its full power.

## HOWTO run these rules

### Prequisites

1. Install `minion` which automatically installs `cincan`
1. `cincan run cincan/volatility3`

### Actual `minion` processing

1. Clone this repository's `rules` folder to your forensicator machine
1. `minion build rules/windows-memory-forensics.rules YOUR_IMAGE_FILE_HERE`

## Example report

You can see an [example report in Markdown format](example-reports/windows-memory-forensics.md) to understand what it produces when run.
