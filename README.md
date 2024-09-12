# Property Hive Backend API

## Project Overview

Live link is at 

Doc link at 

## Installation Instructions
### Prerequisites

Before setting up the project locally, ensure you have the following prerequisites installed:

- Node.js and Express.js
- A Database System (e.g., PostgreSQL, MySQL, SQLite)

### How to run API Locally

1. Clone the repository:
```bash
git clone git@github.com:entsoereng/Property-Hive-Backend-Express.git
```

2. Change into the parent directory:
```bash
cd Property-Hive-Backend-Express
```

3. Set appropriate values for the following Compulsory Environment Variables:
```txt
# Postgres connection string
POSTGRES_DSN=""
# Secret key for signing JWTs
JWTKEY=""
```

3. Install dependency:
```bash
npm install
```
4. Start the App:
```bash
npm start
```

The API should now be running locally at [http://localhost:3000/](http://localhost:3000/).


# Commit Standards

## Branches

- **dev** -> pr this branch for everything `backend` related
- **main** -> **dont touch** this branch, this is what is running in production!

## Contributions

Property-Hive-Backend-Express is open to contributions, but I recommend creating an issue or replying in a comment to let us know what you are working on first that way we don't overwrite each other.

## Contribution Guidelines

1. Clone the repo `git clone git@github.com:entsoereng/Property-Hive-Backend-Express.git`.
2. Open your terminal & set the origin branch: `git remote add origin git@github.com:entsoereng/Property-Hive-Backend-Express.git`
3. Pull origin `git pull origin Dev`
4. Create a new branch for the task you were assigned to, eg `TicketNumber/(Feat/Bug/Fix/Chore)/Ticket-title` : `git checkout -b BA-001/Feat/Sign-Up-from`
5. After making changes, do `git add .`
6. Commit your changes with a descriptive commit message : `git commit -m "your commit message"`.
7. To make sure there are no conflicts, run `git pull origin Dev`.
8. Push changes to your new branch, run `git push -u origin feat-csv-parser`.
9. Create a pull request to the `Dev` branch not `main`.
10. Ensure to describe your pull request.
11. > If you've added code that should be tested, add some test examples.


# Merging
Under any circumstances should you merge a pull request on a specific branch to the `Dev` or `main` branch

### _Commit CheatSheet_

| Type     |                          | Description                                                                                                 |
| -------- | ------------------------ | ----------------------------------------------------------------------------------------------------------- |
| feat     | Features                 | A new feature                                                                                               |
| fix      | Bug Fixes                | A bug fix                                                                                                   |
| docs     | Documentation            | Documentation only changes                                                                                  |
| style    | Styles                   | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc.)      |
| refactor | Code Refactoring         | A code change that neither fixes a bug nor adds a feature                                                   |
| perf     | Performance Improvements | A code change that improves performance                                                                     |
| test     | Tests                    | Adding missing tests or correcting existing tests                                                           |
| build    | Builds                   | Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)         |
| ci       | Continuous Integrations  | Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs) |
| chore    | Chores                   | Other changes that don't modify, backend or test files                                                    |
| revert   | Reverts                  | Reverts a previous commit                                                                                   |

> _Sample Commit Messages_

- `chore: Updated README file`:= `chore` is used because the commit didn't make any changes to the backend or test folders in any way.
- `feat: Added plugin info endpoints`:= `feat` is used here because the feature was non-existent before the commit.
