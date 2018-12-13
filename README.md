# website_blogdown
Blogdown code for the dspg2019 website

# first time setup

```bash
git clone git@github.com:dspg2019/website_blogdown.git
cd website_blogdown
git submodule init
git submodule update
```

# Make changes to website

Separate pages are found in `./content/about/`

Update the text on the front page using the `config.toml`

1. After you make changes to the files, in rstudio you can go to addins > serve site to view and build thd website.
2. When you are happy, commit the changes to the files you made
3. `cd` into the dspg2019.github.io folder and separately commit all the updated files, do not change anything here manually
4. `push` your changes to `dspg2019.github.io`
5. go back up to the website_blogdown and commit the `dspg2019.github.io` reference
6. `push` your changes to `website_blogdown`
