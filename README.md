# Decentralized Devops

Greetings to my fellow Technology Advocates and Specialists.

In this Session, I will explain and walk my readers through the concept of __Decentralized Devops__.

| __NOTE:-__ |
| --------- |
| __For the Purpose of this article, Cloud Infrastructure is considered.__ |

| __CREDITS:-__ |
| --------- |
| 1. In my current organisation, there was a constructive push to share the Cloud Services responsibilities between Cloud Platform Team and Developers. The Idea was 2 Folds - a.) __Remove Cloud Platform Team from critical path of every project delivery__; b.) __Move more responsibilities towards the developers. In this way, project tasks gets expedited, avoiding delays.__ |
| 2. The Summer edition of "__We are Developers__" published the concept of __Decentralized Devops__. The Concept explained was exactly what together with my Cloud Platform Team, I was trying to implement in my current organisation. |

| __DISCLAIMER:-__ |
| --------- |
| The contents of this article is an amalgamation of - a. ) the excerpts from __the Summer edition of "We are Developers"__; and b. ) my learning while __implementing Decentralized Devops together with my Cloud Platform Team__. |

I had the Privilege to talk on this topic in __ONE__ Azure Communities:-

| __NAME OF THE AZURE COMMUNITY__ | __TYPE OF SPEAKER SESSION__ |
| --------- | --------- |
| __Festive Tech Calendar - 2023__ | __Virtual__ |

| __EVENT ANNOUNCEMENTS:-__ |
| --------- |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/48xa0wng7r95f5gyquis.jpg) |

| __OPERATING MODELS:-__ |
| --------- |

| __#__ | __OPERATING MODEL NAME__ | __DETAILS__ |
| --------- | --------- | --------- |
| 1. | Centralized Provisioning Model | The ownership of automation, build, run, manage and maintain Cloud Infrastructure falls on Cloud Platform Team. The request and response model is ITSM (IT Service Management) tickets (Service Request). Developers then needs to wait for the completion of their ticket(s). This wait is because Cloud Platform Team is horizontal by design, catering requests from the whole organisation. |
| 2. | Decentralized Provisioning Model | Cloud Platform Team enables Developers to automate, build, run, manage and maintain Cloud Infrastructure as part of Self Service which is build on set of predefined standards together with security guard rails and best practices. |
| 3. | Encapsulated Devops Model | In any organisation, count of developers are always higher than Cloud Platform and Devops Engineers. Dedicated devops engineer(s) can then become part of the development team helping to deploy Cloud Infrastructure based on the Decentralized framework build by Cloud Platform Team. |

| __WHAT IS DECENTRALIZED DEVOPS:-__ |
| --------- |
| 1. It is a Model/Platform/Framework. It is not a Project or a Team. |
| 2. In Simple words - Decentralized Devops is an operating model where Automation, Build, Run, Manage and Maintainnece of Cloud Infrastructure is a shared responsibility between Cloud Platform Team and Developers. |

| __CONCEPT:-__ |
| --------- |
| 1. This Model gives developers full ownership for building managing and operating their own infrastructure. |
| 2. The Mind set behind is - "you build you run" providing more agility and flexibility to development Team.
| 3. It also requires cultural shift in the organisation as now the development team will own the entire stack - Infrastructure, Application (including data) and Operations. |
| 4. This model then needs to be agreed between Cloud Platform and Development Team as it completely depends upon __maturity and preference by shifting the responsibility towards developers__. |
| 5. With Decentralized DevOps, Centralized governance responsibilities still remain with Cloud Platform team to have the required guard rails. |
| 6. Cloud Platform Team creates deployable templates with security and best Practises that development team can reuse to deploy cloud services. These deployable templates will then be treated as __Inner Source__ (Internal Open source Code). Development team can then contribute as and when required. |
| 7. Platform team being the owner of the Framework, can then validate each developers contribution as part of Pull Requests (PRs). The PRs can be Improvement or New Feature for one or more Cloud Services. __Depending upon code quality, it can be merged and released or rejected.__ |

| __RESPONSIBILITY OF CLOUD PLATFORM TEAM:-__ |
| --------- |
| 1. Implementing IaC (Repeated Deployable Templates) with Security, Governance and Best Practises - __Self Service.__ |
| 2. Managing and Maintaining __Self service Platform.__ - configurations, best practices, implementing feedbacks (Improvements/Feedbacks) added in Product Backlog Items (PBIs), Pull Requests (PRs), releases, rollbacks, guidance, and consultation. |

| __PRINCIPLES TO ENABLE DECENTRALIZED DEVOPS MODEL/PLATFORM:-__ |
| --------- |

| __#__ |  __PRINCIPLES__ |  __DETAILS__ |
| --------- | --------- | --------- |
| 1. | Version Management | In the decentralized devops model, the repeated deployable templates created by Cloud Platform Team (which serves Development Team as Self Service) are build mostly as separate modules. Each of these modules are version controlled with proper release tags. |
| 2. | Customizable | In the decentralized devops model, development team can contribute as and when required to the code base of the deployable templates. The Customization to the code base can be "improvements" or "new feature request(s)". This is achieved by forking the existing code base, refactoring the code and raising a pull request to be reviewed by Cloud Platform Team. |
| 3. | Transparent | In the decentralized devops model, the transparency is maintained by treating the deployable templates as Inner Source (Internal Open Source Code). Developers can any time contribute and acceptance/rejection of any contribution as part of Pull Request (PR) depends upon code quality, keeping the whole process purely transparent. |
| 4. | Self Service | In the decentralized devops model, self service is achieved, if developers can deploy and manage cloud infrastructure (using the deployable templates created by Cloud Platform Team) independently.   |
| 5. | Documentation | In the decentralized devops model, documentation is key. The Self Service will only work when we have a.) Extensive documentation with detailed explanation and examples; b.) training and workshops on the self service; and c.) Roadmap of the platform.  |
| 6. | Process | In the decentralized devops model, there should be a clear definition as what is IN-SCOPE and what is OUT-OF-SCOPE. These are then backed up with Process which are clearly documented and understood both by Cloud Platform Team and Development Team. Another aspect is to have a clear process around a.) how to handle improvements; b.) How to handle New Features; c. ) how to handle Pull Requests (PRs); and d.) How to handle release/rollback management. |

| __IMPLEMENTING DECENTRALIZED DEVOPS MODEL/PLATFORM:-__ |
| --------- |
| In Simple words, think of it as PUB-SUB Model with GitOps Principle. Cloud Platform Team = Publishers (Building, Managing and Maintaining Repeatable Deployable Templates); Development Team = Subscribers (Consumers who deploys and contributes to the platform); and GitOps = IaC maintained in Git which is triggered by a CI/CD Pipeline. |

| __#__ |  __IMPLEMENTATIONS__ |  __DETAILS__ |
| --------- | --------- | --------- |
| 1. | Publishers | Cloud Platform Team publishes and maintains deployable templates. |
| 2. | Subscribers | Developers are the consumers who deploys and contributes to the platform. This requires collaborating with Cloud Platform Team. |
| 3. | Accessibility | This is the delivery capabilities which enables self service, making the development team independent. Here GitOps Principles are applied - IaC maintained in Git which is triggered by a CI/CD Pipeline.  |

__Hope You Enjoyed the Session!!!__

__Stay Safe | Keep Learning | Spread Knowledge__
