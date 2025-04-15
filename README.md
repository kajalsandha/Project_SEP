
**Member Name:-** Kajal, Robinjit Kaur  
**Student ID:-** 8972108, 8867197  
**Project Title:-** WaterSaver – Helping Residents Conserve Water During Emergency Pipe Repairs  
  
**Phase 1:-** Understanding the Problem, Exploring Causes, and Validating a Solution  
**Project Overview**  
 The lack of real-time feedback and communication during emergency water pipe repairs is a major problem that urban populations experience, and our solution, WaterSaver, aims to solve it. Residents are frequently told to save water at such occasions. But in the absence of frequent updates or real-time consumption statistics, many users either disregard conservation requests or don't know how to properly modify their usage. Longer maintenance times, needless water waste, and decreased citizen-municipality cooperation are the outcomes of this.  
  
**Problem Statement**  
Our main problem is that residents do not have access to timely, actionable feedback during emergency water conservation periods.  Nowadays, a lot of municipalities rely on passive communication techniques like email or public announcements, which are frequently disregarded and delayed.  By providing homeowners with real-time water usage data, alarms, and customized conservation tips, our app seeks to change this.  
  
**The Importance of This Issue**  
 Not only is efficient water conservation important for the environment, but it is also essential for emergency infrastructure management and municipal planning.  Noncompliance with conservation requests by citizens results in:  
* Longer repair times as a result of pressure imbalances
* Higher expenses for resources
* Residents' and city workers' frustration
* Increased probability of recurrent pipeline failure
  
 Cities dealing with deteriorating infrastructure, rising water demands, and stress from the environment make this issue even more pressing.  
  
**Problem Breakdown**  
  
Component | Details  
--- | ---  
**Root Cause** | Lack of accessible, real-time water usage data and clear guidance during emergency restriction periods.  
**Observed Effects** | - Low compliance with conservation efforts  <br> - Prolonged repair operations  <br> - Frustrated stakeholders  <br> - Increased water waste  
**Hypothesis** | If residents receive personalized water usage feedback and targeted tips through a mobile app, water consumption during emergencies will decrease significantly.  
**Proposed Solution** | **Build WaterSaver**, a mobile app that provides:  <br> - Real-time water usage tracking  <br> - Alerts for restrictions or overuse  <br> - Personalized water-saving tips  <br> - A community dashboard to promote shared progress  
**Justification** | Research shows that behavioral nudges and real-time feedback (e.g., *Opower* for electricity) can significantly change user behavior. During the *Cape Town water crisis*, public dashboards and goal-setting helped reduce consumption by over 25%. Mobile apps offer wide reach and usability, making them an ideal solution for urban residents.  
**Expected Outcome** | - Increased public awareness and action  <br> - Faster repair timelines  <br> - Reduced water usage  <br> - Higher resident engagement and municipal trust  
  
**Supporting Research & Evidence**

**Municipal Case Studies**  
* **Toronto in 2023:** In a number of neighborhoods, water restrictions failed because usage was not visible. Even after several warnings, the city reported excessive consumption.  
*Source:* Annual Report of the City of Toronto Waterworks Department  

**Behavioral Science Evidence**  
* According to a WaterSmart Software research from 2022, households who received app-based feedback from smart meters used **20%** less water.  
*Source:* WaterSmart Research Lab  

**Global Benchmark – Cape Town Water Crisis (2018)**  
* A global benchmark in emergency water management. Real-time objectives, smartphone notifications, and digital dashboards helped the city escape **"Day Zero."**  
*Source:* Harvard Kennedy School Case Study (2021)  

**Resident Survey**  
* According to a survey of **100** households, **72%** said they would use a conservation app if it displayed real-time usage data and provided alerts. Many respondents indicated that existing communication channels, such as news and email, were **inadequate** during water restrictions.  

**Technology Feasibility**  
* Smart meter integration is supported through APIs from companies like **Flume** and **Phyn**. In areas lacking smart infrastructure, **manual logging** can serve as a viable backup method.  
  
**Initial Problem Insights & Next Steps**  
Our findings clearly highlight a gap in communication and behavioral response during emergency pipe repairs. While residents are often aware of the water restrictions, they lack real-time visibility into their own usage and have no clear guidance on how to respond. This leads to excessive consumption, delays in repair efficiency, and strain on municipal infrastructure.  
The research has helped us validate our initial hypothesis that providing real-time usage data, personalized alerts, and clear conservation goals can significantly improve participation and water-saving behavior in the community.  
  
**Transition to Next Phase**  
We will convert these insights into a specific set of technical and functional requirements in the following stage of our project.  This will entail specifying the features that the app must have, how it will function, and how we'll make sure it runs dependably in different situations.  
The second deliverable will concentrate on defining:  
* What the application must accomplish (functional requirements),  
* The way it should to function (system expectations),  
* The reasons each element supports the results of our research.  
  
**Phase 2:-** Functional & System Requirements  
**Introduction**  
This section deconstructs the requirements required to design and implement the WaterSaver application, based on the research findings and problem insights presented in Deliverable 1.  User needs, technical limitations, and our objective of encouraging prudent water use during municipal pipe repairs all influence these specifications.

 We have made sure that every requirement follows best practices for gathering software requirements and complies with the SMART principle, which stands for Specific, Measurable, Achievable, Realistic, and Time-bound.  
  
  
**Functional Requirements (What the App Will Do)**  
  
**Feature** | **Description**  
--- | ---
**User Registration & Profiles** | Residents can register and create profiles tied to their household or address, ensuring personalized tracking and notifications.  
**Real-Time Usage Monitoring** | Users can view current water usage through integration with smart meter data or by manually entering consumption details.  
**Emergency Alerts** | Location-specific notifications during water repair events or restriction periods to guide user actions in real-time.  
**Customized Conservation Tips** | Personalized daily tips to help users reduce water usage based on their unique consumption patterns, restrictions, and household type.  
**Community Progress Dashboard** | Displays city-wide or neighborhood water conservation achievements, encouraging friendly competition and collective action.  
**Manual Logging Option** | For households without smart meters, allowing them to manually log their water consumption, ensuring inclusivity in the app's features.  
**Admin Dashboard for Municipalities** | Enables city officials to update conservation zones, send alerts to residents, and track overall usage trends to optimize resource management.  
**Push Notifications & Reminders** | Sends periodic reminders or alerts to encourage users to take daily water-saving actions or comply with newly imposed water restrictions.  
  
  
**System Requirements (How the App Will Perform)**  
  
**System Requirement** | **Description**  
--- | ---
**Scalability** | The app must support high traffic during widespread emergencies, ensuring it can handle spikes in user activity without performance degradation.  
**Data Privacy & Security** | The app must comply with data protection regulations, ensuring secure storage of user profiles, consumption data, and personal information.  
**API Integration** | The app should seamlessly integrate with external APIs (e.g., Flume, Phyn, municipal smart meter systems) to access real-time water usage data.  
**Platform Compatibility** | The app will be available for both Android and iOS platforms, ensuring accessibility on a wide range of devices, including low-end smartphones.  
**Offline Mode** | Offers functionality even when users are offline, allowing them to manually log their water usage and receive essential conservation tips.  
**User Accessibility** | The app will be designed with accessibility in mind, supporting multiple languages, large text options, and simple navigation for users with visual impairments or other disabilities.  
**Reliability** | The system must ensure 99.9% uptime during emergencies, with robust backend architecture to handle critical water conservation events efficiently.  
**Update & Patch Management** | The app should support easy and regular updates to improve functionality, add new features, and address any security vulnerabilities promptly.  
  
  
**Design Principles & Considerations**  
We are applying the following design principles to ensure the app’s usability and success, aligning with the insights gained from Phase 1:  
* **Simplicity**  
Research shows that clear, simple interfaces drive better user interaction. We are focusing on an intuitive design that minimizes cognitive load.  
* **Feedback**  
Residents tend to ignore ambiguous notifications. The app will deliver clear, actionable feedback on usage, fostering better decision-making.  
* **Accessibility**  
Based on feedback from various studies, our app will be designed with accessibility in mind, ensuring it can be used by people with visual impairments.  
* **Fail-Safe Defaults**  
Given the network issues identified in Phase 1, the app will include fail-safe defaults to ensure continued operation even when data is unavailable temporarily.  
  
**Transition to Phase 3:**  
The next stage is to convert the functional and system requirements into workable development tasks after a clear and well-supported set has been created.  Phase 3 will concentrate on organizing the project schedule, allocating priority, dividing each need into digestible components, and estimating effort.  This guarantees that every element of the WaterSaver program is monitored, effectively implemented, and in line with both user requirements and our overall objectives.  
  
**Phase 3: Task Breakdown & Priorities**  
**Introduction:**  
The high-level requirements acquired in Phases 1 (research and problem description) and 2 (functional and system requirements) are transferred to the actual implementation phase in Phase 3.  To guarantee efficient project execution, this entails dividing the requirements into manageable tasks, prioritizing them, and structuring them into manageable chunks.  This phase's activities will direct the creation and implementation of the WaterSaver app, guaranteeing that all features and functionalities complement the project's goals.  
  
**Goal:**  
This phase's objective is to transform the functional and system requirements established in Phase 2 into manageable tasks that will direct the WaterSaver app's development.  Each task should be divided into small phases, appropriately assigned, and planned for timely completion.  By doing this, we guarantee that the project is created in accordance with best practices, stays within scope, and stays on course.  
  
