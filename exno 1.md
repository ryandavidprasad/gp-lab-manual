# EXP-01: Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.
## Date:5/3/25
## Aim:
To implement various effects in a material such as emissive, roughness and metallic
properties in Unreal Engine.

## Procedure:
Create a New Material:

Open Unreal Engine.
In the Content Browser, right-click and select Material.
Name it M_EffectsDemo.
Apply Base Color:

Open the material.
Add a Vector Parameter or Constant3Vector node and connect it to the Base Color input.
Add Emissive Effect:

Add a Multiply node.
Connect a Constant3Vector (for emissive color) and a Scalar Parameter (for intensity).
Connect the result to the Emissive Color input.
Control Roughness:

Add a Scalar Parameter node and connect it to the Roughness input.
Lower values = shinier surface, higher values = rougher surface.
Control Metallic Property:

Add a Scalar Parameter node and connect it to the Metallic input.
0 = non-metal, 1 = fully metallic.
Save and Apply Material:

Save the material.
Apply it to any mesh in the scene (like a sphere or cube) to preview the results.
## Output:

![image](https://github.com/user-attachments/assets/38b6b220-6a83-4455-b007-345c83d111d2)

![image](https://github.com/user-attachments/assets/f66bb31f-49aa-43ee-b35e-aca7c1459897)


## Result:
Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine was done successfully.
