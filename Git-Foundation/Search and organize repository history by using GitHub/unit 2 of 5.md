# How to search and organize repository history by using GitHub
Completed  
100 XP  
8 minutes  
Here, we'll discuss how you can use filters, blame, and cross-linking to search and organize repository history.

Put yourself in the position of a developer who has just joined a large project. Someone just posted a new issue reporting a bug related to the web app's sidebar, and you've been assigned to fix it. You've already read through the report a few times and understand the problem being described, so now you need to figure out how to get started with the fix.

As a new team member, you're not yet familiar with the codebase. You also haven't been part of the planning discussions, code reviews, or anything else that would provide you with the context you need to start implementation. You'll first need to acquire that background knowledge to best determine the right fix.

# Searching GitHub
Although you weren't around for the events that led to the sidebar's implementation, many of those events live on in the project's history. Searching the project's repository for "sidebar" will give you a starting point.

There are two search methods available on GitHub: the global search at the top of the page and the scoped search available on certain repository tabs. They support the same syntax and function in the same way, but with some key differences.

# Global search
The global search lets you use the complete search syntax to search across all of GitHub.
![2-global-search](https://github.com/pranjal779/MS-GitHub/assets/50409572/dc6cf5ae-9572-4b20-8cd9-3031d9ac47b6)

The search results are comprehensive and include everything from code to issues to the Marketplace (and even users). This is the best way to find mentions of key terms across multiple result types and repositories.
![2-global-search-results](https://github.com/pranjal779/MS-GitHub/assets/50409572/e3479666-dcca-4e38-bdb9-e4b081cf8b60)

 **!Note**

The filter clause is:pr filters out issues returned from the issues/pull requests store. Some filter clauses, such as is:pr, are only supported by certain search providers and ignored by others. For example, the code-search provider doesn't support that clause, so it will ignore it and return the same code results either way.

In our scenario, using the global search scoped to the current repository is a good way to find code and commits that mention the term "sidebar". You'll also likely get hits for issues and pull requests, although they're not as easy to filter further in the global search results view.

To craft a complex global search, try the advanced search.

# Context search
Context searches are available on certain tabs, such as Issues and Pull requests. These searches are scoped into the current repository and only return results of that type. The benefit to this scoping is that it allows the user interface to expose known type-specific filters such as authors, labels, projects, and more.
![2-context-search](https://github.com/pranjal779/MS-GitHub/assets/50409572/7acc2e7d-30b4-40f9-a930-7e1fe933ca5a)

Using the context search is the preferred option when you're looking for something in the current repository. In our scenario, this is a good way to find search results mentioning "sidebar," which you could then easily refine using the filter dropdowns.

# Using search filters
There are an infinite number of ways to search using the complete search syntax. However, most searches only make use of a few common filters. While these are often available from context search dropdowns, it's sometimes more convenient to type them in directly.

Here are some example filter queries:
![image](https://github.com/pranjal779/MS-GitHub/assets/50409572/a5f215d5-ef75-482a-8c35-f584f60e5f77)

Learn more about Understanding the search syntax

# What is git blame?
Despite its ominous name, git blame is a command that displays the commit history for a file. It makes it easy for you to see who made what changes and when. This makes it much easier to track down other people who have worked on a file in order to seek out their input or participation.

 **!Note**

Some Git systems alias git praise onto git blame to avoid the implication of judgment.

# Blame in GitHub
GitHub extends the basic git blame functionality with a more robust user interface.
![2-github-blame](https://github.com/pranjal779/MS-GitHub/assets/50409572/e8199e5f-7e03-4ad7-b4a6-f1cab4e10d51)
In our scenario, there are a few ways you might get to this view. You might've found some sidebar code from the global search and selected the Blame option to see who worked on it last, or maybe you found a pull request and tracked that back to the last commit that seems related to the bug description. However you got here, the blame view is an effective way to locate a subject matter expert for the task at hand.

# Cross-linking issues, commits, and more
Part of what makes GitHub great for collaborative software projects is its support for linking disparate pieces of information together. Some of this happens automatically, such as when you create a pull request from a series of commits on a branch. Other times, you can use the interface to manually link pull requests or projects to issues using the dropdown options.

# Autolinked references
To make it even easier to cross-link different items throughout your project, GitHub offers a shorthand syntax. For example, if you leave a comment like Duplicate of #8, GitHub will recognize that #8 is an issue and create the appropriate link for you.
![2-autolinked-issue](https://github.com/pranjal779/MS-GitHub/assets/50409572/bdd20b56-5809-4535-b6b2-bc3a5eda5fd8)

GitHub also links commits for you if you paste in the first seven or more characters of its ID.
![2-autolinked-commit](https://github.com/pranjal779/MS-GitHub/assets/50409572/0758cf88-c901-41fb-bac2-4d777228304a)

In our scenario, these links could prove very valuable for ramping up if someone thought ahead to leave the context. For example, the sidebar's current state might have had some known issues related to a JavaScript dependency. If the issue with that dependency was discussed in another issue that didn't explicitly mention "sidebar," then it would be difficult to find. However, if someone had thought ahead to link the issue in the discussion, then it could save you a lot of time now. Keep that in mind the next time you're documenting issues and pull requests.

Learn more about Autolinked references and URLs.

# Looping in users with @mention
Besides linking issues and commits, it's often helpful to associate other people with discussions. The easiest way to do this is by using an @mention. This kind of mention notifies the mentioned user so that they can participate in the discussion. It's also a good way to identify people associated with issues long after they have been closed.
![2-user-mention](https://github.com/pranjal779/MS-GitHub/assets/50409572/9d5d8589-3b37-4ecc-8970-54e30fcfa37a)


# Next unit: Exercise - Connect the dots in a GitHub repository
