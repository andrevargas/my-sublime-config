# MySublimeConfig

My own Sublime Text 3 preferences, available here just to make it portable between my machines. :computer: :left_right_arrow: :computer: <br />
Inspired ~~but not forked~~ from @sirgalligrey's [repo](https://github.com/sirgallifrey/my-sublime-confs).

## How to setup
To start, there are some *dependencies* that need to be met. This guide assumes you have previously installed:
* [Sublime Text 3](https://www.sublimetext.com/3)
* [Package Control](https://packagecontrol.io)
* Of course, [Git](https://git-scm.com/)

With all the prerequisites installed, you need to init a **Git Repository** inside your Sublime Text 3 configuration folder, then add this repo as a **remote**. Type the following commands in your terminal:

```bash
cd ~/.config/sublime-text-3/Packages
git init
git remote add origin https://github.com/andrevargas/my-sublime-config.git
git fetch
git reset --hard origin/master
```
The `git fetch` command allows you to pull this repo's content without merging any changes to your previous Sublime Text configuration. Then, `git reset --hard` will do the rest of the job, restoring your *workdir* to the latest commit of this repo's `master` branch, sweeping out your previous configuration, if it existed.

That's it! Have fun! :sparkles: