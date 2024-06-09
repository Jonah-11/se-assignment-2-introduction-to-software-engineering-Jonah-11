[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15237687&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
Software engineering is a type of engineering involving designing, development and testing of software systems

What is software engineering, and how does it differ from traditional programming?
Software engineering is a type of engineering involving designing, development and testing of software systems. It differs from traditional programming as it involves broader aspects and the life cycle of software development from generation to functionality whereas traditional programming deals with the sole task of writing code for a specific task.

Software Development Life Cycle (SDLC): It is a process used in designing, developing, testing and deploying software applications.

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Phase 1: Initiation. Aims and objectives are given. Research is done during this stage.
Phase 2: Planning. A working plan is drawn where the budget and schedule are drawn.
Phase 3: Execution. Here the work is distributed among members and mode of communication discussed.
Phase 4: Monitoring and Controlling. The progress of development is assesses and changes are made if needed.
Phase 5: Closure. All project activities are finalized and a working sheet documented.

Agile vs. Waterfall Models:Agile model uses an iterative and incremental approach to project management and software development.
waterfall model follows a linear, sequential approach where each phase must be completed before moving on to the next.

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Waterfall model follows a sequence step by step in generating the software while agile builds on a completed project as it improves on the previously developed software.

Requirements Engineering: It is a phase in the software development process that focuses on defining, documenting and maintaining the requirements for a software system.

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Process 1: Gather requirements from customers. Conduct interviews and workshops. 
process 2: The gathered requirements are analyzed and refined to ensure they are complete and consistent. Case modelling, data flow diagrams are used.
Process 3: The requirements are documented in a clearly structured manner. 
Process 4: The documented requirements are validated to ensure that they accurately align with the customer's needs.
Process 5: The requirements are then managed and maintained throughout the project's lifecycle.

Software Design Principles: They are fundamental concepts that guide software developers in creating clean, maintainable and efficient software systems.

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Modularity in software design refers to the design principle of dividing a software system into distinct, self-contained units or modules, each responsible for a specific part of the system's functionality. 
It improves maintainability and scalability of software systems in the following ways:
1. Each module is independent and thus it is easier to debug and test individual modules.
2. Updates are simplified as the change in one module can be made without affecting another module.
3. The code syntax is organized since modularity enforces a clear separation.
4. Different modules can be worked on by different developers making the task easier and be completed faster due to teamwork being possible.
5. Different modules can be scaled independently based on their usage patterns, optimizing resource allocation.

Testing in Software Engineering:  It is verifying and validating that the software meets its requirements and is free of defects and errors.

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?  Testing is essential for ensuring that each module and the overall system function correctly, meeting quality standards and user expectations.
1. Unit testing: It focuses  on individual components of the software ensuring the unit performs as it should.
2. Integration testing: It tests the interaction between integrated modules thus identifying the issues in their interaction.
3. System testing: It involves the testing of the whole integrated system to ensure it meets the specified requirements.
4. Acceptance testing: Validates the software against user requirements and checks if it meets the acceptance criteria.

Version Control Systems: They are tools that help manage changes to source code and other project files over time.

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
They are important in the following ways:
1. It facilitates collaboration between developers by allowing them to work on the same project simultaneously without overwritng other"s work.
2. It provides an audit trail for accountability and traceability giving a complete history of changes made to the project.
3. It also acts as a backup by storing copies of every version of the project helping to recover lost work.
4. It allows merging and combining of changes from different branches into the main project.
5. It provides tools for detecting and resolving conflicts when multiple changes affect the same part of the code.

Examples of popular version control systems and their features include:
1. Git. It has distributed VCS where each developer has a complete copy of the repository allowing for offline work and redundacy. It also supports barnching and merging enabling efficient workflows. It is also designed for speed and efficiency.
2. Subversion. It has a centralised VCS where a single central repository syncs all developers. Has atomic commits that ensures thet the commits are all or nothing preventing partial updates. It  also tracks changes to directories and not just files.
3. Mercurial. It has a distributed VCS similar to Git where each developer has a complete copy of the repository. It is also designed to be easy to learn and use with a consistent command set. It is efficient when handling large projects and repositories.
4. Perforce helix core. Has a centralised VCS designed for large-scale enterprise environments with a focus on performance. Has file locking that prevents conflicts by allowing exclusive file checkouts.Has comprehensive security features including access controls and auditing.


Software Project Management: It involves planning, executing, monitoring and controlling software development projects to meet specific objectives, such as delivering software on time, working within budget and to the desired quality standards.

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

A software project manager is responsible for planning, executing, and overseeing software development projects ensuring that the project meets its objectives, stays within budget, and is delivered on time while maintaining the desired level of quality. He/she acts as a bridge between the development team and other stakeholders, coordinating efforts and managing resources to achieve project goals.

Key Responsibilities of a Software Project Manager:
1. Project Planning and Scheduling.
2. Resource Management and allocation.
3. Budget and risk Management.
4. Quality Assurance.
5. Performance Monitoring.
6. Project Closure.

Challenges faced in managing software projects include:
1. Scope Creep where there are uncontrolled changes or continuous growth in project scope.
2. Limited availability of skilled personnel, tools or budget.
3. Communication Barriers.
4. Delivering the project on time while maintaining quality standards.
5. Balancing the needs and expectations of various stakeholders.
6. Keeping up with rapid technological advancements and integrating new technologies.

Software Maintenance: It is the process of modifying and updating software applications after delivery to correct faults, improve performance or adapt the software to a changed environment.

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle? Software maintenance is an essential part of the software lifecycle, essential for ensuring the longevity, reliability, and effectiveness of software applications thus organizations can keep their software up-to-date, secure and in alignment with user needs and environmental changes. This ongoing process is vital for maintaining the value and functionality of software in a rapidly evolving technological landscape.

Types of Software Maintenance Activities include:
1. Corrective Maintenance which involves identifying and fixing defects or bugs in the software that are discovered after its release. An example is fixing a crash that occurs under specific conditions.
2. Adaptive Maintenance which involves modifying the software to keep it usable within a changing environment, such as adapting to new hardware, operating systems, or regulatory requirements. An example is updating an application to work with the latest version of a web browser.
3. Perfective Maintenance which involves enhancing and improving the software to increase its performance, maintainability, or other attributes. An example is optimizing an algorithm to reduce processing time.
4. Preventive Maintenance which involves making changes to prevent future problems and improve the software's reliability and maintainability. An example is refactoring legacy code to improve readability and prevent future errors.

Ethical Considerations in Software Engineering: They are the responsibilities and moral duties of software engineers to ensure their work adheres to societal, legal and professional standards.

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
Some ethical issues that software engineers might face include:
1. Privacy Concerns where collecting and handling user data raises ethical questions about privacy, consent and data security.
2. Algorithms used in software systems may inadvertently perpetuate biases present in training data leading to unfair outcomes.
3. Failing to address security vulnerabilities in software can have ethical implications, as it puts users' data and privacy at risk.
4. Software development and operation can have environmental consequences, such as energy consumption and electronic waste.

Software engineers can ensure that they adhere to ethical standards in their work by: 
1. Adhering to professional codes of conduct and ethical guidelines provided by organizations like the ACM and the IEEE.
2. Participating in ethical review processes within organizations to evaluate the potential ethical implications of software projects.
3. Involving stakeholders in the development process to ensure multiple perspectives are considered and ethical concerns are addressed.
4. Using ethical decision-making frameworks to evaluate the ethical implications of design choices and software features.

References
1. https://moldstud.com/articles/p-ethical-considerations-in-software-engineering
2. https://www.koombea.com/blog/project-manager-challenges/
3. https://www.sciencedirect.com/topics/computer-science/requirement-engineering


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
