# PaperTime

PaperTime is a specialized Paper fork that enables technical players to manipulate the game speed.

The fork's functionality can be accessed through the command `/stps` (with the permission node of `bukkit.command.stps`)

## Features
- Use `/stps <tps>` to set the game's tick speed
- Pause all world/chunk ticks by setting `/stps 0`
- Step through ticks individually by using `/stps add <ticks>`

## Setup

Download the paperclip from the releases.

The setup is the same as any normal paper server.

**Note for WorldEdit:**

Add the following line to the bottom of `plugins/WorldEdit/config.yml` to enable functionality:
```yaml
allow-editing-on-unsupported-versions: I accept that I will receive no support with this flag enabled.
```
