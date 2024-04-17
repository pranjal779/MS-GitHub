# Knowledge check
Completed  
200 XP  
3 minutes  
Choose the best response for each question, then select Check your answers.  

## Check your knowledge

### 1. What's the best way to make sure you're integrating the most secure versions of your project dependencies? 

Configure your package files to always use the latest versions of dependencies.

{wrong answer}
Check each project's security details closely before adding it to your dependencies by confirming its version status across multiple advisory sites.
Even if this practice helps you start off with a secure version of a given dependency, it won't ensure that you're safe from future vulnerabilities. You would need to constantly monitor every package to ensure compliance, which might be infeasible.

{correct answer}
Enable Dependabot for your repository.
Dependabot scans your repository's dependency manifests and notifies you via pull request whenever a version you rely is marked as insecure.

### 2. Suppose one of your source projects relies on secrets kept in a folder called .secrets. You would like to make sure that the files kept in this folder on development machines aren't inadvertently committed to the repository. Which of these files best helps enforce this policy? 

SECURITY.md

.gitignore
.gitignore can be used to help enforce which files are included in commits by tools that respect it. However, the client enforces this policy and doesn't necessarily prevent users from committing files that violate policy.


CONTRIBUTING.md

### 3. What does secret scanning do? 

Looks for known secrets or credentials committed within the repository.
This approach is done to prevent the use of fraudulent behavior and to secure the integrity of any sensitive data.


Analyzes and finds security vulnerabilities and errors in the code in a GitHub repository.

Secret scanning uses CodeQL to query your code as data.

## Next unit: Summary
