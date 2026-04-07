(This Summary was made with AI, not Xenon but just regular human AI that will definitely not destroy our planet)

🚀 3D Asgard Ship & Space Station Renderer

This project is an experimental web-based 3D visualization pipeline that transforms gameplay footage from X4: Foundations into an interactive 3D scene using LichtFeld Studio.

By leveraging modern 3D Gaussian Splatting (3DGS) techniques, the application reconstructs detailed volumetric scenes — including an Asgard-class ship and surrounding space station structures — directly from video input.

✨ Features
🎥 Video-to-3D Reconstruction
Converts recorded gameplay footage into a 3D scene using Gaussian splatting workflows supported by LichtFeld Studio.

🛰️ Dynamic Scene Composition
Renders large-scale sci-fi assets like capital ships and modular stations in a unified 3D space.

🌐 Web-Based Viewer
HTML + WebGL interface allows users to:
Orbit camera freely
Inspect geometry and depth
View real-time render updates

🧠 Neural Rendering Pipeline
Uses radiance-field-inspired techniques to reconstruct lighting, depth, and geometry from 2D frames

🛠️ Tech Stack
Frontend:
HTML5
3D Processing:
LichtFeld Studio (3D Gaussian Splatting, scene editing, and rendering)

Data Source:
Recorded gameplay footage from X4: Foundations
Optional preprocessing via Blender (for mesh alignment / cleanup)
⚙️ How It Works
Capture Gameplay Footage
Record high-resolution video of ships and stations in X4.
Frame Extraction
Convert video into image sequences.
3D Reconstruction
Import frames into LichtFeld Studio
Generate a Gaussian splat scene (point-based volumetric representation)
Scene Editing
Clean up artifacts, isolate objects (ship + station), and align transforms
Web Export
Convert splat data into a format usable in WebGL
Render via a custom HTML viewer
🧪 Use Cases
Game asset visualization & modding pipelines
Sci-fi scene prototyping
Lightweight alternatives to full mesh-based rendering
Interactive documentation of in-game environments
📸 Example Output
Fully navigable 3D scene of an Asgard destroyer
Surrounding space station infrastructure
Real-time lighting and perspective shifts based on camera movement
⚠️ Limitations
Reconstruction quality depends heavily on video coverage and camera motion
Large scenes can be GPU-intensive
Not a true mesh — uses point-based rendering instead of traditional geometry
📌 Future Improvements
Real-time capture → reconstruction pipeline
VR-compatible viewer
Hybrid mesh + splat rendering
Automated object segmentation (ship vs station)
