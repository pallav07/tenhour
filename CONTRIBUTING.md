# Contributing to Game Project

Thank you for taking the time to contribute! This project is open source and welcomes contributions from everyone, regardless of experience level.

## Setting Up Your Environment

### 1. Install Godot 4

Download [Godot Engine 4.x](https://godotengine.org/download/) — use the **Standard** build (not .NET/Mono).

- **Windows**: Download the `.exe` installer or portable `.zip`
- **macOS**: Download the `.dmg` — drag Godot to Applications
- **Linux**: Download the `.x86_64` binary and make it executable:
  ```bash
  chmod +x Godot_v4.x-stable_linux.x86_64
  ```

### 2. Fork and Clone

```bash
# Fork this repo on GitHub, then:
git clone https://github.com/YOUR_USERNAME/tenhour.git
cd tenhour
```

### 3. Open the Project

- Open Godot Engine
- Click **Import** → select the `project.godot` file in the cloned folder
- Click **Import & Edit**

## Making Changes

### Branching

Always work on a new branch — never commit directly to `main`:

```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/bug-description
```

### Commit Style

Use clear, short commit messages:

```
Add: player jump mechanic
Fix: camera clipping through walls
Update: README with Linux setup steps
Remove: unused placeholder assets
```

### Submitting a Pull Request

1. Push your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
2. Open a Pull Request on GitHub against the `main` branch
3. Describe what you changed and why
4. Link any related issues with `Closes #issue-number`

## Guidelines

- **One change per PR** — keep pull requests focused
- **Test on your platform** before submitting
- **GDScript style**: use tabs for indentation (configured in `.editorconfig`)
- Don't commit the `.godot/` folder — it's auto-generated and gitignored
- Don't commit OS-specific files (`.DS_Store`, `Thumbs.db`, etc.) — they're gitignored

## Reporting Issues

- Search existing issues before opening a new one
- Include your **OS**, **Godot version**, and **steps to reproduce**
- Screenshots or screen recordings are very helpful for visual bugs

## Questions?

Open a [GitHub Discussion](https://github.com/pallav07/tenhour/discussions) or file an issue with the `question` label.
