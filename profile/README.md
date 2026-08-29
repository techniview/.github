# TechniView

TechniView is an LMS System that ties together LeetCode-style technical interview questions with a learning management system. It allows users to practice coding problems, track their progress, and learn new concepts in a structured way.

TechniView is designed to bridge the gap between learning and practical application. By combining a structured learning management system with a robust coding practice platform, it provides students with the tools they need to succeed in technical interviews and beyond. Whether you're a student looking to improve your coding skills or an instructor aiming to provide a comprehensive learning experience, TechniView has you covered.

## Problem Statement
Many people getting a degree in CS don't know how to do a LeetCode-style problem, let alone a whole technical or system design interview. While the University of Cincinnati has courses for Data Structures and Algorithms, and Design and Analysis of Algorithms, these classes do not help directly prepare CS students for the workforce. Data Structures and Algorithms focuses on making code that implements data structures and their underlying algorithms, but does not show how to use them. On the other hand, Design and Analysis of Algorithms takes abstract and theoretical problems, and asks how we could or would make an algorithm on paper, but never asks us to actually implement anything. There is an obvious gap; there is no class or preparation to bridge the application of these topics to the real-world use cases in interviewing, job performance, and overall understanding, which is hindering work preparedness.

## Key Features
- **Question Bank**: A large collection of coding problems categorized by difficulty and topic.
- **Assignments**: Students can be assigned specific problems or problem sets to complete within a given timeframe.
- **Custom Problems**: Instructors can create custom problems to tailor curriculum to students' need.
- **Custom Professor Set**: Professors can create their own problem sets and assignments tailored to their course content.
- **Progress Tracking**: Users can track their progress and see how they improve over time.
- **Professor Dashboard**: Instructors can create and manage problems and problem sets, assignments, and track student performance.
- **Student Dashboard**: Students can view their assignments, submit solutions, and see their performance metrics.
- **Built-in Code Editor**: Users can write and test their code directly in the platform without needing external tools.
- **Real-time Feedback**: Immediate feedback on code submissions, including test case results and performance metrics.

---

## Meet the Team:

<img src="https://avatars.githubusercontent.com/u/115371465?v=4&s=200" width="150" height="150" style="border-radius: 50%;" alt="Derek's Headshot">

### Derek Corniello

#### Biography:
5th year at the University of Cincinnati studying CS and SWE (via ACCEND). Interests include distributed systems, compilers, and programming languages. I have a passion for building complex systems, interesting backends, and tools that make developers' lives easier.

#### Contact Information and Links:
[![Email](https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMCA0SDRjLTEuMSAwLTEuOTkuOS0xLjk5IDJMMiAxOGMwIDEuMS45IDIgMiAyaDE2YzEuMSAwIDItLjkgMi0yVjZjMC0xLjEtLjktMi0yLTJ6bTAgNGwtOCA1LTgtNVY2bDggNSA4LTV2MnoiLz48L3N2Zz4=)](mailto:corniedj@mail.uc.edu)
[![derekcorn.dev](https://img.shields.io/badge/derekcorn.dev-2AC3DE?style=for-the-badge&logoColor=white&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCI+PGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMTAiLz48cGF0aCBkPSJNMTIgMmExNSAxNSAwIDAxNCAxMCAxNSAxNSAwIDAxLTQgMTAgMTUgMTUgMCAwMS00LTEwIDE1IDE1IDAgMDE0LTEwek0yIDEyaDIwIi8+PC9zdmc+)](https://derekcorn.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMjU2JyBoZWlnaHQ9JzI1NicgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJyBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSd4TWlkWU1pZCcgdmlld0JveD0nMCAwIDI1NiAyNTYnPjxwYXRoIGZpbGw9JyNmZmYnIGQ9J00yMTguMTIzIDIxOC4xMjdoLTM3LjkzMXYtNTkuNDAzYzAtMTQuMTY1LS4yNTMtMzIuNC0xOS43MjgtMzIuNC0xOS43NTYgMC0yMi43NzkgMTUuNDM0LTIyLjc3OSAzMS4zNjl2NjAuNDNoLTM3LjkzVjk1Ljk2N2gzNi40MTN2MTYuNjk0aC41MWEzOS45MDcgMzkuOTA3IDAgMCAxIDM1LjkyOC0xOS43MzNjMzguNDQ1IDAgNDUuNTMzIDI1LjI4OCA0NS41MzMgNTguMTg2bC0uMDE2IDY3LjAxM1pNNTYuOTU1IDc5LjI3Yy0xMi4xNTcuMDAyLTIyLjAxNC05Ljg1Mi0yMi4wMTYtMjIuMDA5LS4wMDItMTIuMTU3IDkuODUxLTIyLjAxNCAyMi4wMDgtMjIuMDE2IDEyLjE1Ny0uMDAzIDIyLjAxNCA5Ljg1MSAyMi4wMTYgMjIuMDA4QTIyLjAxMyAyMi4wMTMgMCAwIDEgNTYuOTU1IDc5LjI3bTE4Ljk2NiAxMzguODU4SDM3Ljk1Vjk1Ljk2N2gzNy45N3YxMjIuMTZaTTIzNy4wMzMuMDE4SDE4Ljg5QzguNTgtLjA5OC4xMjUgOC4xNjEtLjAwMSAxOC40NzF2MjE5LjA1M2MuMTIzIDEwLjMxNSA4LjU3NiAxOC41ODIgMTguODkgMTguNDc0aDIxOC4xNDRjMTAuMzM2LjEyOCAxOC44MjMtOC4xMzkgMTguOTY2LTE4LjQ3NFYxOC40NTRjLS4xNDctMTAuMzMtOC42MzUtMTguNTg4LTE4Ljk2Ni0xOC40NTNaJy8+PC9zdmc+&logoColor=white)](https://www.linkedin.com/in/derek-corniello)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/derekcorniello)
[![Resume](https://img.shields.io/badge/Resume-BB9AF7?style=for-the-badge&logo=readme&logoColor=white)](https://derekcorn.dev/resume.pdf)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@DerekCornDev)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/derekcorniello)

#### Experience:
- ENED TA (Fall 2023-Present)
- Siemens DISW: SWE Intern (Spring 2023-Fall 2025)
- Fifth Third Bank: SWE Intern (Spring 2026)
- LinkedIn: SWE Intern (Summer 2026)

Also check out [muxlang](https://github.com/muxlang), [hunch](https://github.com/DerekCorniello/hunch), [dia](https://github.com/DerekCorniello/dia), and my other links above for more of my work!

##### Technical Skills:
- Languages: Python, Go, Rust, Java, TypeScript, C++, SQL
- Development Tools: git, neovim, tmux, docker, Linux, AWS, Unity

##### Soft Skills:
Communication, Leadership, Teamwork, Problem Solving, Time Management

---

<img src="https://avatars.githubusercontent.com/u/youruseridhere?v=4&s=200" width="150" height="150" style="border-radius: 50%;" alt="Ryan's Headshot">

### Ryan Sippy

#### Biography:
...

#### Contact Information and Links:
...

#### Experience:
...

##### Technical Skills:
...

##### Soft Skills:
...

---

<img src="https://avatars.githubusercontent.com/u/youruseridhere?v=4&s=200" width="150" height="150" style="border-radius: 50%;" alt="Jason's Headshot">

### Jason Bellerjeau

#### Biography:
...

#### Contact Information and Links:
...

#### Experience:
...

##### Technical Skills:
...

##### Soft Skills:
...

---

<img src="https://avatars.githubusercontent.com/u/youruseridhere?v=4&s=200" width="150" height="150" style="border-radius: 50%;" alt="Jace's Headshot">

### Jace Shubert

#### Biography:
...

#### Contact Information and Links:
...

#### Experience:
...

##### Technical Skills:
...

##### Soft Skills:
...

---

<img src="https://avatars.githubusercontent.com/u/8715530?v=4" width="150" height="150" style="border-radius: 50%;" alt="Will's Headshot">

### William Hawkins
Our _AMAZING_ advisor! Check his work out on [GitHub](https://github.com/hawkinsw) or on [LinkedIn](https://www.linkedin.com/in/whh3/)

---

## Development Guidelines

### Branch Protection
- `main` is protected - all changes must go through PRs
- PRs require at least 1 approval before merge
- Squash and merge is the default merge strategy
- Branches auto-delete after merge

### PR Workflow
1. Create a feature branch from `main`
2. Make changes and commit
3. Open a PR for review
4. Get approval and squash merge

## Tech Stack

TBD

---

## Why TechniView?

Other similar systems exist, here is why TechniView is different:

### CodePath
[CodePath](https://www.codepath.org/employers/technical-interview-prep) is a free, non-profit organization that provides technical interview preparation courses for students. While it offers a structured curriculum and mentorship, it:
- Doesn't provide a comprehensive learning management system
- Doesn't have the ability to create custom problems and assignments.
- Doesn't offer real-time feedback on code submissions.
- Doesn't have a built-in code editor for users to write and test their code directly on the platform.

### LeetCode
[LeetCode](https://leetcode.com/) is a popular online platform for practicing coding problems, but it:
- Doesn't provide a structured learning management system for instructors to create and manage assignments.
- Doesn't offer the ability to create custom problems and assignments tailored to specific course content.
- Doesn't allow instructors to track student performance and progress over time.
- Keeps it's problem dataset restricted.
- Keeps it's performance metrics and feedback restricted;

### It is proven to be effective elsewhere
Other courses at other universities, such as [Stanford's CS9](https://web.stanford.edu/class/cs9/syllabus) and [Columbia's CS4995.007](https://www.cs.columbia.edu/fall-2022-topics-courses/#w4995.007) have successfully implemented courses that are backed by similar systems and curriculum. However, they do not include the customization and data tracking features that TechniView provides. TechniView aims to provide a more comprehensive and customizable solution for both students and instructors.
