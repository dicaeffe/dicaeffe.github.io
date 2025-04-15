# dicaeffe.github.io

My Github pages repository. Just a POC.

![GitHub](https://img.shields.io/github/license/dicaeffe/cv)
![GitHub tag](https://img.shields.io/github/v/tag/dicaeffe/cv)
![Status](https://img.shields.io/badge/status-work%20in%20progress-red)

# Dev

- Edit files in the docs directory
- Run `bundle install`

## Locla run

You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

- `cd docs`
- `jekyll serve`

# Blog

Jekyll requires blog post files to be named according to the following format:

- `YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

# Issues

If you get `You have already activated X, but your Gemfile requires Y` error message, then solve with:

- `bundle clean --force`

# Theme

- You can override theme's setting by creating the html files in the `docs/_layouts` directory.
- if you want to see the theme's default files use the command `bundle info --path minima` (where _minima_ is the name of the theme)
