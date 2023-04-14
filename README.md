# quarto-imis-slide-template

This is a template project for making slides in quarto using the IMIS logo.

The repository home is: https://github.com/Sumidu/quarto-imis-slide-template.
Check back frequently for updates.

Extensions of this template are welcome :)

## Requirements

This template requires quarto (version 1.2.269+) and uses `renv` to manage dependencies.

You can restore the project after installing it by calling executing the following code in your R console:

```
install.packages("renv")
renv::restore()
``` 


## Hosting reveal.js presentations on Github

You can preview the presentation template [here](https://sumidu.github.io/quarto-imis-slide-template/).
If you want to host your presentation at GitHub do the following:

- put all you output files in a `docs` subfolder.
- name the presentation output `index.html`
- activate github pages and pick the folder option in you branch.

There are more intricate ways of sharing your presentation on github using github actions.
Please read them up if you have more complext content (e.g. complex data analysis).
