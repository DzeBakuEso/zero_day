# Setup Guide

Follow these steps to set up your project directory and initialize a Git repository.

## Steps

1. **Open Terminal**
    - On your computer, open a terminal.

2. **Navigate to Home Directory**
    - Use the following command to navigate to your home directory:
      ```sh
      cd ~
      ```

3. **Create a Directory `zero_day`**
    - Create a new directory named `zero_day` with the following command:
      ```sh
      mkdir zero_day
      ```

4. **Navigate to `zero_day` Directory**
    - Move into the newly created directory:
      ```sh
      cd zero_day
      ```

5. **Initialize Git and Add Remote Origin**
    - Initialize a new Git repository:
      ```sh
      git init
      ```
    - Add the remote origin (replace `your_remote_repository_url` with your actual remote repository URL):
      ```sh
      git remote add origin your_remote_repository_url
      ```

6. **Create `README.md` with Emacs**
    - Create a file named `README.md` using Emacs (or another command line editor, e.g., `nano`, `vim`):
      ```sh
      emacs README.md
      ```
    - Write a small Markdown text to present this project. For example:
      ```markdown
      # Zero Day Project

      This project is a demonstration of initializing a Git repository and managing files within it.
      ```

7. **Add the New File to Git**
    - Add the `README.md` file to the Git staging area:
      ```sh
      git add README.md
      ```

8. **Commit the Change**
    - Commit the change with the message “My first commit”:
      ```sh
      git commit -m "My first commit"
      ```

9. **Push to the Remote Server / Origin**
    - Push the committed changes to the remote repositor

