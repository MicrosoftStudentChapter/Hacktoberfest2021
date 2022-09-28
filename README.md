# Hacktoberfest2k22
<img src="images\2022\hero.svg" alt="Logo" width="150" height="150">


**[MLSC, TIET](https://mlsctiet.co.in/)** is here to celebrate the month-long global celebration of open source software, the   **[Hacktoberfest](https://hacktoberfest.mlsctiet.co.in/)**, with a strong focus on encouraging contributions to open source projects. Many fun events, workshops, goodies, prizes, and other cool stuff await you as this tech bonanza begins!
Scroll down to see the details about contribution and open source. 

 ## Video Links

- [How to generate pull request](https://youtu.be/DIj2q02gvKs)
- [How to solve git merge conflict/comment](https://youtu.be/zOx5PJTY8CI)
- [Beginner Friendly Issues](https://goodfirstissue.dev/)

## Guide to Contribution

- Fork the repo to contribute 
- Clone on your local machine

```terminal
git clone (copy link of the repo and paste)
cd (name of folder where you cloned the repo)
```

- Create a new branch

```markdown
git checkout -b my-new-branch
```
- Add your contribution
- Commit and push

```markdown
git add .
git commit -m "your-commit-msg"
git push origin my-new-branch
```

- Create a new pull request from your forked repository


## Avoid Conflicts (Syncing your fork)

An easy way to avoid conflicts is to add an 'upstream' for your git repo, as other PR's may be merged while you're working on your branch/fork.   

```terminal
git remote add upstream (copy link from the code and paste)
```

You can verify that the new remote has been added by typing
```terminal
git remote -v
```

To pull any new changes from your parent repo simply run
```terminal
git merge upstream/master
```

This will give you any eventual conflicts and allow you to easily solve them in your repo.

### Note: In hacktoberfest, only valid PRs count. Make sure you make PRs to the repositories or issues which are hacktoberfest accepted or have the hacktoberfest tag on them. Before you start writing code, make sure to sign up [here](https://hacktoberfest.digitalocean.com/profile) so that your contributions count. More details about a valid pull request can be found at the [official website](https://hacktoberfest.digitalocean.com/). 

# FAQs
- What is Open-source?
    - Open-source software is computer software that is released under a license in which the copyright holder grants users the rights to use, study, change, and distribute the software and its source code to anyone and for any purpose.

- Who can contribute to hacktoberfest?
    - Anyone with a github account who registered for Hacktoberfest.

- What is the duration of Hacktoberfest 2022?
  - It is from 1st october to 31st october 2022.

- What is the event for?
  - To encourage open source community engagement.

- How can we contribute?
    - This could be done in various ways-
        - One can organize workshops.
        - Mentor others
        - Contribute to projects via pull requests.
        - Share a project for collaboration.


- How can we receive swags and Goodies?
    - By making atleast 4 Pull requests in the repositories recognised by Hacktoberfest.

- What are the benefits of participation?
    - Encourages participation in open source community.
    - Developers are helped to ship good code.
    - Enhancement of github and other technology skills.
    - Chance to bag exciting swags and goodies.

P.S. Don't forget to checkout our other projects at https://github.com/MicrosoftStudentChapter and try solving the issues.
## Happy hacking! May the odds be in your favour!
