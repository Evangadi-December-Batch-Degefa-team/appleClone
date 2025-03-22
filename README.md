GitHub Collaboration Guide for Team Degefa
Team Members:
I(Degefa Gomora)
A (Meaza Mulatu)
B (Gemechis Mulisa)
C (Woinshet Abate)
D (Mohammed Chane)
E(Eyale)
Table 1: Assigning Tasks & Creating Branches
Member	Task	Branch Name
A	Header	header
B	Footer	footer
E	First Section (MacBook Pro)	macbook-section
D	Second Section (iPhone 11 Pro)	iphone-section
A	Third Section (iPhone 11)	iphone11-section
B	Fourth Section - Left (Watch – Series 5)	watch-section
C	Fourth Section - Right (Card is here)	card-section
D	Fifth Section - Left (tv+)	tv-section
A	Fifth Section - Right (AirPods Pro)	airpods-section
B	Sixth Section - Left (MacBook Pro)	macbookpro-section
C	Sixth Section - Right (The new iPad)	ipad-section

STEPS:
Simple steps if you need
Step-by-Step Guide for Collaborating on "appleClone" (Header & Footer Tasks)
Since you are invited as a collaborator and assigned to work on the example  Header and Footer, follow these steps carefully to complete your tasks and submit them to the team leader.
1. Accept the Invitation & Clone the Repository
Before you start working, you need to accept the invitation from the team leader.
📍 Step 1: Accept the Invitation
Check your email or go to GitHub → Click on Notifications.
Find the invitation from the leader and accept it.
Now you have write access to the repository.
📍 Step 2: Clone the Repository
Once accepted, you need to copy the repository to your local computer.
-  git clone https://github.com/Degefa-Gomora/appleClone.git
This will download the project to your local machine.
Go inside the project folder:- cd appleClone
2️⃣ Create Branches for Header & Footer
Since you are working on two sections, create separate branches:
📍 Step 1: Create a Header Branch
- git checkout -b header
📍 Step 2: Create a Footer Branch
- git checkout -b footer
✅ Now you have two separate branches for each section.

3️⃣ Work on Your Assigned Tasks
📍 Step 1: Add Header Code
Open the project in VS Code or any text editor.
Edit index.html to add the header section.
Save the file.
📍 Step 2: Add Footer Code
Switch to the footer branch:
git checkout footer
Then edit index.html to add the footer.
✅ Your header and footer sections are now ready!
4️⃣ Stage, Commit, and Push Your Changes
Now, you need to save and send your work to GitHub.
📍 Step 1: Commit & Push the Header
Switch to the header branch:
git checkout header
Stage and commit:
git add index.html
git commit -m "Added Header section with navigation"
Push to GitHub: git push origin header
📍 Step 2: Commit & Push the Footer
Switch to the footer branch:
- git checkout footer
Stage and commit:
- git add index.html
- git commit -m "Added Footer section with copyright"
Push to GitHub:

- git push origin footer
✅ Now, your changes are available on GitHub.

5️⃣ Create a Pull Request (PR)
Now that your code is on GitHub, you need to request the team leader to merge your changes.
📍 Step 1: Open a Pull Request
Go to GitHub → appleClone → Pull Requests.
Click New Pull Request.
Select your header branch and compare it with main.
Add a title:- "Added Header section with navigation"
Add a description:- "Implemented the header section with navigation links"
Click Create Pull Request.
📍 Step 2: Repeat for the Footer
Create a second Pull Request for the footer branch.
Add a title:- "Added Footer section"
Add a description:- "Implemented footer with copyright info"
Click Create Pull Request.
✅ Now, your leader will review and merge your work.
6️⃣ Keep Your Repository Updated
Before working on any new task, make sure your local repository is up to date.
git checkout main
git pull origin main
This ensures you are working with the latest code.
🎯 Final Checklist
✅ Accepted the GitHub invite
✅ Cloned the repository
✅ Created branches for header & footer
✅ Implemented header & footer sections
✅ Committed and pushed changes
✅ Created pull requests
Once the team leader approves and merges your pull requests, your work will be part of the project!
Thank you in advance!Keep coding and Happy Coding!

Fork on top right---Create fork right bottom--hit code upper right--copy HTTPS URL---Goto folder where you wanna work in and open in vsc and open terminal or bash using Ctrl + `-----git clone paste copyed url---open the cloned folder alone in new vsc for clarity---open html,css,js and work your task-----then check status or what is done using git status or using source control icon in vsc or github desktop---git add . to staged or add all changes and files(This tells Git which files you want to include in the next commit.)---- git comit -m “First commit”(·  git commit saves the staged changes to the local repository;The -m "message" adds a descriptive message explaining what was changed.)---git push(git push sends your local commits to the remote GitHub repository.;This updates GitHub with your changes.)--
