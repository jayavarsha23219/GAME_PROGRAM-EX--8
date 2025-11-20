# GAME_PROGRAM-EX--8

# Landscape Creation and Foliage in Unreal Engine
# Aim
To create a landscape in Unreal Engine, apply a custom landscape material, and add foliage for realistic environment generation.

# Procedure
# 1.Create a New Landscape:
      Open your Unreal Engine project.
      Go to the Modes Panel and select Landscape.
      Set the desired section size, number of components, and overall resolution.
      Click Create to generate the landscape.
      
# 2.Apply a Landscape Material:
      In the Content Browser, create a new Material and name it M_Landscape.  
      Open the material and:
         Use Landscape Layer Blend to blend textures (e.g., grass, rock, dirt).
         Connect appropriate texture samplers to different layers.
         Output the final blend to the Base Color, Normal, and optionally Roughness inputs.
      Save the material.
      Select the landscape in the scene, go to the Details Panel, and assign M_Landscape to the Landscape Material slot.
      
# 3.Add Foliage:
     Go to the Foliage Mode from the Select Mode dropdown.
     In the Foliage Panel, click the + icon to add Static Meshes (e.g., trees, grass, bushes).
     Adjust settings like Density, Scale, and Randomness.
     Use the brush tool to paint foliage onto the landscape.  

# Output

<img width="557" height="300" alt="image" src="https://github.com/user-attachments/assets/a21b8dbf-7d2e-4a0a-82b6-959a194b8a49" />

<img width="563" height="307" alt="image" src="https://github.com/user-attachments/assets/14253d44-eee3-4acb-964f-658069d4ace6" />

# Result
A landscape was successfully created and enhanced with:
    A layered, textured material using M_Landscape.
    Static mesh fol
     
