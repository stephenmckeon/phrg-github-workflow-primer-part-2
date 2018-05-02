# Pairing Project No. 2

## The Plan

This pairing lesson will pivot team member responsibilities in the middle its tasks. Whomever starts as the driver will switch and become the navigator where the lesson specifies. And vice versa.

Before you start, acquire your designated project repo from the course instructor.

# Creating a webpage with images

## Objectives

1. Reinforce git commands like `clone`, `add`, `push`, and `branch`
1. Reinforce bash commands like `cd`, `pwd`, `mkdir`, and `mv`
1. Create and merge pull requests in Github
1. Reinforce html template elements like `head`, `body`, `div` and `image`

## Git cloning

One good way to think about your Github account is that it is your personal file cabinet up in the sky. Github offers you this space in the "Cloud" entirely for free. However, anyone can come by and make a copy of your files from that cabinet. This is exactly what the `git clone` command does. It takes a copy of a set of files, stored in someone's Github account, and then pastes them directly into your local computer. Github calls that file set a public repository, or repo for short. For a fee, Github allows you to put a lock on some of the files in your account. These are called private repos, and Nitro is a great example of this.

Yesterday we created our first public repo on Github. Today, you will be using a previous pair's repo to do your work. This means that both of you will need to use `git clone` to make a copy of another Github user's file cabinet. This can be done with `git clone <copied_ssh_url>`, where the "copied_ssh_url" can be acquired from the Github GUI.

## Pull requests

After we've made updates to our local copy of code, our goal is to update the original Github account copy with our improvements. However, even though the files were free to copy, one can not just go back to the cabinet and swap in our new files (how rude!). So what do we do? We ask permission, or make a `request` to `pull` our new additions into the cabinet. Once we've made this pull request, we wait. When the owner(s) of the Github account have had a chance to look at our request to improve the code, they have the ability to merge it into there "master" copy (a.k.a `master` branch). Now, when someone else comes around to copy these files, they will get your additions as well.

## Instructions


