# prog6001-A2
Assessment 2 Requirement for Git Work flow.

Team Member 1: Creating the Git Repository and Document
Create the Repository:
Go to GitHub and create a new repository.
Initialize it with a README or any other initial files if needed.
Add the HTML Document:
Create the HTML file provided earlier.
Commit this file to the main branch of the repository.
Team Members 2, 3, 4...:
Fork the Repository:

Visit the original repository on GitHub.
Click the "Fork" button on the top right to create a copy under your GitHub account.
Clone the Forked Repository:

Clone the forked repository to your local machine using Git.
bash
Copy code
git clone <forked_repository_url>
cd <cloned_repository_directory>
Make Distinct Changes:

Open the HTML file in a text editor.
Add your own section below the existing content. For example:
html
Copy code
<div class="intro">
    <!-- Your information here -->
    <img src="your_image_url_here.jpg" alt="Your Image" />
    <div>Name: Your Name</div>
    <div>Student ID: Your Student ID</div>
    <div>Email: your.email@example.com</div>
</div>
<div class="image-title">
    <h2>Your Section Title</h2>
</div>
<!-- Additional content -->
Commit Changes:

Add and commit your changes with descriptive messages.
bash
Copy code
git add .
git commit -m "Added my section: Name, Student ID, and Email"
Push Updates to GitHub:

Push your changes to your forked repository on GitHub.
bash
Copy code
git push origin main
Create a Pull Request:

Go to your forked repository on GitHub.
Click the "New pull request" button.
Compare changes and create the pull request to the original repository.
Merge Changes:

Once the pull request is reviewed and approved by the repository owner:
Merge the changes into the main codebase via the GitHub interface.
Documentation:
For documentation purposes:

Take screenshots at each step (forking, committing, creating pull request, merging).
Annotate these screenshots with clear descriptions of the actions taken.
Compile these screenshots and descriptions into a document explaining the workflow followed by each team member.
This documentation will serve as evidence of individual contributions and the collaborative workflow followed during the project.
