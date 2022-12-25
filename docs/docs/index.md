# Cornmaze

The primary source of truth for all our repositories.

This means that:
- Cornmaze should not reference any other repository.
- We store our libraries and scripts over here.
- Some documentation regarding everyone is best viewed here.

## Important links

- [Documentation page](./index.md)
- [Project page](https://github.com/users/TurnipXenon/projects/8)

**Specific sections inside the documentation page:**

- [Onboarding guide](./onboarding.md)

## Contributing to README.md

**Do not edit `./README.md`!** Instead, edit `./docs/docs/index.md`. After editing that file,
run `go run dev/sync_readme/main.go` from the root folder `/`. That should automatically transform all the
relative references.
