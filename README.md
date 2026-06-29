# TPA Mod - Teleport Request System

A Fabric mod for Minecraft 1.21.1 that adds a teleportation request system.

## Features

- **`/tpa <player>`** - Request teleportation to a player
- **`/tpaccept`** - Accept a teleportation request
- **`/tpdeny`** - Deny a teleportation request

## Installation

1. Download the latest `.jar` file from the releases
2. Place it in your `mods` folder
3. Launch Minecraft with Fabric Loader

## Building from Source

### Requirements
- Java 21+
- Gradle

### Build Steps

```bash
# Clone the repository
git clone https://github.com/qkrquddbs/tpa.git
cd tpa

# Build the mod
./gradlew build

# The compiled jar will be in: build/libs/tpa-mod-1.0.0.jar
```

## Usage

### Request Teleport
```
/tpa <player_name>
```
Sends a teleportation request to the specified player.

### Accept Request
```
/tpaccept
```
Accepts the most recent teleportation request received.

### Deny Request
```
/tpdeny
```
Denies the most recent teleportation request received.

## Commands

| Command | Usage | Description |
|---------|-------|-------------|
| `/tpa` | `/tpa <player>` | Request to teleport to a player |
| `/tpaccept` | `/tpaccept` | Accept a teleport request |
| `/tpdeny` | `/tpdeny` | Deny a teleport request |

## Version

- Minecraft: 1.21.1
- Fabric Loader: 0.16.9
- Fabric API: 0.104.0

## License

MIT License

## Author

qkrquddbs
