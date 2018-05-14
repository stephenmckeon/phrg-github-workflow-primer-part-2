# Pairing Project No. 2

## The Plan

In the middle of this lesson's tasks, your responsibilities will pivot. Whomever starts as the driver will switch and become the navigator where the lesson specifies. And vice versa.

Before you start, acquire your designated project repo from the course instructor.

# Creating a webpage with images

## Objectives

1. Reinforce git commands like `clone`, `add`, `push`, and `branch`
1. Reinforce bash commands like `cd`, `pwd`, `mkdir`, and `mv`
1. Create and merge pull requests in Github
1. Use html elements like `head`, `body`, `div` and `image`

## Git forking and cloning

One good way to think about your Github account is that it is your personal file cabinet up in the sky. Github offers you this space in the "Cloud" entirely for free. However, anyone can come by and make a copy of your files from that cabinet. This is exactly what happens when you click "Fork".

Forking makes a copy of the selected file system, stored in someone else's Github account, and then adds it to your account. You can then use `git clone` to copy those files down to your local computer.

Github calls these file sets public repositories, or repos for short. For a fee, Github allows you to put a lock on some of the files in your account. These are called private repos, and Nitro is a great example.

Yesterday we created our first public repo on Github from scratch. Today, you will be using another pair's repo to do your work. This means that both of you will need to fork and clone the code down to your laptop. This can be done by "forking" from the Github GUI and using `git clone <copied_ssh_url>`, where the "copied_ssh_url" can be acquired from your fork's repo page.

## Pull requests

After we've made updates to our local copy of code, our goal is to update the original Github account's copy with our improvements. However, even though the files were free to copy, one can not just go back to the cabinet and swap in our new files (how rude!).

So what do we do? We ask permission, or make a `request` to `pull` our new additions into the original account. Once we've made this pull request, we wait. When the owner(s) of the Github account have a chance to look at our request, they have the ability to merge it into their "master" copy (a.k.a `master` branch). Now when someone else comes around to copy these files, they will get your updated version.

## Instructions

* Open up a new shell session & `cd` to your `pairing_projects` directory
* Verify your location with `pwd`
* In your browser, navigate to the Github repository you will be working on today
* Fork the repo into your account
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
* Navigate to the Github repository and fork it into your account
* Copy the ssh remote url and clone a local copy
* `cd` into your copy
* Create a branch called `display_images`
* Verify your copy now has two branches by running `git branch`

```
[Wed May 02 09:35:44]$ git branch
* display_images
  master
```

* Create an `index.html` on root
* Open your branch in your text editor
* Create a basic html template in the index.html. This template should include the DOC type, a head, a body, and a title of "Nitro Bootcamp Students"
* Right click (or control+click) on the index.html in your editor to open the view in your default browser.

![Open in Browser](https://raw.githubusercontent.com/powerhome/phrg-github-workflow-primer-part-two/master/open-in-browser.png?raw=true "Open in Browser")

A new blank browser view should just have opened. Check to see that your title is showing up in the browser tab:

![Browser Title](https://raw.githubusercontent.com/powerhome/phrg-github-workflow-primer-part-two/master/browser-title.png?raw=true "Browser Title")

Experiment with adding some content inside the html `body` and refreshing the window.

* Wrap "Nitro Bootcamp Students" in a `h1` element, nested inside the body tag
* Add `h2` elements that with each person's name, just like the Markdown README is organized

A very common HTML element is `div` which stands for division. These elements are used to logically group related content in a web view.

* Wrap each `h2` element in a div with a class attribute of "developer"
* Inside each div, under the header elements, add an img tag with a source pointing towards the developer images. Size the images as 100x100 pixels. Remember to utilize Google and previous lessons if you run into difficulties.

Your local browser view should now look like:

![Developer Images](https://raw.githubusercontent.com/powerhome/phrg-github-workflow-primer-part-two/master/developer-images.png?raw=true "Developer Images")

* Git add, commit, and push your changes
* Open a PR in Github and include a screenshot of your work in the PR's body. You can drag and drop images directly into the text area where you write your PR description.

It is important to make reviewing Pull Requests as easy for the reviewer as possible. It makes assessing your changes much more understandable.

End this lesson by asking the repo owner to review & merge your work. If you are a repo owner, make sure there is a screen shot of the final product in the PR's body before you accept the changes.
