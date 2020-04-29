# push-from-tag-event

Trying to isolate a bug pushing from a tag event in GitHub actions

## Goal

The actions in this project should modify a file, then commit those changes back to the repo. Original intent was a generated changelog, this example just appends to the README file.

## Instructions

1. Checkout the repo
2. Run `npm version patch && git push`

---
