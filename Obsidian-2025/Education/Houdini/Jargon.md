# Common Houdini Terminology

- **Promote**  
  Move attributes or parameters from one level to another (e.g., vertex → point).  
  Commonly done in VOPs or with Attribute Promote node.

- **Parameter**  
  A setting or control on a node.  
  Can be keyframed or referenced to drive procedural changes.

- **Wrangle**  
  A node that executes VEX code to manipulate geometry, attributes, etc.  
  Compact way to perform advanced operations.

- **Attribute**  
  Data stored on geometry (points, vertices, primitives).  
  Examples: position (P), normals (N), UVs.

- **Channel Reference (ch())**  
  Expression syntax for referencing other parameters.  
  Makes nodes and parameters interdependent.

- **Groups**  
  Subsets of geometry (points, edges, primitives) that can be isolated or manipulated separately.

- **VEX**  
  Vector EXpression Language used in Wrangles and other advanced node setups.  
  Powers procedural logic and fast computations.

- **VOPs (Vector Operators)**  
  Visual programming for VEX.  
  Nodes that you wire together to build VEX-like logic.

- **SOPs (Surface Operators)**  
  Geometry manipulation context.  
  Where most modeling and attribute editing happens.

- **DOPs (Dynamic Operators)**  
  Context for simulations (rigid body, fluid, pyro, etc.).  
  Manages solvers and simulation states.

- **COPs (Composite Operators)**  
  2D image processing context.  
  Basic compositing inside Houdini.

- **TOPs (Task Operators)**  
  For pipeline automation and batch processing.  
  Uses PDG (Procedural Dependency Graph).

## High-Level Interface
- **Network Editor**  
  Where you create/connect nodes.  
  Each context (SOPs, DOPs, etc.) has its own Network.

- **Scene View (Viewport)**  
  3D workspace to visualize and interact with geometry, lights, cameras.

- **Parameter Pane**  
  Displays parameters of the selected node.  
  Editable settings for procedural control.

- **Shelf Tools**  
  Pre-built tools to quickly create nodes or set up tasks (e.g., “Create Fire”).  
  Speeds up common workflows.

- **Timeline**  
  Where you keyframe and scrub through animation frames.  
  Integrates with CHOPs (Channel Operators) for complex motion.

- **Pane Tabs**  
  Customizable interface sections (Network, Parameters, Scene View, etc.).  
  You can split or combine them as needed.

- **Color-Coded Contexts**  
  SOPs in **green**, DOPs in **orange**, etc.  
  Helps you quickly identify the node type.
