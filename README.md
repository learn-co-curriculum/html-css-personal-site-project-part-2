# Personal Site Project - Part 2

## Objectives

1. Add links, text, and images to HTML pages
2. Save your work and publish to Github

## Instructions

It is time to put what you have learned into practice and grow confidence by building on your own. Your personal website project can be about anything you want. Many students have done portfolio projects, fan sites for a pet or music group, wedding sites, informative sites for non-profits or a family business, and much more. Limit yourself to a simple design and not more than five or six pages. Plan to build something that isn't more complex than the code along videos you have watched. If you get stuck you can refer back to the previous lectures on how to do the things asked of you in this challenge. Below are the step by step instructions you can use as a general guide. Feel free to add more things if you wish or leave things out if they do not apply to your projects needs.

1. In your Learn IDE in the Terminal area, change directory into the folder for your project you created previously in part 1 `cd <your-project-name>`.

2. Make sure you are on your master branch `git checkout master` and create a new branch called site-content like so: `git checkout -b site-content`.

3. Let's create an images folder `mkdir images`

4. Place at least one image into the images folder. 

5. Next, open your favorite code editor and make sure to include at the minimum the following things in your projects HTML page(s):
  - link
  - image
  - heading
  - paragraph
  - list
  - table

6. Once you're finished, preview your code in the browser and if you're satisfied with the way it looks and all code validates, then go ahead and stage, and commit your changes `git add .`, `git commit -m "part 2"`.

7. Then let's merge this branch into master. First `git checkout master`, then `git merge site-content`.

8. Then push it up to your remote `git push origin master`.

9. Then let's merge this branch into gh-pages to see it live. First `git checkout gh-pages`, then `git merge master`.

10. Then push it up to your remote `git push origin gh-pages`.

<p class='util--hide'>View <a href='https://learn.co/lessons/html-css-personal-site-project-part-2'>HTML CSS Personal Site Project Part 2</a> on Learn.co and start learning to code for free.</p>
