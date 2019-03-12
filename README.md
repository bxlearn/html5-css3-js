# html5-css3-js
Build A Real-World HTML5 &amp; CSS3 Responsive Website From Scratch

Commands for initial setup:
git clone https://github.com/USERNAME/html5-css3-js.git
cd html5-css3-js

git remote add upstream https://github.com/bxlearn/html5-css3-js.git
git remote update
git branch -u upstream/master master
git pull

Start work on a new branch lab1 with:
git checkout master
git pull upstream master  # with upstream/master tracking just use `git pull`
git checkout -b lab1

Write, test and commit code code, then:
git push -u origin

If master on upstream has advanced in the meantime:
git checkout master
git pull upstream master
git checkout lab1
git rebase master
git push -f

