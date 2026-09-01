

# wp-ux-design-claude-skill

WordPress UX/design enforcement skill covering Core Web Vitals, mobile-first design, typography systems, color management, navigation UX, page builder patterns, and loading/error states.

## Installation

### Claude Code Plugin Marketplace

```bash
/plugin install https://github.com/xonack/wp-ux-design-claude-skill
```

### Manual Installation

Copy the skill file from the repository root to your Claude Code skills directory:

```bash
mkdir -p ~/.claude/skills/wp-ux-design
cp skills/wp-ux-design/SKILL.md ~/.claude/skills/wp-ux-design/SKILL.md
```

## Usage

Once installed, the skill activates automatically when working on relevant WordPress tasks. You can also invoke it directly:

```
/wp-ux-design
```

## Structure

```
wp-ux-design-claude-skill/
├── README.md
├── LICENSE
├── .claude-plugin/
│   └── plugin.json
└── skills/
    └── wp-ux-design/
        └── SKILL.md
```

## Contributing

PRs welcome. Please follow the [Agent Skills specification](https://agentskills.io/specification) for SKILL.md format.

## License

MIT
