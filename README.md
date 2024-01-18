# OPEN-SOURCE-CONTRIBUTION-NOTE

How to start contributing to Open Source projects on GitHub
#tutorial
#opensource
#github
#programming

The software industry is unique in its reliance on open source projects. What started as a model that defied economic theory, has become the lifeblood of one of the most efficient and powerful technological spaces.

As such, contributing to open source projects is not just a great way to improve your coding chops, but also is an important part of giving back to the open source community which we rely on so heavily.

Contributing is not limited to coding, writing documentation, translations, and even simply informing about a bug that will count towards the betterment of the project. In this tutorial, we’ll be going over how you can get started contributing to open source projects on Github.

# Step 1: Fork the desired project
Now, You can’t simply download the project, make some modifications and upload the changes to an open-source project. There is a specific workflow one should follow when contributing to a project in GitHub. So let's look at the correct way to contribute. We will be using the GitHub first-contributions repository in this tutorial.

Forking will create a copy of the project in your own GitHub account. It allows the users to make any changes to the code while ensuring that these changes do not affect the original repository. Simply click the Fork button on the project repository.


# Step 2 - Clone the Project
Next, you need to clone your forked repo to your local machine to develop the project. Click on the Code icon and select your preferred cloning method. Here, we will use the HTTPS link with the git clone command.


Run the clone command in your local environment:

git clone <link to repo>

# Step 3 - Create A New Branch
The next step is to create a new branch to carry out your development. Navigate to the local folder of the cloned repository and use the git checkout command to create a new branch. For instance, we will create a branch called new-user-contribution.

git checkout -b new-user-contribution



# Step 4 - Develop, Stage, and Commit
In the new branch, you can use your favorite IDE, Text Editor, or any tools to make the necessary changes to the source code. We will simply add a new user to the Contributors.md file.
Then you need to stage these changes and commit the changes to the repository. Use the "git add ." to add the modified files and then the "git commit" command to commit the changes.

git add .\Contributors.md

git commit -m “Add XYZ to Contributors List”


# Step 5 - Push the Changes
The committed changes still reside only in your local environment. Therefore, you need to push these changes to the forked GitHub repository in your account. It can be achieved by using the git push command.


The workflow from git add, git commit to git push will be similar across all development environments. It is the standard way to deliver changes to any git repository regardless of the provider.

# Step 6 - Create a Pull Request
If pushing is successful, you should see a message indicating the new push with the "Compare and pull request" button when visiting the GitHub repository. Click on that button to make a pull request.



It will generate a pull request that directly targets the original repository. If you look at the request, you can see that the changes from the new-user-contribution branch of your forked repository will be merged to the master branch of the original repository.

It's generally a good practice to leave a comment indicating the changes or the reason for the pull request.


Finally, click on the "Create pull request" button to create the request. It will navigate the user to the newly created pull request in the original repository. In this case, the pull request will be created in the first-contributions repository.



That's it, and you have successfully contributed your changes to an open-source project. However, your changes are still not accepted and merged to the original repository. Your changes need to be first verified by the repository maintainers. They will only be merged into the repository after the maintainers approve the request.

Conclusion
