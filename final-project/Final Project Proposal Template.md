> This is an final project proposal template for INFO 441
> Put this as your README.md in your final project github repo

Final Project Website Link:

Final Project Github Repo Link:

# Group X's Final Project Proposal

This is the INFO 441 final project proposal for Group X.

By: Anthony Wen, // put your group members name

## Project Description

#### Who is your target audience? Who do you envision using your application? Depending on the domain of your application, there may be a variety of audiences interested in using your application. You should hone in on one of these audiences.

XXX

#### Why does your audience want to use your application? Please provide some sort of reasoning.

XXX

#### Why do you as developers want to build this application?

XXX

## Technical Description

### Architectural Diagram

![Architectural Diagram](proposal-img/arch-diagram.jpeg)

### Data Flow Diagram

![Data Flow Diagram](proposal-img/data-flow.jpeg)

### Summary Table for User Stories

| Priority | User Story                                            | Description                                                  | Technical Implementation                                                              |
| -------- | ----------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------------------------------- |
| P0       | As a user, I want to create an account and log in/out | Allows users to register, authenticate, and manage sessions. | Use Azure Authentication for login; store authenticated user profile in our database. |
| P0       | ...                                                   | ...                                                          | ...                                                                                   |
| P1       | ...                                                   | ...                                                          | ...                                                                                   |
| P1       | ...                                                   | ...                                                          | ...                                                                                   |
| P1       | ...                                                   | ...                                                          | ...                                                                                   |
| P1       | ...                                                   | ...                                                          | ...                                                                                   |
| P2       | ...                                                   | ...                                                          | ...                                                                                   |
| P2       | ...                                                   | ...                                                          | ...                                                                                   |
| P2       | ...                                                   | ...                                                          | ...                                                                                   |

Add or delete rows and Priorities (P0 P1) as needed

## API Endpoints

> Use this section to document all API routes in your project.  
> For each endpoint, include: method, path, purpose, and any required inputs/outputs.

- User

  - GET /user/login — Authenticates a user and begins a session.

- Resource A

  - GET /resourceA/:id/info — Retrieves detailed information for a specific item.
  - POST /resourceA/create — Creates a new item in the system.

- Resource B
  - GET /resourceB/:id/info — Retrieves information for a specific item or entity.
  - DELETE /resourceB/:id/info — Deletes an existing item or entity.
  - POST /resourceB/:id/info — Adds new data for an item or entity.
    - May include additional logic such as computed fields or database updates
  - PUT /resourceB/:id/info — Updates or modifies existing data.
  - GET /resourceB/:id/profile — Retrieves a profile or summary view for a given item.

Add or delete endpoints as needed

## Database Schema

- Users

  - UserID (number) — Unique identifier for each user.
  - Username (string) — Authentication or login identifier.
  - Role (string) — Determines permission level or access type.
  - AssociatedResourceID (string) — Links the user to another resource (optional).

- ResourceA

  - XXX
  - XXX

  Add or delete resources as needed

- ResourceB
  - XXX
  - XXX
