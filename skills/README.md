# Skills Collection

Personal collection of Claude Code skills.

## Available Skills

| Skill | Description |
|-------|-------------|
| [prompt-optimizer](skills/prompt-optimizer/) | Write efficient prompts that maximize hit rate, minimize revision rounds, and increase template reusability |

## How to Install Skills

### Method 1: Clone and Link

```bash
git clone https://github.com/YOUR_USERNAME/my-skills.git
cd my-skills

# Link individual skills
ln -s $(pwd)/skills/prompt-optimizer ~/.claude/skills/prompt-optimizer
```

### Method 2: Manual Copy

Copy the skill folder to `~/.claude/skills/`:

```bash
cp -r skills/prompt-optimizer ~/.claude/skills/
```

## Adding More Skills

To add a new skill, create a folder under `skills/` with a `SKILL.md` file:

```
skills/
└── your-skill-name/
    └── SKILL.md
```

## License

MIT