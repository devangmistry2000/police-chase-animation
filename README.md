# Night Pursuit — 3D Police Chase

A single-file Three.js police chase experience focused on cinematic action, dense traffic, aggressive police AI, vehicle contact and visible damage.

## Features

- Player-controlled suspect vehicle
- Eight pursuing police vehicles, including SUVs
- Coordinated ramming, interception and rolling roadblocks
- Police helicopter with rotating rotors and tracking searchlight
- Dense procedural city, civilian traffic, street lighting and fog
- Four cinematic camera modes
- Collision sparks, smoke, debris and detachable body panels
- Progressive vehicle deformation and reduced performance as damage increases
- Handbrake drifting, HUD, pursuit timer and speedometer
- Responsive desktop and mobile layout

## Controls

| Control | Action |
|---|---|
| W / Up | Accelerate |
| S / Down | Brake / Reverse |
| A / D or Left / Right | Steer |
| Space | Handbrake drift |
| C | Change camera |
| R | Restart |

## Run

Open `index.html` in a modern browser. An internet connection is required only to load Three.js from the CDN.

For local hosting:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.
