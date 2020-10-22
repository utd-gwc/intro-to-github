# Introduction to GitHub Workshop
This repository (repo) is meant to be used as a supplemental resource for the Introduction to GitHub workshop.

# What to do?
Fork this repository to your personal account.

Clone the forked repository onto your local machine.

Add a card about yourself in the same format as the ones already in the `index.html` file.

Make sure to add the new card inside of the ``<div>`` tag with ``classname="container"``.

## Card Template
```html

<div class="card">
  <h1>Replace this text with your name</h1>
  <br />
  <h2>Replace this text with a short sentence about yourself</h2>
</div>
```

# Then what
Create a new branch on your local machine.

`git checkout -b <new-branch>`

Add this remote repo as a an upstream repo

`git remote add upstream https://github.com/utd-gwc/intro-to-github/`

Add your changes.

`git add .`

Commit your changes with a descriptive commit message.

`git commit -m "<commit_message>"`

Push the new branch to your forked repo with the upstream tag.

`git push -u origin <new-branch>`

Create a pull request to merge this new branch with the master branch on GitHub.

# See what you did
If you set up GitHub Pages (Settings > Scroll Down to "GitHub Pages" > Select main) then you can view the changes you've just made online!

Your github pages website should be viewable at ``https://<your-github-username>.github.io/<your-forked-repo-name>/``. You can see our repo at: https://utd-gwc.github.io/intro-to-github/.

If your pull request gets approved then you should be able to see your changes on our repo's website!

Be patient when looking to see new changes on this free website as GitHub Pages is often slow to update.
