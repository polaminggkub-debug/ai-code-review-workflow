# AI Code Review GitHub Action

Free AI-powered code review using GitHub Models (GPT-4o Mini).

## Usage

1. Copy `.github/workflows/ai-review.yml` to your repository
2. Create a Pull Request
3. AI will automatically review your code and comment on the PR

## Features

- 🤖 Uses GitHub Models Free (GPT-4o Mini)
- 📝 Reviews full file content + diffs
- 🔍 Identifies bugs, security issues, and code quality problems
- 💬 Comments directly on your PR

## No API Key Required

Uses `${{ secrets.GITHUB_TOKEN }}` which is automatically available in GitHub Actions.

## License

MIT
