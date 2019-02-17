##  Requirements for $1,000 Website and IM415 Portfolios

![](https://raw.githubusercontent.com/mrmccormack/1000-vader/master/pros-only.png)
## Darth Vader

- View this repository on https://mrmccormack.github.io/1000-vader/



![](https://raw.githubusercontent.com/mrmccormack/1000-vader/master/darth-mobile-small.jpg)

> Requirements for a professional website

# Steps

1. Log in to Github account
2. Fork this `repository`
3. Think of a *character* other than Darth Vader
4. Work **JUST** in Github, by editing the `index.html` file
5. Change all links, text, references / images to your character

---

# Requirements for $1000 Website Assignment

> Note: this example has ALL of the requirements


---
# Netlify to serve up Github pages

- Github can be **SLOW** to update the web view of your HTML (maybe allows less than 10 updates per hour)
- Github is **NOT** slow for making changes

- **Solution**: **Have Netlify.com serve up you repository**
- Sign up to https://netlify.com with your Github credentials (username  / password)
- Example
- https://1000-darth-vader.netlify.com/  (you can change the subdomain to anything you want)


---
# Favicon - Favorite Icon...

1. Find a .png for your character at least 128x128 pixels (260X260 is recommended)
2. Generate a bunch of icons and the necessary code with https://realfavicongenerator.net
3. Add the code
4. Download all the generated icons
5. add all the icons to your repository - replacing the Darth Vader Icons
6. VERIFY you icon is working with https://realfavicongenerator.net/favicon_checker

> IMPORTANT

Since this is not in the root of a domain... you must remove the `/`

`<link rel="apple-touch-icon" sizes="57x57" href="/apple-icon-57x57.png">` wrong

**becomes**

`<link rel="apple-touch-icon" sizes="57x57" href="apple-icon-57x57.png">` correct

---
# Twitter Cards

- learn from https://davidwalsh.name/twitter-cards
- Add your own images / text
- Example of Twitter Cards when link is a text message (iPhone)

![](https://raw.githubusercontent.com/mrmccormack/1000-vader/master/iphone-twitter.jpg)


---
# Fresh Ping Website Monitor
1. Set up your own FreshPing monitoring account https://www.freshworks.com/website-monitoring/
2. Create your own FreshPing pubic status page https://statuspage.freshping.io/5040-mrmccormackdarthvaderpage1000


---
# Google Analytics

1. Add Google Analytics to your site https://analytics.google.com
2. Add the required JavaScript to your page
3. Wait a day, and check out who has visited your site

---

# HTML W3 Validation
1. Change the HTML validation link to your URL

---

# Website Performance

- add your URL to https://www.webpagetest.org/   (github.com or netlify.com URL)
- How good is your site
- Take a screenshot and add to your repository:
- https://github.com/mrmccormack/1000-vader/blob/master/websitespeedtest.png

- add a link https://www.webpagetest.org/result/190216_DS_279c1e6136583f438ff1c1cf2f7e7c80/ to footer of your page

---

# Chrome Inspector Audit (Lighthouse)

- Using Chrome Inspector - Audit to check performance
- add screenshot to your repository
- Example of Darth Vader
- https://raw.githubusercontent.com/mrmccormack/1000-vader/master/chrome-inspector-audit-lighthhouse.png



---

# Chrome Console - fix errors
- if you can fix any errors show in Chrome Inspector `Console`
- There are errors in Mr. M.'s Darth Vader 1000 -which are **easily** fixed

```
ERROR
Mixed Content: The page at 'https://1000-darth-vader.netlify.com/' was loaded over HTTPS, but requested an insecure image 'http://icons.iconarchive.com/icons/artua/star-wars/256/Darth-Vader-icon.png'. This content should also be served over HTTPS.

```

---

# Mobile Screen Shot

- take a mobile screen shot and add to your repository
- Example:
- https://raw.githubusercontent.com/mrmccormack/1000-vader/master/darth-mobile-small.jpg

> Update your repository README.md file
- add your own information in the README.md file  (this is the file you are looking at now)
- `.md` meads a `markdown` file - **markdown** is a simple language used by all **professional programers**
- it's fast and simple once you learn a few basic things.
- INSTRUCTIONS HERE: https://guides.github.com/features/mastering-markdown/


---
[![Netlify Status](https://api.netlify.com/api/v1/badges/11a7f722-2a18-4846-9e6d-baded153c8a8/deploy-status)](https://app.netlify.com/sites/1000-darth-vader/deploys)
