# TODO:
* add photos to the engineering projects listed
* use a better layout then html tables which is bad form. See [here](https://www.w3schools.com/html/html_layout.asp)

# To view site locally with Jekyll
Instructions for setup are described [here](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/).

To launch, run
```
bundle exec jekyll serve
```
And I can preview the local Jekyll site in the web browser at `http://localhost:4000`

You can view on a mobile device in the same local network by running the following
```
ssh -R 80:localhost:4000 ssh.localhost.run
```
and then going to `https://trefor.localhost.run` on the local device.
