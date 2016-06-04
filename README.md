# misc-scripts
Bits of scripts that didn't fit anywhere else

## prepare-commit-msg
Place `prepare-commit-msg` into your `.git/hooks/` folder. Don't forget to max your script executable eg. `chmod +x prepare-commit-msg`

This script will use the current branch name, presumably in the format `b_12345` to pre-populate the first line of a commit message with `B#12345`.

### Improvements
Could use `pleasant-lawyer-cli` to get the number regardless of naming scheme.
