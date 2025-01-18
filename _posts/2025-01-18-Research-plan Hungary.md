---
title: Research-plan Hungary
updated: 2024-12-27 14:56:12Z
created: 2024-12-21 12:35:47Z
latitude: 35.68919750
longitude: 51.38897360
altitude: 0.0000
---

* * *

# research plan

* * *

- [x] You can search for more relevant literature that could be useful for the topic. (You know the useful sites, such as google scholar, sciencedirect and so on)

Think about what would you like to achieve in the 4 years program. Based on the literature try to set goals and milestones. My personal opinion about PhD is that you should maintain your passion for the topic and work so try to shape it based on your preferences. We have already discussed what would be the main direction but you can think it further.

Some guidelines for the research plan:

- [ ] make some literature review,
- [x] introduce the field,
- [ ] what is the current state and
- [ ] what are knowledge gaps in the articles, based on that you can raise the research questions.
- [ ] After that you can introduce your contribution,
- [ ] what do you want to do,
- [ ] what do you want to achieve.
- [ ] In a separate section you can highlight the relevance and importance of your research.
- [ ] In another section make a planned progress, like what do you want to do in the first semester, first year, after the second year, last year so on (Rough estimation).
- [ ] Also, in another section try to present the publication strategy. For example this trial slicing could be already an article topic if you further work on it and for example compare it with the non constant layer thickness g-code. Also once we have slicer software we can make mechanical testing of the parts as a separate article. Or extend the solution to 6axis robot arm (that we also have at the university).

## Here are the challenges of multi-axis 3D-printing mentioned in the text:

`Staircase Effect:` Constructing along curved features can improve accuracy but avoiding the staircase effect on complex surfaces is difficult.

`Supporting Structures:` Current methods are expensive, and curved bed methods have limited shapes and high errors.

`Surface Quality:` Gravity affects fluid flow, leading to inconsistent surface quality on complex surfaces.

`Redundant Degrees of Freedom:` Adding these to tooling mechanisms and build platforms is necessary but complex.

`Laser Tilting Angle:` Affects surface quality significantly in path planning.

`Mechanical Properties:` Difficult to achieve optimal properties while avoiding the staircase effect.

`Collision Risk:` Larger beds increase collision risk with the nozzle.

`Manufacturing Scale:` Balancing large-scale manufacturing and non-supporting manufacturing is challenging.

`Standards for Communication:` Lack of standardization for communication between CAD systems and robot-assisted manufacturing processes.

`Model Types:` STL, point cloud data, and STEP models have their own challenges, including the need for smoothing and processing.

`IoT Systems:` Developing IoT systems for real-time monitoring and control is complex but necessary.

`Defect Detection:` Integrating machine learning for defect detection and quality improvement is a work in progress.

`Energy Consumption:` Analyzing energy consumption data for optimization is challenging.

> Tang, Pengfei, Xianfeng Zhao, Hongyan Shi, Bo Hu, Jinghu Ding, Buquan Yang, and Wei Xu. 2024. “A Review of Multi-Axis Additive Manufacturing: Potential, Opportunity and Challenge.” Additive Manufacturing 83 (June 2023). https://doi.org/10.1016/j.addma.2024.104075.

* * *

These challenges highlight the areas that need further research and improvement in the field of multi-axis 3D-printing.

`General Applicability:` Many current methods are only applicable to simple, specific structures and equipment. Advanced algorithms for complex structural space partitioning and equipment adaptability are needed.

`Manufacturing Speed and Stability`: The end-motion speed of multi-axis robotic arms is high, but multi-axis 3D printing mechanisms are slower due to material feeding efficiency, material curing time, and motion control algorithms.

`Manufacturing Accuracy:` Errors in multi-axis robotic arms and the need for high-precision positioning sensors and calibration methods to synchronize multiple mechanisms.

`Ease of Use`: The complexity of programming and configuration processes requires professional knowledge, and an intuitive user interface is needed for broader accessibility.

`Demand-Driven Manufacturing:` Different physical requirements need accurate modeling and dynamic processing directions, and construction of suitable forming paths and control methods.

`Integration of Technologies:` Combining various technologies such as physical field analysis, path planning, mechanism design, motion control, new materials, and data-driven process optimization methods.

`Machine Learning Optimization`: Using machine learning for control algorithms, optimizing motion paths and parameter settings, and real-time monitoring and analysis of sensor and visual data during printing.

`Open-Source Systems`: Promoting the development of multi-axis 3D printing through open-source systems to reduce system implementation complexity and continuously integrate new solutions.

> Yao, Yuan, Longyu Cheng, and Zhengyu Li. 2024. “A Comparative Review of Multi-Axis 3D Printing.” Journal of Manufacturing Processes 120 (April): 1002–22. https://doi.org/10.1016/j.jmapro.2024.04.084.

`Underdeveloped Algorithms for RBAM`

```
Lack of novel algorithms for multiaxial deposition, non-planar layers, and advanced infill strategies.
Need for holistic approaches combining multiple optimization factors.
```

`Limited Commercial Software Capabilities`

```
Absence of automated tools to manage RBAM-specific needs like non-uniform layers and curved deposition.
```

`Fragmented Research Directions`

```
Algorithms developed for specific geometries without general applicability or integration.
```

`Inadequate Slicing Strategies`

```
Non-planar and non-uniform slicing techniques are underexplored, despite their potential benefits.
```

`Insufficient Guidelines for Infill Strategies`

```
Lack of standardized approaches to determine optimal infill strategies for performance-specific goals.
```

`Competitiveness of RBAM`

```
Challenges in benchmarking RBAM against traditional manufacturing methods (forming, machining, molding).
```

`Translation to Robot Programs`

```
Limited tools for converting deposition paths into robot programs with full control of process parameters.
```

## Future

Advanced Geometry Representation

```
Develop tools to support Flexible Representations (FRep) for enhanced modeling of complex parts.
```

Integrated Multiaxial Deposition Methods

```
Create holistic frameworks combining support minimization, orientation optimization, and deposition parameter tuning.
```

Hybrid Approaches for Multiaxial Deposition

```
Combine discrete and continuous deposition strategies for better generality and applicability.
```

Enhanced Slicing Algorithms

```
Innovate non-planar and non-uniform slicing methods tailored to part geometries and sub-volumes.
```

Guidelines for Infill Optimization

```
Define guidelines and tools for selecting optimal infill strategies, including for curved and non-uniform layers.
```

==**Decision-Making Tools for Designers**==

```
Develop systems to estimate and compare design, cost, and effort across manufacturing technologies.
```

Automated Translation Tools

```
Build interpreters for generating robot programs from CNC files with continuous parameter control.
```

Trajectory Optimization

```
Research approximation strategies for paths followed by articulated robots.
```

> Lettori, Jacopo, Roberto Raffaeli, Pietro Bilancia, Margherita Peruzzini, and Marcello Pellicciari. 2022. “A Review of Geometry Representation and Processing Methods for Cartesian and Multiaxial Robot-Based Additive Manufacturing.” International Journal of Advanced Manufacturing Technology 123 (11–12): 3767–94. https://doi.org/10.1007/s00170-022-10432-8.

* * *

![a6d5e8ad0020c942cafce2ea096919e2.png](../_resources/a6d5e8ad0020c942cafce2ea096919e2.png)

![2c68a07a3c15538c576b3e02657e1522.png](../_resources/2c68a07a3c15538c576b3e02657e1522.png)

> Xiao, Xinyi, and Sanjay Joshi. 2020. “Process Planning for Five-Axis Support Free Additive Manufacturing.” Additive Manufacturing 36 (September 2019): 101569. https://doi.org/10.1016/j.addma.2020.101569.

* * *

![9765c5886192bbf3f7d8138736b5e445.png](../_resources/9765c5886192bbf3f7d8138736b5e445.png)

![373137b570fc810c4cee8330fbb12248.png](../_resources/373137b570fc810c4cee8330fbb12248.png)  
![3e276f4068f8d530d02ad9d9d3acc1d2.png](../_resources/3e276f4068f8d530d02ad9d9d3acc1d2.png)

![aee8151356eefa3d54448646d144c92e.png](../_resources/aee8151356eefa3d54448646d144c92e.png)

Five research questions have been formulated to perform the review work:

1.  What types of geometry representations are adopted in the AM context?
2.  How are AM geometries elaborated and processed?
3.  What are the algorithms used in the multiaxial deposition approaches?
4.  What are the types of slicing for RBAM?
5.  What are the types of infill strategies for RBAM?

![ca787548ffcba2b3fb983396ef24db15.png](../_resources/ca787548ffcba2b3fb983396ef24db15.png)

![d0d1606c876bb26801f2e553a454d025.png](../_resources/d0d1606c876bb26801f2e553a454d025.png)

![9260d1210105ac7d1dd3b133e86ae7ed.png](../_resources/9260d1210105ac7d1dd3b133e86ae7ed.png)

![f4fbd2de71769a8dad357d7a61c69b30.png](../_resources/f4fbd2de71769a8dad357d7a61c69b30.png)

![c3a919211188a833a866348b1762f529.png](../_resources/c3a919211188a833a866348b1762f529.png)

![1add55c5d85408e3dad32aa7a8fa0e04.png](../_resources/1add55c5d85408e3dad32aa7a8fa0e04.png)

> Lettori, Jacopo, Roberto Raffaeli, Pietro Bilancia, Margherita Peruzzini, and Marcello Pellicciari. 2022. “A Review of Geometry Representation and Processing Methods for Cartesian and Multiaxial Robot-Based Additive Manufacturing.” International Journal of Advanced Manufacturing Technology 123 (11–12): 3767–94. https://doi.org/10.1007/s00170-022-10432-8.

## writing a prompt for chatgpt;
I am providing a research plan (RP) for "Automated toolpath generation for multi-axis 3D printing"; I read some papers. there are reviews papers. I know that the first thing I need is a literature review, but for now I omid it, because it is not necessary for now. first step: I have to explain the topic thoroghly then talk about the some classifications, after that the challanges, and questions that need to be answered. second step: for what I am going to do in the future, first I should choose in which class the research is going to carry on, then talk challanges we are going to face, then how we should encounter those challanges. I also would insisit on a specific aspect of the research that would be intersting to working on. so step by step I will give you material that you need to give me a proper RP.
first step:
    
explain the topic thoroghly
        1. a common workflow of printing:  
            ![454e4cedecc13f65222090ad7e385582.png](../_resources/454e4cedecc13f65222090ad7e385582.png)
1. CAD Model (STL, 3MF, ...)
2. Part orientation/ Multiaxial deposition
3. Slicing         
4. Infill strategy
5. Simulation
6. Manufacturing
7. Post processing
                
> Lettori, Jacopo, Roberto Raffaeli, Pietro Bilancia, Margherita Peruzzini, and Marcello Pellicciari. 2022. “A Review of Geometry Representation and Processing Methods for Cartesian and Multiaxial Robot-Based Additive Manufacturing.” International Journal of Advanced Manufacturing Technology 123 (11–12): 3767–94. https://doi.org/10.1007/s00170-022-10432-8.  
                > Path Planning in Additive Manufacturing (AM):
                

Path planning  
Path planning in AM refers to the design and optimization of deposition paths that guide the print head (e.g., nozzle, laser) during the fabrication process. This strategy determines the movement of the tool to achieve desired product qualities and properties while minimizing time and material usage.  
path planning is using the out put of these steps:

1.  part orientation
2.  slicing
3.  infill strategy  
    to generate routes for moving the print head

aims of working on path planing strategies:

Improve mechanical properties  
Fabricate thin-walled parts  
Fabricate functionally graded compositions  
Fabricate lightweight parts  
Fabricate isotropic parts  
Easy part removal after fabrication  
Improve surface quality  
Improve shape accuracy  
Improve shape accuracy for corners  
Improve shape accuracy under velocity constraints  
Improve infill distribution quality  
Save material  
Save time

examples for plaining strategies:  
Nonplanar strategy  
Path projection strategy  
Kralji´c strategy  
Group-based strategy  
Collision-free strategy

- [ ] classifications,

-   type of the multi-axis matrial extrusion 3D-printer regardless of Coordinate System:

        1. a ordinary Working table with 1,2 and/or 3 extra degrees of freedom. (nozzel direction is fixed)  
		 2. Manipulator with six degrees of freedom, Robotic. (Table is fixed but nozzel have 6 digree of freedom)  
         3. Combination of manipulator (robot) and working table with 6 and 2 degrees of freedom respectively,  
             4. others: 4-axis 3d-printers it is ordinary working table with nozzle that has 1 dgree extra freedom.  

- Part orientation/ Multiaxial deposition
    1. Fixed (ordinary 2.5 axis printers)
    2. Multiaxial
        1. volume decomposition  
        2. selection of the orientation of each part (decison-making)

- Slicing
                1. Planar
                2. non-planar = curved (NOT found in commercial software)
       type of layers : 
                1\. the distance between layers  
                \- uniform slicing (Constant)  
                \- adaptive slicing  
                2\. thickness  
                \- Uniform  
                \- Non-uniform

aims of working on path planing strategies:

Improve mechanical properties  
Fabricate thin-walled parts  
Fabricate functionally graded compositions  
Fabricate lightweight parts  
Fabricate isotropic parts  
Easy part removal after fabrication  
Improve surface quality  
Improve shape accuracy  
Improve shape accuracy for corners  
Improve shape accuracy under velocity constraints  
Improve infill distribution quality  
Save material  
Save time

examples for plaining strategies:  
Nonplanar strategy  
Path projection strategy  
Kralji´c strategy  
Group-based strategy  
Collision-free strategy  
-  challanges:

1. Core Technical Challenges

    1. Staircase Effect: Avoiding this defect on complex surfaces remains a major hurdle despite improved accuracy along curved features.
    2. Surface Quality: Inconsistent quality caused by gravity's effect on fluid flow during deposition.
    3. Collision Risk: Larger beds and complex tool movements increase the risk of nozzle collisions.
    4. Thermal Stress and Warping: Managing thermal gradients to prevent residual stresses and deformation.
    5. Path Continuity and Transition: Ensuring smooth transitions between layers or sections to maintain structural integrity.
    6. Post-Processing Complexity: Removing supports and finishing multi-axis geometries is more challenging than in traditional 3-axis systems.
    7. Material Compatibility: Achieving seamless integration of multiple materials in multi-material deposition.
    8. Manufacturing Speed and Stability: Limited by material feeding rates, curing times, and slower motion control in multi-axis setups.
    9. Redundant Degrees of Freedom: Complexity increases significantly with the addition of more motion axes to the system.

2. Algorithmic and Software Limitations

1. Underdeveloped Algorithms for RBAM: Lack of holistic approaches for multiaxial deposition, non-planar slicing, and advanced infill strategies.
2. Inadequate Slicing Strategies: Current methods for non-uniform and non-planar slicing are underexplored despite their potential benefits.
3. Advanced Geometry Representation: Need for flexible tools like FRep for modeling complex parts.
4. Translation to Robot Programs: Few tools efficiently convert multi-axis paths into executable robot programs.
5. Machine Learning Optimization: Real-time analysis and optimization of toolpaths using AI and sensor data integration.

3. Operational and Implementation Barriers

1. Ease of Use: Complex programming and configuration processes necessitate professional expertise; user-friendly interfaces are essential.
2. Manufacturing Accuracy: Errors in multi-axis mechanisms require precise sensors and calibration for synchronization.
3. Cost of Implementation: High costs associated with hardware, software, and training limit widespread adoption.
4. Safety and Automation: Balancing high-speed operations with safety in automated environments is critical.
***

   - questions that need to be answered:
1. What types of geometry representations should be adopted in the AM context?
2. How are AM geometries elaborated and processed?
3. What algorithms are best suited for multiaxial deposition approaches?
4. Which types of slicing methods are optimal for RBAM?
5. Which types of infill strategies for RBAM would be chosen?
6. What is the effect of infill strategies in RBAM on mechanical properties versus traditional 3-axis 3D printers?
7. Which type of multi-axis material extrusion 3D printer, regardless of the coordinate system, should be chosen?
8. What are the computational challenges associated with real-time toolpath generation for multi-axis systems, and how can they be addressed?
9. How do different multi-axis motion systems (e.g., robotic arms, delta printers) impact toolpath planning complexity?
10. What methods can be employed to optimize material usage and minimize print time in multi-axis 3D printing?
11. How can collision detection and avoidance be integrated into toolpath generation algorithms?
12. What role does feedback and adaptive control play in ensuring precision in multi-axis additive manufacturing (AM)?
13. How do heat dissipation and thermal effects influence toolpath strategies in multi-axis systems?
14. What is the impact of anisotropy in material properties on toolpath design for functional multi-axis prints?
15. How can multi-material deposition be incorporated into multi-axis toolpath generation?
16. What are the implications of different CAD/CAM software integrations for multi-axis AM?
17. How can machine learning and AI be leveraged to enhance toolpath optimization and predict errors in multi-axis 3D printing?
18. How can finite element analysis (FEA) be used to inform toolpath design and evaluate the structural integrity of printed components?
19. What decision-making frameworks can be developed to balance speed, precision, and cost in multi-axis 3D printing workflows?
***

- [ ] second step:
    
    - [ ] which classes,
    - [ ] challanges
    - [ ] how we should encounter those challanges.
    - [ ] decision-making
	- [ ] Finite element analysis

robot-based AM (RBAM)



Finite element analysis to generate load paths Generation;  
decison-making for anything selection (from the orientation to infill strategy to path plannnig strategies)

some information;
Multi-axis 3D printing has emerged as a key solution to the challenges associated with the strength, anisotropy, and fabrication of large-scale structures in material-deposition-based 3D printing processes.
multi-axis printing is expected to achieve more uniform material distribution, so that the material deposition path is no longer limited to a fixed direction, reduc- ing the anisotropy problem of the part, thereby improving mechanical isotropy [6].
Compared with traditional Cartesian coordinate 3D printing, the multi-axis system can adjust the construction direction and posture of the print head to make the molten material deposition more closely conform to the surface curvature, thereby

Therefore, as an emerging trend, multi-axis 3D printing not only expands the geometric freedom but also brings new opportunities for improving the performance of AM parts, ogies, where strength is notably pronounced along the axis of the fine wire but comparatively weaker in other directions [7]. In stark contrast, multi-axis 3D printing demonstrates the capability to augment the mechanical properties of 3D printed models by introducing con- trolled anisotropy and determining the optimal printing direction

There is no unified software for convenient multi axis 3D printing.

The structure is relatively simple and the software supports a lot n 2.5/3 axis 3d printers. .
Anisotropy — parts are weaker along the Z-axis in 2.5/3 axis 3d printers. 
multi-axis 3d priners: 
Can produce complex geometries with high quality, More uniform mechanical properties due to variable layer orientation, Enhanced detail due to the ability to change printing angles and support-free, Can print large parts with complex geometries,  multi-axis 3d priners.
Mechanics: Complex, including at least 4 degrees of freedom with possible combination [38] of rotation and tilt functions [35,39].
Better, able to print suspended structures and complex shapes without [12,40] or with minimal support [29].
Usually smoother because it supports surface layered printing [11] and reduces the use of supporting structures [41].
Large-size printing: Potential for larger build volumes [19,19], suitable for printing large objects.
Slower for complex geometries [42], but faster for some applications (A large amount of support is required in traditional 3D printing).
Associated technologies: Robotic arms, multi-axis motion platforms [17], specialized slicing software [10].
Complexity and cost: Higher, requiring more complex mechanical systems and software support.
*** 

