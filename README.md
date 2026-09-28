# Real-Time Continuum Viscoelastic Bouncing Sphere

A real-time 3D continuum mechanics simulation written in Python and PyQt6.

## Highlights
- **Viscoelastic Contact Mechanics:** Hertzian boundary contacts paired with Kelvin-Voigt internal dampening.
- **Deformable Geometry:** Dynamic mesh compression, surface restitution, and approximate volume preservation.
- **Telemetry Overlay:** Real-time velocity vectors, kinetic/potential energy balance, and computational throughput.

## Getting Started

```bash
python3 -m venv venv
source venv/bin/activate
pip install PyQt6 numpy
python coupled_physics_sphere.py

