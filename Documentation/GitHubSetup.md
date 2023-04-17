# GitHub Guide for the DIMLab

GitHub is a website that serves as an online location to store Git repositories.
Git is a version control system that allows for robust collaboration across users.

## Getting Started

### Step 1: Create a GitHub Account

Navigate to [github.com](https://www.github.com) and sign up for an account.

### Step 2: Get Added to DIMLab GitHub Organization

This will be done by someone who already has access to the Organization along with admin privileges.

    Adding Someone to the GitHub Organization:
    - Navigate to the "Design of Innovative Machines Laboratory (DIMLab)" Organization on GitHub
    - Go to the "People" tab
    - Select "Invite Member" in the "People" tab
    - Enter the user's username or email

Once someone has invited you to the organization, check your email for an invitation. Follow the instructions in the email, and you should be added to the organization.

### Step 3: Get Added to a Team

Within a GitHub organization, people can be split into teams, much like a real life organization works. One person can be part of many teams. Being added to a team requires the intervention of a person with admin privileges.

    Adding Someone to a Team:
    - Navigate to the "Design of Innovative Machines Laboratory (DIMLab)" Organization on GitHub
    - Go to the "Teams" tab
    - Select the desired team
    - Within the team page, select "Add a Member"
    - Enter the user's username or email

Upon being added to a team, you should be able to see it in your view of the organization

### Step 4: Downloading and Installing GitHub Desktop

Git can be installed directly onto your computer, however using Git by itself can be difficult for new users. In order to make DIMLab projects more accessible, it is recommended to use GitHub's software called "GitHub Desktop". GitHub Desktop offers an intuitive and easy to use user interface.

To download GitHub Desktop, start off by navigating to [desktop.github.com](https://desktop.github.com/) and selecting "Download"

Upon downloading, open the .exe file and follow the instructions as they appear. Once installed and opened, GitHub Desktop should show a first time setup. Follow the instructions. Once complete, you should be signed into GitHub desktop with the same GitHub account you used for the GitHub organization.

## Using GitHub and GitHub Desktop

GitHub can be thought of like other cloud storage options, such as Google Drive or OneDrive, however it does not act like those services. GitHub repositories do not automatically appear in GitHub Desktop, and they do not sync automatically either. This provides a robust collaborative system that minimizes user conflicts and sync issues.

### Cloning a Repository

In order to add a repository to your local drive, you must first clone it from GitHub. This is done very easily in GitHub Desktop.

- Open GitHub Desktop
- Select "File" from the top menu
- Select "Clone Repository" from the "File" menu
- Scroll through the list of your repositories until you find the one that you want to clone
- Specify the path you would like to store the files at. Default is your desktop folder
- Select "Clone" and wait for GitHub Desktop to download the files

Once a repository is cloned, it should not need to be cloned again unless it is removed from your local system.

### Fetching

Fetching can be thought of like syncing with GitHub. Whenever you fetch, GitHub Desktop contacts the GitHub servers and checks for any changes. If no changes are detected, then no files will be downloaded. If changes are detected, GitHub Desktop will download the changes from the GitHub servers and implement them on your local system.

IMPORTANT: It is recommended that you fetch every time you're going to start making changes to a repository. This is a best practice to avoid merge issues and file conflicts.

- Open GitHub Desktop
- Check that you are on the correct repository in GitHub Desktop by checking the "Current Repository" option in the top left corner.
- Select the "Fetch Origin" option on the top bar of the user interface.
- If changes are detected, you will have to select "pull changes" to update your local copy of the repository

Once you have fetched changes and GitHub Desktop has updated your local copy, you are free to start working on the repository.

### Commiting and Pushing Changes

Just like fetching, in order to update the repository with the changes you made to your local copy, you must commit your changes and then push them.

Commiting changes allows for Git to store the changes you made to the repository locally.

- Open GitHub Desktop
- Check that you are on the correct repository in GitHub Desktop by checking the "Current Repository" option in the top left corner.
- On the left item bar, you should see a list of all the files you made changes to since you last commited.
- In the bottom left corner of the interface, enter a title for your commit in the section next to your profile picture. (Note: a description is optional)
- Once you have titled your commit, click "Commit to main"

At this point, you have saved the changes you made in Git. In order for your changes to show up, you need to push the changes to GitHub.

- In GitHub Desktop, locate the "push" button in the top bar of the user interface (should be located where the fetch button was).
- Select "push" and wait for GitHub Desktop to upload your changes to GitHub
- Open the repository on [github.com](https://www.github.com) and verify that your changes are showing up.

Now the changes you made to the repository have been successfully stored in the repository on GitHub. Other users will need to fetch and pull your changes before they appear on their local copy.

### Creating and Changing Branches

Branches are a feature in Git that allows for changes to be made independently of another branch. These branches can remain completely separate, or they can be merged later. Branches are perfect for experiments that may cause irreversible changes to files. Branches are also useful for separating production files from experimental files. Merging two branches can be a difficult process, so be aware of the challenges that will come when creating and modifying a branch.

Creating a branch in GitHub Desktop is very simple:

- Open GitHub Desktop
- Check that you are on the correct repository in GitHub Desktop by checking the "Current Repository" option in the top left corner.
- In the top bar of the interface, select the "Current Branch" option.
- In the dropdown, select "New Branch".
- Give your branch a name and then click "Create".

Now that you have created a branch, you can switch between branches:

- Open GitHub Desktop
- Check that you are on the correct repository in GitHub Desktop by checking the "Current Repository" option in the top left corner.
- In the top bar of the interface, select the "Current Branch" option.
- Select the desired branch.

You should now be working on the branch that you selected. Be aware of which branch you are working in before making changes.

## Managing the GitHub Organization

GitHub Organizations provide many tools that are useful.
Organizations can be split up into teams. This feature is useful because it organizes the members of an organization into the their respective groups. Using teams also streamlines the collaboration process for repositories.

### Creating a Team

- Navigate to the "Design of Innovative Machines Laboratory (DIMLab)" Organization on GitHub
- Go to the "Teams" tab
- Select "New Team"
- Enter the required Information

### Adding Members to a Team

- Navigate to the "Design of Innovative Machines Laboratory (DIMLab)" Organization on GitHub
- Go to the "Teams" tab
- Select the desired team
- Within the team page, select "Add a Member"
- Enter the user's username or email

Once a team is created, many parts can be assigned to it. The most important part is the repository.

### Creating a Team Repository

- Go to the "Teams" tab
- Select the desired team
- Within the team page, select "Repositories" in the top right corner.
- Select "Add a Repository"
- Enter the desired name of the repository

GitHub also provides a feature called "Projects". Projects allows for useful collaboration features such as communication, task distribution and management, and issue tracking.

### Creating a Project

- Navigate to the "Design of Innovative Machines Laboratory (DIMLab)" Organization on GitHub
- Go to the "Projects" tab
- Select "New Project"
- Enter the required Information

### Assigning a Project to a Team

- Navigate to the "Design of Innovative Machines Laboratory (DIMLab)" Organization on GitHub
- Go to the "Teams" tab
- Select the desired team
- Within the team page, select "Projects" in the top right corner.
- Select "Link a Project"
- Enter the name of the project you created.
