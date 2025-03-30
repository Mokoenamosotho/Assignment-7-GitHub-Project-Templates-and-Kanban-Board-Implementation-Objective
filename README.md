# Assignment-7-GitHub-Project-Templates-and-Kanban-Board-Implementation-Objective

Customization Choices

In this section, we explain the customizations made to the Kanban board to better align with the needs of the AI-Driven Automated Database Recovery project for Western Cape Hospitals. These adjustments ensure that the project tracking process supports both Agile methodologies and specific project requirements.

1. Added ‘Testing’ Column
Reason:
The addition of the Testing column allows the team to track tasks that are under review or testing. This is crucial for ensuring that system components, such as AI-powered failure prediction models and data recovery mechanisms, are thoroughly tested before being moved to production.

Benefit:
By adding this column, we create a clear distinction between development tasks and testing activities. This ensures that issues can be traced and resolved before a feature is considered "Done." The Testing phase also ensures that the final system performs to specifications and that QA activities are given their due focus.

Example Task:

Test AI Model for Failure Prediction: Task to evaluate the prediction model's accuracy using historical data.

2. Added ‘Blocked’ Column
Reason:
The Blocked column is added to manage tasks that cannot proceed due to dependencies or unresolved issues. These could include tasks that are waiting on third-party approvals, external tools, or critical infrastructure updates.

Benefit:
Having a dedicated Blocked column enables better visibility of project blockers, helping the team address delays quickly. It serves as a visual indicator to both the team and project manager when there are hindrances to progress, ensuring no task is forgotten or left behind.

Example Task:

Setup Data Encryption: Blocked due to pending approval of encryption keys.

3. Use of Agile-Friendly Columns
Reason:
The basic Kanban board includes essential columns such as To Do, In Progress, and Done, which are well-suited for Agile workflows. These columns represent key stages in the lifecycle of tasks.

Benefit:

To Do: Tasks awaiting attention are visible to all team members.

In Progress: Current tasks are tracked to ensure that they are actively being worked on.

Done: Completed tasks can be quickly reviewed, helping ensure accountability and visibility.

These basic columns help support Agile principles by providing transparency, adaptability, and a structured workflow that allows tasks to progress smoothly.

4. Automation Features
Reason:
For tasks like Automated Data Recovery, the team will benefit from automation. As part of the customization, we opted to enable GitHub’s Project Automation features (if applicable) to ensure that tasks move across the board when certain conditions are met.

Benefit:
Automation ensures that the Kanban board stays up-to-date without requiring manual intervention. This helps maintain focus on critical tasks while reducing administrative overhead. For instance, tasks related to pull requests (PRs) or issue resolutions will automatically be moved when PRs are merged or issues are closed.

5. Custom Task Assignment and @Mentions
Reason:
Each task on the board is linked to a specific team member via @mentions. This is done for accountability and clear ownership. The use of @mentions within the tasks ensures that the right person is notified of the task and can quickly act upon it.

Benefit:
This approach ensures that team members are always aware of their responsibilities, and they can easily check which tasks need their attention. It also encourages collaboration by allowing immediate feedback or requests for clarification from others on the team.

Conclusion
By customizing the Kanban board with the Testing and Blocked columns, as well as utilizing GitHub’s automation and assignment features, the team is empowered to effectively manage tasks, ensure clear visibility, and quickly adapt to any changes or blockers during the implementation of the AI-Driven Automated Database Recovery system.

This approach will streamline the process, helping the project stay on track while maintaining a clear view of progress, potential risks, and upcoming needs.