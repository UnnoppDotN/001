# 001

## Setup

Run the setup script once to prepare local configuration:

```bash
./scripts/setup.sh
```

## Scripts

- `scripts/setup.sh`: Initializes local environment files.

## Using Codex

The Codex CLI can help with common tasks such as answering questions about the repo,
editing files, and running commands. A typical workflow is:

1. Describe the task you want to do (for example, "update the setup script to add
   another environment variable").
2. Review the proposed changes and ask for adjustments if needed.
3. Run the suggested commands or tests, then confirm the results.

Tips:

- Be specific about the files or behavior you want to change.
- Mention any constraints (for example, "don't edit tests" or "keep behavior the same").
- Ask for a summary and tests when you are ready to review.
