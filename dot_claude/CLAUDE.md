# Search tools

- Use the built-in **Grep tool** for all content searches — never run `grep` or `rg` in Bash.
- Use the built-in **Glob tool** for all file searches — never run `find` or `ls` in Bash.

The Grep tool uses ripgrep internally and returns structured, token-efficient results. Bash grep/rg commands produce raw shell output with extra whitespace, color codes, and headers that waste tokens.
