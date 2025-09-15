# RoboJuggler: Learning Dexterous Juggling through Reinforcement Learning

Humans regularly learn and perform complex and nuanced motor skills, such as walking, playing sports, or manipulating objects with dexterity, that remain challenging benchmarks for even state-of-the-art robotic systems. Among these tasks, juggling represents a particularly compelling benchmark because it requires precise timing, coordinated manipulation, and dynamic control. Although robotic juggling has been demonstrated previously, most methods exist within simplified 2D simulators, using pre-programmed skills or expert demonstrations, use non-dexterous end-effectors, or rely on binary-reward or open-loop policies that limit adaptability and realism.

In this project, we leverage GPU-parallelized reinforcement learning in Isaac Gym to teach a robot hand-arm system with a human-like Allegro gripper to juggle objects—a task not commonly addressed in existing literature. We attempted juggling with up to three balls and achieved solid two-ball juggling performance, demonstrating sustained catches and throws. To support this, we designed a custom simulation environment with carefully crafted reward and state frameworks to scale and stabilize PPO, using domain-specific insights to iterate on control behavior, curriculum design, and reward sparsity. The result is a high-performing policy capable of executing multi-ball juggling in a physically realistic environment. This work demonstrates the feasibility of complex dexterous behaviors using standard RL algorithms, provided that environment engineering and parallel simulation are properly leveraged.

Final Report is in the repo as a [pdf](Robojuggler_Final_Report.pdf).



https://github.com/user-attachments/assets/0fe62941-21c3-473a-bd49-c808364fd6d2

