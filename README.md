#Introduction#
Jekyll is a simple, blog aware, static site generator. It takes a template directory (representing the raw form of a website), runs it through Textile or Markdown and Liquid converters, and spits out a complete, static website suitable for serving with Apache or your favorite web server. This is also the engine behind GitHub Pages.

In Comoyo we use Jekyll as our static blog, where you can fork, make pull requests, and write simple Markdown to serve a hyper-efficient blog straight from github. The blog will be available from comoyo.github.com.

#Getting started#
* Make sure you have Ruby installed. 1.8.7 or newer will do.
* Run: 
    $ gem install bundler
* Fork this repo to your personal repo, and make a clone.
* In the root of the project, run: 
    $ bundle install
* Compile the blog with
    $ jekyll
* See the blog at localhost:4000

See https://github.com/mojombo/jekyll and https://github.com/mojombo/jekyll/wiki/usage for further details.

To create a post, use one of the samples below, or copy the sample post in _posts

#Adding authors#
Authors are added in _config.yml. Please use the same indentation, name and format when adding an author. 

#Samples#
This gives some minimal samples for posts. Keep them in this format, and update old ones should convention change.

##Posts##
    ---
    layout: post
    author: dagingaa
    title: How I Stopped Worrying and Love the Atom Bomb
    category: Test
    ---
    Your awesome post here

#Plugins#
    Github Pages does not support custom plugins.

