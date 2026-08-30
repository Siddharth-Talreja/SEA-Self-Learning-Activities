# Self Learning Activity 1

## 1. Comparison of Agile and DevOps

### 1.1 What is Agile?
Agile software development is an iterative, flexible approach that prioritizes continuous delivery, collaboration, and adaptability.

- Agile Mindset: Focuses on adaptability, collaboration, and customer satisfaction.
- Quick Response to Change: Adapts rapidly to changing requirements and priorities.
- Regular Demonstrations: Frequently showcases project progress for feedback.
- Cross-Functional Teams: Encourages collaboration through self-organizing teams.

#### Agile Software Development Process
Agile software development, often just called 'Agile', focuses on being flexible and practical when delivering software. Instead of launching everything at once, Agile delivers small, valuable updates to users over time.

- Requirements Gathering: The development team works closely with the customer to understand what they really need from the software. The team listens carefully to the customer’s needs, then sorts and prioritizes these requirements to make sure the most important features are developed first.
- Planning: The team creates a clear plan for how they’ll build the software. They decide which features to focus on in each development cycle (called an iteration).
- Development: This is where the team starts turning their plan into reality. They work in short, focused cycles, building small, usable pieces of the product. Each cycle builds on the last, which helps the team stay on track and get quick feedback to keep improving.
- Testing: As the software gets built, it’s also tested to make sure it works properly and meets the customer’s needs. Testing ensures the product is of high quality and free from errors, so problems are caught early on before they become bigger issues.
- Deployment: Once everything is tested and working as expected, the software is deployed, which means it’s ready for customers or end-users to start using. It’s the moment when all the development work comes to life.
- Maintenance: Even after the software is released, the job isn’t done. The team keeps maintaining the software, verifying it continues to work well and stays up-to-date with any new needs or changes from the customer.

### 1.2 What is DevOps?
DevOps is the combination of cultural philosophies, practices, and tools that increases an organization’s ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes. This speed enables organizations to better serve their customers and compete more effectively in the market.
Under a DevOps model, development and operations teams are no longer “siloed.” Sometimes, these two teams are merged into a single team where the engineers work across the entire application lifecycle, from development and test to deployment to operations, and develop a range of skills not limited to a single function.

In some DevOps models, quality assurance and security teams may also become more tightly integrated with development and operations and throughout the application lifecycle. When security is the focus of everyone on a DevOps team, this is sometimes referred to as DevSecOps.

These teams use practices to automate processes that historically have been manual and slow. They use a technology stack and tooling which help them operate and evolve applications quickly and reliably. These tools also help engineers independently accomplish tasks (for example, deploying code or provisioning infrastructure) that normally would have required help from other teams, and this further increases a team’s velocity.

### 1.3 Difference between Agile and Devops
Agile methodology and DevOps are two complementary practices that bring efficiency and predictability to all aspects of software development. The agile methodology is an iterative software development approach that focuses on collaboration, rapid software releases, and customer feedback. It’s a cultural and management philosophy that aims to get every team member to focus on continuous improvement and value delivery to customers. DevOps is a software delivery approach that removes silos between existing development and operations teams. DevOps teams use tools and practices to automate processes that historically have been manual and slow—such as deploying code or provisioning infrastructure. These tools and practices increase an organization’s ability to quickly deliver applications and services.

| Agile | DevOps |
|---|---|
| Agile is a software development methodology that focuses on developing software in small, iterative cycles. | DevOps is a set of practices that combines software development and IT operations to deliver software efficiently and reliably. |
| Agile mainly focuses on collaboration, flexibility, continuous feedback, and adapting to changing requirements during development. | DevOps mainly focuses on automation, continuous integration, continuous delivery, deployment, and monitoring throughout the software lifecycle. |
| Agile improves the way development teams plan, develop, test, and modify software. | DevOps extends this process by improving how software is developed, deployed, operated, and maintained in production. |

## Case Study of Jira and Asana in Real World Projects

### Jira
Jira is a popular project management and issue-tracking tool widely used in software development and testing. It helps teams manage tasks, monitor project progress, and streamline workflows efficiently.

- Used for bug tracking and issue management.
- Supports Agile methodologies such as Scrum and Kanban.
- Improves collaboration among developers, testers, and project managers.

### Asana
Asana is a project management software developed in the year 2008 by Dustin Moskovitz and Justin Rosenstein. It is a web and mobile application which is designed to help the teams track, manage and organize developing teams to collaborate and manage their work efficiently. It is a software-as-a-service that allows teams to communicate, assign and specify a deadline for a particular task. It provides a RESTful interface that allows users to update and access their data on the platform for communicating with various environments from command-line or native applications.

The main difference between the two is that Jira is specifically used for agile methodology whereas Asana is a general purpose project management software.

### Real Life examples of usage of Jira and Asana:
Different organizations and companies use different apps based on their needs. Some may even use a hybrid model

#### Asana:
- **Zoom:**  Departments use Asana as a central source of truth. Engineering teams use Jira for code sprints, but sync tasks back to Asana. Marketing and sales teams plan global campaigns natively in Asana without bothering engineers for minor status updates.

#### Jira :
- **Avaratak:**  Organizations migrating off business-centric tools into structured environments use Jira to enforce naming conventions, permissions, and field standards from day one, preventing future technical debt and messy data cleanups.

#### Hybrid:
-  Many firms such as Zoom use both by bridging them together. Technical teams work in Jira while business groups operate in Asana, utilizing a two-way sync for descriptions, comments, and statuses so both sides stay aligned without tool switching.

## Writing Effective User Stories

### What are User Stories
A user story is the smallest unit of work in an Agile framework. It’s an end goal, not a feature, expressed from the software user’s perspective.

A user story is an informal, general description of a software feature written from the end user's or customer's perspective. The purpose of a user story is to articulate how a piece of work will deliver a particular value back to the customer.

### Format of a User Story:
The format of a user story is as follows:
**“As a [persona], I [want to], [so that].”**
This can be explained as follows:
- "As a [persona]": Who are we building this for? We’re not just after a job title, we’re after the persona of the person. Max. Our team should have a shared understanding of who Max is. We’ve hopefully interviewed plenty of Max’s. We understand how that person works, how they think and what they feel. We have empathy for Max.

- “Wants to”: Here we’re describing their intent — not the features they use. What is it they’re actually trying to achieve? This statement should be implementation free — if you’re describing any part of the UI and not what the user goal is you're missing the point.

- “So that”: how does their immediate desire to do something this fit into their bigger picture? What’s the overall benefit they’re trying to achieve? What is the big problem that needs solving?

### Examples of a User Story:
The following are some examples of a User Story:
- As Max, I want to invite my friends, so we can enjoy this service together.
- As Sascha, I want to organize my work, so I can feel more in control.
- As a manager, I want to be able to understand my colleagues progress, so I can better report our success and failures.

### How to write Effective User Stories:
An effective user story is a short description of a feature from the user's point of view. It generally follows the format: **“As a [type of user], I want [goal/action], so that [benefit/reason].”** A good user story should clearly identify who needs the feature, what they want to accomplish, and why they need it. It should be small, focused on a single requirement, and describe user value rather than technical implementation.

An effective user story should also have clear **acceptance criteria** that define the conditions that must be satisfied for the story to be considered complete. A commonly used guideline for writing good user stories is **INVEST**: Independent, Negotiable, Valuable, Estimable, Small, and Testable.


### Acceptance Criteria:
Acceptance criteria are the conditions that a product, user story, or increment of work must satisfy to be complete. They’re a set of clear, concise, and testable statements that focus on providing positive customer results.

Instead of focusing on how you reach a solution, acceptance criteria are the final desired outcome of the task.

They are seen as predefined requirements in Agile methodologies—specifically a user story must satisfy to be considered complete. They also work as a type of Agile requirements documentation that outline certain conditions that must be met for successful delivery.

A user story describes the need and tells us what is to be done. Acceptance Criteria tells us what all needs to be done to fulfil the user story.

eg. 
**User Story:**
As a customer, I want to reset my password, so that I can regain access to my account if I forget it.

**Acceptance Criteria:**

* The customer can request a password reset using their registered email address.
* The system sends a password-reset link to the registered email address.
* The password-reset link expires after a defined period.
* The customer can create a new password using the link.
* The customer can log in successfully using the new password.
