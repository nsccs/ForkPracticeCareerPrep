### Hello everyone and welcome to our Club fork-practice repository! 
<br></br>
This is a generalized Git Workflow to help gain the skills to collaborate on open source projects.

1. Follow the instructions below
2. Create your changes either in the GitHub or locally
3. Submit changes in a PR to the original repo
<br></br>

Questions or thoughts? <a href="https://discord.gg/xfeXTySSbX" target="_blank">Connect with us on Discord</a>.

> For an overview of terminal commands check out this <a href="https://www.youtube.com/watch?v=UDlIJkvOOPw&list=PL6k4gMRDdFjhHvq9Oulmyph2LezQMU4lg&index=3&t=2s" target="_blank">video</a> our club member Beck created.


<br></br>
# GitHub Workflow
<br></br>
---
### GitHub UI Instructions
---
<br></br>
1. Fork this repository<br></br>
   *Done from NSC GitHub Repository (click link below)*  
   <a href="https://github.com/NSC-Computer-Science-Club/ForkPracticeCareerPrep" target="_blank">https://github.com/NSC-Computer-Science-Club/ForkPracticeCareerPrep</a>
   <br></br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![Highlighting Fork Button Location](readme_images/fork.png)


2. The repo will appear under your profile. Click this repository (We will do our work from here)<br></br>

   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![](readme_images/myProfileRepo.png)

<br></br>
   > *For a Deeper dive Using Git Bash command line. Follow Steps **A** thru **G** Under **Terminal Commands*** below
 
   <br></br>

3. Click the green "Add file" button. Select "Create new file"<br></br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![](readme_images/Adding%20file%20from%20UI.png)<br></br>

4. At the top of the file will be a textbox to name your file. Include the subfolder. Typing the name of the subfolder and then a forward-slash will indicate a new folder. Then type readme.md
<br></br>

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![](readme_images/newFile.png)
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![](readme_images/newFileWithFolder.png)
 <br></br>

5. Then add markdown of your choosing to illustrate what you learned. Here is a <a href="https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax" target="_blank">GitHub reference</a> to help with markdown.
<br></br>

6. Once you are satisfied with your changes. Save your file by scrolling down and clicking the green "Commit new file" button.
<br></br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![](readme_images/commit.png)
<br></br>

7. <a name="Step">From your GitHub Profile submit a pull request</a>
<br></br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![](readme_images/pullRequest.png)
<br></br>
<br></br>

---
### Terminal Commands
---
**Switch to the Git Bash terminal**

   On your computer navigate to the folder where you want to store your copy within the Git Bash terminal. 
   
   Cloning will create a subfolder including all the files within the repository.
   <br></br>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; A. Clone this repository `git clone https://github.com/NSC-Computer-Science-Club/ForkPracticeCareerPrep.git`

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![Highlighting Cloning option in GitHub](readme_images/clone.png)
  <br></br>

**Switch to your file management system**
<br></br>


  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; B. Create a subfolder within this copied repository. Name it your GitHub profile user name.<br></br>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; C. In this folder create a README.md file<br></br>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; D. Open this file and add your markdown and save the file.<br></br>


**Switch to the Git Bash terminal**
<br></br>


 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; E. Add your changes from the terminal `git add .`<br></br>

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; F. Commit your changes `git commit -m "My created subfolder with markdown file."`<br></br>

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; G. Push your changes to your GitHub Profile repository `git push origin main`<br></br>


> Continue with <a href="/README.md/#Step">**step 7**</a> above
<br></br>

---
### References
---

[GitHub Markdown Reference Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[Link to Beck’s Git Intro Video](https://www.youtube.com/watch?v=UDlIJkvOOPw&list=PL6k4gMRDdFjhHvq9Oulmyph2LezQMU4lg&index=3&t=2s)

[Link to GitHub Profile Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)

[Link to Good First Issue](https://goodfirstissues.com/)

[Link to Fork Me Repo](https://github.com/atapas/fork-me)

[YouTube Video Walkthrough](https://www.youtube.com/watch?v=h8suY-Osn8Q)

[Public Apis](https://github.com/public-apis/public-apis)

[Choosing Projects](https://github.com/collections/choosing-projects)

#### Speaker References

[GitHub Collaboration Features](./speaker_references/GitHub%20Collaboration%20Features.pdf)

[Sample Sequences of Commands](./speaker_references/Sample%20sequence%20of%20git%20commands.pdf)


