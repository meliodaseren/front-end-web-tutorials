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


## Domain Name System (DNS)

![Domain Name System (DNS)](./images/domain_name.png)

In the top portion of the diagram:

1. Bob wants to call Sue, but does not have Sue's phone number memorized.
2. Bob types "Sue" into his phone and his phone identifies the phone number associated with Sue.
3. The phone call is then made. Sue's phone receives a request (it rings). If Sue answers, Bob and Sue are connected and can now communicate.

Your computer communicates with websites in a simliar fashion.

In the bottom portion of the diagram:

1. Bob wants to load the Codecademy website, but does not have Codecademy's IP address memorized.
2. Bob types www.codecademy.com into his browser and the DNS then identifies the IP address associated with www.codecademy.com.
3. The request to load Codecademy's website is then made. If the server successfully responds, Bob can now load and communicate with Codecademy's website.

For more details, read the following Codecademy resource:

* [HTTP Requests](https://www.codecademy.com/articles/http-requests)

![DNS](./images/DNS.png)

```bash
$ dig www.yourcustomdomain.com
```
