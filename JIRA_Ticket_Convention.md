# JIRA Ticket Creation Convention

This document outlines the conventions adopted by our team for creating tickets in JIRA, ensuring consistency and clarity across our projects.

## Contents

- [Introduction](#introduction)
- [Ticket Types](#ticket-types)
- [Epic Association](#epic-association)
- [Ticket Prioritization](#ticket-prioritization)
- [Using Labels](#using-labels)
- [Documentation of Tickets](#documentation-of-tickets)
- [Examples](#examples)
- [Conclusion](#conclusion)

## Introduction

Adopting a consistent ticket creation convention is crucial for the effective management and tracking of tasks, features, and bugs in our projects. This facilitates better understanding and handling of the project scope and issues among the team members.

## Ticket Types

When creating a ticket in JIRA, it is essential to specify the ticket type clearly to streamline our workflow and ensure proper categorization of tasks, features, and bugs.

### Types

- **BUG (`BUG`)**: Use this type when there's a regression or an issue stemming from a previously completed FEATURE or TASK.
- **FEATURE (`FEATURE`)**: This type is used for new functionalities, such as the creation of a new page or feature within the project.
- **TASK (`TASK`)**: Regular or maintenance tasks such as site updates or client-requested text changes fall under this category.

## Epic Association

Every ticket created must be associated with an epic. This ensures that all tasks, features, or bugs are tracked under a broader project goal, facilitating better project management and visibility.

### How to Associate an Epic

- When creating a new ticket, select the relevant epic from the 'Epic Link' dropdown menu in JIRA.
- If the appropriate epic does not exist, consult with the project manager before creating a new epic.

## Ticket Prioritization

It is important to prioritize tickets to ensure that critical issues and high-impact features are addressed promptly.

### Prioritization Levels

- **Critical**: Immediate action required. Affects major functionality with no workaround.
- **High**: Important issue affecting a feature with a workaround possible but not ideal.
- **Medium**: Issue affects a minor feature or has an easy workaround.
- **Low**: Non-critical issues that do not affect functionality or performance directly.

## Using Labels

Labels help in further categorizing and filtering tickets beyond types and epics. Use labels to indicate specific projects, technologies, or urgency.

### Suggested Labels

- `frontend`, `backend`, `database`: Indicates the area of the project affected.
- `urgent`: Marks tickets that require immediate attention.
- `enhancement`: Tags tickets proposing improvements rather than critical changes.

## Documentation of Tickets

Proper documentation within a ticket is crucial. It should include:

- A clear, concise title.
- A detailed description of the issue or feature.
- Steps to reproduce the issue, if applicable.
- Screenshots or logs if they help clarify the issue.

## Examples

Here are some examples to clarify the usage of each ticket type and the association with an epic:

- **Bug in login feature**: `BUG: Error in user authentication post password reset` - This ticket would be linked to the "User Authentication Enhancements" epic and marked `urgent`.
- **New user dashboard page**: `FEATURE: Create new dashboard page for user settings` - This ticket should be associated with the "Dashboard Improvements" epic and labeled `enhancement`.
- **Update website content**: `TASK: Update homepage text as per client's new requirements` - This task needs to be linked to the "Website Content Updates" epic.

## Conclusion

Following this convention is imperative for all team members involved in the project. It ensures that everyone is on the same page regarding how tasks are categorized and managed within JIRA, and how they contribute to broader project objectives. Should there be any confusion or a need for an exception to these rules, team members should consult with the project manager.

For further modifications or suggestions on these conventions, please discuss them during our regular team meetings or through direct communication with the project management team.
