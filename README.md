# MERN Authentication

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/ttran375/mern-auth)

The repository contains:

* Distributed code from **eCentennial** used to build a **MERN Authentication** application.
* `/.devcontainer`: Configuration file used by **Codespaces** to determine operating system.
* `/.vscode`: Configuration file used by **Codespaces** to configure Visual Studio Code settings.
* `/client/.eslintrc`: Settings for [ESLint](https://eslint.org/) included for code consistency and quality.
* `/client/.prettierrc`: Settings for [Prettier](https://prettier.io/) used to format code.
* `package.json` and `yarn.lock`: Defines the application information for [Node.js](https://nodejs.org/), dependent packages, and the versions needed for each.

## Getting Started

Select **Open in GitHub Codespaces** and then **Create codespace**. **GitHub** will prepare the development environment with all installed dependencies.

### Update .env File

Reference the example provided `client/.env.example` to create `client/.env`.

```.env
MONGODB_URI=mongodb+srv://your_user:your_password@your_cluster.mongodb.net/YourDatabase?retryWrites=true&w=majority&appName=YourApp/yourcollection
```

### Start the Server

After setting up the environment variables, change directory to `client` and start the server.

```sh
cd client
yarn dev
```

Navigate to `http://localhost:5173/` to register an account and sign in.
