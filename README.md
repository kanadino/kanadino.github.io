# How to host a resume on GitHub page

## Purpose
  
  This README Markdown file will help us host and format our resumes on a static website step by step(we use GitHub pages as an example here). In addition, our instructions will connect with general principles of current technical writing mentioned in Andrew Etter's Modern Technical Writing.

## Prerequisites

  Before reading the instructions of this README document, please make sure you have following documents and information:
  - A resume written in Markdown format, and there is a tutorial about Markdown in More Resources section
  - A GitHub account, [here][link 1] is a website to sign up a GitHub account
  - A computer can log into you GitHub account
  
  [link 1]: https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home
  
## Instructions
  
### Creating a repository 
1. Log into our GitHub account main page
    - We can see a list of repositories which is located on the left side of the web page.
2. Click **New** button
    - This action can bring us to the web page for creating a repository.
3. Type */ownername.github.io*/ into Repository name blank
    - This action will create your own site to host some information.
4. Make our repository be public 
    - It will allow other people or contributors to check your repository content 
5. Select **Add a README file** 
    - README file helps other contributors or people who want to learn our materials to know the purpose of this repository and how to run our codes.
6. Click **Create Repository** 
    - After doing this action, we can get a reposity which will contain our resume, README documents.

### Uploading our resume.md  
 1. Go to our new created repository 
 2. Click **Add file** button 
 3. Click **Upload files** button
    - It will bring us to the web page to upload our resume file 
 4. Drag our resume.md to the rectangular box or
    click **choose your files** to choose from our device 
 5. Changing our resume.md to index.md 
    - It will set our resume to host on the static site, which is not shown the README file
 6. Enter the description what we did for this commit 
    - It will help other contributors or ourselves to know what we did in the past
 7. Click **Commit changes** to the file we just created or uploaded   
 
### Formatting our resume
1. Click **Add file** button 
2. Click **Create new file** button 
   - It will breing us to the web page to typing code
3. Use _ _config.yml_ as the name of file
   - This file will use to format the static site, which can decide Jekyll template.
4. Type these two lines of code
  ```
  theme: jekyll-theme-minimal
  title: "My Resume"
  ```
   - The theme will determine the format of our resume in the static website. Here we use the Jekyll templates provided by GitHub and apply them to GitHub Pages. We can also change the title of the website by using second line code. We can find more Jekyll template from More Resources section of this file, which is provided by the GitHub team. We can also find other templates online.
5. Enter the description what we did for this commit 
    - It will help other contributors or ourselves to know what we did in the past
6. Click **Commit changes** to the file we just created or uploaded 
 
### Opening the static site
1. Add https://ownername.github.io into the website search bar
   - Then we will find the resume host on the GitHub Page.

## More Resources
- [A Markdown tutorial][link 2]
- [Modern technical writing: An introduction to software documentation][link 3], which is written by Andrew Etter.
- [More information about GitHub Pages][link 4], which is created by the GitHub team.

[link 2]: https://www.markdowntutorial.com
[link 3]: https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS
[link 4]: https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages

## Authors and Acknowledgements

- Author
  - Hong Gao
- Acknowledgements
  - Thanks to Cody Gordon, Rolf Olayan, and VICTOR IFEAKACHI EZENDU for their valuable advices on my README and resume files.

## FAQs
1. Why is Markdown better than a word processor?
  - Since Markdown is easier to learn and read.
2. Why is my resume not showing up?
  - Firstly, we need to make sure our name of resume.md already changed to index.md.
  - Secondly, we need to make sure the website address is https://ownername.github.io.
  - Finally, GitHub might need 10 minutes to change the site if we make any changes to our resume. Creating the static site might need 1 hour if we have not used GitHub Pages to generate a website. For more specific information, we can check the **Actions** of the current repository to know the current running process and time.

## Image
![resume demo](https://github.com/kanadino/kanadino.github.io/blob/main/myResume.gif)
