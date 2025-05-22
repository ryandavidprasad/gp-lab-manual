# EXP-01: Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.
## Date:5/3/25
## Aim:
To implement various effects in a material such as emissive, roughness and metallic
properties in Unreal Engine.

## Procedure:
1.Create a New Material:

2.Open Unreal Engine.
In the Content Browser, right-click and select Material.
Name it M_EffectsDemo.
Apply Base Color:

3.Open the material.
Add a Vector Parameter or Constant3Vector node and connect it to the Base Color input.
Add Emissive Effect:

4.Add a Multiply node.
Connect a Constant3Vector (for emissive color) and a Scalar Parameter (for intensity).
Connect the result to the Emissive Color input.
Control Roughness:

5.Add a Scalar Parameter node and connect it to the Roughness input.
Lower values = shinier surface, higher values = rougher surface.
Control Metallic Property:

6.Add a Scalar Parameter node and connect it to the Metallic input.
0 = non-metal, 1 = fully metallic.
Save and Apply Material:

7.Save the material.
Apply it to any mesh in the scene (like a sphere or cube) to preview the results.
Output


## Output:

![image](https://github.com/user-attachments/assets/5ab77593-88ec-427a-b27b-e11b23fb54dd)

![image](https://github.com/user-attachments/assets/a6498699-c2d3-4a1e-bf77-1a71cd86a29c)



## Result:
Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine was done successfully.
