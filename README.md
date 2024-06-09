[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15244541&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

Software Engineering is a discipline that involves the application of principles of computer science and mathematics to design, develop, and maintain software systems.

What is software engineering, and how does it differ from traditional programming?

Software engineering is the systematic application of engineering principles to the design, development, and maintenance of software systems. Software engineering employs a more structured and organized process that includes requirements engineering, design, coding, testing, and maintenance. This approach ensures that the software development process is methodical and scientific, which helps in producing dependable, efficient, and maintainable software. Software engineers are involved in all aspects of the software development lifecycle, including concept, design, coding, testing, and maintenance. They use engineering principles to ensure that the software aligns with customer requirements and integrates well with the overall system infrastructure. The primary goal of software engineering is to create software that is reliable, efficient, and maintainable. This involves using a disciplined approach to manage the complexity of software systems and ensure their long-term viability.
Traditional programming, often referred to as software development, focuses primarily on writing code to create software that meets the requirements. While it may involve some level of planning and testing, it is generally less structured compared to software engineering. Traditional programmers are primarily focused on the implementation phase. They take the software design and bring it to life by writing the necessary code. Their main concern is to ensure that the software functions correctly and meets the specified requirements. Traditional programming aims to produce software that meets the immediate requirements and is free of defects. While reliability and maintainability are important, the focus is more on delivering functional software quickly.


Software Development Life Cycle (SDLC):
Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

The Software Development Life Cycle (SDLC) is a structured process used by software engineers to design, develop, and test high-quality software. 
i)	Planning and Requirement Analysis
This initial phase involves defining the project’s purpose, gathering requirements from stakeholders, and conducting a feasibility study. The goal is to understand what the software needs to achieve and to plan the project accordingly. The tasks undertaken at this stage include Cost-benefit analysis, scheduling, resource estimation, and allocation with an outcome being a software requirement specification document 
ii)	Defining Requirements
In this phase, the team establishes detailed requirements for the software, determining what the application will do once launched, the necessary components, and the resources needed. In this phase, the tasks that are undertaken include gathering input from stakeholders, defining detailed requirements, and resources needed for the project from this phase, the output is clear and detailed requirements that guide the design and development phases 
iii)	Designing Architecture
This phase involves creating a blueprint for the software, outlining its structure and components. It includes system design, user interface design, security considerations, and the selection of development tools. The tasks that are undertaken in this stage include analyzing requirements, identifying the best solutions, and creating prototypes. This stage provides detailed design documents that serve as a guide for the development phase 
iv)	Developing Product
In this phase, developers start programming and building the entire system based on the design specifications. This is where the actual coding happens. This stage has the bulk of the programming tasks that include writing code, following predefined guidelines to ensure code quality, and integrating different components. The output from this stage is functional software that is ready for testing 
v)	Product Testing and Integration
This phase involves evaluating the developed product to ensure it meets the requirements and is free of defects. Different types of testing are conducted to identify and fix bugs. The tasks undertaken in this stage include unit testing, integration testing, system testing, performance testing, and security testing. From this stage, what is gotten is a tested and verified software product that is ready for deployment 
vi)	Deployment and Maintenance
Once testing is complete, the software is deployed to the production environment. This phase also includes ongoing maintenance to fix bugs, update the software, and monitor its performance. This stage involves moving the software to the live environment, addressing any issues that arise, and planning for upgrades based on user feedback. From this stage a fully functional software product that is maintained and updated as needed is obtained.


Agile vs. Waterfall Models:
Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

The Agile model is an iterative approach to software development that emphasizes continuous releases, customer feedback, and adaptability. It allows for ongoing reiteration, with development and testing activities occurring concurrently. It has the following general characteristics
a)	Incremental Testing: Agile emphasizes incremental testing to identify and resolve issues throughout the development process.
b)	Minimal Documentation: Agile relies on minimal documentation, focusing on self-organizing teams and collaboration.
c)	Flexibility: Agile allows changes in project development requirements, promoting adaptability and continuous improvement.
d)	Customer Collaboration: Heavy emphasis on developer-client communication and feedback.
Agile project management is a good fit in cases where the end goal may be unclear or difficult to define when complex systems require frequent feedback loops, or when timelines and budgets are tight. It is also particularly effective for developing software applications since it allows for quick iteration and testing along the way. In the development of mobile applications, the Agile model has been widely used due to the dynamic nature of the mobile app market. Mobile app development often involves evolving requirements, frequent updates, and the need for quick adaptation to user feedback. Agile's iterative approach allows for continuous improvement and the ability to respond to changing market demands.

On the other hand, the waterfall model is a linear and sequential approach to software development, where each phase must be completed before moving on to the next. It treats each phase as distinct and isolated, requiring the completion of one phase before moving on to the next. It has the following general characteristics:
a)	Sequential Phases: Each phase must be completed before the next begins.
b)	Heavy Documentation: Waterfall relies heavily on documenting each step in detail to ensure that all team members are on the same page.
c)	Rigid Structure: Changes are difficult to implement once a phase is complete.
d)	Well-defined requirements: Suited for projects with well-defined requirements and a clear final product.
The waterfall model fits projects with well-defined requirements, clear final products, and limited changes expected during the development process. It is particularly useful for large, complex projects with specific and unchanging requirements. The Waterfall model has been historically used in the development of critical systems such as air traffic control systems. In such projects, the requirements are well-defined, and a structured and sequential approach is essential to ensure that each phase is completed thoroughly before moving on to the next. The Waterfall model provides a systematic and well-documented process, ensuring that the system's design, development, and testing are meticulously planned and executed. In the development of an air traffic control system, where the requirements are highly regulated and safety-critical, the Waterfall model would be preferred. The sequential nature of the Waterfall model aligns with the need for thorough planning, documentation, and rigorous testing at each stage of the system's development.

The two models have the following key differences
a)	Approach to Testing: Agile emphasizes incremental testing to identify and resolve issues throughout the development process, while testing in the waterfall model is usually done at specific milestones, often towards the end of the project.
b)	Documentation: Agile relies on minimal documentation, focusing on self-organizing teams and collaboration, while the waterfall model relies heavily on documenting each step in detail to ensure that all team members are on the same page.
c)	Flexibility: Agile allows changes in project development requirements, whereas changes are difficult to implement once a phase is complete in the waterfall model.
d)	Customer Collaboration: Agile encourages customer collaboration and feedback, while the waterfall model follows a more structured and less interactive approach.
e)	Understanding these differences is crucial for choosing the most suitable approach for a specific project, as it helps in aligning the right methodology with the project's specific needs and goals.


Requirements Engineering:
What is requirements engineering? Describe the process and its importance in the software development lifecycle.

Requirements engineering is the process of eliciting stakeholder needs and desires and developing them into an agreed-upon set of detailed requirements that can serve as a basis for all subsequent development activities. It involves constructing abstract descriptions of the desired structure or behaviour of a system and/or its problem domain. The goal is to develop and maintain sophisticated and descriptive System Requirements Specification documents that guide the software development process. In the software development life cycle, requirements engineering serves the following functions:
a)	Understanding Stakeholder Needs: Requirements engineering is crucial for understanding and documenting the needs and expectations of all stakeholders involved in the software development process. It ensures that the software system meets the needs of all stakeholders, including end users, and aligns with the organization's objectives.
b)	Basis for Development Activities: The detailed requirements developed through requirements engineering serve as the foundation for all subsequent development activities. They provide a clear and structured roadmap for the design, coding, testing, and deployment phases of the software development lifecycle.
c)	Managing Changes and Updates: Effective requirements engineering ensures that any changes or updates to the requirements are properly documented and communicated to all stakeholders. This helps in tracking and controlling changes throughout the software development lifecycle, ensuring that the requirements remain valid and relevant.
d)	Reducing Errors and Delays: By translating imprecise, incomplete needs and wishes of potential users into complete, precise, and formal specifications, requirements engineering plays a crucial role in reducing software errors at the early stages of development. This contributes to the overall success of software development projects.


Software Design Principles:
Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

a)	Modularity in software design refers to the practice of dividing software into separate, independent modules, each responsible for a distinct feature or functionality. It involves breaking down complex systems into smaller, more manageable components that are loosely coupled. These modules can be developed and maintained independently, making the software system easier to understand, navigate, and evolve. In software engineering, it is important for the following reasons:
b)	Improved Maintainability: Modularity enhances the maintainability of software systems. By dividing the system into smaller modules, each with a well-defined responsibility, it becomes easier to locate and fix bugs or make changes without impacting other parts of the system. This isolation of functionality simplifies testing, debugging, and maintenance efforts.
c)	Enhanced Scalability: Modularity contributes to the scalability of software systems. As the system grows, new modules can be added or existing modules can be modified without affecting the entire system. This flexibility allows for the incremental expansion of functionality, making it easier to adapt to changing requirements and accommodate future growth.
d)	Code Reusability: Modularity promotes code reusability. Well-designed modules can be reused in different projects or within the same project, reducing development time and effort. By encapsulating specific functionality within modules, developers can leverage existing modules instead of reinventing the wheel, leading to increased productivity and efficiency.
e)	Readability and Understandability: Modularity improves the readability and understandability of software systems. By breaking down complex systems into smaller, cohesive modules, the code becomes easier to understand and navigate. Each module focuses on a specific functionality, making it easier for developers to comprehend and reason about the system's behaviour.


Testing in Software Engineering:
Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

Different levels of software testing are performed at various stages of the software development process. These levels help in identifying bugs early and ensuring better software quality. The main levels of testing are:
a)	Unit Testing
Unit testing is the first level of testing and focuses on testing individual components or units of code in isolation. It involves testing small, independent units of code, such as functions or methods, to ensure they function correctly. Unit testing is crucial as it helps identify defects in individual units of code early in the development process. It ensures that each unit of code works as intended and can be integrated successfully into the larger system. Unit testing improves code quality, reduces the likelihood of bugs, and facilitates easier debugging and maintenance.
b)	Integration Testing
Integration testing verifies the interaction and communication between different modules or components of the software system. It tests the integration points and ensures that the modules work together as expected. Integration testing is essential for identifying issues that may arise when different modules are combined. It helps detect defects related to data flow, communication, and compatibility between modules. Integration testing ensures that the integrated system functions correctly and that the modules work harmoniously together.
c)	System Testing
System testing evaluates the entire software system as a whole. It tests the system's compliance with functional and non-functional requirements, including performance, reliability, security, and usability. System testing is crucial for assessing the system's behaviour and performance in real-world scenarios. It ensures that the software system meets the specified requirements and performs as expected. System testing helps identify any defects or inconsistencies that may arise when different components interact, providing confidence in the overall system's quality.
d)	Acceptance Testing
Acceptance testing is performed to validate the software system against the business requirements and ensure that it meets the needs of the end-users or stakeholders. It focuses on replicating user behaviour and verifying if the system satisfies the specified criteria. Acceptance testing is crucial for gaining confidence in the software system's readiness for deployment. It ensures that the system meets the expectations of the end-users and aligns with the business requirements. Acceptance testing helps identify any gaps between the system and the desired outcomes, allowing for necessary adjustments before final acceptance.
Testing is crucial in software development for several reasons:
i.	Bug Identification: Testing helps identify defects and bugs in the software system, allowing for their early detection and resolution. This reduces the likelihood of issues reaching end-users and improves the overall quality of the software.
ii.	Quality Assurance: Testing ensures that the software system meets the specified requirements and performs as expected. It helps validate that the system functions correctly, and is reliable, secure, and user-friendly.
iii.	Risk Mitigation: Testing helps mitigate risks associated with software development. By identifying and addressing defects early, testing reduces the chances of costly failures, security breaches, or negative user experiences.
iv.	Customer Satisfaction: Thorough testing ensures that the software system meets the needs and expectations of end-users. It helps build trust, enhances user satisfaction, and increases the likelihood of successful adoption and usage of the software.
v.	Cost and Time Efficiency: Detecting and fixing defects early in the development process is more cost-effective and time-efficient than addressing them later. Testing helps identify issues early, reducing the time and effort required for debugging and maintenance.

Version Control Systems:
What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

Version Control Systems (VCS) are software tools that help developers efficiently manage and track changes made to source code. They provide a systematic approach to recording modifications, keeping a history of changes, and facilitating collaboration among developers working on the same project. Version control systems enable teams to work together, manage code versions, and ensure the integrity and traceability of software development. This is very important in software development for the following reasons:
i.	Collaboration and Teamwork: Version control systems enable multiple developers to work on the same project simultaneously. They provide a centralized repository where developers can access, modify, and merge code changes. VCS allows for seamless collaboration, ensuring that team members can work together efficiently and avoid conflicts.
ii.	Change Tracking and History: VCS keeps a detailed record of every modification made to the codebase. This allows developers to track changes, understand the evolution of the code, and revert to previous versions if needed. Version control systems provide a comprehensive history of the project, making it easier to identify and resolve issues.
iii.	Code Integrity and Safety: VCS ensures the integrity and safety of the codebase. It allows developers to work on their branches or copies of the code, reducing the risk of accidental modifications or conflicts. VCS also provides mechanisms for code review, ensuring that changes are reviewed and approved before being merged into the main codebase.
iv.	Branching and Parallel Development: Version control systems support branching, which enables developers to create separate lines of development. Branches allow for parallel development of new features, bug fixes, or experiments without affecting the stability of the main codebase. Branches can be merged back into the main codebase when ready.
Below are some of the popular version control systems and their features
i.	Git: Git is a distributed version control system known for its speed, flexibility, and scalability. It allows for offline work, branching, merging, and distributed collaboration. Git provides a decentralized repository model, making it popular for open-source projects and large-scale development teams.
ii.	Subversion (SVN): Subversion is a centralized version control system that tracks changes to files and directories over time. It offers features like atomic commits, branching, tagging, and merging. SVN is known for its simplicity and ease of use, making it suitable for smaller projects or teams.
iii.	Mercurial: Mercurial is a distributed version control system that emphasizes ease of use and performance. It offers features like branching, merging, and distributed collaboration. Mercurial is known for its simplicity and intuitive command-line interface.
iv.	Perforce: Perforce is a centralized version control system designed for large-scale projects and teams. It provides features like atomic commits, branching, merging, and fine-grained access control. Perforce is known for its scalability, performance, and support for large binary files.
v.	Team Foundation Version Control (TFVC): TFVC is a centralized version control system provided by Microsoft's Team Foundation Server (TFS). It offers features like branching, merging, and integration with other Microsoft development tools. TFVC is commonly used in Microsoft-centric development environments.
vi.	Bitbucket: Bitbucket is a web-based version control system that supports both Git and Mercurial repositories. It provides features like code hosting, pull requests, code review, and integration with other development tools. Bitbucket is often used for collaborative development and hosting of private repositories.

Software Project Management:
Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

The role of a Software Project Manager is crucial in overseeing and managing the successful execution of software development projects. They are responsible for planning, organizing, and coordinating all aspects of the project, ensuring that it is completed on time, within budget, and meets the specified requirements. The project manager serves as a bridge between the development team, stakeholders, and senior management, ensuring effective communication and collaboration throughout the project lifecycle.
The following are some of the key responsibilities of a software project manager
i.	Project Planning: The project manager is responsible for defining the project scope, objectives, deliverables, and timelines. They create a detailed project plan, allocate resources effectively, and establish milestones to track progress. Planning involves identifying risks, developing contingency plans, and setting realistic expectations.
ii.	Team Management: The project manager builds and leads the project team, ensuring that the right resources are assigned to the project. They provide guidance, support, and motivation to team members, fostering a collaborative and productive work environment. Team management includes task assignment, performance monitoring, conflict resolution, and promoting professional development.
iii.	Stakeholder Management: The project manager acts as a liaison between stakeholders, including clients, end-users, senior management, and the development team. They facilitate effective communication, manage expectations, and ensure that stakeholders are informed about project progress, risks, and changes. Stakeholder management involves addressing concerns, obtaining feedback, and maintaining positive relationships.
iv.	Risk Management: The project manager identifies, assesses, and manages risks throughout the project lifecycle. They develop risk mitigation strategies, monitor potential issues, and take proactive measures to minimize the impact of risks on the project. Risk management includes anticipating challenges, adapting plans, and ensuring project continuity.
v.	Quality Assurance: The project manager is responsible for ensuring the quality of the software deliverables. They establish quality standards, define testing and quality control processes, and monitor adherence to quality requirements. Quality assurance involves conducting reviews, inspections, and audits to identify and address any deviations or defects.
vi.	Budget and Resource Management: The project manager is accountable for managing the project budget and resources effectively. They track project expenses, monitor resource utilization, and make adjustments as necessary. Budget and resource management involves optimizing resource allocation, controlling costs, and ensuring efficient use of available resources.
Below are some of the challenges faced by software project managers in the execution of their duties
i.	Time Management: Staying on schedule is crucial in software projects, but changes to the original plan are common as projects evolve. Project managers must be skilled in time management, risk assessment, and contingency planning to ensure progress despite roadblocks or changes.
ii.	Scope Management: Managing scope creep, which refers to uncontrolled changes or additions to project scope, is a common challenge. Project managers must carefully define and manage project scope, ensuring that changes are properly evaluated, approved, and controlled to prevent scope creep.
iii.	Communication and Collaboration: Effective communication among team members, stakeholders, and senior management is essential. Project managers must facilitate clear and timely communication, manage expectations, and address conflicts or misunderstandings that may arise.
iv.	Resource Allocation: Allocating resources efficiently and effectively is crucial for project success. Project managers must assess resource availability, balance workloads, and ensure that the right resources are assigned to the right tasks. They must also handle resource constraints and adapt plans accordingly.
v.	Risk Management: Identifying and managing risks is a continuous challenge in software projects. Project managers must proactively identify potential risks, develop mitigation strategies, and monitor risks throughout the project. They must be prepared to handle unforeseen challenges and adapt plans as needed.
vi.	Managing Stakeholder Expectations: Balancing the expectations of different stakeholders can be challenging. Project managers must understand stakeholder needs, manage conflicting expectations, and ensure effective communication to maintain stakeholder satisfaction

Software Maintenance:
Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Software maintenance is the process of modifying and updating a software system after it has been delivered to the customer. It is a critical part of the software development lifecycle, ensuring the continued effectiveness, reliability, and value of the software. Maintenance activities can be divided into several categories, each serving a specific purpose in ensuring the ongoing functionality and adaptability of the software.
Below are some of the types of software maintenance activities
i.	Corrective Maintenance: This type of maintenance is essential for rectifying bugs observed while the system is in use or enhancing the performance of the system. It involves identifying and fixing defects to ensure the software functions as intended.
ii.	Adaptive Maintenance: Adaptive maintenance focuses on modifying the software to adapt to changes in the environment, such as operating system upgrades, hardware changes, or regulatory requirements. It ensures that the software remains compatible and functional in evolving technological landscapes.
iii.	Perfective Maintenance: Perfective maintenance involves making enhancements to the software to improve its performance, efficiency, or user experience. It aims to optimize the software's functionality, usability, and maintainability, often including refactoring code, optimizing algorithms, or adding new features.
iv.	Preventive Maintenance: Preventive maintenance aims to proactively identify and address potential issues before they manifest as problems. It involves activities such as code reviews, performance monitoring, and security audits to identify and mitigate risks, ensuring the software's long-term stability and reliability.
Software maintenance is crucial for the following reasons:
i.	Bug Fixing and Issue Resolution: Software maintenance ensures that bugs and issues identified during the software's use are addressed promptly, improving the software's reliability, stability, and user satisfaction.
ii.	Adaptation to Changing Environments: Maintenance allows the software to adapt to changes in technology, operating systems, hardware, and user requirements, ensuring that the software remains compatible, functional, and secure in evolving environments.
iii.	Enhancement of Functionality: Through maintenance, the software can be enhanced with new features, improved performance, and better usability, meeting the changing needs and expectations of users and ensuring the software remains competitive and valuable.
iv.	Risk Mitigation: Maintenance activities, such as security audits and preventive measures, help identify and mitigate potential risks and vulnerabilities, reducing the likelihood of security breaches, data loss, or system failures.
v.	Longevity and Cost-Effectiveness: By maintaining and updating software, organizations can extend its lifespan and avoid the need for costly redevelopments, maximizing the return on investment and reducing the total cost of ownership.
vi.	User Satisfaction and Retention: Well-maintained software that addresses user needs and provides a positive user experience contributes to user satisfaction and retention, demonstrating a commitment to quality and customer support.

Ethical Considerations in Software Engineering:
What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

Software engineers may encounter various ethical issues in their work, which can have significant implications for the products they develop and their impact on society. Some of the ethical issues that software engineers might face include:
a)	Data Management and Privacy: Ethical concerns related to the collection, storage, and use of user data. This includes ensuring compliance with regulations and customer expectations, as well as making ethical choices regarding the handling of personal data.
b)	Monetization of User Data: The ethical implications of how businesses generate revenue and incentivize developers and managers, especially in cases where user data is viewed as a valuable currency and there is a desire to monetize this data. This can lead to ethical dilemmas regarding the ethical sharing of user data.
c)	Balancing Professional Obligations and Ethical Responsibilities: Situations where engineers must balance their professional obligations with their ethical responsibilities, such as pushing back against requests that conflict with ethical principles, seeking advice, or considering whether they can continue working under certain conditions.
d)	Professional Responsibility and Standards: The importance of adhering to professional standards governed by a code of ethics to justify the work of software engineers. This includes the need to ask ethical questions and ensure that products and related modifications meet the highest professional standards possible.
To ensure they adhere to ethical standards in their work, software engineers can take several measures:
a)	Education and Training: Continuous education and training on ethical choices, data management practices, and compliance with regulations are essential. This includes staying informed about the latest legislative actions in the jurisdictions where customers use their software.
b)	Collaboration and Communication: Collaboration between engineering leadership and legal teams can help avoid ethical shortcomings. Open communication and collaboration within the software team can also facilitate the identification and resolution of ethical concerns.
c)	Adherence to Professional Standards: Adhering to professional standards governed by a code of ethics is crucial. This involves acting consistently with the public interest, ensuring that products meet the highest professional standards, and promoting no interest adverse to the employer or client unless a higher ethical concern is being compromised.
d)	Ethical Deliberation: Engaging in ethical deliberation and asking ethical questions before embarking on a new project. This involves considering the implications of the work and ensuring that it aligns with ethical principles and professional responsibility.
e)	Balancing Professional and Ethical Responsibilities: When faced with conflicting requests or situations, software engineers should navigate them with a deep understanding of both ethical principles and intellectual property laws. This may involve seeking advice, informing the employer or another appropriate authority of ethical concerns, and making decisions that align with ethical standards.

References

References
Collegenp. (2023, February 10). Understanding the Key Concepts of Software Engineering. Www.collegenp.com. https://www.collegenp.com/article/software-engineering-and-its-major-concepts/
Feder, M. (2023, March 17). Software Developer vs. Programmer vs. Software Engineer. University of Phoenix. https://www.phoenix.edu/blog/programmer-vs-software-engineer-key-differences.html
FORE, P. (2024, February 24). Software developer vs. software engineer: Seemingly so similar career tracks—but with some distinct differences. Fortune Education. https://fortune.com/education/articles/software-engineer-vs-software-developer/
GeeksforGeeks. (2018, October 12). Software Engineering | Introduction to Software Engineering - GeeksforGeeks. GeeksforGeeks. https://www.geeksforgeeks.org/software-engineering-introduction-to-software-engineering/
Kerry, M. (2023, May 2). Understanding the Key Differences between software engineering and software developer. Www.linkedin.com. https://www.linkedin.com/pulse/software-engineering-developer-difference-monica-kerry/
Roberts, S. (2023, August 23). What is Software Engineering? A Complete Guide. Www.theknowledgeacademy.com. https://www.theknowledgeacademy.com/blog/what-is-software-engineering/



Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
