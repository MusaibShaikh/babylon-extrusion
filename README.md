# Babylon.js 2D Shape Extrusion and Manipulation

## Goal:
The goal of this assignment is to create a Babylon.js application that allows the user to draw arbitrary 2D shapes on the ground plane, extrude them into 3D objects with a fixed height, and then manipulate those objects by moving the object and editing their vertices using buttons for mode selection.

## Requirements
1. Use Babylon.js to create a 3D scene with a ground plane.

2. Implement functionality to allow the user to draw 2D shapes on the ground plane using mouse interactions (e.g., left-click to add points, right-click to complete the shape). Provide a "Draw" button to enter the draw mode.

3. Once the shape is completed (a closed loop), provide a UI element (e.g., button) to initiate the extrusion process. The extrusion height can be a fixed hard coded value.

4. Allow the user to move the extruded objects on the ground plane using mouse interactions (e.g., click and drag). Provide a "Move" button to enter move mode.

5. Implement functionality to edit the vertices of the extruded object using mouse interactions (e.g., click and drag to move vertices). Provide a "Vertex Edit" button to enter vertex edit mode.

6. Provide visual cues and UI elements to indicate the selected object and active editing mode (move or edit vertices).

## Setup:
1. Clone Repository:
    ```bash
    git clone https://github.com/MusaibShaikh/babylon-extrusion
    ```

2. Install Dependencies: 
    ```bash
    npm install
    ```

3. Running the Program:
    ```bash
    npm run dev
    ```


## Functionality:

### Add Shape:
- Click on the "Add Shape" button to start drawing a shape on the ground.
- Click on the ground to add vertices to the shape.
- Once vertices are added, set your desired extrusion length, default is 10, click "Extrude" to create a 3D extrusion.
- You can Add as many shapes as you want by clicking Add Shape button.

### Delete Shape:
- Click on the "Delete Shape" button to enter the delete mode.
- Click on a 3D shape to hide it.
- Click "Save" to confirm deletion or "Cancel" to revert.
- Note: Only one shape can be deleted at a time. Also, you may need to change viewing angle a little if the object is not highlighted.

### Move Shape:
- Click on the "Move Shape" button to enter the move mode.
- Click on a 3D shape to select it and create a holographic copy.
- Move the hologram to the desired location.
- Click "Save" to confirm the move or "Cancel" to revert.
- Note: Only one shape can be moved at a time. Also, you may need to change viewing angle a little if the object is not highlighted.

### Vertex Edit:
- Click on the "Vertex Edit" button to enter vertex editing mode.
- Click on a 3D shape to enter edit mode.
- Add vertices, remove vertices, or move vertices using respective buttons.
- For each of the vertice operation, click "Save" to confirm the changes or "Cancel" to revert.
- Click "Done" to after finishing all the edit changes.
- Note: Multiple vertices can be added, removed, or moved at once. Also, you may need to change viewing angle a little if the vertex is not highlighted.
