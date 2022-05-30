# personal_site

How to update site once you have confirmed that edits work using local tests:

1. In RStudio, run the command ```blogdown::build_site()```
2. Copy public folder contents to AndersonMonken.github.io repo (not the folder itself)
  - Windows `xcopy C:\Users\Monke\Documents\test_site3\public\ C:\Users\Monke\AndersonMonken.github.io\  /E/H/Y`
  - Linux `cp -R /mnt/c/Users/Monke/Documents/test_site3/public/* /mnt/c/Users/Monke/AndersonMonken.github.io/`
3. Git add and commit these files then push to GitHub
4. Check www.andersonmonken.com that the site works



Getting set up with custom domain with [this blog post](https://trentyang.com/how-to-setup-google-domain-for-github-pages/)

