# Chunchun's personal website

The code is originally forked from the [`github/personal-website`](https://github.com/github/personal-website) repo.

## Installation

### Install in your local development environment

If you want to manage your website in a local web development environment, you'll be using [Ruby](https://jekyllrb.com/docs/installation/).

Once you've found a home for your forked repository, **[clone it](https://help.github.com/articles/cloning-a-repository/)**.

```
git clone https://github.com/appletreeisyellow/appletreeisyellow.github.io.git
cd appletreeisyellow.github.io.git
```

#### Install Jekyll

Jekyll is a [Ruby Gem](https://jekyllrb.com/docs/ruby-101/#gems) that can be installed on most systems.

1. Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/)
2. Install Jekyll and [bundler](https://jekyllrb.com/docs/ruby-101/#bundler) [gems](https://jekyllrb.com/docs/ruby-101/#gems)

```
gem install jekyll bundler
```

3. Change into your new directory

```
cd personal-website
```

4. Install missing gems

```
bundle install
```

5. Build the site and make it available on a local server

```
bundle exec jekyll serve
```

You should see something like:

```
Configuration file: /octocat/personal-website/_config.yml
            Source: /octocat/personal-website
       Destination: /octocat/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.
                    done in 14.729 seconds.
 Auto-regeneration: enabled for '/octocat/personal-website'
    Server address: http://127.0.0.1:4000
  Server running... press ctrl-c to stop.
```

Don't worry about the "No GitHub API authentication could be found" message. [API authentication is only necessary](https://github.com/jekyll/github-metadata/blob/master/docs/authentication.md) if you intend to display more detailed metadata, like a branch name.

6. Now browse to [http://localhost:4000](http://localhost:4000)

## Develop and deploy

**Use `master` branch to push all the original code.**

The code on `gh-pages` branch is automatically generated by Github Action if the action workflow on `master` branch is successful.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## TODO

- [x] Github Action
- [ ] SEO
- [ ] Google Analytics
- [ ] site map
- [ ] web3forms.com?
