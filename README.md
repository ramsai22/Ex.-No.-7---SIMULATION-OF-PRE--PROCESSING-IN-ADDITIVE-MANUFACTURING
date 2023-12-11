# Ex. No. 7 - SIMULATION OF PRE PROCESSING IN ADDITIVE MANUFACTURING
### DATE: 11/12/2023
## AIM:
### To simulate the Pre Processing for 3D printing.

## REQUIREMENTS:
### System - Windows 7 or higher, 1 GB RAM.

## PROCEDURE:
### Pre-processing encompasses the steps between design and printing. Process of 3D printing starts with designing in CAD. Then printer software slices 3D CAD file into layers. For each slice, the software converts the data into machine code that determines tool paths for the machine to follow. The various steps in pre-processing from design to printing are as follows:

### 1)	CAD File
### 2)	Conversion to STL a. Orientation b. Support Structure c. Slicing d. Path Planning

### 1. CAD File
### Every manufacturing process starts with the process of designing and as in any type of manufacturing, there are certain limitations to the materials and manufacturing processes that dictate how the product should be designed, 3D printing is no different. In 3d printing, characteristics of hardware, software, temperature, filament and many other factors play an important role in how a digital model translates into a printed object. Some of them are designed with a strong base, grain direction, overhung, wall thickness, round corners and tolerances.

### 2. Conversion to STL
### In order to check the interface of the object and make it reliable to 3d printers, conversion to STL file is required. It also facilitates other features like quick error check, bridging the gap between CAD platforms, exhibition purposes and 3D digitizer extension.

### a. Orientation:
### Orientation plays a vital role in the final product of 3d printing as it affects the part accuracy, manufacturing time, strength and surface finish. There are various orientations by which we can print the object such as vertically upward, vertically downward and in horizontal plane.

### b. Support Structure:
### Support structures are required where the objects are unable to get printed directly. Support structures help to guarantee the printability of a section during the 3D printing measure and also it can assist with forestalling part twisting, secure a section to the printing bed and guarantee that parts are joined to the fundamental body of the printed part.

### c. Slicing:
### The motive behind slicing a 3D model is to transform the model into guidelines for the 3D printer. To play out this errand, the slicing software isolates the item into numerous layers. It's classified "slicing" since it "slices" the 3D model to make numerous layers. After the layers have been made, the slicing software applies different qualities to every one of them.

### d. Path Planning:
### Path planning helps to improve the printed surface quality, shape accuracy and infill distribution quality. There are various ways for path planning which can be used to print the objects which may affect the following factors in objects like raster path, grid path, spiral path and zigzag path.

![image](https://github.com/Sellakumar1987/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/113594316/baef8515-67d7-4c96-accc-4ee88035c9e7)

### ●	All the processes related to pre-processing will be shown on the screen.
### ●	Select CAD file preparation from the visible list.
### ●	When the first process is selected then it will open in the blank space in the left side of the screen.
### ●	Select the options of process of pre-processing in the sequence in which they are shown.
### ●	If the user follows an incorrect sequence then a pop-up will appear on the screen showing the name of the process to be selected.

## Output:
## CAD file preparation:
![image](https://github.com/ramsai22/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/150319855/e9daa7d4-8601-4ef2-b167-f9baacd72cef)
## Explanation:
The first step in rapid prototyping is to prepare a computer-aided design (CAD) model of the object to be fabricated using layer based manufacturing processes.

The process begins with importing the 3D CAD model into the software environment, typically in formats like STL. The CAD model undergoes geometry repair and cleanup to address imperfections, gaps, or errors that could hinder the printing process. Adjustments to scale and orientation are made to match the intended size and optimize placement within the build chamber, minimizing supports and improving surface finish.

Analyzing wall thickness and feature size is essential for structural integrity, while hollowing and lattice structures may be applied to reduce material usage and printing time. The generation of support structures, necessary for overhanging features, is a crucial step, often involving both automated and manual adjustments. Checking and editing overhangs ensures that the model aligns with the printer's capabilities.

Once this process complete,the model is either converted or exported as STL file.
## Conversion to STL:

![Screenshot 2023-12-11 155850](https://github.com/ramsai22/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/150319855/c5382185-38b9-4b9d-846a-13d10ac8fb0d)
## Explanation:
STL file is also known standard tesstellation language in which model is represented as triangular patterns.It covers only the information about surface structure of the model not the internal features. Conversion to STL is a crucial step in preparing CAD models for 3D printing. STL, or Standard Tessellation Language, is a widely used file format that represents 3D models using a mesh of interconnected triangles. The process involves generating this mesh from the original CAD model, ensuring a closed and watertight structure. The resolution of the STL file is a key consideration, balancing detail with file size. Surface normals must be consistently oriented to prevent printing issues.

The conversion is essential for compatibility with 3D printers, as STL provides a straightforward representation of the model's geometry. The file undergoes optimization to reduce size without compromising detail. Once converted, the STL file serves as input for subsequent stages in additive manufacturing, including slicing and toolpath generation. This standardized format simplifies complex geometric shapes for easy interpretation by 3D printers, contributing to the efficiency of the overall 3D printing workflow. On CAD software itself ,it process and convert CAD file into STL file.

## Orientation:

![Screenshot 2023-12-11 213533](https://github.com/ramsai22/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/150319855/cae4a4bf-5aa3-42cc-aba1-952c8b3c08d0)

## Explanation:
In slicer software STL file is loaded .The object orientation is need to be check.without proper orientation ,time and excess material can be consumed. Orientation in 3D printing refers to how a model is positioned within the printer's build chamber. This decision significantly impacts various aspects of the printing process. Proper orientation minimizes the need for support structures, enhances surface finish, and influences printing time. It also affects structural strength, material flow, and heat distribution during printing.

The choice of orientation is crucial for optimizing the overall efficiency of the print, ensuring stability, and achieving the desired balance between quality, material usage, and printing time. Simulation tools and experience play a role in determining the optimal orientation, allowing users to visualize and analyze the potential outcomes before initiating the printing process. A proper orientation increase strength of the model .The model should be printed along the direction of force that going to withstand.
## Support structure:

![Screenshot 2023-12-11 213717](https://github.com/ramsai22/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/150319855/1bdcc1d4-fe9e-4330-ac02-e752cdde2164)
## Explanation:
As we see before proper orientation need lesser support material .But at some places there might be need of support material which supports overhanging parts(ie.,angle above 45).However they need to be removed after printing. Support structures are integral in 3D printing, providing temporary support for overhanging or complex features during the printing process. Generated automatically based on the model's geometry, these structures anchor to the build platform and prevent issues like sagging or collapse. Support materials match the main print material and are designed for easy removal post-printing.

Proper orientation reduces the need for extensive supports, optimizing material usage and simplifying post-processing. Users can adjust support density and patterns, with manual placement available for complex geometries. Post-processing involves careful removal of supports to avoid damage. While supports are crucial, minimizing their use is essential for printing efficiency, as excessive supports can increase material consumption and printing time. Advanced slicing software aims to optimize support generation, contributing to more efficient 3D printing processes.
## Slicing:

![Screenshot 2023-12-11 213859](https://github.com/ramsai22/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/150319855/8ed75e3c-f223-4b27-9328-255cc9b95f8d)
## Explanation:
Slicing is converting digital 3D models into printing instructions for a given 3D printer to build an object. Slicing is a fundamental step in 3D printing where slicing software breaks down a 3D model into horizontal layers, generating toolpaths for the 3D printer. These toolpaths guide the printer in depositing or curing material layer by layer to build the final object. Users can define various print parameters, such as layer height, speed, and support structures, influencing print quality and characteristics.

The output is G-code, a set of instructions for the printer. Slicing software often includes preview or simulation features for users to inspect and address potential issues before printing. The process aims to optimize efficiency, reducing print times and material usage. Compatibility with specific 3D printers is crucial, ensuring that the generated G-code aligns with the printer's specifications. Slicing is a critical link between the digital model and the physical printed object, impacting the overall success of the additive manufacturing process. In addition to the model itself, the instructions contain user-entered 3D printing parameters, such as layer height, speed, and support structure settings.

## Path planning:

![Screenshot 2023-12-11 214055](https://github.com/ramsai22/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/150319855/d9b28c7b-f7f3-4996-a022-e03bb058fa13)
## Explanation:
The infill pattern determines the arrangement of the internal structure within the 3D printed object. Common infill patterns include rectilinear, honeycomb, grid, and concentric. The process considers digital representations of the environment, including obstacles and boundaries. Key elements include defining start and goal states, obstacle avoidance, and optimization criteria like minimizing travel time. Path planning algorithms account for constraints such as robot dynamics and environmental changes, and they can be categorized as local or global planning. The generated path is represented by waypoints, mathematical curves, or line segments.

Real-time adaptations and feedback control may be integrated, and the choice of algorithm depends on the application's complexity and requirements. Effective path planning is essential for ensuring safe, efficient, and reliable robotic navigation in diverse environments. Each pattern has its own characteristics in terms of strength, material usage, print time, and surface finish. The choice of infill pattern depends on the specific requirements of the printed object.

### Name:paida ram sai
### Register Number: 23007931

## Result: 
### Thus the simulation on the Preprocessing in additive manufacturing is completed.
