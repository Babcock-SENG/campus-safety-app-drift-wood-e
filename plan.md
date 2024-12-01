# Campus Safety App - Project Plan 

## Project Details
- **Title**: Campus Safety App - Project Plan  
- **Group Name**: Drift Wood-E  
- **Course**: SEN 201 - Introduction to Software Engineering  
- **Submission Date**: 02-12-2024  
- **Lecturer Name**: Mr. Awoniyi Amos  

## Team Members & Roles
- **Abara Henry Chiemezie (23/0238)**: Gantt chart  
- **Alex-Hope Chukwumeniem (22/2939)**: Requirement analysis  
- **Hussaini Fadil Olalekan (23/0004)**: Use case & scenario analysis  
- **Ikechukwu Chikamso Michael (23/0218)**: Risk analysis  
- **Nnah Samuel Enyinnaya (22/3801)**: Paper prototype  
- **Olomu Faith Kikelomo (23/0270)**: Software proposal  

---

## Requirements Analysis  

### Functional Requirements
1. **Emergency Response Features**:  
   - *Emergency Contact Access*: The system shall provide users with a list of emergency contacts and allow them to save emergency contacts, such as campus security, friends, and medical services.  
   - *Panic Button*: The system shall allow users to trigger an alert that notifies campus security during emergencies.  

2. **Real-Time Communication**:  
   - *Live Chat*: Shall enable real-time communication with campus security personnel and other students.  

3. **Safety Map**:  
   - *Safety Map*: Shall display a map highlighting safe zones, incidents, and security patrol routes on campus.  
   - *Geo-location Sharing*: Shall allow the user to share their real-time location with campus security during emergencies.  

4. **Broadcast System**:  
   - *Notifications and Alerts*: System shall allow campus security to send campus-wide security updates and emergency alerts to all users.  

### Non-Functional Requirements
1. **Performance**:  
   - Triggering the panic button and live chat should respond to user actions within 2 seconds.  
   - The map, even in high traffic, should load within 3 seconds.  

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
**Agile Methodology (Scrum)**  
- **Low Client Feedback**: Focus on iterative progress and flexibility, making changes based on team reviews and internal testing.  
- **Time Constraints**: Scrum's incremental deliveries allow the team to meet tight deadlines with regular outputs.  
- **Efficiency in Iterations**: Agile enables the team to work in manageable iterations, ensuring quick internal feedback and improvements.  

---

## Risk Analysis

| **Phase**            | **Risk**                                       | **Probability (1-5)** | **Impact (1-5)** | **RMMM**                                                                                 | **RE (Risk Exposure)** |
|-----------------------|-----------------------------------------------|-----------------------|------------------|-----------------------------------------------------------------------------------------|------------------------|
| **Requirement Gathering** | Ambiguous or incomplete requirements         | 3                     | 4                | Conduct detailed interviews with stakeholders, create clear and documented user stories | 12                     |
|                       | Inadequate user input from students           | 4                     | 3                | Gather continuous feedback through surveys or focus groups with target users            | 12                     |
| **Design**            | Inaccurate app design hindering usability     | 3                     | 4                | Iterative design approach with user testing, A/B testing, and prototyping              | 12                     |
|                       | Security design flaws                         | 2                     | 5                | Use secure coding practices, implement strong encryption, and conduct security audits  | 10                     |
| **Development**       | Inadequate API integration                    | 4                     | 4                | Collaborate closely with third-party services, regular integration testing             | 16                     |
|                       | Bugs in real-time map/location features       | 4                     | 5                | Thorough testing (manual and automated) of all map and location-related functionalities | 20                     |
| **Testing**           | Incomplete test coverage                      | 3                     | 5                | Comprehensive testing (unit, integration, and user acceptance tests)                   | 15                     |
|                       | Test environment mismatch with production     | 3                     | 4                | Replicate production environment during testing, conduct load and stress tests         | 12                     |
| **Deployment**        | Compatibility issues with devices/OS          | 3                     | 4                | Test on a range of devices and operating systems, use cross-platform tools             | 12                     |
|                       | Server downtime or failure during scaling     | 3                     | 5                | Use cloud services with scalability options, load balancing, and monitoring tools       | 15                     |
| **Maintenance**       | Lack of timely updates                        | 2                     | 5                | Set up regular update cycles, monitor security advisories, and apply patches quickly   | 10                     |
|                       | User data loss/corruption due to database issues | 3                   | 5                | Regular data backups, use transactional databases, and implement data recovery plans    | 15                     |

---

## Attachments
- Gantt chart  
- Use case diagram  
