
# ✏️ Module 03: Sketching Fundamentals

Welcome to the point where ideas begin to take shape!

Before we build complex 3D models, we need to master the foundation: **2D sketching**.

In Fusion 360, sketches define the geometry and dimensions that many 3D features are built from. A rectangle can become a box, a circle can become a cylinder, and a carefully dimensioned profile can become a functional mechanical component.

Let's turn rough ideas into precise engineering geometry! 🚀

## 🎯 Mission Objectives

By the end of this module, I aim to:

- Create and edit 2D sketches.
- Understand sketch planes and the Sketch workspace.
- Use Line, Rectangle, Circle, Arc, and other basic sketch tools.
- Apply dimensions to control exact sizes.
- Understand geometric constraints.
- Distinguish between under-constrained, fully constrained, and over-constrained sketches.
- Create accurate sketches ready for 3D modeling.

## 🧠 1. What Is a Sketch?

A sketch is a collection of 2D geometry created on a plane.

It can contain lines, circles, arcs, rectangles, and other supported geometric elements.

For example, I can sketch a rectangle measuring 60 mm × 40 mm. Later, I can extrude it by 10 mm to create a rectangular solid.

**Engineering rule:** A shape that looks correct on screen is not necessarily dimensionally correct.

## 🛠️ 2. Essential Sketch Tools

| Tool | Purpose |
|---|---|
| Line | Creates straight line segments |
| Rectangle | Creates rectangular profiles |
| Circle | Creates circular geometry |
| Arc | Creates curved geometry |
| Center Diameter Circle | Creates a circle using its center and diameter |
| Trim | Removes unwanted portions of sketch geometry |
| Offset | Creates geometry at a specified distance from existing geometry |
| Mirror | Creates a reflected copy of sketch geometry |
| Sketch Dimension | Defines numerical measurements |
| Constraints | Control geometric relationships |

*Note: Tool availability and exact command names can vary by sketch context and Fusion version.*

## 📏 3. Dimensions: Precision Matters!

Dimensions define the numerical size or position of sketch geometry.

Examples:

- A rectangle with a length of 60 mm.
- A circle with a diameter of 10 mm.
- Two parallel lines separated by 20 mm.

Dimensions help make designs accurate, repeatable, and easier to modify.

### Mini Example

Suppose I need a rectangular mounting plate:

- Length: 60 mm
- Width: 40 mm

I should create the rectangle and apply the required dimensions instead of estimating its size by eye.

## 🧩 4. Geometric Constraints

Constraints define relationships between sketch elements.

| Constraint | Meaning |
|---|---|
| Coincident | Connects points or places geometry on another geometric element |
| Horizontal / Vertical | Keeps a line horizontal or vertical |
| Parallel | Keeps two lines parallel |
| Perpendicular | Keeps two lines at 90° |
| Equal | Makes supported geometry elements equal in size |
| Tangent | Creates a smooth tangent relationship between supported elements |
| Concentric | Aligns the centers of circular geometry |
| Midpoint | Places a point at the midpoint of a line segment |
| Fix / UnFix | Locks or unlocks geometry relative to the sketch |

Constraints help a sketch behave predictably when dimensions or geometry are changed.

## 🔒 5. Under-Constrained vs Fully Constrained

### Under-Constrained

Some sketch geometry can still move or change size because its position or dimensions are not completely defined.

### Fully Constrained

The sketch geometry has no remaining unintended degrees of freedom under the applied dimensions and constraints.

### Over-Constrained

The sketch contains conflicting or redundant constraints or dimensions that Fusion cannot resolve as specified.

**Goal:** Learn to create a well-defined sketch without adding unnecessary or conflicting constraints.

## 🔬 6. Hands-On Mission

I will create these sketches in Fusion 360:

### Exercise A: Rectangle

- [ ] Create a new sketch on a suitable plane.
- [ ] Draw a rectangle.
- [ ] Set its length to 60 mm.
- [ ] Set its width to 40 mm.
- [ ] Add appropriate dimensions and constraints.

### Exercise B: Circle

- [ ] Create a circle.
- [ ] Set its diameter to 20 mm.
- [ ] Apply appropriate constraints.
- [ ] Verify the displayed dimension.

### Exercise C: Mounting Plate Sketch

- [ ] Create a rectangle measuring 80 mm × 50 mm.
- [ ] Add four circles for mounting holes.
- [ ] Position the holes using dimensions.
- [ ] Check the geometry for accuracy.
- [ ] Save the design.

The hole diameter and hole positions will be chosen and documented as part of the exercise.

## 📸 Screenshots and Evidence

Save screenshots of my actual work in the `images/` folder:

- `01_Basic_Sketch.png`
  <img width="1917" height="978" alt="Screenshot 2026-10-13 143324" src="https://github.com/user-attachments/assets/613a5e0f-63c5-4730-8e1a-e8d8a11ab651" />
- `02_Dimensioned_Rectangle.png`
- `03_Constrained_Circle.png`
- `04_Mounting_Plate_Sketch.png`

Save the corresponding Fusion design files in `design_files/`.

## 🐛 Mistakes and Lessons Learned

Document real problems I encounter:

- Why did my sketch move unexpectedly?
- Which dimensions or constraints were missing?
- Did I accidentally add conflicting constraints?
- How did I fix the sketch?

Understanding mistakes is part of becoming a better designer.

## 🏁 Module Completion Criteria

- [ ] Create basic sketch geometry.
- [ ] Apply dimensions accurately.
- [ ] Use common geometric constraints.
- [ ] Understand sketch constraint states.
- [ ] Complete the mounting plate sketch.
- [ ] Save the design and add screenshots.
- [ ] Document at least one lesson learned.

## 🚀 What's Next?

**Module 04: 3D Modeling Basics**

Next, I will learn how to turn sketches into 3D objects using tools such as Extrude, Revolve, Fillet, Chamfer, and Hole.

*Sketch with purpose. Dimension with precision. Design like an engineer!* 🔧
