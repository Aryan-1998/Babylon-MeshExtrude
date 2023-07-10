# Interactive Extrude Mesh Project 

This project is an interactive tool for extruding 3D meshes. It allows users to manipulate and modify the geometry of a mesh by interactively extruding its faces.

## Usage
1. Clone the repository.
2. Run the following command:

   - npm install
   - npm run dev

After the command will be executed, open your browser and navigate to local host url to load site.

## Instructions

1. ### Extrude the mesh
   
   - To perform an extrusion, click on one of the faces of the cube. This action will select the face for extrusion.
   - Once the face is selected, move your cursor. You will notice that the selected face moves in the direction of its normal vector.
   - To complete the extrusion, click again (release the click after the first click).
     
2. ### Reset the mesh
   
   - A reset button is located in the top-right corner of the scene. Clicking the reset button will revert the dimensions of the cube, 
   undoing any changes made to it.

3. ### chanding to different mesh

   - You can choose any mesh for trial, uncomment cylinder code for extruding the cylinder and the extrusion function would still work, except, after the reset, it is going to reset to being a cube.
