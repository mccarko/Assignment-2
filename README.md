# **How to Upload a Resume to GitHub**
## Intended Audience  
This README is intended for users with little experience using markdown and github. Perhaps this is your first experience with creating a webpage or maybe you have no experience using markdown. Regardless of your ability following the steps below will allow for even someone with no tech experience to be able to upload nice looking webpages using GitHub.
## Prerequisites
* [Download and install Atom.](https://atom.io/)
* [Create a GitHub account if needed.](https://github.com/join)
## Instructions
### Step 1. Write your Resume in markdown
1. Make sure you have an editor like [Atom](https://atom.io/) installed.
2. Once done launch Atom.
3. Open the file tab located at the top right corner of Atom and select add project folder.
 1. Chose the location of where you want the project folder to be.
 2. Right click and select make new folder (name it whatever you like).
 2. Select the created folder then click the button on the bottom right of the window to confirm the selection.
3. Open the file tab and select new file.
4. Save the file in your project folder as "index.md" (it must be named exactly like this or else Github will not automatically display your resume page by default).
5. Dowload [this extension](https://atom.io/packages/markdown-preview) to be able to preview work (feel free to search around for other extensions that look interesting at [this link](https://atom.io/packages).
6. Once downloaded select the packages tab, then hover over markdown preview and select toggle preview so that you can see how your work will work (5+6 can be skipped if you are confident in your work, additionally GitHub will also display a preview so you can always upload the work to check it).
7. Complete the [tutorial](https://www.markdowntutorial.com/lesson/3/) to get accustomed to markdown commands so that you can format your resume. (If you are well experienced in markdown this step can be skipped)
8. Write the resume in Atom using the markdown language(if you get stuck or are unsure if a certain command exists then check the reasources section of the README for a full list of commands).
9. Save the final version being sure that it is named "index.md".

### Step 2. Posting the resume to a GitHub account
1. Make sure you have an account [registered with Github.](https://github.com/join) 
2. Login to your GitHub account
2. Click the profile picture in the top right corner to open a drop down menu then select "your repositories".
3. Click the green "new" button on the right side that has a book icon in it to create a new repository.
4. Name the repository, and give it a description if you want. Make sure it is set to public if you want others to be able to view your webpage and then click "Create repository".
5. Click on your profile picture and then click "your repositories". After your new repository will be visible, click on the newly created repository.
6. Select "Upload files", then click "choose your files" then go to where index.md was saved and select it. Then click "commit changes".
7. To find your website link first go to the repository, then click  settings and scroll down to "GitHub Pages" and the link will be just bellow the header.

### Step 3. Formating the resume with a Jekyll theme
1. Select the repository that contains the resume.
2. Click settings.
3. Scroll down to "GitHub Pages" and click "Change theme".
4. Scroll through the themes untill a desired one is found, select the desired theme then click "Select Theme".
5. You may have to wait a few minutes for the changes to be made but after the wait next time you click on the link to your resume it should now be styled using the selected theme.

## More Resources
* [Visit this link for markdown commands.](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [An additional link for markdown commands.](https://github.github.com/gfm/)
* [Visit this link for questions about working with GitHub.](https://help.github.com/en/github/working-with-github-pages)
* [Visit the Atom forums for any atom related questions.](https://discuss.atom.io/)
* [Visit this Atom page for a list of packages you can use to customize your Atom client.](https://atom.io/packages)

## Authors and Acknowledgments
|Name: |Role:|
|------|-----|
|Kory McCarthy|Author|
|Denesi Jatto|Editor|
|Dow Griffith|Editor|
|Christina Penner|Prof|

## FAQs
* When I click on my website link I am shown the README instead of the resume, any solution?
 * Make sure your resume is titled index.md. Github will default to showing README if no index file is found so ensure that your resume is title index and the link should display it.
* I am using a non markdown language but still want to post my pages using GitHub, can I still use this README?
 * Yes, much of the information included is not markdown specific. You will need to find other reasources if you require help writing in a different language however the information regarding GitHub hosting and Jekyll themes will remain true regardless of the language you use. 
* I didn't name my resume index.md, how can i fix this?
 * Click on the resume file then select the pencil in the top right corner of the preview window. You should now be able to type over the file name and replace it with index.md.
* After uploading I noticed that I made a mistake in my formating. Do I have to reupload the file with the changes done in Atom or can I make changes in GitHub?
 * You can edit your markdown files on the GitHub site. First select the file you want to change then click on the pencil located at the top right corner of the preview window. You are now able to edit the file.
