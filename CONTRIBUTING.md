# Contributing

## Development Setup

This website is built using the Jekyll static site generator. As such, you must
install a number of prerequisites in order to actively contribute to this repo:

 1. [**Mac OSX only**] Ensure you have the XCode Developer Command Line Tools installed:

    ```shell
    xcode-select --install
    ```

 2. Ensure you have a version of [Ruby](https://www.ruby-lang.org/) >= `2.0.0` installed:

    ```shell
    ruby --version
    ```

    If not, fix that!


 3. Ensure you have [Bundler](http://bundler.io/) installed:

    ```shell
    gem install bundler
    ```


 4. Ensure you have [Jekyll](http://jekyllrb.com/) ([Jekyll for GitHub Pages](https://help.github.com/articles/using-jekyll-with-pages/), technically) installed:

    ```shell
    bundle install
    ```



## Development Workflow

You can build and serve the site by executing the following command:

```shell
bundle exec jekyll serve
```

Optionally, if you want Jekyll to monitor your pages' source files and automatically rebuild them on the fly if they change, you can add the `--watch` flag:

```shell
bundle exec jekyll serve --watch
```



## More Information

For further info on this workflow, use the following resources:

 - the [Jekyll for GitHub Pages documentation](https://help.github.com/articles/using-jekyll-with-pages/)
 - the [Jekyll documentation](http://jekyllrb.com/docs/home/)
