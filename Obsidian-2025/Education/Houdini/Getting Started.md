## Node-Based Workflow
- Everything is an operator (node).
- Wire them together to build your scene.

## Contexts & Networks
- Geometry (SOPs)
- Shading (MATs)
- Compositing (COPs)
- Dynamics (DOPs)
- Each context has its own node network.

## LookDev & Layout
- Create and place assets.
- Materials and shading in LookDev.
- Arrange objects in your scene.

## Lighting & Rendering
- Lights are also nodes.
- Render with Mantra or Karma.
- Set parameters in the Render context.

## Animation & Characters
- Rig with bones or KineFX.
- Keyframe in Timeline or use CHOPs.

## VFX & FX Nodes
- Fire, smoke, fluids in DOPs.
- Specialized nodes for pyro, particles.

## Objects & Hierarchy
- Organize items in `/obj` networks.
- Each object references geometry, lights, cameras, etc.

# From the Video on Houdini's website

![[Pasted image 20250207093639.png]]

![[Pasted image 20250207093727.png]]

![[Pasted image 20250207093831.png]]

XPU is a hybrid renderer that uses the GPU and then only uses the CPU if it absolutely needs to use it.

![[Pasted image 20250207093951.png]]

![[Pasted image 20250207094016.png]]

# Object level
primarily focused on transformations.
![[Pasted image 20250207094054.png]]

# Geometry level:
 



















