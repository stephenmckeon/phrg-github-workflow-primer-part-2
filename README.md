# Pairing Project No. 2

## The Plan

This pairing lesson will pivot team member responsibilities in the middle its tasks. Whomever starts as the driver will switch and become the navigator where the lesson specifies. And vice versa.

Before you start, acquire your designated project repo from the course instructor.

# Creating a webpage with images

## Objectives

1. Reinforce git commands like `clone`, `add`, `push`, and `branch`
1. Reinforce bash commands like `cd`, `pwd`, `mkdir`, and `mv`
1. Create and merge pull requests in Github
1. Use html elements like `head`, `body`, `div` and `image`

## Git cloning

One good way to think about your Github account is that it is your personal file cabinet up in the sky. Github offers you this space in the "Cloud" entirely for free. However, anyone can come by and make a copy of your files from that cabinet. This is exactly what the `git clone` command does. It takes a copy of a set of files, stored in someone's Github account, and then pastes them directly into your local computer. Github calls that file set a public repository, or repo for short. For a fee, Github allows you to put a lock on some of the files in your account. These are called private repos, and Nitro is a great example of this.

Yesterday we created our first public repo on Github. Today, you will be using a previous pair's repo to do your work. This means that both of you will need to use `git clone` to make a copy of another Github user's file cabinet. This can be done with `git clone <copied_ssh_url>`, where the "copied_ssh_url" can be acquired from the Github GUI.

## Pull requests

After we've made updates to our local copy of code, our goal is to update the original Github account copy with our improvements. However, even though the files were free to copy, one can not just go back to the cabinet and swap in our new files (how rude!). So what do we do? We ask permission, or make a `request` to `pull` our new additions into the cabinet. Once we've made this pull request, we wait. When the owner(s) of the Github account have a chance to look at our request, they have the ability to merge it into there "master" copy (a.k.a `master` branch). Now, when someone else comes around to copy these files, they will get your updated version.

## Instructions

* Open up a new shell session & `cd` to your `pairing_projects` directory
* Verify your location with `pwd`
* In your browser, navigate to the Github repository you will be working on today
* Copy its ssh remote url and use `git clone` to pull down a local copy
* `cd` into your copy
* Create a branch called `developer_images` (remember how to do this? If not, check previous lessons)
* Verify your copy now has two branches by running `git branch`

```
[Wed May 02 08:32:21]$ git branch
* developer_images
  master
```

* Jump in Connect and download a headshot of each class member. Make sure all 6 photos are on your Desktop.
* If the photos are not named already, name each of these files with the developer's first and last name, for example: "KraigSchwerin.jpg"
* From your shell, create a new directory called `img`
* Use the `mv` command to move all 6 photos into this new directory on your branch.
* Stage these files with `git add`
* Commit them with `git commit` and a short informative message
* Push them up with your new branch with `git push origin developer_images`
* Create a Pull Request on Github and ask the repo's owner to review the change

## Switch Drivers

Once the repo owner has merged the `developer_images` PR:

* `cd` to your `pairing_projects` directory and verify your location with `pwd`
* Navigate to the Github repository, copy its ssh remote url and clone a local copy
* `cd` into your copy
* Create a branch called `display_images`
* Verify your copy now has two branches by running `git branch`
* Create an `index.html` on root
* Open your branch in your text editor
* Create a basic html template in the index.html. This template should include the DOC type, a head, a body, and a title of "Nitro Bootcamp Students"
* Right click (or control+click) on the index.html in your editor to open the view in your default browser.

![Open in Browser](img/open-in-browser.png?raw=true "Open in Browser")
