# Campus Safety App - Project Plan 

## Title: Campus Safety App - Project Plan  
- **Group Name**: Drift Wood-E  
- **Course**: SEN 201 - Introduction to Software Engineering  
- **Submission Date**: 02-12-2024  

## Team Members & Roles:
 
- **Alex-Hope Chukwumeniem (22/2939)**: Requirement analysis  
- **Hussaini Fadil Olalekan (23/0004)**: Use case & scenario analysis  
- **Ikechukwu Chikamso Michael (23/0218)**: Risk analysis  
- **Nnah Samuel Enyinnaya (22/3801)**: Paper prototype  
- **Olomu Faith Kikelomo (23/0270)**: Software proposal
- **Abara Henry Chiemezie (23/0238)**: Gantt Chart 

**Lecturer Name**: Mr. Awoniyi Amos  

---

## Requirements Analysis  

### Functional Requirements
1. **Emergency Response Features**:  
   - Emergency Contact Access: the system shall provide users with a list of emergency contacts and allow them to save emergency contacts, such as campus security, friends, and medical services.  
   - Panic Button: the system shall allow users to trigger an alert that notifies campus security during emergencies.  

2. **Real-Time Communication**:  
   - Live Chat: shall enable real-time communication with campus security personnel and other students.  

3. **Safety Map**:  
   - Safety Map: shall display a map highlighting safe zones, incidents, and security patrol routes on campus.  
   - Geo-location Sharing: shall allow the user share real-time location with campus security during emergencies.  

4. **Broadcast System**:  
   - Notifications and Alerts: System shall allow campus security send campus wide security updates and emergency alerts to all users.  

### Non-Functional Requirements
1. **Performance**:  
   - Triggering the panic button and live chat should respond to user actions within 2 seconds.  
   - The map, even in high traffic should load within 3 seconds  

2. **Reliability**:  
   - The system should be available 99.9% of the time, especially during emergencies.  

3. **Security**:  
   - Data transmissions, including location sharing and chat messages, should be encrypted to protect user privacy.  

4. **Usability**:  
   - The interface should be intuitive and easy to navigate, even during high-stress situations.  

5. **Scalability**:  
   - The app should handle increased user loads, such as during campus-wide emergencies.  

6. **Compatibility**:  
   - The app should work across iOS and Android devices with minimal performance differences.  

---

## Development Process Model
**For this project Agile methodology (Scrum to be specific) would be ideal because of its:**  
1. **Low Client Feedback**:  
   With low client involvement, Agile will allow us focus on iterative progress and flexibility. Changes can be made based on team reviews and internal testing rather than depending on external feedback.  

2. **Time Constraints**:  
   Agile is ideal for such a project that has a tight deadline as it emphasizes incremental deliveries. In Scrum, the project is divided into sprints (short cycles of work), and the team can focus on delivering a viable product early on.  

3. **Efficiency in Iterations**:  
   Agile will allow the team work in short, manageable iterations, delivering small chunks of the product at regular intervals. Which is essential as we need quick feedback internally to improve the product.  

---

## Risk Analysis  

| Phase               | Risk                                             | Probability (1-5) | Impact (1-5) | RMMM (Risk Mitigation, Monitoring, and Management)                                    | RE (Risk Exposure) |
|---------------------|-------------------------------------------------|-------------------|--------------|--------------------------------------------------------------------------------------|--------------------|
| **Requirement Gathering** | Ambiguous or incomplete requirements         | 3                 | 4            | Conduct detailed interviews with stakeholders, create clear and documented user stories | 12                 |
|                     | Inadequate user input of feedback from students  | 4                 | 3            | Gather continuous feedback through surveys or focus groups with target users         | 12                 |
| **Design**          | Inaccurate app design that hinders usability    | 3                 | 4            | Iterative design approach with user testing, A/B testing, and prototyping            | 12                 |
|                     | Security design flaws                           | 2                 | 5            | Use secure coding practices, implement strong encryption, and conduct security audits | 10                 |
| **Development**     | Inadequate API integration (for emergency contact, security updates) | 4            | 4            | Collaborate closely with third-party services, regular integration testing           | 16                 |
|                     | Bugs in real-time map or location features      | 4                 | 5            | Thorough testing (manual and automated) of all map and location-related functionalities | 20                 |
| **Testing**         | Incomplete test coverage                        | 3                 | 5            | Comprehensive testing (unit, integration, and user acceptance tests)                 | 15                 |
|                     | Test environment does not match production      | 3                 | 4            | Replicate production environment during testing, conduct load and stress tests       | 12                 |
| **Deployment**      | Compatibility issues with different devices or OS versions | 3            | 4            | Test on a range of devices and operating systems, use cross-platform tools           | 12                 |
|                     | Server downtime or failure when scaling app after deployment | 3           | 5            | Use cloud services with scalability options, load balancing, and monitoring tools     | 15                 |
| **Maintenance**     | Lack of timely updates to security patches or bug fixes | 2            | 5            | Set up regular update cycles, monitor security advisories, and apply patches quickly | 10                 |
|                     | User data loss or corruption due to database issues | 3                | 5            | Regular data backups, use transactional databases, and implement data recovery plans  | 15                 |


## Use case  diagram
[use-case diagram](/usecase.png)

## link to live site
https://babcock-seng.github.io/campus-safety-app-drift-wood-e/

