---
permalink: /
title: About me
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi there!
My name is Tayyab Jafar, you can call me Tay.

I am a former Astrophysics student, attended Queen's University, and am now currently attending Sheridan College for my Honours Bachelor of Information Sciences (Cyber Security).

CV
======

EDUCATION
======
- Astrophysics – Bachelor of Science (Honours) - Queen's University (2013-2017)
- Cyber Security – Bachelor of Information Sciences (Honours) - Sheridan College (2020-2023) 

WORK EXPERIENCE
======
**[ソラミツ SORAMITSU](https://soramitsu.co.jp/) – 1 yr 5 mos**
- _Cybersecurity Analyst & DevSecOps_ (May 2022 - Oct 2022):
- - Develop new products and iterate on features
- - Perform smart contracts security and logic audit
- - Review smart contracts of decentralized applications, present and test vulnerabilities
- - Identify, report, and advise on mitigation of security risks associated with crypto, web 3 and blockchain assets
- - Automation of all aspects of open-source software development lifecycle
- - Assistance to deployment from small scale projects to blockchain infrastructure
- _Technical Community Manager_ (Jun 2021 - May 2022):
- - Supporting users by responding to questions and concerns in official communities as quick as possible to ensure clients’ needs and issues are met and dealt with rapidly
- - Researching, diagnosing, and identifying solutions to resolve technical issues and troubleshoot new problems and report to development team to ensure patches are pushed out as soon as possible
- - Working with query commands in command line and utilizing tools for blockchain analysis
- - Writing and maintaining documentation to guide users, update wiki and tutorials to minimize interference of work activities from support questions
- - Collaborating with marketing team and assisting with interviews and establishing community activities
- - Building with external projects in the industry, developing and maintaining business relationships
- - Assisting in hiring procedures and onboarding new employees into technical support roles



**[Trillium Health Partners](https://thp.ca/) - 3 mos**
- _OneTHP Support Hospital Information Systems_ (Aug 2020 - Oct 2020):
- - Worked in database management to facilitate and support transfer from Meditech to Epic electronic health recording software.
- - Provided training and assistance to colleagues working in manual transfer positions who lacked technical prowess to complete tasks.
- - Remote assisted and used a variety of support tools to complete merging requests from healthcare records.


PROJECTS
======




Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
