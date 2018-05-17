# Install Instructions

Install Ruby (version Ruby+Devkit 2.4.X (x64)), from [here](https://rubyinstaller.org/downloads/).

## Jekyll

Go to the command line and execute:

```sh
gem install jekyll bundler jekyll-paginate #This is going to install Jekyll, Bundler and jekyll-paginate on your PC
jekyll -v #To make sure it is instaled correctly
```

[Jekyll Docs](https://jekyllrb.com/docs/configuration/)

[Jekyll Paginate](https://jekyllrb.com/docs/pagination/)

## Run Localy

To run the site localy, execute:

```sh
bundle exec jekyll serve -w # "-w" for watch
```

## Add Pages

To see more about the structure and how to do things to this theme see: [Add Pages](add.pages.md)