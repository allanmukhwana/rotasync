## Inspiration
Many organizations struggle to manage and coordinate the varying routines by different personnel within their departments. With the rise in remote working, the challenge is even greater! We believe in the power of technology to foster better communication and productivity in the workplace, so we created RotaSync!

## What it does
RotaSync is a transformative digital tool that enables departments to collaborate seamlessly on routines. At its core, it prompts team members to deliver their tasks on time via automated emails, maintains a checklist of tasks, provides a platform for team members to submit their reports and for supervisors to review and comment on these reports. It even grades the team's performance systematically in a period, ensuring everyone stays accountable for their roles. All this is managed through secure communication powered by Nylas API.

## How we built it
We leveraged the power of AI with the robust and secure Nylas APIs to build an email module within RotaSync. With it, we can disseminate routine tasks to respective team members concurrently while maintaining a checklist of tasks. We used different frameworks to manage the front end and back end of RotaSync, ensuring the system is user friendly and robust.

## Challenges we ran into
Synchronizing the system to send emails concurrently whilst creating a checklist of tasks was a significant challenge. Also, implementing an algorithm to systematically grade performance based on the total routines in a period required many iterations to get right.

## Accomplishments that we're proud of
We're proud to have developed a tool that alleviates some of the coordination and communication dilemmas faced by many organizations. Seeing RotaSync streamline the process of routine task management, from assigning of tasks to grading of performance, and making lives easier has been very fulfilling.

## What we learned
We learned that AI and communication APIs like Nylas can greatly transform the level of coordination and productivity within teams. We also learned that simplicity, relevance, and reactivity are key elements in designing a successful productivity tool.

## What's next for RotaSync - Elevate productivity, simplify routines!
We plan to make RotaSync even better! Our immediate goal is to introduce features like real-time collaboration, document sharing, and more advanced task tracking. Further ahead, we envision integrating RotaSync with other popular productivity tools whilst maintaining its core function as an independent solution that drives efficiency within any workspace.


# RotaSync User Documentation

## 1. Admin User

Admins primarily have the following responsibilities:

### Companies Setup:
Admin can create accounts for companies that have registered with RotaSync.

- Click on the "+" button on the Companies tab and fill in the forms.
- Validate and review information then save.

### Department Setup:
Admin can create and manage departments within companies.

- Click on the "+" button on the Departments tab.
- Fill in the department's name, company it belongs to, and its description.
- Validate and review information then save.

### Roles Setup:
Admin can establish roles within departments.

- Click on the "+" button on the Roles tab.
- Provide role name, assign it under a department, and provide a brief description.
- Validate and review information then save.

### Team Setup:
Admin can assign members to their respective roles within departments.

- Click on the "+" button on the Team tab. 
- Fill in team member's information, assign a role and department.
- Validate and review information then save.

### Supervisors Setup:
Admin can assign supervisors for monitoring the teams.

- Click on the "+" button on the Supervisors tab.
- Fill in supervisor's information, assign a department.
- Validate and review information then save.

## 2. Team Members

As a team member, you will receive daily emails listing the routines to be done for a particular period. Here's how to make the most of RotaSync.

### Checking Routines:
- Open the daily email from RotaSync.
- Click on the Report Link enclosed in the email and check the routines for the day.

### Submitting a Report:
- Once you have completed your routines, revisit the Report Link in the email.
- Input whether you completed the routine and any problems encountered.
- Remember to submit the report before the given deadline.

## 3. Supervisors

Supervisors are responsible for reviewing the submitted reports and providing comments.

### Review Reports:
- Go to the Reports tab.
- Browse through the submitted reports, displayed by team members and periods.

### Commenting on Reports:
- Click on a report for a detailed view.
- After reviewing, type your comments in the comment box if any.
- Click submit to update the report with your comments. 

Remember, supervisors cannot edit or delete a comment once it has been posted, so review before submitting your comment.
