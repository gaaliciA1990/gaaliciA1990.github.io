# Github Pages Setup Process

This is a brief "how to" for setting up the website, as well as documenation for a successful setup. 
Github Pages Setupn is not complete and needs supplemental steps as laid out below

1. First start with the steps in this link

  installing jekyll: https://jekyllrb.com/docs/

2. Set up the github page following these instructions

  GitHug Pages: https://pages.github.com/

3. Then, follow the steps laid out to set up a local copy of the website

  Installation via Bash on Windows 10: https://jekyllrb.com/docs/installation/windows/
  
# Updating a theme to the Website
1. Find a theme of your choice

Examples: 
https://jekyllthemes.io/
http://jekyllthemes.org/
https://jekyllrb.com/docs/themes/ - This also provides instructions on how to update the defaults!
https://jamstackthemes.dev/ssg/jekyll/
http://themes.jekyllrc.org/

2. Download the files from the github repo to your desktop

3. Copy the files into your webpage repo.

4. Using command line, run the following command
`bundle update`

5. On a successful complete, run the following command
`bundle exec jekyll serve`

TL/DR; My pages theme instructions (beautifully documented, kudos to the creator!): The About tab https://jamstackthemes.dev/demo/theme/devlopr/

---
# Customization

### Page Settings and themes

Set the theme and settings of the page through the **_config.yml** file.

### To edit the about section

fileName = about.markdown

### Home page

fileName = index.markdown

---
# Working with Website from the terminal

### Launching the website
1. In the repo folder, enter the command: `bundle exec jekyll serve`
2. Enter the following into the url line: http://localhost:4000/

