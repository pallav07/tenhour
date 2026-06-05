# Game Project

An open source 3D game built with [Godot Engine 4](https://godotengine.org/). This project is community-driven — anyone is welcome to contribute, report bugs, or suggest features.

## About

> _Add a short description of your game here — what it is, what makes it fun, and what the goal is._

## Features

- Built with Godot 4 (GDScript)
- Cross-platform: Windows, macOS, Linux
- 3D with Jolt Physics
- Open source under the MIT License

## Getting Started

### Prerequisites

- [Godot Engine 4.x](https://godotengine.org/download/) — download the **Standard** version (not .NET/Mono unless you plan to use C#)

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/pallav07/tenhour.git
   cd tenhour
   ```

2. Open **Godot Engine**

3. Click **Import** → navigate to the cloned folder → select `project.godot`

4. Press **F5** or the ▶ Play button to run the game

### Platform Notes

| Platform | Renderer | Notes |
|----------|----------|-------|
| Windows  | Vulkan / D3D12 | Both supported by Godot 4 |
| macOS    | Metal | Godot 4 uses Metal automatically |
| Linux    | Vulkan | Ensure Vulkan drivers are installed |

## Project Structure

```
tenhour/
├── icon.svg          # Default project icon
├── project.godot     # Godot project configuration
└── ...               # Your scenes, scripts, assets go here
```

## Contributing

Contributions are welcome and appreciated! Please read [CONTRIBUTING.md](CONTRIBUTING.md) to get started.

You can help by:
- Fixing bugs
- Adding new features or levels
- Improving art or sounds
- Writing or improving documentation

## License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.
You are free to use, modify, and distribute this project.
