# Resume template

*A simple Jekyll-powered resume template.*

![img](images/screenshot.png)

## Docs

### Running locally

First install the [Jekyll prerequisites](https://jekyllrb.com/docs/#instructions).

To test locally, run the following in your terminal:

```bash
bundle install
bundle exec jekyll serve
```

Open your browser to the location printed in the terminal output (default `http:://127.0.0.1:4000`).

### Running locally with Docker

To test locally with docker, run the following in your terminal after installing docker into your system:

```bash
docker image build -t resume-template .
docker run --rm --network host resume-template
```

### Customizing

First you'll want to fork the repo to your own account. Then clone it locally and customize, or use the GitHub web editor to customize.

#### Options/configuration

Most of the basic customization will take place in the `/_config.yml` file. Here is a list of customizations available via `/_config.yml`:

[...write these out...]

#### Editing content

Most of the content configuration will take place in the `/_layouts/resume.html` file. Simply edit the markup there accordingly

### Publishing to GitHub Pages for free

[GitHub Pages](https://pages.github.com/) will host this for free with your GitHub account. Just make sure you're using a `gh-pages` branch, and the site will automatically be available at `yourusername.github.io/resume-template` (you can rename the repo to resume for your own use if you want it to be available at `yourusername.github.io/resume`). You can also add a CNAME if you want it to be available at a custom domain...

### Configuring with your own domain name

To setup your GH Pages site with a custom domain, [follow the instructions](https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/) on the GitHub Help site for that topic.

## License

The code and styles are licensed under the MIT license. [See project license.](LICENSE) Obviously you should not use the content of this demo repo in your own resume. :wink:

Disclaimer: Use of Lisa M. Simpson image and name used under [Fair Use](https://en.wikipedia.org/wiki/Fair_use) for educational purposes. Project license does not apply to use of this material.
