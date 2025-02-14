# Codecatalyst Learning


<details> 
  <summary> <h2>Introduction</h2></summary> 

### What is Git?
Git is a distributed version control system that allows developers to track changes in their code, collaborate with others, and manage different versions of their projects efficiently. It enables multiple developers to work on the same project simultaneously while keeping a history of all modifications.

### Why Use Git for Version Control?
- **Collaboration**: Git makes it easy for teams to collaborate on projects without overwriting each other's work.
- **Version History**: It maintains a history of changes, allowing you to revert to previous versions if necessary.
- **Branching and Merging**: Git supports branching, enabling developers to work on features independently and merge changes seamlessly.
- **Performance**: Most operations are performed locally, making them quick and efficient.

</details>

<details>
  
 <summary> <h2>Setting Up Git</h2> </summary>

### Install Git on Your Computer
To install Git, visit the official download page: [Download Git](https://git-scm.com/downloads).

### Configure Git
After installing Git, configure it with your username and email:
1. Open Git Bash.
2. Run the following commands:
    - git config --global user.name "Your UserName"
    - git config --global user.email "Your Email"

For detailed instructions, refer to this article: [How to Set Up Git Using git config](https://www.geeksforgeeks.org/how-to-set-up-git-using-git-config/).

</details>

<details>
<summary> <h2>Getting Started with Git in VS Code</h2> </summary>

### Setting Up GUI Git in VS Code
To integrate Git with Visual Studio Code, follow this guide: [How to Install Git in VS Code](https://www.geeksforgeeks.org/how-to-install-git-in-vs-code/).

</details>

<details>
  
<summary> <h2>Working with Repositories</h2> </summary>

1. **Create a Repository**
    - Create a repository named `codecatalyst-learning` on your system:
      ```
      mkdir codecatalyst-learning
      cd codecatalyst-learning
      git init
      ```

2. **Push Your Repository to GitHub**
    - After creating your local repository, push it to GitHub.

      ![Screenshot 2025-01-05 182630](https://github.com/user-attachments/assets/cc601e2c-2c61-422c-a200-7cddcefc14cd)


3. **Clone a Sample Repository**
    - Clone any sample repository onto your system and upload the screenshot in your README file.

      ![Screenshot 2025-01-05 183052](https://github.com/user-attachments/assets/96052dde-239f-4127-8ce9-e259fb55af8a)

</details>

<details>
  
<summary> <h2>Basic Git Operations</h2> </summary>

1. **Add a Sample File**
    - Create a sample file (e.g., `README.md`) and stage it.

2. **Make Changes and Check Status**
    - Edit the file and check the status.

3. **Commit Changes**
    - Commit the staged changes with a meaningful message.

4. **Push Changes**
    - Push your committed changes to the GitHub repository.

      ![Screenshot 2025-01-05 183637](https://github.com/user-attachments/assets/6b4532b3-3d88-43cd-b4ab-2b80f4eba463)

</details>

<details>
  
<summary> <h2>Branching and Collaboration</h2> </summary>

1. **Create a Branch**
    - Create a branch named `secondary-branch`.

2. **Switch to the Branch**
    - Switch back to the `main` branch or any other branch as needed.

      ![Screenshot 2025-01-05 184102](https://github.com/user-attachments/assets/9735aa0c-75dd-4f36-b2ba-deab8c40f757)

</details>

<details>
  
<summary> <h2>Merging Changes</h2> </summary>

1. **Merge the New Branch**
    - Merge `secondary-branch` into `main`.

2. **Simulate a Merge Conflict**
    - Edit the same file in both branches, then resolve any conflicts that arise.

      ![Screenshot 2025-01-06 1054151](https://github.com/user-attachments/assets/5d5e1436-315e-4c7b-8649-b8e17aa85198)
      ![Screenshot 2025-01-06 105433](https://github.com/user-attachments/assets/5a54e483-546c-4f84-9863-7a49186ebfe8)

</details>
