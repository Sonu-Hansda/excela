# Excela

**Excela** is a simple command-line tool to help developers easily set up their projects with a variety of configurations. Whether you're starting a backend, frontend, or full-stack project, **Excela** simplifies the process by guiding you through the setup of essential tools like **TailwindCSS**, **Vite**, and other useful utilities for modern web development.

## Features

- **Easy Project Setup**: Quickly initialize backend, frontend, or full-stack projects.
- **MERN Stack Setup**: Helps you set up a full MERN (MongoDB, Express, React, Node.js) stack with minimal effort.
- **Frontend Setup**: Initialize frontend projects using tools like **Vite** or **Create React App**.
- **TailwindCSS Integration**: Optionally include **TailwindCSS** for modern, responsive UI design.
- **Efficient Configuration**: Select your preferred tools and technologies during the setup process.

### Installation

You can use **Excela** in two ways:

1. Directly via `npx` (no installation required).
2. By installing it globally or locally with `npm`.

### Option 1: Using `npx` (Recommended for Quick Use)

Run the following command to use **Excela** without installation:

```bash
npx excela@latest
```

### Option 2: Install Globally or Locally

```bash
npm install -g excela
```

Once installed, you can run the tool using:

```bash
excela
```

### `npx excela@latest`

This command will walk you through setting up a project by asking you a few questions about your preferred tech stack. Based on your choices, it will:

- Set up **frontend** (with **Vite** or **Create React App**).
- Set up **backend** (Node.js or Express).
- Set up **full-stack** (MERN stack).
- Optionally include **TailwindCSS** for frontend styling.

## Setup Process

During the initialization, **Excela** will ask you a few questions to determine the configuration of your project. These include:

1. **Project Name**: The name for your new project.
2. **Tech Stack Choice**: Choose whether you want a **backend**, **frontend**, or a **full-stack (MERN)** setup.
3. **Frontend Setup**:
   - Select the build tool: **Vite** or **Create React App**.
   - Choose the project language: **JavaScript** or **TypeScript**.
   - Optionally add **TailwindCSS** for modern CSS styling.
4. **Backend Setup**: Choose whether you want a backend with **Express**.

Once the choices are made, **Excela** will create the project structure, install dependencies, and set up configuration files.

## Example Usage

After running the following command, you'll be prompted to make selections for your project:

```bash
npx excela@latest
```

### **Contributing**

If you'd like to contribute to **Excela**, feel free to submit a pull request! Here's how you can contribute:

1. Fork the repository.
2. Clone your fork locally.
3. Create a new branch for your changes.
4. Make your changes and commit them.
5. Push the changes to your fork.
6. Create a pull request from your fork to the main repository.
