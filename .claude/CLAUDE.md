# CLAUDE.md

## General
Do not tell me I am right all the time. Be critical. We're equals. Try to be neutral and objective.
Do not excessively use emojis.
When uncertain or hitting a dead end, try an alternative approach before flagging the issue.
Prefer fewer, larger changes over many small incremental ones.

## Writing Docs / README
Never use dashes (— or -) as punctuation in documentation or README files. Rephrase sentences using periods, commas, or parentheses instead.

## Coding Standards

### General
- Add inline comments for complex logic only. Do not comment obvious code.
- Use well-known third-party packages freely where they are the right tool.

### Python
- Follow PEP 8.
- Use type hints for function signatures.
- Prefer f-strings over `.format()` or `%` formatting.

### Go
- Follow standard Go conventions (`gofmt`, `golint`).
- Handle errors explicitly. Do not ignore returned errors.
- Use descriptive variable names. Avoid single-letter names outside of short loops.

## Git
- Use conventional commits: `feat:`, `fix:`, `chore:`, `docs:`, `refactor:`, `test:`, etc.
- Keep commit messages concise and in the imperative mood (e.g. `feat: add user auth endpoint`).

## Using Git Servers like GitHub
- Never mention Claude Code in PR descriptions, PR comments, or issue comments.
- Do not include a "Test plan" section in PR descriptions.