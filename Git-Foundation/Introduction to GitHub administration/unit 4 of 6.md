How does GitHub organization and permissions work?
Completed
100 XP
10 minutes
In the previous unit, you explored the different ways that users can authenticate themselves with GitHub. In this unit, you'll learn about permissions for each hierarchical level:

Repository permissions
Team permissions
Organization permissions
Enterprise permissions
Repository permission levels
You can customize access to a given repository by assigning permissions. There are five repository-level permissions:

Read - Recommended for non-code contributors who want to view or discuss your project. This level is good for anyone that needs to view the content within the repository but doesn't need to actually make contributions or changes.
Triage - Recommended for contributors who need to proactively manage issues and pull requests without write access. This level could be good for some project managers who manage tracking issues but don't make any changes.
Write - Recommended for contributors who actively push to your project. Write is the standard permission for most developers.
Maintain - Recommended for project managers who need to manage the repository without access to sensitive or destructive actions.
Admin - Recommended for people who need full access to the project, including sensitive and destructive actions like managing security or deleting a repository. These people are repository owners and administrators.
You can give organization members, outside collaborators, and teams different levels of access to repositories owned by an organization. Each permission level progressively increases access to a repository's content and settings. Choose the level that best fits each person or team's role in your project without giving more access to the project than necessary.

After you create a repository with the correct permissions, you can make it a template so that anyone who has access to the repository can generate a new repository that has the same directory structure and files as your default branch. To make a template:

On GitHub.com, go to the main page of the repository.

Under the repository name, select Settings. If you can't see the Settings tab, open the dropdown menu and then select Settings.
<img width="720" alt="repository-actions-settings" src="https://github.com/pranjal779/MS-GitHub/assets/50409572/0388b030-4f36-45e9-95c7-10352d1213d4">

Select Template repository.

Team permission levels
Teams provide an easy way to assign repository permissions to several related users at once. Members of a child team also inherit the permission settings of the parent team, providing an easy way to cascade permissions based on the natural structure of a company.

There are two levels of permissions at the team level:
![image](https://github.com/pranjal779/MS-GitHub/assets/50409572/0905a87a-2471-444a-94e2-79d895be4f84)

An organization owner can also promote any member of the organization to be a maintainer for a team.

To audit access to a repository that you administer, you can view a combined list of teams and users with access to your repository in your settings:
![manage-access-overview](https://github.com/pranjal779/MS-GitHub/assets/50409572/04418e18-2642-4679-b346-74cd8b0f6898)

Organization permission levels
There are multiple levels of permissions at the organizational level:
![image](https://github.com/pranjal779/MS-GitHub/assets/50409572/7153773a-0557-4490-ae90-d5ae75446562)

In addition to these levels, you can also set default permissions for all members of your organization:
<img width="615" alt="org-base-permissions" src="https://github.com/pranjal779/MS-GitHub/assets/50409572/d46c1a48-3e9a-4e45-a654-085f320a7a67">


For improved management and security, you might also consider giving default read permissions to all members of your organization and adjusting their access to repositories on a case-by-case basis. If you have a relatively small organization with a low number of users, a low number of repositories, or a combination of the two, this level of restriction might be unnecessary. If you trust everyone with pushing changes to any repository, you might prefer to give all members write permissions by default.

## Enterprise permission levels
Recall from earlier that enterprise accounts are collections of organizations. By extension, each individual user account that is a member of an organization is also a member of the enterprise, and you can control various settings related to authentication from this higher level.

There are three levels of permission at the enterprise level:
![image](https://github.com/pranjal779/MS-GitHub/assets/50409572/568dd322-3785-4206-be67-1b485315aa88)

In addition to these three levels, you can also set a policy of default repository permissions across all your organizations:
<img width="577" alt="enterprise-base-permissions" src="https://github.com/pranjal779/MS-GitHub/assets/50409572/704790f3-6ef6-49b7-82cd-6f4a5a01757c">

For improved management and security, you can give default read permissions to all members of your enterprise and adjust their access to repositories on a case-by-case basis. In a smaller enterprise, such as one with a single, relatively small organization, you might prefer to trust all members with write permissions by default.

## Repository security and management
You can oversee the security and management of your repositories in several ways.

## Create protection rules
To manage changes to content within your repository, you can create branch protection rules to enforce certain workflows for one or more branches. Protection rules that can be applied to a branch include:

- Require a pull request before merging.
- Require status checks to pass before merging.
- Require conversation resolution before merging.
- Require signed commits.
- Require linear history.
- Require merge queue.
- Require deployments to succeed before merging.
- Lock the branch by making it read-only.
- Restrict who can push to matching branches.

Additionally, you can set branch rules that apply to everyone, including administrators. For example, you can allow force pushes to matching branches and allow deletions from users who have push access.

## Add a CODEOWNERS file
By adding a [CODEOWNERS](https://docs.github.com/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-code-owners#codeowners-syntax) file to your repository, you can assign team members or entire teams as code owners who are responsible for code in the repository. When someone opens a pull request that modifies code that belongs to a code owner, the code owner is automatically requested as a reviewer.

You can create the CODEOWNERS file in either the root of the repository or in the docs or .github folder.

View traffic by using Insights
Anyone who has push access to a repository can view its traffic. In the traffic graph, they can view full clones (not fetches), visitors from the past 14 days, referring sites, and popular content.

To access the traffic graph:

1) On GitHub.com, go to the main page of the repository.

2) Under your repository name, select Insights.
<img width="720" alt="repository-navigation-insights-tab" src="https://github.com/pranjal779/MS-GitHub/assets/50409572/7f944dc4-370c-4ecf-8eb7-cf6479cec909">
3) On the left, select Traffic.
<img width="152" alt="traffic-tab" src="https://github.com/pranjal779/MS-GitHub/assets/50409572/545bcaf9-44cc-412f-9f98-bb45e8eee6d2">

4) Optionally, you can select Clones or Views to see the traffic graph for clones or views.

## Next unit: Knowledge check
