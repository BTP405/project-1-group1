[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/545oUMxH)

### Please use the following template to add a ReadMe for your repo.

## 1. Project Title and Description
    - Title: Budget Buddy
    - Description: A budget-management web application that helps you keep track of your expenses, providing extensive insights into your routine spending.
## 2. Installation
    - Dependencies: 
        - pip3 install -U Flask
        - pip3 install python-dotenv
        - pip3 install mongoengine
        - pip3 install certifi
        - pip3 install bcrypt
        - pip3 install pyjwt
        - pip3 install torch
        - pip3 install llama-index
    - Installation Instructions: Provide step-by-step instructions on how to install and set up your project.
    For backend:
        - Install all python dependencies
        - cd server
        - python3 main.py
    For frontend:
        - cd client
        - npm i
        - npm run dev
        - npm run tw:build
## 3. Usage
    To use the project open http://localhost:3000, when the project is running, you will see the home page. Navigate to the login/signup page from the header     and fill the fields needed. You will be redirected to the dashboard, from where you can analyse your spending routines, view, add, edit, delete         spendings. Click the user icon in the header to navigate to other pages. In profile, you can edit your budget, and view the user info. In the resources, you can find useful resources, and use AI search to find relevant articles. (Key usage screenshots are attached)
    ![image](https://github.com/BTP405/project-1-group1/assets/158524114/0e9b0e4d-121e-4213-8571-44dc836c5b08)
    (Sign Up)

    ![image](https://github.com/BTP405/project-1-group1/assets/158524114/0a8cb66d-b113-456e-925f-1b5150050859)
    (Dashboard)

    ![image](https://github.com/BTP405/project-1-group1/assets/158524114/9db9085b-ba92-4b2e-9114-feea0e96d970)
    (Spendings list)

    ![image](https://github.com/BTP405/project-1-group1/assets/158524114/c85f8214-dc79-43a7-b836-09c76281ab34)
    (Profile)

    ![image](https://github.com/BTP405/project-1-group1/assets/158524114/a4e56ef0-e6e5-43ad-8645-0eedbee435a7)
    (Resources)
## 4. Features
    - Login/Sign Up
    - Detailed spending statistics Dashboard, with graphs, and informative modules.
    - Spending record search and filtering
    - Spending records management (create, update, delete)
    - Budget update for various periods including monthly, weekly, and daily budgets
    - Useful budgeting resources with integrated AI search that will help to find the most relevant article

## 5. Contributing
    - If you want to contribute to our project, you are required to follow these guidelines:

## Workflow Conventions 📜

- All the source code is located in this repo. Backend code is located in `/server` and the Frontend code is located in `/client` respectively.
- All the sensitive information goes into `.env` file that is `.gitignore` 'd. It must not be shared within GitHub but rather via private communication channels.
- When you are working on a new feature, you create a new branch from `main` for it. After finishing the work, you make a Pull Request. Example of the branch name: `server/feature/authorization` or `client/bugfix/search-bar`

## Branch Naming Conventions 🌿
### To maintain an organized codebase, we adhere to the following branch naming conventions:


- New Features: `feature/<feature-name>`
- Bug Fixes: `bugfix/<bug-name>`
- Hot Fixes: `hotfix/<hotfix-name>`
- Releases: `release/<release-version>`
- Improvements: `improvement/<improvement-name>`
- Refactoring: `refactor/<component>`
- Documentation: `docs/<what-to-document>`
- Development: `develop (This is an ongoing branch where features are merged and tested)`
- Main Branch: `main (This is the default branch, often reflecting the production-ready state of our code)`

## GitHub Project Board 📌

- Board: View items from the current iteration and development progress
- Backlog: View all tasks that will be completed in the following iterations
- User Stories: View all User Stories and their descriptions
- My Tasks: View all Tasks assigned to @me

## 6. Credits
    - Authors: 
        - Vladyslav Huziienko
        - Maksym Volkovynskyi
        - Jimbert Manalo

## 7. License
    The project was not initially built as an open-source project, so it is not going to be distributed under any licence, only the end product will be available to the users.

