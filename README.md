# get-open-prs
![status](https://circleci.com/gh/:owner/:repo.svg?style=shield&circle-token=:circle-token)
# Installation
- Put the github usernames of your team members as an array of strings in the `team.json` file.
- Set an environment variable called `GITHUB_TOKEN` with your github api token.
- `npm install -g` to install globally and to be able to use the keyboard shortcut anywhere.
- You can now get the current open prs for your team by typing `gop` in any directory.
![screenshot](https://raw.githubusercontent.com/sdotson/get-open-prs/master/screenshot.png)
- After typing the `gop` command, a prompt will appear for you to select a specific pr to review. Once you hit enter, your default browser will open the pr.
- You'll then be given the option to continue reviewing other prs.
