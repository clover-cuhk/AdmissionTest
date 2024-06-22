# AdmissionTest
Clover Lab Admission Test: Dynamic Control of a Double Pendulum for Linear Motion Along the Negative X-Axis

**Problem Description:**

Consider a double pendulum system in a two-dimensional plane, modeled within the MuJoCo physics simulation environment. The system comprises two rigid links, each of 1 meter in length, connected serially. One end of the first link is fixed to a pivot point, while a 1kg point mass (representing a small ball) is attached to the free end of the second link. Two motors, denoted as Motor M1 and Motor M2, are installed at the joints: M1 between the fixed pivot and the first link, and M2 between the first and second links.

The initial condition sets both links horizontally aligned with the ground. Under the influence of gravity, the system is allowed to move freely within the plane without any restrictions other than the ones imposed by your control strategy. Neglect the masses of the links and all frictional forces, focusing solely on the 1kg point mass.

Your task is to devise a real-time control algorithm to compute the torques (\( \tau_{M1} \) for Motor M1 and \( \tau_{M2} \) for Motor M2) necessary to guide the 1kg ball along a straight path in the negative X-axis direction, while minimizing its vertical displacement from the initial Y position. The speed of the ball along the X-axis can vary over time but must remain directed negatively.

**Deliverables:**

1. **Mathematical Formulation:** Derive the equations of motion for the double pendulum system under the given constraints, expressing the relationship between the required motor torques (\( \tau_{M1}, \tau_{M2} \)) and the system's state variables (angles and angular velocities of the links).

2. **Control Strategy:** Propose a control strategy that outlines how to compute \( \tau_{M1} \) and \( \tau_{M2} \) at every time step, ensuring the described linear motion of the ball. Discuss the rationale behind your chosen approach, considering factors such as stability, efficiency, and practical implementation within the MuJoCo framework.

3. **Simulation Implementation:** Implement your control algorithm within the MuJoCo simulation environment. Demonstrate successful guidance of the ball along the negative X-axis with minimal vertical deviation. Provide visualizations and quantitative analyses (e.g., trajectories, torque profiles) to validate your solution.

4. **Analysis & Optimization:** Evaluate the performance of your control scheme in terms of the objectives: maintaining a linear trajectory along the X-axis and minimizing Y-axis displacement. Discuss potential improvements or adjustments to enhance the system's precision and efficiency.

**Submission Requirements:**

Submit a detailed report outlining your mathematical formulation, control strategy, simulation results, and analysis. Include relevant code snippets, simulation visuals, and any additional supporting documentation that illustrates your understanding and successful execution of the task.
