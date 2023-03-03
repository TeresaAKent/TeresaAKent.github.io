# Whisker Research

This is a github repository for the code used to develop whisker-inspired sensors by Teresa Kent and her collaborators as part of her PhD in the Micro Robotics Lab in the Robotics Institute at Carnegie Mellon University.


# Identifying Contact Distance Uncertainty in Whisker Sensing with Tapered, Flexible Whiskers
### Teresa A. Kent, Hannah Emnett, Mahnoush Babaei, Mitra J. Z. Hartmann, Sarah Bergbreiter

**Abstract-Whisker-based tactile sensors have the potential to perform fast and accurate 3D mappings of the environment, complementing vision-based methods under conditions of glare, reflection, proximity, and occlusion. Current algorithms for mapping with whiskers make assumptions about the conditions of contact, but these assumptions are not always valid and can cause significant sensing errors. Here we introduce a new whisker sensing system with a tapered, flexible whisker. The system provides inputs to two separate algorithms for estimating radial contact distance on a whisker. Using a Gradient-Moment (GM) algorithm, we correctly detect contact distance in most cases (within 4% of the whisker length). We introduce the Z-Dissimilarity score as a new metric that quantifies uncertainty in the radial contact distance estimate using both the GM algorithm and a Moment-Force (MF) algorithm that exploits the tapered whisker design. Combining the two algorithms ultimately results in contact distance estimates more robust than either algorithm alone.**

Files Available-
1. Code implementation of the tracking algorithm which converts a test video into a csv file of the motion of tracked points
2. Code to preform analysis on the components of the sensor including
    * Output of predicted whisker bending from the quasistatic simulator developed at northwestern university in the Sense Lab
    * Analysis on the sensitivity of acrylic cut springs to forces produced by whisker bending

_Kent, T. A., Emnett, H., Babaei, M., Hartmann, M. J., & Bergbreiter, S. (2023). Identifying Contact Distance Uncertainty in Whisker Sensing with Tapered, Flexible Whiskers. International Conference on Robotics and Automation_


# Whisksight: A reconfigurable, vision-based, optical whisker sensing array for simultaneous contact, airflow, and inertia stimulus detection
### Teresa A Kent , Suhan Kim , Gabriel Kornilowicz , Wenzhen Yuan, Mitra J. Z. Hartmann, and Sarah Bergbreiter

**Abstract—The development of whisker-based sensing systems faces at least two important technical challenges: scaling up the number of whiskers to large arrays while retaining a simple interface; and detecting the wide variety of stimuli that biological whiskers can sense, including both direct touch (contact) and airflow. Here we present the design for a whisker array that leverages a camera to measure whisker rotations without a complex interface. Whiskers are magnetically attached to an elastomer “skin,” ensuring that the system is both scalable and reconfigurable. Direct contact is measured fromthe relative motion between each whisker and the skin, while airflow and inertia can be inferred from the signal experienced by allwhiskers in the array. Individual whiskers can resolve the direction of contact transverse to the whisker within 6.2◦ and whisker rotation magnitude to within 0.5◦. An algorithm is developed to distinguish inertial forces from airflow and contact.**

Files Available-
1. Code which converts recorded video from the sensor into labeled stimuli types, csv files with analyzed data, and helper videos
2. One video which was analyzed during testing
3. Helper function for creating the video outputs

_Kent, T. A., Kim, S., Kornilowicz, G., Yuan, W., Hartmann, M. J., & Bergbreiter, S. (2021). Whisksight: A reconfigurable, vision-based, optical whisker sensing array for simultaneous contact, airflow, and inertia stimulus detection. IEEE Robotics and Automation Letters, 6(2), 3357-3364_
