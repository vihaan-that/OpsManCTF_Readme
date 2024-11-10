# OpsManCTF_Readme
ReadME file for the chakravyuh challenge



# OpsmanCTF - Challenge Instructions

Welcome to OpsmanCTF! Before you begin, please carefully read the following instructions.

## Getting Started

### Step 1: Familiarize Yourself with Git Basics
To navigate through the levels in this challenge, you’ll need to clone the repository and switch between different commits locally. If you’re new to this, please refer to the official documentation for your preferred platform:

- [GitHub Documentation](https://docs.github.com/en/get-started/quickstart)
- [Git Documentation](https://git-scm.com/doc)
- [GitLab Documentation](https://docs.gitlab.com/ee/topics/git/)

Once you've cloned the repository and are comfortable switching between commits, you're ready to dive into the levels.

### Step 2: Running Each Level
Each level is structured as a separate commit with a dedicated file. Here’s how to start each level:

1. **Navigate to the level's commit** (refer to the Git documentation above if you’re unsure how to do this).
2. Do the following after navigating to each level’s commit:
   ### navigate to the level folder and thenn run the command, replace x with the level number:
   ## USE WSL if you're on windows.
   ```bash
   ./levelx
   ```

4. Run the setup commands before beginning the level:
   ```bash
   npm install
   npm run dev
   ```

### Step 3: Solving the Levels
The challenge contains four levels:

- **Levels 1-3**: These levels are the initial stages and can be completed in any order, although they are arranged in increasing order of difficulty.
- **Level 4**: This level can only be accessed and completed after you've solved Levels 1-3.

In each level, you’ll uncover part of a 6-character flag. Each level will reveal **two characters** of the flag, which you’ll need to collect in sequence.

## Notes
1. Carefully solve Levels 1-3 to gather the first three parts of the flag.
2. Ensure all dependencies and configurations are correct by running `npm install` and `npm deploy` before starting each level.
3. Only proceed to Level 4 once Levels 1-3 are fully completed.

Good luck, and happy hacking!
