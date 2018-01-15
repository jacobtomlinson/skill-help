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

Replies with the doc string for provided skill.

> user: help help
>
> opsdroid: help - Displays this help message

## Add your skill to the help output

Add a [docstring](https://www.python.org/dev/peps/pep-0257/) to your skill. The format is: skill usage, `-`, and a description of the skill.

```
skill_name <required_parameter> [optional_parameter] - Description of the skill
```

The usage should follow the [docopt](http://docopt.org/) format.
