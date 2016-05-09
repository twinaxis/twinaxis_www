# twinaxis_www
jekyll source for https://twinaxis.com

# What is this?
A very basic website for the domain https://twinaxis.com.  I'm trying to become more comfortable with Jekyll as a static site generator.  Most of the initial commits are just to setup the plumbing so that it auto-deploys.  On the hosting provider, I have a post-receive git hook that deploys the latest version.  On a development system, I configured a remote deploy target that pushes to that git repo.  Every time I push, it redeploys to the www folder and updates the website.  

# Should I fork this?
I wouldn't bother unless we add something really interesting, it is basically the output of jekyll new w/ very little modification.

