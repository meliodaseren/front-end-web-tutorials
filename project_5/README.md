## Installing Jekyll

Jekyll is a Ruby gem (also known as a [RubyGem](http://guides.rubygems.org/what-is-a-gem/))

```bash
$ gem install jekyll
```

## Generate a Static Site

```bash
$ jekyll new personal-website
```

## Preview Your Site Locally

```bash
$ cd personal-website

$ jekyll serve http://localhost:4000/
```

## Jekyll's Directory Structure

Jekyll offers a standard directory structure, as well as components that help speed up development.

1. `_config.yml` - This is a configuration file that contains many values that need to be edited only once. These values are used across your site, for example, your site's title, your e-mail, and more. Note that this is a .yml file, which you can learn more about [here](http://www.yaml.org/start.html).
2. `_includes/` - This directory contains all the partials (code templates that keep you from repeating your code over and over) that your site uses to load common components, like the header and the footer.
3. `_posts/` - This directory is where blog posts are stored. New blog posts can be added and will be rendered with the site's styling, as long as the file name follows Jekyll's standard naming convention.
4. `_layouts/` - This directory contains templates that are used to style certain types of posts within the site. For example, new blog posts will use the HTML layout defined in post.html.

You can learn more about the Jekyll directory structure [here](https://jekyllrb.com/docs/structure/).


