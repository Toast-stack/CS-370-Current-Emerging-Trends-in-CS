# CS-370: Current and Emerging Trends in Computer Science

## Course Overview

This repository contains assignments and projects completed for Southern New Hampshire University's CS-370 course, "Current and Emerging Trends in Computer Science." The course focuses on advanced topics in computer science, emphasizing artificial intelligence (AI) and machine learning (ML). Key competencies developed include:

- **Artificial Intelligence Concepts**: Understanding the fundamental principles and techniques of AI and intelligent systems.
- **Algorithm Analysis**: Applying AI algorithms to solve complex problems effectively.
- **Emerging Technologies Evaluation**: Assessing the societal impacts of current trends and emerging technologies in computer science.

## Projects

### Project One: Neural Networks and Personalization

**Objective**:  
This project explores the fundamentals of neural networks, their role in personalization, ethical concerns, and the impact of GDPR on data usage.

**Understanding Neural Networks**  
Neural networks consist of three key layers:

- **Input Layer**: Receives raw data.
- **Hidden Layers**: Process and analyze patterns in the data.
- **Output Layer**: Provides a result based on the processed data.  
  They function similarly to human intuition, making decisions based on learned patterns.

**Personalization Using Neural Networks**  
Neural networks enhance user experience through recommendation systems, like YouTube and TikTok, which analyze user preferences to tailor content. This personalization improves engagement but raises concerns about algorithmic bias and data privacy.

**Ethical Considerations**  
AI systems can unintentionally introduce biases, as seen in cases like Amazon's hiring algorithm. Additionally, platforms like YouTube collect vast user data, often without full transparency. These "black box" systems raise concerns about data privacy, user profiling, and ethical AI implementation.

**GDPR and Data Protection**  
GDPR enforces transparency, purpose limitation, data minimization, and accountability. While it restricts data collection, it also ensures user privacy and prevents unethical data usage. Companies must balance personalization with responsible data handling.

**Compliance and Best Practices**  
To comply with GDPR, companies should:

- Be transparent about data collection.
- Use anonymization and encryption.
- Limit data storage and access.
- Implement federated learning for privacy protection.

**Outcome**:  
While neural networks offer powerful personalization tools, companies must implement ethical AI practices and align with GDPR regulations to ensure user trust and data security.

### Project Two: Human vs. Machine Problem Solving in Pathfinding

**Objective**:  
To compare human and machine approaches to solving mazes and analyze the role of reinforcement learning in AI pathfinding.

**Human vs. Machine Problem Solving**

- **Human Approach**: Humans solve mazes by locating the exit and planning their route with minimal moves. They use intuition and can consider the broader maze layout.
- **Machine (Intelligent Agent) Approach**: Machines rely on trial and error, focusing only on their current position and possible next moves, and learning from rewards or punishments for their actions.

**Comparison Between Approaches**

- **Similarity**: Both start with an initial move that can seem random.
- **Difference**: Humans leverage intuition and future planning, while machines base decisions on current knowledge and exploration-exploitation trade-offs.

**Reinforcement Learning and Pathfinding**

- **Exploration vs. Exploitation**:
  - Exploration involves the agent learning the environment by trial and error.
  - Exploitation uses the learned information to optimize the path.
  - Ideal balance shifts over time: start with high exploration (100%) and gradually move toward more exploitation as the agent learns (e.g., 40% exploration, 60% exploitation in mid-stage, and eventually 20% exploration, 80% exploitation when the path is optimized).

**Deep Q-Learning in Maze Solving**

- Utilizes neural networks to predict Q-values and choose actions.
- The agent evaluates states, receives feedback (rewards or punishments), and iterates until the optimal path is found.
- Combines exploration to gather knowledge and exploitation to find efficient solutions.

**Outcome**:  
The project demonstrated how reinforcement learning enables machines to solve pathfinding problems effectively by balancing exploration and exploitation strategies.

## Connection to Computer Science

Throughout this course, I focused on AI development using reinforcement learning techniques. We also explored Deep Q-learning, as well as AI systems like AlphaGo and AlphaGo Zero, which demonstrate advanced capabilities in self-training beyond merely replicating human behavior. Additionally, we discussed the ethics of AI, highlighting its growing prevalence in various applications, from online chatbots to toys.

### What Do Computer Scientists Do and Why Does It Matter?

Computer scientists develop new technology and software to solve problems. They employ the scientific method—hypothesizing, experimenting, and analyzing—to innovate or optimize existing technologies. Their work is crucial for advancing automation, improving efficiency, and driving innovation across various industries.

### How Do I Approach a Problem as a Computer Scientist?

The most important part of problem-solving is first understanding the actual problem. This involves gathering all relevant information from the client, including their perceived issue, desired outcomes, constraints (such as budget and time), and assessing whether the proposed solution is feasible. Breaking down the problem into manageable components and systematically addressing each part ensures a comprehensive and effective solution.

### What Are My Ethical Responsibilities to the End User and the Organization?

Ethics play a pivotal role in computer science. Key responsibilities include:

- **Honesty**: Being transparent about capabilities, limitations, and potential risks associated with the technology.
- **Non-Maleficence**: Ensuring that the technology does not harm users or society.
- **Consent**: Obtaining informed consent from users, keeping them aware of how their data is used and how the technology operates.
- **Transparency**: Providing clear information about processes and decisions made by AI systems to build trust and accountability.

By adhering to these ethical principles, computer scientists can create technologies that are responsible, fair, and beneficial to society.
