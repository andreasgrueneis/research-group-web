
# Intro and set up

To get the site running do the following:

  sudo apt-get install ruby-dev
  sudo gem install jekyll
  sudo pip2 install pybtex

First initialize git submodules (need to be done only once)

  git submodule update -i

and then just make

  make

if you want to serve it just hit

  make serve

# Usual workflow

The usual workflow is that you create a local server to actually serve
locally the generated website, you do this by doing

  make
  make serve

After this, you can open the website in your browser, for example if
it is in the port 4000 you can go to firefox and open the url

  localhost:4000

Now if you edit one file, the jekyll serve will generate the website
automatically.
