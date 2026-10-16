# Contributing

Thanks for helping improve android-engineering-skills.

## Report a problem or suggest an idea

[Open an issue](https://github.com/lennonpetrick/android-engineering-skills/issues) to:

- report a rule that is wrong, unclear or outdated
- share a case where an agent didn't follow a skill as expected
- request a new skill, such as navigation, Room, modularization or instrumented tests

## Submit a change

Pull requests are welcome. For a new skill or a large change, open an issue first so we can agree on the approach.

When editing or adding a skill:

- Keep one skill per folder, with a `SKILL.md` that has `name` and `description` in its frontmatter. The folder name must match `name`.
- Write the `description` on one line, so an agent can tell when to use the skill. Lead with the tasks it applies to.
- Keep each `SKILL.md` under 20,000 characters, the limit Android Studio recommends.
- Add a short note about your change under "Unreleased" in [CHANGELOG.md](CHANGELOG.md).

Contributions are licensed under the [MIT License](LICENSE), the same as the rest of the project.
