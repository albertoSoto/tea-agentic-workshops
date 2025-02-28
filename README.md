# tea-agentic-workshops

## Getting Started with Magnolia CLI v5

This guide will help you set up your development environment for Magnolia using CLI version 5.

### Prerequisites
- Node.js installed on your system
- npm (Node Package Manager)

### Installation Steps

1. Install Magnolia CLI globally using npm:
```bash
npm install @magnolia/cli -g
```

2. Verify the installation:
```bash
which mgnl    # Shows the path where mgnl is installed
mgnl -V       # Shows the installed version
```

### Creating a New Project

1. Create and enter a new directory for your project:
```bash
mkdir mgnl
cd mgnl
```

2. Initialize a new Magnolia project:
```bash
mgnl jumpstart
```
Follow the prompts to configure your project according to your needs.

3. Install dependencies:
```bash
yarn
```
or if you prefer npm:
```bash
npm install
```

4. Start the development server:
```bash
mgnl start
```

Your Magnolia project should now be running locally!

## Presentations

This repository includes Marp presentations about agentic workflows and modern development practices. You can find them in the `slides` directory.

### Available Presentations
- [Agentic Workflows: The Case of Junie](slides/agentic-workflows.md) - A hands-on session covering:
  - AI-powered development workflows
  - Magnolia Light Development (20min workshop)
  - Sanity.io Integration (20min workshop)

For instructions on how to view or export the presentations, please refer to the [slides README](slides/README.md).

## Updating from CLI v4
If you're using Magnolia CLI version 4 and need to update to version 5, please follow the instructions in [UPDATE_MAGNOLIA_CLI.md](UPDATE_MAGNOLIA_CLI.md).
