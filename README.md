# Discrete Structures (CMPSC 102) Lab 7

## Title
Ethical Topics in Discrete Structures

This repository contains information about Discrete Structures lab deliverables. This assignment invites students to investigate articles discussing ethics as associated to Computer Science.

## Dates

Handed out: 1 November 2022

Due and presentation : 8th November 2022

## Contents

- [Objectives](#Objectives)
- [Cloning Your Repository](#Cloning-Your-Repository)
- [Part 1](#Part-1)
- [Part 2](#Part-2)
- [Deliverables](#Deliverables)
- [Assessment](#Assessment)

---

## Objectives

- To gain skill in reading literature and gathering facts about the described science.
- To gain experience in determining the onset of an ethical dilemma in a Discrete Structures research setting.
- To think critically about the outcome of the Discrete Structures research in terms of ethical handling, fairness, justice and accountability.

## Motivation

We recently began a conversation after watching a video in class: _Coding_ from Netflix' "Explained" series. In the video, the implications of computer code and algorithms to our daily lives were discussed in terms of ethical dilemmas.

In the video, it was discussed that solutions from computer code, running algorithms, may make our world a better place in some regards, there are still many problems that may result from the usage of the code or algorithms due to poor design and testing.

## Part 1

__In this assignment__, you (working in a group if you choose) are to use online search engines to find article(s) in journalism or scientific literature that discuss ethical problems in terms of code, programming and /or algorithm utilization. You will use the articles(s) to be able to introduce and present the ethical conundrum in CS to the class.

For example, a potential article might discuss the cyber bullying, shaming and other undesirable qualities that have emerged from social networking technologies. Another idea might concern the "street-use" of technology (i.e., a usage of the technology which was not a part of its conception).

The abuse caused by technologies due to poor design and development may be another track that you could explore. Facial recognition, for example, was discussed in (Code of Ethics for Facial Recognition)[https://ojs.victoria.ac.nz/wfeess/article/view/7642/6832] by Caitlin Fisher. There are many potential project ideas available by searching keywords relating to ethical topics such as following; "computer crime", "security" ,"privacy", "misinformation (accuracy)", "liability", "responsibility", "intellectual property", "access" and many others.

Once you have located an appropriate article in which terms from computer science and ethics are mentioned together, you are to complete the reflection questions of your lab.

## Part 2

__Next lab__: You and your group are to present your research of an ethical problem stemming from code or algorithm-use which from the article. In your presentation, you are describe the article, state the ethical concern and provide details about how the problem can be resolved. You are encourged to provide your own ideas about how to prevent harm from being done. Your presentation will last up to ten minutes.

## Cloning Your Repository

To use the link that you were given in class, please follow the steps below.

- Click on the link and accept the assignment.
- Once the importing task has completed, click on the created assignment link which will take you to your newly created GitHub repository for this lab.
- Clone this repository (bearing your name) and work locally.
- As you are working on your lab, you are to commit and push regularly. The commands are the following.

```
git add -A
git commit -m ``Your notes about the commit here''
git push
```

After you have pushed your work to your repository, please visit the repository at the GitHub website (you may have to log-in using your browser) to verify that your files were correctly sent.


## GatorGrade

You can check the baseline writing and commit requirements for this lab assignment by running department's assignment checking `gatorgrade` tool. To use `gatorgrade`, you first need to make sure you have Python3 installed (type `python --version` to check). If you do not have Python installed, please see:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, if you have not done so already, you need to install `gatorgrade`:

- First, [install `pipx`](https://pypa.github.io/pipx/installation/)
- Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`:

`gatorgrade --config config/gatorgrade.yml`

## Deliverables

- Write a reflection of about 200 words to describe the chosen article and the ethical implication outlined in it. The above-mentioned themes of Part 1 to consider are also to be addressed in your `writing/reflection.md` document.

## Assessment

The grade that a student receives on this assignment will have the following components.

- **GitHub Actions CI Build Status [up to 25%]:**: For the lab repository associated with this assignment students will receive a checkmark grade if their last before-the-deadline build passes. This is only checking some baseline writing and commit requirements as well as correct inclusion of files. An additional reduction will given if the commit log shows a cluster of commits at the end clearly used just to pass this requirement. An addition reduction will also be given if there is no commit during lab work times. All other requirements are evaluated manually.

- **Mastery of Technical Writing [up to 40%]:**: Students will also receive a check mark grade when the responses to the writing questions presented in the `reflection.md` reveal a proficiency of both writing skills and scientific knowledge. To receive a check mark grade, the submitted writing should have correct spelling, grammar, and punctuation in addition to following the rules of Markdown and providing conceptually and technically accurate answers.

- **Mastery of Oral Communication [up to 35%]**: Students will receive a portion of their assignment grade when the team presentation shows a complete understanding of the written work and ability to communicate its ideas.
