[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15264948&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
Software engineering is the discipline concerned with applying engineering principles to the design, development, testing, and maintenance of software systems. 

What is software engineering, and how does it differ from traditional programming?
Software engineering is a systematic approach to the development, maintenance, and evolution of software systems, while traditional programming typically refers to the act of writing code to solve specific problems or implement functionalities within a software application.

Software Development Life Cycle (SDLC):
The Software Development Life Cycle (SDLC) is a structured process used by software engineers and developers to design, develop, test, deploy, and maintain software systems. It consists of several phases, each with its own set of activities and deliverables. 

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

Requirements Gathering and Analysis:

In this phase, project stakeholders collaborate to gather and document the software requirements. This involves understanding the needs of users, defining functional and non-functional requirements, and identifying constraints and risks.

System Design:

During this phase, the system architecture and design are developed based on the gathered requirements. This includes defining the overall structure of the software system, specifying components, interfaces, and data flows, and creating detailed design documentation.

Implementation (Coding):

In this phase, developers write code based on the design specifications. Programming languages, frameworks, and tools are used to implement the software solution according to the defined requirements. Code quality and adherence to coding standards are important considerations during this phase.

Testing:

The testing phase involves verifying and validating the software to ensure that it meets the specified requirements and quality standards. Testing activities may include unit testing, integration testing, system testing, and acceptance testing. Defects are identified, reported, and fixed during this phase.

Deployment:

Once the software has been thoroughly tested and approved, it is deployed to the production environment. This involves installing the software on the target systems, configuring it as necessary, and ensuring that it operates correctly in the production environment.

Maintenance and Support:

The maintenance phase involves ongoing support and enhancements to the software after it has been deployed. This includes fixing defects, addressing user feedback, implementing new features, and making updates to accommodate changes in the environment or requirements.

Agile vs. Waterfall Models:
Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Waterfall model follows a linear, sequential approach with a focus on upfront planning and documentation while the Agile model emphasizes flexibility, collaboration, and iterative development to deliver value to customers quickly and adapt to changing requirements. 
Waterfall Model:

Sequential Approach: The Waterfall model follows a sequential, linear process where each phase must be completed before moving to the next. The phases typically include requirements gathering, design, implementation, testing, deployment, and maintenance.

Emphasis on Planning and Documentation: It requires extensive upfront planning and documentation, with detailed specifications and design documents created before implementation begins.

Rigid and Predictable: The Waterfall model is characterized by its rigidity and predictability. Once a phase is completed, it's challenging to make changes without impacting subsequent phases, making it less adaptable to changing requirements or feedback.

Suitable for Well-defined Projects: It is well-suited for projects with clearly defined requirements and stable technology, where the scope and objectives are unlikely to change significantly throughout the development process.

Agile Model:

Iterative and Incremental: The Agile model emphasizes iterative and incremental development, with small, manageable increments of functionality delivered in short time frames called sprints. It allows for flexibility and adaptation to changing requirements and priorities.

Collaboration and Communication: Agile places a strong emphasis on collaboration and communication among cross-functional teams, including developers, testers, and stakeholders. Continuous feedback and collaboration are essential to the Agile process.

Adaptability: Agile is highly adaptable, allowing for changes to be incorporated at any stage of development. It embraces uncertainty and welcomes changes in requirements, making it well-suited for projects with evolving or unclear requirements.

Focus on Customer Value: Agile prioritizes delivering value to the customer early and frequently, ensuring that the most valuable features are developed first and can be iteratively refined based on feedback.


Requirements Engineering:

What is requirements engineering? 
Requirements engineering is the process of eliciting, analyzing, documenting, and managing the requirements for a software system. It involves understanding the needs and expectations of stakeholders, translating them into well-defined requirements, and ensuring that those requirements are effectively communicated and managed throughout the software development lifecycle.

Describe the process and its importance in the software development lifecycle.
Elicitation: Gathering requirements from stakeholders, including users, customers, business analysts, and other relevant parties. This involves techniques such as interviews, workshops, surveys, and observation to identify and understand the needs and expectations of stakeholders.

Analysis: Analyzing and prioritizing requirements to ensure they are clear, complete, consistent, and feasible. This step involves refining requirements, resolving conflicts, and identifying dependencies or constraints.

Documentation: Documenting requirements in a structured format to capture the desired functionality, performance, and constraints of the software system. Common artifacts include requirements documents, user stories, use cases, and requirement specifications.

Validation: Validating requirements to ensure they accurately reflect the needs of stakeholders and can be implemented effectively. This may involve techniques such as reviews, walkthroughs, prototyping, and simulations to verify that requirements meet quality criteria and address stakeholders' concerns.

Management: Managing requirements throughout the software development lifecycle, including tracking changes, maintaining traceability between requirements and other project artifacts, and addressing scope creep or requirement volatility. Requirements management tools and techniques are used to ensure that requirements remain up-to-date and aligned with project goals.

Requirements engineering is crucial in the software development lifecycle for several reasons:

Alignment with Stakeholder Needs: It ensures that the software system meets the needs and expectations of stakeholders, including users, customers, and business owners, by capturing their requirements accurately.

Risk Mitigation: Properly defined and managed requirements help mitigate project risks by identifying potential issues, conflicts, and ambiguities early in the development process.

Cost and Time Savings: Clear, well-defined requirements reduce rework, delays, and costly changes later in the development lifecycle by providing a solid foundation for design, development, and testing activities.

Quality Assurance: Effective requirements engineering contributes to the overall quality of the software system by providing a basis for validation and verification activities, ensuring that the delivered product meets specified requirements and quality standards.

Software Design Principles:
Software design principles are fundamental guidelines and best practices that help software engineers create modular, maintainable, and scalable software systems. These principles guide the process of designing software architecture, components, and modules to achieve qualities such as flexibility, reusability, and extensibility. 


Explain the concept of modularity in software design.
Modularity in software design refers to the practice of breaking down a software system into smaller, self-contained, and interchangeable modules or components, each responsible for a specific set of functionalities or concerns. These modules encapsulate related code, data, and behavior, allowing developers to design, implement, test, and maintain software systems more effectively.

 How does it improve maintainability and scalability of software systems?
Encapsulation: Modules encapsulate their internal implementation details, exposing only well-defined interfaces or APIs to other modules. This encapsulation hides the complexity of the module's internal workings, promoting information hiding and reducing dependencies between modules.

Separation of Concerns: Modularity allows developers to separate different concerns or aspects of functionality into distinct modules. Each module can focus on a specific area of functionality, such as user interface, business logic, data access, or communication, making the system easier to understand, maintain, and extend.

Reusability: Modular design promotes code reusability by allowing developers to reuse existing modules in different parts of the software system or in other projects. Well-designed modules with clear interfaces can be easily integrated into new contexts without modifying their internal implementation, saving time and effort.

Scalability: Modular architectures can scale more effectively as the size and complexity of the software system grow. Developers can add, remove, or replace modules as needed, without affecting the rest of the system. This scalability facilitates incremental development, enabling teams to work on different modules concurrently and integrate them seamlessly.

Testability: Modular design improves the testability of software systems by isolating components for testing. Each module can be tested independently, using automated unit tests or integration tests, to verify its correctness and behavior. This isolation reduces the scope of testing and makes it easier to identify and fix defects.

Flexibility and Maintainability: Modularity enhances the flexibility and maintainability of software systems by reducing coupling between modules. Changes to one module are less likely to affect other modules, allowing developers to make modifications, enhancements, or bug fixes with minimal impact on the rest of the system. Additionally, modular architectures facilitate refactoring and evolution of the software over time.

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). 
Unit Testing:

Unit testing involves testing individual units or components of the software in isolation. A unit is the smallest testable part of the software, typically a function, method, or class. Unit tests verify that each unit behaves as expected and meets its specifications. Test cases are designed to cover different scenarios, including normal inputs, boundary conditions, and error conditions. Unit testing is usually automated and performed by developers during the coding phase.
Integration Testing:

Integration testing focuses on testing the interactions and interfaces between different units or modules of the software. It verifies that the units work together correctly when integrated into larger components or subsystems. Integration testing can be performed at different levels of granularity, including module-to-module integration, subsystem integration, and end-to-end system integration. Test cases are designed to validate data flow, communication protocols, error handling, and other aspects of integration. Integration testing helps detect interface mismatches, integration bugs, and other issues that may arise when combining units.
System Testing:

System testing evaluates the behavior and functionality of the entire software system as a whole. It verifies that the system meets the specified requirements and performs as expected in its intended environment. System testing covers a wide range of tests, including functional testing, performance testing, usability testing, security testing, and reliability testing. Test cases are designed to simulate real-world usage scenarios and validate the system's compliance with functional and non-functional requirements. System testing is typically performed by dedicated testing teams or quality assurance engineers before the software is released to users.
Acceptance Testing:

Acceptance testing assesses whether the software meets the acceptance criteria and satisfies the needs of the stakeholders, including customers, end-users, and business owners. It validates that the software delivers the expected value and functionality required by the users. Acceptance testing can take various forms, such as user acceptance testing (UAT), alpha testing, beta testing, and operational acceptance testing (OAT). Test cases are based on user stories, use cases, or business requirements and are designed to evaluate the software from the perspective of the end-users or customers. Acceptance testing is typically performed in a production-like environment by users or stakeholders who provide feedback and approval before the software is deployed or released.

Why is testing crucial in software development?
Identifying Defects: Testing helps identify defects, bugs, and errors in the software code and functionality. By systematically running test cases, developers can uncover issues that may arise under different conditions, including edge cases and unexpected inputs. Identifying defects early in the development process reduces the cost and effort of fixing them later.

Ensuring Quality: Testing ensures that the software meets quality standards and performs as expected. Through various types of testing, such as functional testing, performance testing, usability testing, and security testing, developers can validate that the software meets the specified requirements, functions correctly, and delivers the desired value to users.

Validating Requirements: Testing validates that the software meets the requirements specified by stakeholders, including customers, users, and business owners. By comparing the actual behavior of the software against the expected behavior defined in requirements documents, test cases help ensure that the software fulfills its intended purpose and satisfies the needs of its users.

Enhancing Reliability: Testing improves the reliability and stability of the software by identifying and addressing defects and vulnerabilities that could lead to system failures or crashes. Through rigorous testing, developers can verify that the software behaves predictably and consistently under different conditions, reducing the risk of unexpected failures in production environments.

Increasing Customer Satisfaction: Testing helps ensure that the software meets the expectations and requirements of customers and users. By delivering high-quality software that is free of defects and meets user needs, developers can enhance customer satisfaction, build trust, and improve the overall user experience.

Reducing Risks: Testing helps mitigate risks associated with software development, including technical, financial, and reputational risks. By proactively identifying and addressing defects and issues, developers can reduce the likelihood of costly rework, project delays, security breaches, and negative impacts on business operations or brand reputation.

Facilitating Maintenance and Evolution: Testing provides a safety net for making changes to the software over time. By having a comprehensive suite of tests, developers can confidently refactor code, add new features, or make enhancements without introducing regressions or unintended side effects. Testing ensures that modifications to the software do not compromise existing functionality and maintain the overall integrity of the system.

Version Control Systems:

What are version control systems, and why are they important in software development? 
Version control systems (VCS) are tools that help developers manage changes to source code, documents, and other files in a collaborative software development environment. They track modifications made to files over time, facilitate collaboration among team members, and enable the management of multiple versions or branches of a software project.

Version control systems are important in software development for several reasons:

Collaboration: VCS allow multiple developers to work on the same codebase concurrently without interfering with each other's changes. Developers can collaborate on projects more effectively, share code, review changes, and merge contributions seamlessly.

Change Tracking: VCS track changes made to files, recording who made the changes, when they were made, and what changes were made. This enables developers to understand the history of a project, revert to previous versions if needed, and identify the source of bugs or issues.

Backup and Recovery: VCS serve as a backup mechanism for project files, ensuring that changes are safely stored and can be recovered in case of accidental deletion, corruption, or data loss. Developers can restore previous versions of files or entire projects from the VCS repository.

Branching and Merging: VCS support branching and merging, allowing developers to create separate branches of a project to work on new features, bug fixes, or experiments without affecting the main codebase. Branches can be merged back into the main branch once changes are completed and tested.

Auditing and Compliance: VCS provide a record of all changes made to project files, making it easier to audit changes, track contributions, and ensure compliance with regulatory requirements or software development standards.

Continuous Integration and Deployment (CI/CD): VCS integrate with CI/CD pipelines to automate the process of building, testing, and deploying software changes. Automated workflows triggered by changes in the VCS repository enable rapid feedback, faster release cycles, and improved software quality.


Give examples of popular version control systems and their features.
Git:

Distributed version control system (DVCS) known for its speed, scalability, and flexibility.
Supports branching, merging, and distributed workflows.
Offers lightweight branching, local commits, and offline access.
Popular hosting platforms include GitHub, GitLab, and Bitbucket.

Software Project Management:

Discuss the role of a software project manager. 
The role of a software project manager is critical in overseeing the planning, execution, and delivery of software projects, ensuring that they are completed on time, within budget, and according to quality standards. Project managers play a key role in coordinating various stakeholders, managing resources, mitigating risks, and ensuring that project objectives are met.

What are some key responsibilities and challenges faced in managing software projects?
Key Responsibilities:

Project Planning and Scheduling:

Developing project plans, defining project scope, objectives, and deliverables.
Creating project schedules, timelines, and milestones to guide project execution.
Estimating resources, budget, and effort required for project completion.
Stakeholder Management:

Communicating with stakeholders, including clients, sponsors, team members, and other project stakeholders.
Managing expectations, addressing concerns, and facilitating collaboration among stakeholders.
Providing regular project updates, progress reports, and status meetings to keep stakeholders informed.
Resource Allocation and Management:

Identifying and allocating resources, including personnel, equipment, and budget, to support project activities.
Managing resource availability, workload, and conflicts to ensure efficient utilization of resources.
Monitoring and tracking resource usage, costs, and productivity throughout the project lifecycle.
Risk Management:

Identifying potential risks, issues, and uncertainties that may impact project success.
Assessing the likelihood and impact of risks and developing strategies to mitigate or respond to them.
Monitoring and controlling risks throughout the project lifecycle, implementing risk mitigation measures as needed.
Quality Assurance:

Establishing quality standards, metrics, and processes to ensure that project deliverables meet quality requirements.
Conducting quality reviews, inspections, and testing to verify compliance with quality standards.
Implementing corrective actions and continuous improvement initiatives to address quality issues and enhance project outcomes.
Change Management:

Managing changes to project scope, requirements, and deliverables throughout the project lifecycle.
Assessing the impact of changes on project objectives, schedule, and budget.
Implementing change control processes to evaluate, approve, and track changes effectively.
Team Leadership and Motivation:

Providing leadership, direction, and support to project team members.
Fostering a positive team environment, promoting collaboration, and motivating team members to achieve project goals.
Resolving conflicts, addressing team dynamics, and promoting professional development and growth.

Challenges:

Scope Creep: Changes in project scope, requirements, or priorities during the development process can lead to scope creep, where the project expands beyond its original boundaries. Managing scope changes while maintaining project objectives, timelines, and resources can be challenging.

Resource Constraints: Limited availability of skilled personnel, equipment, or budget can pose challenges in resource allocation and management. Balancing resource constraints with project requirements and objectives is essential to ensure project success within budget and schedule constraints.

Schedule Management: Managing project schedules, milestones, and dependencies to ensure timely delivery can be challenging, especially in complex projects with multiple stakeholders and dependencies. Unexpected delays, changes, or disruptions can impact project timelines and require proactive schedule management.

Risk Management: Identifying, assessing, and mitigating risks that may impact project success, including technical challenges, dependencies, and external factors, requires proactive risk management strategies and contingency planning.

Quality Assurance: Ensuring that project deliverables meet quality standards and customer expectations while managing time and resource constraints is a common challenge in software projects. Implementing effective quality assurance processes, testing strategies, and quality control measures is essential to address quality challenges.

Communication: Effective communication among project stakeholders, team members, and external partners is critical for project success. Miscommunication, misunderstandings, or lack of communication can lead to delays, conflicts, and project failures. Establishing clear communication channels, feedback mechanisms, and collaboration tools is essential to address communication challenges.

Technical Complexity: Dealing with technical complexities, such as integration issues, scalability challenges, performance bottlenecks, or evolving technologies, can pose challenges in software projects. Addressing technical challenges requires a deep understanding of the underlying technologies, effective problem-solving skills, and collaboration among technical teams.

Change Management: Managing changes to project scope, requirements, or priorities while maintaining project objectives, timelines, and resources is a common challenge in software projects. Implementing effective change control processes, evaluating the impact of changes, and communicating changes to stakeholders are essential to address change management challenges.

Team Dynamics: Addressing team dynamics, conflicts, and motivation to maintain a positive and productive work environment is crucial for project success. Building a cohesive team, fostering open communication, and providing leadership and support to team members are essential to address team dynamics challenges.

Client Expectations: Managing client expectations, requirements, and feedback to ensure customer satisfaction and project success can be challenging. Understanding client needs, setting realistic expectations, and managing communication and feedback effectively are essential to address client expectations challenges.



Software Maintenance:

Define software maintenance and explain the different types of maintenance activities.

Software maintenance refers to the process of modifying, updating, enhancing, and optimizing software systems after they have been deployed or released. It involves making changes to software to address defects, accommodate new requirements, improve performance, ensure compatibility with evolving technologies, and enhance user experience. 

 Why is maintenance an essential part of the software lifecycle?
Software maintenance is essential for keeping software systems functional, reliable, and aligned with the needs of users and stakeholders over time.

Maintenance is an essential part of the software lifecycle for several reasons:

Addressing Defects and Issues: Software maintenance allows developers to identify, diagnose, and fix defects, errors, and issues that may arise after the software has been deployed or released. By addressing these issues promptly, maintenance ensures that the software remains functional, reliable, and error-free for users.

Adapting to Changing Requirements: Maintenance enables software systems to adapt to changing user needs, business requirements, and technological advancements over time. By modifying, updating, or enhancing the software, maintenance ensures that it remains relevant, competitive, and aligned with the evolving needs of users and stakeholders.

Improving Performance and Efficiency: Maintenance activities such as optimization, tuning, and performance enhancements can improve the performance, efficiency, and scalability of software systems. By optimizing algorithms, streamlining processes, and addressing performance bottlenecks, maintenance helps maximize the performance and usability of the software.

Enhancing Security and Compliance: Maintenance includes implementing security patches, updates, and fixes to address vulnerabilities, security threats, and compliance requirements. By staying vigilant against security risks and ensuring compliance with industry standards and regulations, maintenance helps protect the integrity, confidentiality, and availability of software systems.

Extending Lifespan and Value: Maintenance extends the lifespan and value of software systems by ensuring their continued functionality, relevance, and usefulness over time. By investing in maintenance activities, organizations can prolong the lifespan of software systems, delay obsolescence, and maximize the return on investment in software development.

Sustaining User Satisfaction: Maintenance plays a crucial role in sustaining user satisfaction and loyalty by addressing user feedback, requests, and issues in a timely manner. By listening to users, incorporating their feedback, and continuously improving the software, maintenance helps build trust, confidence, and loyalty among users.

Supporting Business Continuity: Maintenance ensures business continuity and operational stability by addressing critical issues, emergencies, and disruptions that may impact the availability or functionality of software systems. By responding promptly to emergencies, performing routine maintenance checks, and implementing preventive measures, maintenance helps minimize downtime and maintain business operations.

There are several types of maintenance activities that can be performed on software systems:

Corrective Maintenance:

Corrective maintenance involves fixing defects, errors, or malfunctions discovered in the software after it has been deployed. This includes identifying and diagnosing problems, analyzing root causes, and implementing fixes or patches to resolve issues and restore the software to its intended functionality.

Adaptive Maintenance:

Adaptive maintenance involves modifying software to accommodate changes in the operating environment, such as hardware upgrades, operating system updates, or changes in regulatory requirements. This may involve making adjustments to the software configuration, settings, or interfaces to ensure compatibility and optimal performance in the updated environment.

Perfective Maintenance:

Perfective maintenance involves improving or enhancing existing software to add new features, functionalities, or capabilities requested by users or stakeholders. This may include implementing new features, optimizing performance, enhancing usability, or improving the overall user experience to meet evolving needs and expectations.

Preventive Maintenance:

Preventive maintenance involves proactively identifying and addressing potential issues or risks in the software to prevent future problems or failures. This may include refactoring code, optimizing algorithms, updating documentation, or performing regular system checks and maintenance tasks to keep the software running smoothly and prevent future problems.

Emergency Maintenance:

Emergency maintenance involves addressing critical issues or urgent problems that require immediate attention to prevent significant disruptions or downtime. This may include responding to system crashes, security breaches, data loss incidents, or other emergencies that pose a risk to the integrity or availability of the software system.

Routine Maintenance:

Routine maintenance involves performing regular, ongoing tasks to ensure the health, stability, and performance of the software system. This may include performing backups, applying software updates and patches, monitoring system performance, and conducting regular maintenance checks to identify and address potential issues before they escalate.


Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

Privacy and Data Protection: Software engineers may encounter ethical dilemmas related to the collection, storage, and use of personal data. They must ensure that software systems handle sensitive information ethically and responsibly, respecting user privacy and data protection laws.

Security Vulnerabilities: Software engineers may face ethical challenges related to cybersecurity, including the discovery and disclosure of security vulnerabilities in software systems. They must balance the need to protect users and systems against potential threats with the responsibility to disclose vulnerabilities responsibly and mitigate risks.

Bias and Fairness: Software engineers may confront ethical issues related to bias and fairness in algorithmic decision-making systems. They must consider the potential impact of their design choices on different user groups and ensure that software systems are fair, unbiased, and inclusive.

Intellectual Property: Software engineers may encounter ethical dilemmas related to intellectual property rights, including copyright infringement, patent disputes, and licensing issues. They must respect intellectual property laws and ethical principles when developing and using software components and libraries.

Environmental Impact: Software engineers may face ethical challenges related to the environmental impact of software systems, including energy consumption, carbon emissions, and electronic waste. They must consider the environmental consequences of their design choices and strive to develop sustainable and eco-friendly software solutions.

Social Responsibility: Software engineers may confront ethical issues related to the social impact of technology, including job displacement, inequality, and societal harm. They must consider the broader implications of their work and advocate for ethical and socially responsible use of technology to address societal challenges and promote positive social change.

To ensure they adhere to ethical standards in their work, software engineers can take several proactive measures:

Education and Training: Stay informed about ethical principles, laws, regulations, and best practices relevant to software engineering. Participate in ethics training programs, workshops, and seminars to enhance ethical awareness and decision-making skills.

Ethical Guidelines and Codes of Conduct: Adhere to ethical guidelines and codes of conduct established by professional organizations, such as the ACM Code of Ethics and Professional Conduct or the IEEE Code of Ethics. Use these guidelines as a framework for ethical decision-making and behavior.

Ethical Risk Assessment: Conduct ethical risk assessments to identify potential ethical issues and risks associated with software projects. Consider the potential impact of design choices, algorithmic decisions, and system behaviors on users, stakeholders, and society.

Ethical Design and Development Practices: Incorporate ethical considerations into the design, development, and testing phases of software projects. Consider the ethical implications of design choices, data collection practices, user interfaces, and system behaviors, and strive to design software systems that uphold ethical principles and values.

Transparency and Accountability: Be transparent about ethical considerations, risks, and limitations associated with software systems. Communicate openly with stakeholders about ethical dilemmas, trade-offs, and decisions, and take responsibility for the ethical implications of your work.

Continuous Reflection and Improvement: Engage in continuous reflection and self-assessment to evaluate the ethical implications of your work and identify opportunities for improvement. Seek feedback from colleagues, mentors, and stakeholders, and be open to learning from ethical challenges and mistakes.


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
