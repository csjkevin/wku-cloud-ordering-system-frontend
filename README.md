# WKU Canteen Ordering System Frontend

This is the repository for a senior capstone project - WKU Canteen Ordering System.

The project is frontend and backend separated. This repository is for the frontend of the system.

## Getting Started

### Install Dependencies

The packages of the project are managed by npm (Node Package Manager) or other node package managers such as yarn, pnpm, etc.

Before starting the project, you need to install dependencies.

`npm install`

If you have Node.js installed in your system, you should have the command of npm. If not, you can check [Node.js](https://nodejs.org/).

### Start the app

To start the app in the development mode, run:

`npm start`

Open [http://localhost:8000](http://localhost:8000) to view it in your browser.

The page will reload when you make changes.

You may also see any lint errors in the console.

## Deployment

To deploy the project, run:

`npm run build`

A production release will be packed into the `dist` folder.

It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.

Your app is ready to be deployed!

## Collaboration & Contribution Guideline

### Code Style

The code style must be unified with the project. If `prettier` is effective in the project, the code will be automatically formatted to the unified format defined in `.preitterrc`.

### Commit Message

The commit message must be in the following format:

```
<type>(<scope>): <short summary>
```

The `<type>` and `<summary>` fields are mandatory, the `(<scope>)` field is optional.

The type must be one of the following:

* **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
* **ci**: Changes to our CI configuration files and scripts (examples: CircleCi, SauceLabs)
* **docs**: Documentation only changes
* **feat**: A new feature
* **fix**: A bug fix
* **perf**: A code change that improves performance
* **refactor**: A code change that neither fixes a bug nor adds a feature
* **test**: Adding missing tests or correcting existing tests

## Additional Information

This project is based on React. To learn React, check out the [React documentation](https://reactjs.org/).

This project was bootstrapped with [UmiJS](https://umijs.org). You can learn more in the [UmiJS documentation](https://umijs.org/docs/getting-started).
