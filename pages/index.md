---
layout: home
title: Welcome
permalink: /
section: home
intro_paragraph: >-
  If you're reading this, you've likely already seen my portfolio page available
  at [galaxial.github.io](galaxial.github.io), and are looking for how to get
  started in creating your own. This guide will walk you through the steps to
  getting your template deployed so that you can unleash your creativity and
  make it yours. 


  For this tutorial, you will need:


  * A github account

  * A Netlify Identity account


  (If you don't have either of these yet, head over to [github.com](github.com),
  and [netlify.com](netlify.com) respectively to make your account, and meet
  back here when you're ready)


  Now, let's get started, shall we?
---




The first thing you'll want to do is find yourself a template, there are many available to choose one, so try to find one that best resembles your vision for your site. 

For this tutorial I'll be using the Jekyll Netlify Boilerplate, if you would like to follow along yourself you can also start with it by accessing it at <https://templates.netlify.com/template/jekyll-with-netlify-cms-boilerplate/>

Once You've found your template, you should be able to see a button marked 'Deploy to Netlify'

![Deploy to netlify screenshot](/assets/img/uploads/netlify-homepage-deploy.png "Deploy to Netlify")

This button will bring you to a page prompting you to connect your github account to your netlify identity. Click it, and it will prompt you to login and connect. 

![Connect to Github Screenshot](/assets/img/uploads/connect-to-github.png "Connect to Github")

Now that you're connected, this is where you're able to start making it yours. The next screen will prompt you to enter a repository name and to save & deploy. The repository name you choose here will be the name of the repository created in your github account, as well as part of the url that will be used to access your new portfolio, so choose wisely!

Once you have something you're happy with, go ahead and 

![Name Save Deploy Screenshot](/assets/img/uploads/name-save-deploy.png "Name, Save, Deploy")

Once you've hit deploy, you should see something like this:

![Site Loading Screenshot](/assets/img/uploads/deploy_complete-s4.png "Site Loading")

It will tell you that the site is currently deploying. This will take a few moments. In the meantime, you'll be receiving an email from your netlify account informing you that you've received an invite to a site. This will initially look like a random string of characters, but don't worry, we'll be changing that shortly. 

After you've accepted the invite and the site has finished deploying, click on 'Site Settings' to make some changes. 

![Change Name Screenshot](/assets/img/uploads/change_name_s5.png "Change Site Name")

Next you'll want to click 'Change Site Name', enter your new name, and save. 

Congratulations! Your template can now be reached at your_site_name.netlify.com!

But we're not done yet here. 

You're likely wanting to have a more prestigious namespace than Netflix, and any techie around knows the name github, so next we'll move on to publishing your page through github pages, and get into how to make changes to your site. 

Now you'll want to head back over to your github account. You may have noticed a new entry in your repositories, with the name that we entered just a few steps back. Open it up and take a look inside.

![Github Repository populated screenshot](/assets/img/uploads/repo_populated_s6.png "Your Github Repo is now populated")

Your github repository is now populated! As a developer or designer looking to custom craft a portfolio page rather than simply using generator engines such as Wordpress or Blogspot, you'll likely recognize a thing or two poking around in your new repository. Unfortunately the exact structure varies greatly from template to template, so this tutorial can't be a catch-all for all netlify templates. Your template should include a README in the root folder, so refer to that for customization instructions on how to modify the html, css (and js, or whatever other frameworks your particular template runs from). For example,  with the template I've chosen, most of what you're looking for that isn't simply a raw html page can be found in the _config.yml or the admin folder to modify base page settings. 

If you've chosen the same template as myself for this tutorial, you're in luck and have access to a content manager that will make creating, administrating, and publishing pages a breeze. Many templates will have access to this, or their own version with different methods of accessing it. For ours, we can reach the content manager at your_site_name.netlify.com/admin 

This will bring you here:

![content manager screenshot](/assets/img/uploads/admin_editor.png "Content Manager Screenshot")

From here, you can create, edit, and publish both pages, and post entries for your site, as well as use a universal media content manager. 

By now you should have either some content and customization, or are simply excited to move ahead to moving your site to github pages. This is a relatively simple process. First, you'll need to open the repository your site is currently stored in, and go to the settings page. 

Scroll down until you reach the 'Github Pages' section.

![publish to github pages screenshot](/assets/img/uploads/master_branch_s7.png "Publish to Github Pages")

Under 'Source', you should see a dropdown menu. Open this and select 'Master Branch'. 

Github will take a few moments to publish your site, and then you're done!



Congratulations! You can now reach your new portfolio site at your_github_account.github.io/your_repository_name
