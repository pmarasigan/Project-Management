## Pet Shelter Project
Gisella Kontaria, Spring 2023


### Executive Summary    

This paper will introduce you to “Pet Shelter”, an open-source pet shelter web page project. Pet Shelter aims to become a platform that connects those looking to put their pet up for adoption with potential pet adopters in an efficient and seamless manner. The platform is created to improve the adoption process by making it beginner-friendly for those who are new to the process and will also use a user-centric approach by tailoring the process based on each user’s needs and preferences. This ensures that the platform is easy to use and navigate, providing a smooth experience for both pet owners and potential adopters.

To achieve that goal this project is looking to assemble a team of developers and designers and a project manager to work collaboratively and cross-functionally using the Agile Scrum methodology as the project management framework of choice. This paper will explore and provide a comprehensive overview of the project planning process, including its background, goals, scope, and strategies. Additionally, the paper will examine the potential risks and challenges associated with the project and discuss how the team plans to mitigate them.


### Background

#### Problem identification

According to online pet enthusiast forums, there are several problems tied to the current pet adoption process. The process is usually categorized into several phases: search, inquiring, application (Best Friends Animal Society, 2021). Each phase is often plagued with their own set of issues, starting from the initial search phase.

In the search phase, potential adopters face difficulties in finding the exact breed or type of pet they want, often because the search filters don't provide the necessary details. Additionally, they may struggle to locate pets in their vicinity or obtain detailed information, including health, behavior history, or the pet's personality, to make an informed decision.
Moving on, when inquiring about a specific pet, many adopters encounter communication issues. These instances include running into shelters or rescues that either don't respond to their queries or delay in doing so (Human Animal Support Services, 2021). There are also transparency issues where some shelters withhold details about the pet until the adoption application is submitted and approved, introducing a knowledge gap between the owner and adopter.

Lastly, when adopters are applying to adopt a pet, many of them find that the application requirements are extensive, strict, or lengthy. There is also no clear criteria for approval and hence the entire process is often vague. Additionally, there may be additional steps, such as background checks, home visits, and reference checks, which can prolong the adoption process (Million Cat Challenge, 2021). This is unsuited for those who are looking for a speedier process and have no prior adoption background.

These challenges in the pet adoption process can also be overwhelming for potential adopters, hindering them to try in the first place or causing some to give up on the adoption process altogether.


#### Target Audience and Goals

There are two interested parties in this project: potential pet owners looking to adopt a pet and current pet owners looking to donate a pet. It is important to first characterize their unique needs and pain points that Pet Shelter aims to address.

For potential pet owners, the primary pain point is the cost associated with adopting a pet. Many individuals are deterred from pet ownership due to the high costs tied to the process of getting a pet, such as how existing shelters often have a lot of hidden overhead costs charged. Therefore the process can be daunting for those who are not ready to spend a considerable amount of money. The Pet Shelter platform aims to make the adoption process more accessible and affordable for all. This will suggest that pet ownership is not a luxury limited to the privileged few.

Another pain point for potential pet owners is inexperience in the adoption process. Many individuals who are new to the adoption process may feel overwhelmed by the process as they are unsure of what to expect, where to start, or even confused about how to find the right pet. The Pet Shelter platform aims to create a user-friendly and beginner-friendly platform that caters to the needs of those who are new to the adoption process. The platform will do so by providing detailed information about each pet, including health and behavior history, personality traits, and photos, to help potential adopters make informed decisions.

For current pet owners looking to donate a pet, the primary pain point is often the emotional difficulty of parting with a beloved pet. Many pet owners are attached to their pets and want to ensure that their pets go to loving homes. This is often not achieved through existing shelters since they are often not informed who the new owners are, since communication is usually only done with the shelter and not the new owner. The Pet Shelter platform aims to create a safe and compassionate space for pet owners looking to donate a pet, ensuring that pets are placed with loving and responsible owners. The platform provides guidance and support throughout the donation process, making it easier for pet owners to part with their pets knowing that they will be well taken care of, and also removes the middlemen so that the communication will be only between the owners and adopters.

To recap, the Pet Shelter platform aims to address the unique pain points of both potential pet owners and current pet owners looking to donate a pet. By creating a user-friendly and simple-to-navigate platform, this web application hopes to make the adoption process more accessible and affordable for all, encouraging more individuals to consider pet ownership.

#### Why Open Source?

The Pet Shelter platform is an open source project, meaning that it is publicly accessible and free for anyone to use, modify, and distribute (Reviano, 2021). There are several reasons as to why the project is suited for an open-source approach.

Firstly, open source allows for continuous development and improvement by a community of developers. Currently, there are several APIs out there that provide pet adoption data. However, it requires significant data cleaning efforts to ensure accuracy and relevance. The way existing APIs are structured makes it almost impossible to predict where and when the data is sourced. Since it is important that Pet Shelter utilizes data that is not outdated, the community effort involved in open source reduces the amount of time spent on the data cleaning process and therefore makes sure that the data used in this platform remains up-to-date.

Secondly, open source promotes transparency and accountability. As discussed above, there is a significant level of distrust between parties in the pet adoption process. Therefore, to resolve this existing issue, Pet Shelter needs to be a reliable platform the users can trust. An open source approach allows for greater scrutiny of the project's code and operations as it is visible for anyone to see and make changes. This ensures that the platform is held to a high standard of accountability if there is some information that needs change.

Lastly, open source ensures adaptability. Since this platform aims to remain up and running for the long-term, the project has to stay on track with newer technologies. To stay relevant, it has to be able to easily adjust to new shifts in technology and trends. Having a growing community of developers involved in the open source project ensures that it can keep pace with these changes. Additionally, the size of the team in an open source setting also ensures that these execution of changes happen in a timely manner.


### Project Scope

The project's scope will be divided into different phases, and the platform will be launched after completing the initial phase 1. The features included in phase 1 are crucial for the platform to stand out in the market, while those included in phase 2 are desirable but not necessary. Continuous user testing and iterations will occur in the series of phases launched afterwards.

The platform will have two distinct views: admin and user. The admin view will be intended for pet owners, while the user view will be designed for potential pet owners. The list of features will differ for each view, with the user view being more restricted in terms of what can be viewed. For instance, the admin view will have the ability to remove a pet, while the user view will not. In short, the scope of this web page will include views that allows users to manage their pets, search, adopt, and make donations to support the shelter's work depending on their roles.

#### Phase 1        

| ![](https://user-images.githubusercontent.com/124402288/234653003-6c27c6c2-6ec8-4556-8054-2f33e58b1058.png) | 
| :--: |
| <b>Figure 1.</b> Homepage Wireframe [View](https://github.com/OREL-group/Project-Management/issues/281). |   

__User-facing Features__

* Homepage: A homepage with information about the shelter and its mission.
* Search and filter: A search functionality for finding available pets based on various filtering criteria, such as species, breed, age, gender, and location.
* User registration: A user registration system that allows users to create an account as a user. Rounds of verification (ie. through email or phone number) will be included to mitigate for fake accounts.
* Save functionality: A save button that allows users to save their favorite pets to the saved page
* Contact form: A contact form for filling in their personal information and getting in touch with the owner.

__Admin-facing Features__

* Pet management: A pet management dashboard for pet owners to add and manage pets that they have enlisted, including functionalities to edit their information, photos, and availability status.
* Profile: A profile page to view past and current adoption history.
* Analytics: A reporting system that provides owners with insights into their ratings as pet owners, including adoption statistics.
* Enlist a pet form: A form to fill to enlist a pet in the platform. All fields are required, such as breed, type, color, picture of pet, and pet health conditions. This ensures that all the information of a pet is complete by the time it is up online.
* User registration: A user registration system that allows users to create an account as an admin. Rounds of verification (ie. through email or phone number) will be included to mitigate for fake accounts. This number will be used as a mode of communication to adopters.

#### Phase 2 

* Donation system: A donation system available in both admin and user views intended for supporting the platform financially.
* Ratings: A rating system where both users and admins can rate their interaction and experience with each other. This feature is important as it can be used as a way to indicate accountability. There should also be a validation system where anyone can only give ratings to people they have interacted with beforehand to prevent scamming.

All these features will be designed to be scalable and modular, making it easy for customizations in the future. The web page will also be tested rigorously for bugs and vulnerabilities to ensure that it is secure and reliable for both pet owners and users.


#### Contributor and Stakeholder Management

| ![](https://user-images.githubusercontent.com/124402288/234652666-239fdc8b-57d1-4484-9c22-acd55effcaf5.jpg) | 
| :--: |
| <b>Figure 1.</b> Stakeholder Hierarchy Diagram [View](https://github.com/OREL-group/Project-Management/issues/280). |   

The Project Manager oversees the entire project and is responsible for spearheading the meetings, cross-functional task management, marketing efforts, and coming up with a prioritization matrix. Below the Project Manager are Developers and Designers. The Developers branch is further divided into Front-end and Back-end Developers, with the former responsible for client-facing properties and the latter responsible for database set up and management. The Designers branch is divided into UI/UX Designers and Graphic Designers where the former is responsible for prototyping and the latter responsible for drawings.


### Project Constraints

The Pet Shelter project will be subject to various constraints that are including but not limited to the following that must be considered to ensure its success.

* Budgeting: The project will have a limited budget as it is being developed as an open source project. The only revenue stream planned to be in place for this platform is through donation / crowdsourcing. This means that the project must be resource-efficient and implements cost-effective strategies as it does not have a stable income stream.
* Timeline: The project must be completed within a timely manner to ensure that what has been built remains relevant and useful to all parties. This timeline also creates a sense of urgency which is ideal as it is better to be up and running as fast as possible. Therefore, it is necessary for the team to use a project management framework that is most well suited to the objectives to ensure that it can be completed within the allotted time frame. This will be explored further in the later sections of this paper.
* Compatibility: The web page must be compatible with a wide range of browsers and devices to ensure that it is accessible to all users. This requires the team to develop the platform using responsive design, ensuring that the platform can adapt to different screen sizes and devices. The team must also test the platform across different browsers and devices to ensure that it functions correctly.
* Security: The web page must be secure and protect user data to prevent data breaches and other security issues. It is important that all the open source efforts implement industry-standard security protocols to ensure the data saved from the platform is protected from unauthorized access or use. For example, practices such as encryption and two-factor authentication methods can be utilized.


### Licensing

As an open-source project, the Apache License 2.0 is a suitable choice as it allows for the project to be used, modified, and distributed by anyone without restrictions, encouraging community involvement and development. This license is also well suited for commercial use, encouraging wider adoption and aligning with the goals of Pet Shelter.


### Strategies

#### Technology Stack

The Pet Shelter web application will be developed using modern web technologies, with the technology stack of choice being ReactJS with a NodeJS backend. This choice was based on the need for a dynamic and scalable web page. ReactJS allows developers to reuse code across screens of different sizes and breakpoints, making it easier to develop for both desktop and mobile platforms (Metizsoft Solutions Pvt. Ltd, 2019). ReactJS and NodeJS technologies that have been chosen for the project are also open source and free to use, keeping costs minimal.

#### Codebase Management

The team will use Github as their version control of choice because it is widely used and free. Github is compatible with all operating systems, making it preferred for an open-source project involving developers using different devices.

#### Agile Methodology

To achieve the project's objectives, the team will assemble a group of developers, designers, and a project manager who will work collaboratively to create a functional and user-friendly platform. The team will use the Agile methodology, which emphasizes iterative and incremental development to ensure that the project meets all its requirements. This approach also allows the team to break down the project into smaller, more manageable tasks, making it easier to track progress and make necessary adjustments (ZenTao, 2021).

#### Task Management Tool

The team will use a Kanban board to manage tasks and monitor progress. Under the Agile methodology, sprints will be used to plan for work distribution (Association for Project Management, 2021). The tools suited for this are Confluence as the note-taking tool and Jira as the task management tool as they support seamless integration between the two. Sprints created on Jira can easily be embedded in a Confluence notebook.

#### Communication

The team will use Slack as the mode of communication because it supports different channels, making it easy for teams to get together and meet based on the work they are doing. As the team grows, Discord channels may be preferred, but Slack is sufficient for a small team at the beginning.


### Project Timeline

Phase 1 of this project will be completed within a timeframe of 3 months and will be regularly updated and maintained by a community of developers to ensure that it remains up-to-date with the latest technologies and best practices. The project manager will be responsible for efficient communication between all parties and also spearhead meetings to make sure the project stays on track with the deadlines. 

The project timeline is as follows:

* Week 1-2: Project planning and requirements gathering
* Week 3-4: Designing the user interface and developing wireframes
* Week 5-6: Developing the home page and features for the two different views
* Week 7-8: Developing the database to manage pet and user information
* Week 9-10: Developing and testing the web page locally and with beta users
* Week 11-12: Launching the web page and gathering feedback for next iteration of launch


### Development Cycle

This software development cycle outlines the process the Pet Shelter project team will follow to develop the website. The development cycle will be executed in sprints, and the team will review and adjust the plan during each sprint based on feedback from stakeholders and the progress made during the previous sprints.

#### Execution / Deployment

During the initial phase of the Pet Shelter project, the team will focus on developing the basic features necessary to create a functional and user-friendly platform for pet adoption. Phase 1 will be executed in a series of sprints as follows:

* Sprint 1: Develop wireframes and mockups for the basic layout, review with stakeholders and incorporate feedback, and look for pet adoption APIs to be used as mock data.
* Sprint 2: Develop HTML, CSS, and JavaScript code for the homepage and search functionality. Conduct initial testing of the homepage and basic layout using mock data.
* Sprint 3: Develop user registration system for both user and owner and set up database for each.
* Sprint 4: Develop contact form and conduct initial testing, concluding the phase 1 features. Then conduct the initial round of testing for the first working prototype.
* Sprint 5: Develop donation system and officially deploy the website with invitations to join.

#### Monitoring/Maintenance

The project manager will serve as the website's admin and will monitor and maintain the website, removing any fishy information. They will perform regular updates within the content and security and constantly update the policies related to pet adoptions. The team will gather analytic data, visualize insights and evaluate how the product is doing based on the defined metrics. They will hand out customer satisfaction surveys for feedback and improvements.

#### Transfer of Ownership

When it is time for the project to be transferred to a new team, the current team will transfer ownership and provide training to the next batch of project managers and developers responsible for the next phase of the launch. They will ensure that the code is always properly documented for transfer of ownership and practice good coding practices.


### Community Engagement

#### Mailing List and Newsletter 

To keep users updated on the newest pets available for adoption, the team will provide a feature for users to be a part of the mailing list. User preferences will be saved and notifications will be sent for pets that match their preferences. Additionally, the team will release a monthly newsletter to keep contributors informed about changes to the platform.

#### Rating System

The team plans to implement a rating system where users can leave reviews and ratings for pets, owners, and buyers. These reviews will provide valuable insights to potential adopters about the pets they are interested in and the owners they are considering. Moreover, owners can make informed decisions based on the ratings of potential adopters. The team will closely monitor the reviews and take action against scammers or those who provide fake information to ensure that the rating system is fair and accurate.

Additionally, users who receive a certain number of positive reviews can earn badges or become verified buyers or owners. To incentivize users to provide accurate and helpful reviews, the team will reward them with points or other incentives. This will enhance the platform's credibility and trustworthiness, leading to more adoptions and donations.

#### Collaboration with Animal Enthusiast Organizations 

To gather useful insights and foster partnerships, the team will collaborate with animal enthusiast organizations for early beta testing. These organizations are the right target for testing as they are likely to provide valuable feedback and insights into the adoption process. Building connections with these groups can also help promote the Pet Shelter web application and achieve a wider reach.


### Project Sustainability

To ensure the project's sustainability, the team will streamline the process to upload pets, contact owners, and give reviews. They will develop multiple straightforward entry points for new community members and make website modifications based on current trends. The team will establish an agile project workflow and allow loyal and active members to verify owner's listings.

The project manager will review entries and monitor reviews to prevent scammers or fake information. The team will allow users to encourage features to be added or removed through a customer feedback survey to maintain the website's user-centeredness. They will also allow users to search for a pet by distance from where they are located and maintain open channels for community feedback. Finally, the team will ensure that the code is properly documented for transfer of ownership.


### Project Expansions

Currently, the plan is to scale the project beyond the Champaign-Urbana area while maintaining a community and user-centered focus when entering each new city. This will involve adapting to the needs of each specific location and establishing partnerships with local animal enthusiast organizations to increase the platform's reach and relevance. The hope is to become a valuable resource for all pet enthusiasts across multiple regions in the future.


### References     

Best Friends Animal Society. "Pet Adoption Barriers and Solutions." Best Friends Network, 2021, https://network.bestfriends.org/proven-strategies/operations/fostering-adoption/pet-adoption-barriers-and-solutions.

Human Animal Support Services. "Barrier Busting Basics for Busy Animal Shelters." Human Animal Support Services, 2021, https://www.humananimalsupportservices.org/blog/barrier-busting-basics-for-busy-animal-shelters/.

Million Cat Challenge. "Removing Barriers to Adoption." Million Cat Challenge, 2021, https://www.millioncatchallenge.org/resources/removing-barriers-to-adoption.

Reviano. "Open-Source Software: Good for Small Business?" Reviano, 2021, https://www.reviano.com/blog/open-source-software-good-for-small-business.html.
Metizsoft Solutions Pvt. Ltd. "Combination of React and Node.js for Ultimate Web Application Development." Metizsoft Blog, 2019, https://www.metizsoft.com/blog/combination-of-react-and-node-js.

Association for Project Management. "Agile Project Management." APM Resources, 2021, https://www.apm.org.uk/resources/find-a-resource/agile-project-management/.

ZenTao. "Why Agile Methodology Makes Sense for Small Teams." ZenTao Blog, 2021, https://www.zentao.pm/blog/why-agile-methodology-makes-sense-for-small-teams-1095.html.

