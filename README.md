# wildaye.co.uk

This is a github site operated by photographer Kara Hood (Kara Mudie). It runs on jekyll, built and served by github pages from [wildaye.co.uk](https://wildaye.co.uk). The orgininal template was [photorama](https://github.com/sunbliss/photorama) by 
Anna Prigkipaki ([@sunbliss](https://github.com/sunbliss)) but the code has been heavily modified.

## Writing a blog post

Your blog posts (aka "journal" entries) are in the `_posts` folder. Each file is one post. The filename should be something like `2020-11-21-holiday-story.md`. The best way to make a new post is to copy an existing file and change the filename and then edit it from there.

You should start by editing the YAML header to give the new post a title, subtitle, date, and so on. The edit the body of the story. You are writing in *markup*, which make it easy to focus on the text without worrying about details of the layout.

## Collections
You can organise photos on the site into *collections*, which are accessed through the *gallery* menu. Each collection has its own markdown file in the *_collections* folder. The name of the file is the name of the collection. The images themselves go in a folder with exactly the same name under the *img* folder. 

So, to make a new collection called "Landscape"

* Add a folder called "Landscape" to the *img* folder
* Place all of the images for the new collection in that Landscape folder. Make sure they are between 1600 and 2000 pixels wide.
* Add a file called `Landscape.md` in the `_collections` folder
* List the images with their titles in the YAML header of the new Landscape.md file.
* Add the new collection to the `gallery/index.md` file so it appears on the Gallery page.

## Galleries

* Landscapes
* Living Things
* Plant Life
* Seascapes
