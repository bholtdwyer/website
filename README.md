# Holt Dwyer
Personal Academic Website. 

Note to self on deploying website:

Website is managed through Github. Add or update files locally, then git add or update, git commit, and git push origin master. Will then automatically rebuild on netlify. No need to mess around with R project (in fact best not to as you might accidentally update Hugo, which breaks the site!)

Main page is governed by public/index.html. Other content is for whatever reason by folders under "content". Paths in links refer to files/folders under "content" folder. For example a link to "/about" corresponds to the folder website/content/about.
