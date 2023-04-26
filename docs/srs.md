# Sofware Requeriments Document (SRS)

## Introduction

### Proposal

The purpose of this document is to describe the functional and non-functional requirements for Cognitive To-do, a task management tool designed to help users organize and complete their personal and professional tasks.

### Scope

This document covers the software requirements for the Cognitive To-do application, including its main functionalities, user interface features, performance and security requirements, and system constraints.

## System overview

### Product Perspective

Cognitive To-do is an application that enables users to create, organize, and manage tasks and task lists. It offers features such as account management and user authorization, a good performance, as well as an exceptional design.

## Functional Requirements

### 1. Accounts Management

1. Users should be able to create, edit, and delete their accounts.
2. Users must provide their full name, email, and password to create an account.
3. Users should be able to log in to access their data.

### 2. Task Management

1. Users should be able to create, edit, and delete individual tasks.
2. Users should be able to organize tasks into lists or categories.

## Non-Functional Requirements

### 1. Performance

1. The app should respond quickly to user actions and maintain high performance.
2. The app should be able to manage a large number of tasks without losing performance.

### 2. Security

1. User data must be securely stored using encryption and other security measures.
2. The app should require user authorization to access stored data and ensure user privacy.

### 3. Availability

1. The app must be available 24 hours a day, 7 days a week.
2. The app should be available in different Web Browsers.
3. The app must be available in different views, Desktop view and Mobile views, using Responsive Design.

### 4. Usability

1. The application should have an intuitive and easy-to-use user interface with clear and consistent visual elements throughout all views.
2. The application should provide clear and understandable error and confirmation messages to the user in case of problems or important actions.

### 5. System Restrictions

#### Supported Platforms

1. The application should be compatible with desktop operating systems such as Windows and macOS.
2. The application should be compatible with popular web browsers such as Google Chrome, Mozilla Firefox, Brave, and Microsoft Edge.

#### Technologies and Tools

1. The application should be developed using modern, widely used, and optimized technologies and tools.

#### Supported Languages

1. The application should be available in multiple languages, including English and Spanish.

### 6. Use Cases

1. Use Case 1: User creates an account
   * Actor: User
   * Description: The user creates a new account in the system.
   * Main Flow:
     * The user enters the account creation form.
     * The user enters their email and password as credentials for their account.
     * The user confirms the entered data and creates the account.
2. Use Case 2: User logs in to the system
   * Actor: User
   * Description: The user logs in to the system using the credentials of their account.
   * Main Flow:
     * The user enters the login form.
     * The user enters their account credentials (email and password).
     * The system authorizes the user.
     * The user logs in to the system with their account.
     * The user accesses the data saved or related to their account.
3. Use Case 3: User recovers their password
   * Actor: User
   * Description: The user recovers their "password" credential of their account.
   * Main Flow:
     * The user enters the password recovery form.
     * The user enters the email associated with their account.
     * The user receives a link to a view of the application where they can enter their new password.
     * The user enters the view.
     * The user enters their new password.
     * The system authorizes the user.
     * The user logs in to the system with their account.
     * The user accesses the data saved or related to their account.
4. Use Case 4: User creates a task
   * Actor: User
   * Description: The user creates a new task.
   * Main Flow:
     * The user enters the create task view.
     * The user enters the name, description (optional), and date (optional) of the task.
     * The task is added to the user's task list.
5. Use Case 5: User edits a task
   * Actor: User
   * Description: The user edits a task in their task list.
   * Main Flow:
     * The user selects the edit button on a task in their task list.
     * The user can edit the following details of the task: name, description, or date.
     * The user confirms the changes and makes them.
     * The system authorizes the user and makes the changes in the system.
6. Use Case 6: User deletes a task
   * Actor: User
   * Description: The user deletes a task from their task list.
   * Main Flow:
     * The user selects the delete option on a task in their task list.
     * The user confirms the action and deletes the task.
     * The system authorizes the user and makes the changes in the system.
