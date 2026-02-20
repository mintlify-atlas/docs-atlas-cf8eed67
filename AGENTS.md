# fzf Documentation - Project Instructions

## About this project

- This is the official documentation site for fzf, built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "fuzzy finder" not "fuzzy search"
- Use "shell integration" not "shell plugin"
- Use "key binding" not "keyboard shortcut"
- Use "preview window" not "preview pane"

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Use backticks for command-line options: `--height`, `--preview`
- Use triple backticks with language tags for code blocks

## Content boundaries

- Document all public fzf command-line options
- Document shell integration for Bash, Zsh, and Fish
- Document Vim/Neovim plugin integration
- Focus on practical examples and real-world use cases
- Don't document internal implementation details
- Don't document experimental or undocumented features
