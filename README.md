# opsdroid skill hello

A skill for [opsdroid](https://github.com/opsdroid/opsdroid) to respond with help strings from loaded skills.

## Requirements

None.

## Configuration

None.

## Usage

#### `help`

Replies with all doc strings from loaded skill functions.

> user: help
>
> opsdroid:
help: help - Displays this help message
help_skill: help <skill_name> - Displays usage for provided skill

#### `help <skill_name>`

Replies with the doc string for <skill_name>.

> user: help help
>
> opsdroid: help - Displays this help message
