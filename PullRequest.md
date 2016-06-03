---
date: "2016-03-14"
draft: false
weight: 213 
title: "Lab - Git Pull Request"
---

### Lab Duration: 20 minutes

### Lab Objective

The objective of this lab is to give students a basic introduction to git and git pull requests.  Many open source projects rely on git for decentralized collaboration including OpenStack.

#### 1. Setup Github Account (If you have not already done so)

0. In a new tab, **[Create a Github account](https://github.com/join) or [Login](https://github.com/login)**

    ![Create an account](https://i.imgur.com/uTDaD5s.png)

0. Navigate to the Alta3 OpenStack Glossary project

    `https://github.com/alta3/openstack-labs`      

0. Star the repository

    ![Star this repository](https://i.imgur.com/LLAQVg7.png)

    > Staring is like a bookmark on github.com,  you can view and search your stared repositories at [github.com/stars](github.com/stars)

#### 2. Fork the project )If you have not already done so)

0. **Fork the lab repository** into your account

    ![Fork this repository](https://i.imgur.com/JJc2Dht.png)

    ![Fork this repository](https://i.imgur.com/S9iDb2e.png)

    ![Fork this repository](https://i.imgur.com/Ro71WF6.png)

#### 3. Edit a file in the repository

1. **Navigate to (click on) a file** you would like to edit.  The this example will add a new glossary term to our glossary.

    ![click on glossary](https://i.imgur.com/jhmtH0h.png)

2. The file contents are sumarized on this page.  Additionally we can perform operations that give us insights about this specific file (i.e. length, size, authors, and change history).  **Click the edit file icon** to make a new change.

    ![click edit](https://i.imgur.com/toKCgK0.png)

3. **Make a change**, in this example we add a fictitious new OpenStack Service "Aardvark"

    ![aardvark service](https://i.imgur.com/aLp5ZQY.png)

4. After you are finished editing, **scroll to the bottom and add a descriptive commit message and click "Commit Changes"

    ![commit](https://i.imgur.com/ngc5hQv.png)

    ![changes](https://i.imgur.com/K0I1dao.png)

#### 4. Create a Pull Request

1. **Navigate back to the project base page**.  Notice that our branch is now ahead of the master branch.  Let's create a pull request to get our addition added back into the main repository.  Click the "Pull Request" link.

    ![pull request](https://i.imgur.com/2LpvADQ.png)

2. On the pull request page, **first scroll down to see the list of changes in this request**.  It should only be our added Aardvark service highlighted in green.  If we had removed lines they would be highlighted in red.

    ![changes](https://i.imgur.com/zouC43q.png)

3. **Create the pull request**

    ![pull request create](https://i.imgur.com/dMvqH1b.png)

    ![finished request](https://i.imgur.com/MnFQNxd.png)

4. At this point your instructor will accept the changes. Below is a screenshot of the email that is generated to a project maintainer when a pull request is submitted.  Refresh your page a few times until your instructor accepts your changes.

    ![pull request email](https://i.imgur.com/rmhgdPZ.png)

    > How does the page change after a pull request has been accepted?

You should now have a basic familiarity with most of the git processes as realized within the GitHub ecosystem.  
Please remember that these are the most basic types of functionality and most developers will manage these processes from their own tools within their development environment.

