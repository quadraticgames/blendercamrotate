# Blender Camera Rotation Script

A Python script for Blender that creates a smooth circular camera animation around a central point. Perfect for architectural visualization, product showcases, or any 3D scene where you need a rotating camera view.

## Features

- Creates a circular camera path around a central point
- Adjustable camera height, radius, and rotation speed
- Configurable target offset for precise camera focus
- Automatically creates keyframes for smooth animation
- Works with existing camera or creates a new one if needed

## Parameters

- `radius`: Distance from the center point (default: 330 units)
- `height`: Camera height above ground (default: 95 units)
- `rotation_speed`: Animation speed (default: 0.005 radians per frame)
- `total_frames`: Length of animation (default: 1550 frames)
- `target_offset`: Adjustable offset for camera focus point (x, y, z)

## Usage

1. Open Blender and your desired scene
2. Open the Script Editor in Blender
3. Load and run this script
4. The camera animation will be automatically created
5. Press Alt+A to preview the animation

## Requirements

- Blender 2.8 or newer
- Python 3.x (included with Blender)

## Installation

1. Download `main.py`
2. In Blender, go to the Scripting workspace
3. Open `main.py` in the text editor
4. Click "Run Script" or press Alt+P

## Customization

You can modify the following variables in the script to customize the animation:
```python
radius = 330        # Adjust the distance from center
height = 95         # Adjust the camera height
rotation_speed = 0.005  # Adjust the rotation speed
total_frames = 1550     # Adjust animation length
```

## License

MIT License

## Author

Created by Joe Stallings
