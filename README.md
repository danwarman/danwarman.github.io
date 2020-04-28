# Personal Site

I don't have much of a portfolio right now. The past several years of working experience have been dedicated to ecommerce companies and developing in private repositories. That said, this is to be the space to include anything I feel worthy of showcasing (if i'm allowed to).

## Getting Started

These instructions will enable someone (me when I forget) to run a copy of this project locally.

As I develop on a Mac, this will be focused on setting up for Mac only.

### Prerequisites

To develop locally, I am using Jekyll. Jekyll is a Ruby program so there are a few requirements to run it and manage gem dependencies.

The following are requirements to get up and running.

#### Install Homebrew
Homebrew is a package manager that will ensure installing further dependencies is simple.

It can be installed in the projects directory root - where all personal projects are located.

**Official Documentation:** https://brew.sh/

Paste the following command in to macOS Terminal:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

#### Install Ruby
To run Jekyll, a Ruby program, Ruby must be installed. This can be done in the project root as other projects may not be using Ruby.

**Official Documentation:** https://www.ruby-lang.org/en/documentation/installation/

With Homebrew installed, we can simply paste the following in to macOS Terminal:

```
brew install ruby
```

On completion, the following command should successfully return the Ruby version:
```
ruby -v
```

#### Install Jekyll
Best to follow the official documentation here - it's only a few simple steps.

**Official Documentation:** https://jekyllrb.com/docs/step-by-step/01-setup/

### Build

With Jekyll installed, the following commands can be run in macOS Terminal to build the site and/or run the local webserver:

* `jekyll build` - Builds the site and outputs a static site to a directory called _site.
* `jekyll serve` - Does the same thing except it rebuilds any time you make a change and runs a local web server at `http://localhost:4000`.

## Deployment
I'm using Github Pages to deploy this site which is running off of the `master` branch.

I am **not** coding directly on `master` but am instead creating new branches and opening pull requests in to it. This way, I can cleanly mantain code and review my own work to erradicate any potential errors or typos.

## Built With

// TODO

