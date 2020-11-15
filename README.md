# karamudie.co.uk

This is a github site operated by photographer Kara Hood (Kara Mudie). It will run on jekyll, built and served by github pages. The current template is [photorama](https://github.com/sunbliss/photorama) by 
Anna Prigkipaki ([@sunbliss](https://github.com/sunbliss)).

## Template help information

If you want to use your **own domain** go to the root of your project's repository, create a CNAME file and add a line with your domain name, e.g. `www.yourdomain.com`.

Go to your domain name registrar and add a CNAME record pointing your domain to GitHub Pages:
- type: CNAME
- host: www.yourdomainname.com
- answer: yourusername.github.io/repositoryname
- TTL: 300

----------

- In order to send **newsletters** about your posts to your subscribers, you should register an account in [tinyletter](http://www.tinyletter.com " tinyletter").

Find the line `'https://tinyletter.com/yourproject', ` in the *newsletter.html* and replace 'yourproject' with your registered website.

You can always ommit the newsletter rendering by deleting the line `{% include newsletter.html %}
` in the *default.html* layout.

----------

If you want to use the matching **NEWSLETTER** template, you must always create a new file  by copying its respective index.html and renaming it to e.g. 2016-March-newsletter.html and then save it inside the folder and the accompanying images inside the 'images folder', so it can be accessed to your viewers through their browser. In this case the root url for the above newsletter will be ***http://yourgithubusername.github.io/yourproject/2016-March-newsletter.html***. Copy this link and replace this part of the code `http://www.yoursite.com/newsletter/year-month-newsletter` with it.

----------

**TAGS** and **CATEGORIES** of the posts 

When you add a tag or a category name in the front matter of a post, don't forget to add the responding markdown files in /journal/tag/ folder and in /journal/category folder, so they can always render when browsing the journal or searching in the respective page.

----------
