# Spatial Prefabs

Pre-configured, ready-to-import prefabs for Spatial.io Creator Toolkit projects.

## Directory Overview
- Vehicles/ - Flight rigs and vehicle systems packaged for quick reuse.

## Included Prefabs

### Flight System v1.2 Pro
- Packages: FlightSystem_v1.2_Pro.unitypackage, FlightHUD_v1.0.unitypackage
- Preview media: Images/MetaDyn_FlightSystem1.2_Pro*.png
- Notes: flight controller script with an optional HUD package for cockpit overlays.

### Flying Cube v1.2
- Package: FlyingCube_v1.2.unitypackage
- Notes: lightweight sample vehicle for validating flight mechanics.

## Usage
1. Open the Spatial Creator Toolkit project in Unity.
2. Import the desired .unitypackage via Assets > Import Package > Custom Package.
3. Review any included documentation inside the package and configure scene-specific references (inputs, cameras, spawn points).
4. Test the prefab in a clean scene before sharing with other contributors.

## Contribution Guidelines
- Include .unitypackage exports and supporting preview media.
- Document dependencies, input mappings, and configuration steps in the prefab folder.
- Keep filenames descriptive and versioned (e.g., MyPrefab_v1.0.unitypackage).
- Provide lightweight demonstration scenes or prefabs whenever possible.
- Validate performance in Spatial Creator Toolkit builds before submitting updates.
