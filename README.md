# PASAWebsite a new website for PASA
To generate, it is best to use linux or Windows Subsystem for Linux if you are on windows.

Ensure ruby is installed:

`sudo apt-get install ruby`

Then install bundler using gem:

`gem install bundler`

cd into the repo and run:

`bundle install`

and finally generate the website by running:

`bundle exec jekyll serve`

the generated website is in the `_site` folder
