# unity-2d-platformer-tp

2D platformer built in Unity 6 for a game-dev lab: tilemap level, physics-based player movement and jumping, camera follow, and idle/run animations with the Pixel Adventure asset pack.

## What's inside

- **TP1 – Level:** tilemaps and tile palettes, tiled background, sorting layers (`Background`, `Terrain`), player sprite, Rigidbody2D, Box Collider 2D, Tilemap + Composite colliders.
- **TP2 – Player:** `PlayerMovement` script (left/right, jump, sprite flip, respawn after falling), camera following the player, `Player_idle` / `Player_running` animations with Animator transitions on a `Running` bool.

## Setup

1. Open the project with **Unity 6** (`6000.6.10f1` or newer).
2. Import **[Pixel Adventure 1](https://assetstore.unity.com/packages/2d/characters/pixel-adventure-1-155360)** (free) from the Package Manager > My Assets. It is not included in this repo because of its license.
3. Open `Assets/Scenes/SampleScene.unity` and press **Play**.

## Controls

| Key | Action |
|---|---|
| ← → / A D | Move |
| Space | Jump |

## Project layout

| Folder | Content |
|---|---|
| `Assets/Scenes` | The level scene |
| `Assets/Scripts` | `PlayerMovement.cs` |
| `Assets/Animations` | Animation clips and the Animator controller |
| `Assets/Terrain`, `Assets/Background` | Tile palettes and tile assets |
