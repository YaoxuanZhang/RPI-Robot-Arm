# RPI Robotics 6-Axis DoM Arm (Annin Robotics 4)

This repository contains a Blender IK rig for the RPI Robotics 6-Axis Degree of Movement (DoM) Arm. The IK rig allows you to simulate and control the movements of the arm within the Blender software.

Animated Render Demonstration

https://github.com/YaoxuanZhang/RPI-Robot-Arm/assets/18201848/8cd5e0dd-7378-4c76-9b4f-49f61d702f40

IK Demo as of v1.1

https://github.com/YaoxuanZhang/RPI-Robot-Arm/assets/18201848/3d08114e-f34e-4fbe-b6fe-794dd43d9817

## Features

- Inverse Kinematics (IK) control
- Adjustable joint limits to match the physical limitations of the arm
- Realistic arm physics simulation

## Getting Started

To use the IK rig, follow these steps:

1. Clone or download this repository to your local machine.
2. Open Blender and navigate to the directory where you cloned/downloaded the repository.
3. Open the `.blend` file corresponding to the version you are looking for.
4. You will see the 3D model of the arm with the IK rig applied.
5. Use the control bones to move and animate the arm.
6. Adjust the joint limits if needed to match the physical limitations of the arm.

## Exporting Blender Data to a Micro-controller

In the future, we plan to develop code projects that allow for exporting Blender data to a micro-controller. This will enable you to control the RPI Robotics 6-Axis DoM Arm directly from your micro-controller, providing a seamless integration between the virtual arm in Blender and the physical arm.

## Special Thanks

I would like to extend a special thanks to the following individuals and organizations for their contributions:

- Thomas Byrne: OBJ Assembly
- [Annin Robotics](https://www.anninrobotics.com/): Robot Design and CAD

## File Structure

The file structure of this repository is as follows:

- `BLD - IK Rigs`: The directory containing all versions of the IK rigs.
- `README.md`: This file, providing an overview and instructions.

## Dependencies

This IK rig was created in Blender version 3.6.4, thus requiring that version or above for optimal compatibility. Make sure you have Blender installed on your machine before using this rig.

## Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request. Contributions are welcome!

## License

This project is licensed under the [MIT License](LICENSE).
