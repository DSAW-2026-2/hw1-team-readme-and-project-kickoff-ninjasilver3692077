# PlayReal

PlayReal is a web application for private student groups that organize daily or weekly challenges. Participants can see the active challenge, upload a photo as evidence, vote for the best submissions, earn points, keep streaks, and view a group ranking.

## Problem

Student groups often organize challenges through WhatsApp, Instagram, or other messaging tools. This creates a specific problem: challenge evidence gets mixed with normal conversations, votes must be counted manually, and students do not have a clear way to see who participated, who received votes, or who is leading the ranking.

For example, if a group of Universidad de La Sabana students creates a daily creative challenge, the photos may be sent in a chat, reactions may be used as votes, and someone has to manually count results. After a few days, the group loses track of previous submissions, points, and participation streaks.

PlayReal solves the need for a centralized space where small groups of university students can manage challenges, evidence, voting, points, streaks, and ranking in one place.

## Web App Justification

PlayReal deserves to be a web application instead of a spreadsheet, WhatsApp group, or existing social tool for these concrete reasons:

1. **Structured challenge flow:** A web app can organize the complete flow `Group -> Challenge -> Evidence -> Voting -> Score -> Ranking`. A chat mixes all evidence with unrelated messages and does not separate each challenge clearly.

2. **Automatic voting and scoring:** A web app can validate one vote per user, prevent users from voting for themselves, calculate points automatically, and update rankings. A spreadsheet or WhatsApp group would require manual counting and is more likely to produce errors.

3. **Visual evidence and history:** A web app can show submissions as cards with photo, author, comment, vote count, and date. This creates an organized feed and history of previous challenges, which is difficult to maintain in a chat or spreadsheet.

4. **Private group experience:** A web app can support private groups with invitation codes, user roles, and group-specific rankings. Existing social networks are not designed for small private challenge competitions with points and streaks.

5. **Responsive access:** A web app can be used from a computer or phone browser without installing a native mobile app, which makes it realistic for a semester project and accessible for students.

## Target Users

The target users are **university students who participate in small private friend groups and want to stay motivated through visual challenges, evidence, votes, points, streaks, and a group ranking**.

Initial scope:

- Students from Universidad de La Sabana or similar university environments.
- Groups of friends or classmates.
- Small communities that already use chats to organize casual challenges.
- Users who prefer a simple and visual web experience.

The project is not initially aimed at public communities, companies, paid competitions, or massive social networks.

## User Stories

- **As a student group member, I want to create a private challenge group so that I can invite my friends and participate with them.**
- **As a participant, I want to see the active challenge so that I know what activity I need to complete and before when.**
- **As a participant, I want to upload a photo with a comment so that I can prove that I completed the challenge.**
- **As a participant, I want to vote for another member's submission so that the group can choose the best evidence fairly.**
- **As a participant, I want to see the group ranking so that I can know my position, points, completed challenges, and current streak.**

## Team Roles

- **Juan Esteban - Project lead:** Defines the problem, target users, user stories, AI log, and coordinates the project.
- **Andres - FrontEnd and design:** He is responsible for the creative and visual side of the project, focusing on user experience and frontend development.
- **Jorge - Backend deployment and database lead:** He designs the server-side logic and manages the data storage for the PlayReal platform.
- **Daniel - Feedback and testing lead:** He gathers user feedback and tests the PlayReal platform for usability and performance.

## Figma Sketch

Figma link: https://www.figma.com/make/N0d9HVxNgSnsa5966sK7Yv/PlayReal?t=gVXmmL1W3W2mxLKf-1

The sketch must show at least one annotated screen. The current planned screen is the **PlayReal Home Web**, which includes:

- Top navigation with project name and active group.
- Active challenge card with deadline and upload action.
- Personal progress card with completed challenges, streak, and ranking position.
- Recent submissions feed.
- Group ranking summary.
- Responsive mobile preview.

## Landing Page

GitHub Pages URL: https://dsaw-2026-2.github.io/hw1-team-readme-and-project-kickoff-ninjasilver3692077/

## AI Log

AI was used to support the initial organization of the project idea, problem statement, user stories, and delivery structure.

### Exact Prompt Used

> Help me define the problem, target users, and user stories for a web application called PlayReal, focused on group challenges with photo evidence, voting, points, streaks, and ranking.

### What Changed From The AI Generated Version

- The scope was reduced to a realistic MVP for a third-semester web development course.
- The target user was made more specific: university students in small private friend groups.
- Extra features such as private chat, payments, geolocation, artificial intelligence, public social networks, and complex minigames were removed from the first version.
- The interface direction was adapted from mobile app references into a responsive web dashboard.
- Team roles were assigned according to the needs of the first homework submission.

### Why These Changes Were Made

The changes were made to keep the project realistic for the semester, aligned with the course rubric, understandable for the team, and focused on the central MVP flow:

`Group -> Challenge -> Evidence -> Voting -> Score -> Ranking`