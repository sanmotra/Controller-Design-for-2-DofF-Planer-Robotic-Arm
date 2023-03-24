# Controller-Design-for-2-DofF-Planer-Robotic-Arm
Welcome to my Github profile! I'm excited to share with you my work on controller design for 2-degree of freedom (2dof) robotic arm
<h1>Introduction to 2DOF Robotic Arm Mathematical Model</h1>
<p>The 2DOF robotic arm mathematical model is the backbone of this project. The dynamic model will be used to create a controller for the robotic arm, which is the highlight of this project. In this introductory section, we will take a closer look at the different elements of the mathematical model and explain them in detail.</p>
<h2>2DOF Robotic Arm Elements</h2>
<p>The 2DOF robotic arm mathematical model consists of the following elements:</p>
<ul>
  <li><strong>θ<sub>1</sub> and θ<sub>2</sub>:</strong> The angular position of each arm of the robot</li>
  <li><strong>l<sub>1</sub> and l<sub>2</sub>:</strong> The link lengths</li>
  <li><strong>l<sub>c1</sub> and l<sub>c2</sub>:</strong> The distance from the previous joint to the center of mass of the arm. If the arm were not as symmetrical as in this example, the center of mass would require more than one distance to know where it is geometrically.</li>
</ul>
<p>Additionally, the following matrix represents the inertias of the arm regarding the fixed frame respect to the body (in the previous graph this frame is B<sub>1</sub> = {x<sub>1</sub>, y<sub>1</sub>, z<sub>1</sub>}). This matrix is symmetric:</p>
<img src="https://i.imgur.com/wqlZTW6.png" alt="Inertia Matrix">
<p>If the object has a very peculiar shape (like a cylinder), there are deterministic formulas to calculate the inertia tensor. However, in most real cases, the inertia tensor must be calculated using CAD software, where the physical properties must be placed on the arm before calculating the inertia tensor.</p>
<h2>Equations of the Robotic Arm</h2>
<p>The dynamic model of the 2DOF robotic arm can be represented using the following equations:</p>
<p>Equation 1:</p>
<img src="https://i.imgur.com/J5b5I7w.png" alt="Equation 1">
<p>Equation 2:</p>
<img src="https://i.imgur.com/HQ2V8wz.png" alt="Equation 2">
<p>Note that in this course we will not delve into how to obtain the dynamic model of these robots, but there are many methods for this.</p>
