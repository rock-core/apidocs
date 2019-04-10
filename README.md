# Rock Website Management

This package contains the [jekyll](https://jekyllrb.com/) based website
generation for Rock Robotics API Doc
The website can be accessed as https://rock-core.github.io/apidocs


## Local generation of the website

### Prerequisites
Without an existing Rock installation
you have to install jekyll using rubygems.

With an existing Rock installation 
add the following to your install/gems/Gemfile:
```
  gem "jekyll",">=3.3.0"
```
and run
```
bundle update
```

### Rendering of the website

Run

```
jekyll serve -c _config.yml
```

Open http://127.0.0.1:4000 in a browser to view the current website.
