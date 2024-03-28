# Exercise - Code with Codespaces and Visual Studio Code
Completed  
100 XP  
5 minutes  
Now that you understand the Codespaces lifecycle and processes, it's time to practice coding in Codespaces and Visual Studio Code (VS Code). Follow the instructions below to complete this exercise.

## Instructions
1) Right-click the GitHub exercise link to open it in a new tab.
2) On the GitHub Exercise Welcome page, right-click the Start course button to open it in a new tab.
    - In the new tab, most of the prompts automatically fill in for you.
    - For owner, choose your personal account or an organization to host the repository.
    - We recommend creating a public repository, as private repositories use Actions minutes.
3) Scroll down and select the Create repository button at the bottom of the form.
4) After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README.

### When you finish the exercise in GitHub, return here to:

 - Complete a knowledge check.  
 - Review a summary of what you learned in this module.  
 - Earn a badge for completing this module.  


# Code with GitHub Codespaces and Visual Studio Code
## Develop code using GitHub Codespaces and Visual Studio Code!

# Step 1: Create your first codespace and push code
Welcome to "Develop code using GitHub Codespaces and Visual Studio Code"! 👋

**What's the big deal about using a codespace for software development?** A codespace is a development environment that's hosted in the cloud. You can customize your project for GitHub Codespaces by committing configuration files to your repository (also known as configuration-as-code), which creates a repeatable codespace configuration for all users of your project. Each codespace you create is hosted by GitHub in a Docker container that runs on a virtual machine. You can choose the type of machine you want to use depending on the resources you need.

GitHub offers a range of features to help your development team customize a codespace to reach peak configuration and performance needs. For example, you can:

- Create a codespace from your repository.
- Push code from the codespace to your repository.
- Use VS Code to develop code.
- Customize the codespace with custom images.
- Manage the codespace.

To begin developing using GitHub Codespaces, you can create a codespace from a template or from any branch or commit in a repository. When you create a codespace from a template, you can start from a blank template or choose a template suitable for the work you're doing.

⌨️ Activity: Start a codespace
We recommend opening another browser tab to work through the following activities so you can keep these instructions open for reference.

1) Start from the landing page of your repository.

2) Click the green Code button located in the middle of the page.

3) Select the Codespaces tab in the box that pops up and then click the Create codespace on main button.
    - Wait about 2 minutes for the codespace to spin itself up. Note: It's a virtual machine spinning up in the background.

4) Verify your codespace is running. The browser should contain a VS Code web-based editor and a terminal should be present such as the below:
![207355196-71aab43f-35a9-495b-bcfe-bf3773c2f1b3](https://github.com/pranjal779/MS-GitHub/assets/50409572/c4727aed-3950-4066-acaf-108f6e2df2cb)

⌨️ Activity: Push code to your repository from the codespace
1) From inside the codespace in the VS Code explorer window, select the index.html file.

2) Replace the h1 header with the below:

   <h1>Hello from the codespace!</h1>

3) Save the file.

    Note: The file should autosave.

4) Use the VS Code terminal to commit the file change by entering the following commit message:
```
git commit -a -m "Adding hello from the codespace!"
```

5) Push the changes back to your repository. From the VS Code terminal, enter:
```
git push
```
6) Your code has been pushed to your repository!

7) Switch back to the homepage of your repository and view the index.html to verify the new code was pushed to your repository.

8) Wait about 20 seconds then refresh this page (the one you're following instructions from). GitHub Actions will automatically update to the next step.

## Next unit: Knowledge check
