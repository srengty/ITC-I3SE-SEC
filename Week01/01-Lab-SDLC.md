<div style="margin-bottom: 20px;">
<div class="header" style="background-color: #26679cff;">
    <h3>Software Engineering Concepts</h3>
    <h4>SE - Lab 01</h4>
</div>
</div>
<div style="text-align: right; font-style: italic; margin-bottom: 20px;">
    <p>Start date: <span style="color: #26679cff;">24 October, 2025.</span><br>
    Due date: <span style="color: #26679cff;">29 October, 2025.</span> </p>
</div>

# Lab Overview
This lab is designed to introduce you to the fundamental concepts of Software Engineering, focusing on the Software Development Life Cycle (SDLC).

# Practical Example: Attendance System Using Java
Let's apply each SDLC phase to develop an attendance system using Java:

## 1. Requirement Analysis
- **Functional Requirements**: 
    - Record student attendance (present/absent)
    - Generate attendance reports
    - Manage student database
    - Calculate attendance percentage
- **Non-functional Requirements**:
    - System should handle 500+ students
    - Response time < 2 seconds
    - Data security and backup

## 2. Design
- **Architecture**: MVC (Model-View-Controller) pattern
- **Database Design**: 
    - Students table (id, name, email, course)
    - Attendance table (student_id, date, status)
- **UI Design**: Swing-based desktop application
- **Class Design**: Student, Attendance, AttendanceManager classes

## 3. Implementation (Coding)
```java
public class Student {
        private int studentId;
        private String name;
        private String course;
        // constructors, getters, setters
}

public class AttendanceManager {
        public void markAttendance(int studentId, boolean isPresent) {
                // Implementation logic
        }
        
        public double calculateAttendancePercentage(int studentId) {
                // Calculate and return percentage
        }
}
```

## 4. Testing
- **Unit Testing**: Test individual methods using JUnit
- **Integration Testing**: Test database connectivity
- **System Testing**: Test complete workflow
- **User Acceptance Testing**: Teachers validate the system

## 5. Deployment
- Package application as JAR file
- Install on school computers
- Configure database connections
- Train users on system usage

## 6. Maintenance
- Monitor system performance
- Fix bugs reported by users
- Add new features (SMS notifications, mobile app)
- Regular database backups and updates

# Your Tasks to Complete
Answer the following questions based on the SDLC phases and the practical example provided above.

## Questions
1. What is the purpose of the Requirement Analysis phase in the SDLC?
2. How does the Design phase contribute to the overall success of a software project?
3. Why is Testing considered a critical phase in the SDLC?
4. What are the key activities involved in the Deployment phase?
5. How does Maintenance ensure the long-term success of a software application?

## Analysis Questions
There are many ways to take the attendance of the students, such as:
- Manual attendance sheet
- Biometric systems (fingerprint/iris scan)
- RFID attendance systems
- Mobile apps for self-check-in
- QR code-based attendance

Choose any two methods and compare them based on the following criteria:
1. Accuracy
2. Ease of Use
3. Implementation Cost
4. Time Efficiency
5. Student Privacy

Provide a brief analysis of the advantages and disadvantages of each method you choose.

# Submission Guidelines
- Submit your answers in a well-formatted document (PDF or Word).
- Include code snippets where applicable.
- Ensure clarity and conciseness in your explanations.