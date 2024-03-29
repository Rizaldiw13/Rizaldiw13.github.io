# Host Your Resume Online

## <u> Purpose </u>

Follow the steps below to host your own resume online. We will host your resume using a static site generator on Github Pages.

[Demo of the Website](https://rizaldiw13.github.io/)

![Demo](https://github.com/Rizaldiw13/Rizaldiw13.github.io/blob/main/app/resume%20demo.gif)

## <u> Getting started </u>

### **Prerequisites**

You will need a couple of things before we start
- A Github account
	+ If you dont have a Github account, navigate to [Github](https://github.com/) and create a new account.
- [Github Desktop](https://desktop.github.com/)
	+ Github Desktop will help you update your files and compare the changes you made easily.
- [Ghostwriter](https://ghostwriter.kde.org/)
    + A markdown text editor

## <u> Instructions </u>
### Step 1: Setting Up The Github Repository

In his book, Andrew Etter encourages us to publish our writing on a website instead of a PDF. When publishing our writing on a PDF, the PDF will eventually be outdated and we need to create another PDF file to update our writing. However, when we publish our writing on a website, we don't need to create a new website to update its content. We can just continuously make the necessary changes on that same website and keep its content up to date.

Moreover, for anyone who wants to view our writing, we can give them a link to our published website. For our purposes, we will use Github Pages to host our website.
 
1. Navigate to Github and login to your account.
2. Navigate to this repository.
	+ This repository contains a resume template that we will use to create our own resume.
3. Click the **Fork** button on the top right of the page.
4. 	Fill out the required information 
	+ For Repository Name, enter your Github username followed by `.github.io`. For example, `yourusername.github.io`
	+ Leave everything else on default.
	+ Click **Create Fork**
5. Click the **Settings** button at the top of the page
6. Select **Pages** on the left sidebar
7. Select `Deploy from branch` for source and select `main` for branch under `Build and Deployment`
8. Click **Save** once you are done and your repository are now all set-up.

### Step 2: Edit Your Resume

Andrew Etter explains that using lightweight markup languages allows users to quickly publish a writing with a simple syntax. This allows anyone to contribute to the content as the simple syntax creates an easily readable information. We will use Github Desktop to make a copy of our GitHub repository and edit our resume using a Markdown Text Editor called Ghostwriter.

1. Open Github Desktop and sign in to Github
2. Click the `file` button on the top left
3. Select `clone` repository
4. Select the repository that we created in Step 1.
	+ For example: `username.github.io`
5. Click on `clone`
6. Select `Repository` on the top left
7. Select `Show in Explorer`. This will bring you to the file directory of your resume. 
8. Right click on `_config.yml` in that file directory,  and select `Open with` and choose `Notepad`.
	+ Edit the `title: ` and `description: ` so that it matches your resume
	+ Save the file once you are done
9. Right click on `index.md`in the same file directory. Select `Open with` and choose `ghostwriter`
	+ As you may have noticed, your screen will be split into two. The left side of the screen is where you will write out your resume and the right side of the screen is the preview of your resume
	+ Write out the content of your resumes in this markdown file
	+ Save the file once you are done

You have now successfully made the changes you want on your resume. Your resume is now ready to be published on GitHub Pages

### Step 3: Uploading and Publishing Your Resume

Andrew Etter explains the importance of using version control system to manage our content. Version control systems such as GitHub allow us to track the change we made to our content overtime. It also make sit easier for us to share our source files to anyone who wants to contribute. In this step, we will use Github Desktop and Github to manage our repository.

1. Open Github Desktop
2. Click on the summary text box on the bottom left and type a short description of what we did
	+ For example: 'Created Resume in ghostwriter'
3. Click on `Commit to main` and wait for the process to finish
4. Click on 'Push origin'

Now your resume should be built and published in Github.

## <u> More Resources </u>
+ To learn more about Markdown, visit [Markdown Tutorial](https://www.markdowntutorial.com/)
+ If you wish to change the look of your resume, check out [Jekyll Themes](http://jekyllthemes.org/themes/slate/) and [Github Supported Themes](https://pages.github.com/themes/) for more themes

## <u> Authors and Acknowledgements </u>
+ tsusdere for their [Slate Jekyll theme](https://github.com/pages-themes/slate) 
+ AJ Manigque and Safran Bin Kader for peer reviewing this readme and resume.

## <u> Frequently Asked Questions </u>

### Why is Markdown better than a word processor?

Markdown is simple to use and easy to learn because it uses plain text formatting syntax. Users can focus more on writing their content instead of spending more time on formatting. Moreover, markdown files are also highly portable and compatible across different platforms, applications, devices. This means that users can edit their files on any device/app that support text files.

### How do i change my theme?

Visit [Jekyll Themes](http://jekyllthemes.org/themes/slate/) and [Github Supported Themes](https://pages.github.com/themes/) to choose your desired themes. To change your theme, copy the link of your chosen theme and open Github Desktop. Repeat step 6 to step 8 in the "Edit Your Resume" section. In step 8, replace the current link in the `remote_theme: ` with the link of your chosen theme. Follow the steps in the "Uploading and Publishing Your Resume" section to finalize the change.