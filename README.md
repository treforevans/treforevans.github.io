# TODO:
* consider using a powerful theme like [this](https://github.com/sourcethemes/academic-kickstart) that will make the website look good more easily
* update profile pic. Make aspect ratio narrower so renders better on small screens
* add an arrow for the DIRECT image from continuous to discrete
* complete the boundary of Ontario for the gp-grid image
* switch gp-grief pic to the poster version
* list the courses I have TA'd
* consider adding a list of awards and achievements (see CV)

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
