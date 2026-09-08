# CityBuilder
A 2d city builder made with the [Godot Engine](https://github.com/godotengine/godot) and [DefaultECS](https://github.com/Doraku/DefaultEcs).

## How to Run and Build

### Requirements
- [Godot Engine](https://godotengine.org/) 3.x (Mono version, requires .NET)
- [.NET SDK](https://dotnet.microsoft.com/download) (Version 8.0 or compatible for tests)

### Running the Game
1. Open the Godot editor.
2. Import the `project.godot` file located in the root of the repository.
3. Build the .NET project by clicking the **Build** button in the top right of the Godot editor (or run `dotnet build CityBuilder.sln`).
4. Press the **Play** button (or `F5`) to run the game.

### Running Tests
Tests for the core logic can be found in the `CityBuilder.Tests` project. To run them:
```sh
dotnet test CityBuilder.Tests
```

## Attributions

- [Game-icons.net](https://game-icons.net)
