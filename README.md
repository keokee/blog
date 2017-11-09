# Keokee

It's pretty minimal, but leverages large type and drastic contrast to make a statement, on all devices.

## Getting Started

If you're completely new to Jekyll, I recommend checking out the documentation at <http://jekyllrb.com> or there's a tutorial by [Smashing Magazine](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/).

```
$ git clone git@github.com:johnotander/pixyll.git
$ cd pixyll
$ gem install bundler # If you don't have bundler installed
$ bundle install
```

#### Verify your Jekyll version

It's important to also check your version of Jekyll since this project uses Native Sass which
is [only supported by 2.0+](http://jekyllrb.com/news/2014/05/06/jekyll-turns-2-0-0/).

### Jekyll Serve

Then, start the Jekyll Server. I always like to give the `--watch` option so it updates the generated HTML when I make changes.

```
$ jekyll serve --watch
```

Now you can navigate to `localhost:4000` in your browser to see the site.

##### If you don't want the header to link back to the root url

You will also need to tweak the header include `/{{ site.baseurl }}`:

```html
<header class="site-header px2 px-responsive">
  <div class="mt2 wrap">
    <div class="measure">
      <a href="{{ site.url }}/{{ site.baseurl }}">{{ site.title }}</a>
      <nav class="site-nav right">
        {% include navigation.html %}
      </nav>
    </div>
  </div>
</header>
```

A relevant Jekyll Github Issue: <https://github.com/jekyll/jekyll/issues/332>

### Contact Form

The contact form uses <http://formspree.io>. It will require you to fill the form out and submit it once, before going live, to confirm your email.

More setup instructions and advanced options can be found at [http://formspree.io](http://formspree.io/)


### Disqus

To configure Disqus, set up a [Disqus site](https://disqus.com/admin/create/) with the same name as your site. Then, in `_config.yml`, edit the `disqus_shortname` value to enable Disqus.

### txtpen

To configure txtpen, set up a [txtpen site](https://txtpen.com/go) with the same name as your site. Then, in `_config.yml`, edit the `txtpen_sitename` value to enable txtpen

### Customizing the CSS

All variables can be found in the `_sass/_variables.scss` file, toggle these as you'd like to change the look and feel of Pixyll.

### Page Animation

If you would like to add a [fade-in-down effect](http://daneden.github.io/animate.css/), you can add `animated: true` to your `_config.yml`.

### AnchorJS

[AnchorJS](https://github.com/bryanbraun/anchorjs): _A JavaScript utility for adding deep anchor links to existing page content. AnchorJS is lightweight, accessible, and has no dependencies._ You can turn it on by toggling `enable_anchorjs`. Because it offers many ways for customization, tweaks should be done in `_includes/footer.html`. Default settings after turning AnchorJS on are:

```html
<script>
    anchors.options.visible = 'always';
    anchors.add('article h2, article h3, article h4, article h5, article h6');
</script>
```

See [documentation](http://bryanbraun.github.io/anchorjs/#basic-usage) for more options.

### Web analytics and search engines

You can measure visits to your website either by using [Google Analytics](https://www.google.com/analytics/) tracking embed or the more advanced [Google Tag Manager](https://www.google.com/analytics/tag-manager/) container.
* For Google Analytics set up the value for `google_analytics`, it should be something like `google_analytics: UA-XXXXXXXX-X`.
* For Google Tag Manager set up the value for `google_tag_manager`, it should be something like: `google_tag_manager: GTM-XXXXX`.
* _Do not_ set both of above methods because this will cause conflicts and skew your reporting data.
* Remember that you need to properly configure the GTM container in its admin panel if you want it to work. More info is available in [GTM's docs](https://www.google.com/analytics/tag-manager/resources/).

Your website is, by default, set to be allowed for crawling and indexing by search engines. (Unless you made yourself a custom robots.txt file). You can use front matter settings on each page to control how search engines will it. Sometimes you may want to exclude a particular page from indexing or forbid Google to store a copy of your page in its cache. It is up to you. Use the `meta_robots` frontmatter key and assign values based on [this table](https://developers.google.com/webmasters/control-crawl-index/docs/robots_meta_tag?hl=en#valid-indexing--serving-directives). Some examples:

```yaml
# exclude page from index
meta_robots: noindex

# allow indexing, disallow caching
meta_robots: noarchive

# allow indexing, disallow crawling links
meta_robots: nofollow

# disallow indexing, follow links
meta_robots: noindex,follow
```

## Upgrading

Pixyll is always being improved by its users, so sometimes one may need to upgrade.

#### Ensure there's an upstream remote

If `git remote -v` doesn't have an upstream listed, you can do the following to add it:

```
git remote add upstream https://github.com/johnotander/pixyll.git
```

#### Pull in the latest changes

```
git pull upstream master
```

There may be merge conflicts, so be sure to fix the files that git lists if they occur. That's it!
