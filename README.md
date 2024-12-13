# learning-path-dashboard
Learning Path Dashboard Web App with progress tracking

Goal of the project is to make a learning path dashboard web app 
	Features
•	Two primary users: Instructor and Student
•	Instructor can design micro-courses by uploading content in the form of text, PDFs, links to external videos, etc 
•	As a method to try to maintain integrity of the platform, instructors must get their profile verified by the organisation they work for before publishing a course.
•	Students can enrol in courses
•	Live progress for a course is visible to both students and instructors too (this helps to provide timely feedback and correction from the instructor if needed)
•	Community page to facilitate peer engagement and support
•	“Marketplace” called recommending similar courses  

	Use cases
•	It can be used within educational institutions as a part of evaluation criteria 
•	Can also be used by volunteers/non-profit organizations to provide e-education to underprivileged children at low cost (since platforms like Coursera, Udemy, etc are paid and expensive)



To update changes to Git from local repository (if forgotten to pull beforehand) follow these steps:

(Run these commands in terminal in VSCode in the project folder)

1. Check your current git status
   
   👩🏻‍💻Run command: git status
   
   This will show you which files have been modified and need to be committed.
   


2. Pull Latest Changes
   
   Before you commit, you'll want to pull the latest changes from the remote repository. However, since you haven't updated Git yet and want to avoid any merge conflicts, first stash your local changes.
   
   👩🏻‍💻Run command: git stash

   
   
3. Pull Changes from the Remote Repository
   
   👩🏻‍💻Run command: git pull origin main



4.  Apply Your Stashed Changes
   
   👩🏻‍💻Run command: git stash pop
   
5.  Add and Commit Your Changes
    
   👩🏻‍💻Run commands:
   git add .
   git commit -m "Your commit message"

11. Push Your Changes (back to remote repository)
   👩🏻‍💻Run command: git push origin main
   This ensures that your local changes are safely added

