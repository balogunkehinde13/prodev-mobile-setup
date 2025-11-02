# 🏗️ Project Scaffolding and Setup Log

This document details the steps taken to initialize and configure the React Native project using the Expo framework, along with observations from common cleanup commands.

---

## 🛠️ Scaffolding an Expo App

This section outlines the commands executed to create the project structure.

### Steps Followed for Scaffolding an Expo App

1.  **Ensured Node.js and npm are installed** on the development machine.
    * Command to check: `node -v` and `npm -v`

2.  **Used the `create-expo-app` utility** to initialize the new project:
    ```bash
    npx create-expo-app@latest prodev-mobile-app-0x00
    ```
    * *Note:* The `@latest` flag ensures the most recent version of the tool is used.

3.  **Navigated into the newly created project directory:**
    ```bash
    cd prodev-mobile-app-0x00
    ```

4.  **Started the development server** to confirm the initial blank app runs correctly in Expo Go:
    ```bash
    npx expo start
    ```

---

## 🧹 Observations from the `reset-project` Command

The `reset-project` script is often used in Expo tutorials to quickly reset a project back to a clean state by removing example files and boilerplate code after the initial setup.

### Command Execution

The command executed to reset the project was:
```bash
npm run reset-project