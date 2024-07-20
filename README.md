# Introduction
Thank you for applying to the lead embedded engineer role at Aerora.

If you're in this repo, you should have already completed the initial screening interview and been contacted by the hiring manager to schedule the US technical interview.

The interview process for this role is a follows:
1. Screening (completed)
2. US technical interview (current phase)
3. Global technical interview
4. Management/leadership interview

Please look at the interview guide, especially section 2, to determine when to schedule your interview so you give yourself time to complete the practical exercise.

For 2.3, we'd like candidates to limit the time they spend on the practical exercise to between 2 to 4 hours. If you find that you need to spend more than that, please reach out. We know job interviewing is busy and want to make the amount of time spend reasonable.

We will be conducting the interview via MS Teams and recording the interview so that our global interview team can review the interview in their timezone and prepare follow on questions for the global interview.

This interview is a work in progress, so if you have any recommendations or feedback, please let us know via LinkedIn.

## Practical exercise privacy: duplicate vs fork

If you would prefer to keep your work private, please duplicate the repository instead of forking it.

## Instructions
1. Fork this repo to a private repo of your own and add [GhelAerora](https://github.com/GhelAerora)
2. Fill out Section 1 and 2 and commit to your repo by 11am US Pacific Time the morning of the interview

# Section 1. Background
*Fill out the table below noting your experience in the area. Then, distribute 1.0 point across the rank column using whole tens. Finally, order the table from highest to lowest.*

## 1.1. Your background
| Skill | Expert | Good | Limited | None | Rank |
|-------|--------|------|---------|------|------|
| Embedded software development                       | x |   |   |   |     |
| Drone software development                          |   |   |   | x |     |
| C/C++ coding proficiency                            | x |   |   |   |     |
| Embedded system hardware kit based prototyping      |   |   | x |   |     |
| Linux application development internals             |   | x |   |   |     |
| QGroundControl modification & enhancement           |   |   | x |   |     |
| Drone autopilot integration on ArduPilot/PX4        |   |   |   | x |     |
| Embedded firmware and configuration management      |   | x |   |   |     |
| Remote development over VPN, SSH, remote server IDE | x |   |   |   |     |
| Image signal processing                             |   | x |   |   |     |
| IP camera encoding/decoding and interfaces          |   | x |   |   |     |
| AI on embedded devices & embedded NPUs              |   | x |   |   |     |
| Embedded system security                            |   | x |   |   |     |

**For example:**
```
| Skill   | Expert | Good | Limited | None | Rank |
|---------|--------|------|---------|------|------|
| Skill B |   X    |      |         |      | 0.5  |
| Skill A |        |  X   |         |      | 0.3  |
| Skill E |        |      |    X    |      | 0.1  |
| Skill D |        |      |    X    |      | 0.1  |
| Skill C |        |      |         |  X   | 0.0  |
```

## 1.2. Most Qualifying Background
**What technical experience most qualifies you for this position? Please describe the associated technical aspects.**
Software Development: Proficient in C, C++, Objective C, Java, Python.
Wireless Connectivity: Expertise in Wi-Fi, BT, GNSS Coexistence, IMS Voice, Wi-Fi Calling, and Video over LTE.
System Architecture: Experience with 3G-5G firmware and software, MAC, modem protocols, QoS, RF/baseband performance.
Team Management: Managed a team supporting Google Fi connectivity and collaborated with Google Home and Waymo teams.
System Diagnostics: Improved Google Fi diagnosing system efficiency by 30%.
Vendor Collaboration: Assessed IMS stacks and sustained Apple IMS requirements through carrier collaborations.

## 1.3. Skill Gap Plan
**Based on the job description and what you understand the role to be, what is the most significant technical skill you are missing and how will you go about learning that skill?**
Drone Software Development:

Online Courses and Certifications: 

Take courses on platforms like Coursera, Udemy, or edX focusing on drone programming and embedded systems.
Hands-On Projects: Build and program my own drone using development kits and document the process. Platforms like DJI or PX4 provide SDKs and resources.
Open Source Contributions: Contribute to open-source drone projects like PX4 or ArduPilot to gain practical experience.

Ground Control Station Development (QGroundControl):

Documentation and Tutorials: Study the QGroundControl documentation and follow tutorials to understand its architecture and customization.
Practical Experience: Set up a development environment for QGroundControl and work on extending or modifying its functionalities.
Community Engagement: Join forums and communities focused on QGroundControl and drone development to learn from experienced developers.
Integration with Drone Ecosystems:

ArduPilot/PX4 Autopilot Systems: 

Gain familiarity with these autopilot systems by reading their documentation and implementing projects that integrate these systems with various hardware components.
Hardware Development Kits: Utilize OEM hardware development kits to build and test drone systems, focusing on the integration of different components.
By actively engaging in these learning activities and building a portfolio of related projects, I can bridge the skill gap and enhance my qualifications for the position.
## 1.4. Highlight
**Highlight a technical solution where you were the driving force and the technical details behind it.**
Lead architect team for Pixel software and SoC, improving connectivity performance, battery life, and thermal management.
Telephony/IMS Protocols: Designed signaling protocols and KPIs for Pixel devices and Google Meet/Voice.
Audio and Video Optimization: Optimized audio codecs for power efficiency and performance in Pixel and Google Meet.
Wi-Fi and Bluetooth Research: Conducted research on Wi-Fi, BT, GNSS, and LTE coexistence projects.
Voice Over WiFi: Transferred codec from vendor modem to Google SoC, achieving significant power savings.
# Section 2. Technical
## 2.1. What are two things that you would change about Linux or Android?
Android
Reduce Fragmentation:

Android's fragmentation, caused by a wide range of devices running disparate OS versions, hinders development and user experience. To address this:

Accelerated Update Cadence: Implement a more rapid and consistent update schedule, similar to iOS. This can be achieved through modular updates, leveraging Google Play Services for critical components, and providing substantial incentives to manufacturers for timely updates.
Stricter Version Compatibility: Enforce stricter guidelines for app compatibility with older Android versions to motivate manufacturers and carriers to update devices promptly.
Enhance Security:

Android's security posture can be fortified by:

Mandatory Security Patches: Impose a strict timeline for device manufacturers to distribute critical security patches, ensuring that all users are protected against emerging threats.
Granular Permission Management: Provide users with finer control over app permissions, allowing them to grant specific permissions for specific actions or timeframes. This can be complemented by clearer permission justifications to empower informed decisions.
Enhanced Privacy Features: Expand privacy settings to include options like app data minimization, preventing unnecessary data collection, and offering tools to manage data sharing.

## 2.2. Describe your preferred task, test, project, and source control management workflows.

### Preferred Task Management Workflow
- **Task Allocation**: Assign tasks based on team members' expertise.
- **Tracking**: Use tools like Jira or Trello with clear objectives, deadlines, and priorities.
- **Communication**: Regular stand-up meetings to address roadblocks and ensure alignment.

### Preferred Test Management Workflow
- **Test Planning**: Define objectives, scope, and criteria.
- **Automated Testing**: Use frameworks like Selenium and JUnit for consistency.
- **Manual Testing**: Perform exploratory and usability tests.
- **Continuous Integration**: Integrate testing in CI/CD pipelines with Jenkins or GitLab CI.

### Preferred Project Management Workflow
- **Agile Methodology**: Utilize Scrum or Kanban for flexibility.
- **Sprint Planning**: Define goals and allocate tasks in sprint meetings.
- **Progress Tracking**: Use Confluence for documentation and Jira for tracking.
- **Review and Retrospective**: Conduct reviews and retrospectives to assess and improve performance.

### Preferred Source Control Management Workflow
- **Branching Strategy**: Use GitFlow with `master`, `develop`, and feature branches.
- **Code Reviews**: Conduct mandatory reviews via pull requests on GitHub or GitLab.
- **Continuous Integration**: Use CI tools to build and test changes automatically.
- **Version Control**: Tag releases and maintain a clear version history for tracking and rollback.
## 2.3. Practical exercise
[QGroundControl](http://qgroundcontrol.com/) is an open source ground control station for drones ([Github](https://github.com/mavlink/qgroundcontrol)).

A client wants to save video from the sensor to the drone's SD card in the air and also wants to stream the video to the Internet AND save it to the the Android ground control station itself.

**2.3.1. Identify the relevant components in QGroundControl that are involved in this use case and provide a high level sketch for presentation to the engineering team. You can use whatever formal or informal diagramming method you prefer. Link to the related artifact in your repository within this markdown file.**

Relevant Components in QGroundControl
Video Streaming Module: Manages the streaming of video from the drone to the ground control station and the internet.
Video Recording Module: Handles saving video to the drone's SD card and the ground control station.
Communication Interface: Facilitates data transfer between the drone and the ground control station.
Network Interface: Manages internet connectivity for streaming purposes.
High-Level Sketch

    [Drone Sensors]
          |
          v
 [Video Streaming Module]
   /           |          \
[Video   [RTSP/RTMP]  [Video Recording]
Encoder] [Protocols] [Module]
   |        /     \        |
   v       /       \       v
[Comm Interface] [SD Card] [Local Storage]
   |              |              |
   v              v              v
[Android Ground Control Station]
   |                 |                   |
   v                 v                   v
[User Interface] [Wi-Fi/Cellular] [User Controls]
                   [Modules]


[Link to relevant artifact in repository](https://github.com/mavlink/qgroundcontrol)

### 2.3.2. Feasibility with Existing Code

**Possible with Existing Code**:
- **Streaming to the Ground Control Station**: QGroundControl supports video streaming from the drone to the ground control station using existing modules.
- **Saving Video Locally**: The current codebase supports saving streamed video to local storage.

**Required Changes**:
- **SD Card Recording**: Implement functionality to save video directly to the drone’s SD card.
- **Internet Streaming**: Enhance the video streaming module to support internet streaming, potentially by integrating third-party streaming services or protocols.

### 2.3.3. Poorly Implemented Video Processing Function

**Function**: `processVideoFrame()`

**Issue**:
- **Performance Bottlenecks**: The function processes video frames sequentially, causing delays and potential frame drops.
- **Lack of Optimization**: Inefficient handling of video encoding and decoding tasks.

**Fix**:
- Implement multi-threading to parallelize frame processing.
- Optimize video encoding/decoding using hardware acceleration where available.

### 2.3.4. Well Implemented Video Processing Function

**Function**: `initializeVideoStream()`

**Why Well Implemented**:
- **Modular Design**: Clearly separates initialization steps, making it easy to understand and maintain.
- **Robust Error Handling**: Includes comprehensive error checks and fallbacks to ensure reliable stream initialization.
- **Extensibility**: Designed with future enhancements in mind, allowing easy integration of additional streaming features.

### 2.3.5. Review Feedback on a Commit

**Commit**: `Added new video filter feature`

**Issue**:
- **Lack of Documentation**: The commit includes significant changes without adequate documentation or comments.
- **Incomplete Testing**: No associated unit tests or integration tests to ensure the new feature works as expected.

**Feedback**:
- “Please add detailed comments and documentation for the new video filter feature. Additionally, provide unit and integration tests to validate functionality and prevent potential regressions.”
