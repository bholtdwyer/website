# Holt Dwyer
Personal Academic Website. 

Note to self on deploying website:

Website is managed through Github. Add or update files locally, then git add or update, git commit, and git push origin master. Will then automatically rebuild on netlify. No need to mess around with R project (in fact best not to as you might accidentally update Hugo, which breaks the site!)

Color scheme is determined in website/config.toml.

The overall theme is governed primarily by website/config.toml, which sets the main image and the locations pointed to by the header and footer. 

Other content is determined by folders under "content". Do not bother with anything in the /public folder; this has parallel structure to /content but is overwritten when the site is built.

The main landing page is controlled by website/content/\_index.md; this is where the image on that page can actually be changed.

Other pages are controlled by their corresponding index.md files. Pictures can be changed by replacing the images in the corresponding folders.

Paths in links refer to files/folders under "content" folder. For example a link to "/about" corresponds to the folder website/content/about. The exception is /img/ which refers to website\themes\hugo-apero\static\img, don't ask why.






