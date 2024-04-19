# Knowledge check
Completed  
200 XP  
3 minutes  

Choose the best response for each question, then select Check your answers.

# Check your knowledge

## 1. What is not a good reason to create a pull request? 

You would like to receive feedback on prospective changes before merging your feature branch into main.

You want to merge your bug fix branch into main, but don't have permission.

Your branch can't be merged into main due to upstream changes made since you created it. Creating a pull request lets the other contributor know they need to pull their changes out so you can put yours in.
This isn't how pull requests work. Also, the etiquette is for you to be sure your branch can be cleanly merged into the base before creating a pull request.

## 2. How can you ensure that pull requests for a given area of the repository aren't merged unless certain users or teams approve? 

Clearly explain the pull request policy in CONTRIBUTING.md.

Use a CODEOWNERS file and enable required reviews.
A CODEOWNERS file enables you to assign users or teams as required reviewers using the same syntax as .gitingore files.


Add a table mapping directory paths to required users in SECURITY.md.

## 3. You've been requested to review a pull request. As you read through it, you notice several minor coding errors and typos. How should you handle the review? 

Start a review and fix obvious typos inline. Add comments in places that require further discussion or offer educational value. Complete the review with changes requested.
Contributors always appreciate when reviewers show an interest in getting their code merged.


Leave single comments for each issue you come across, but don't change the code. For typos, include the correct spelling of the word as a reference. Approve the pull request if you trust the author to implement your suggestions.

Reject the pull request. We can't risk any bugs accidentally being merged into an important branch.

# Next unit: Summary

