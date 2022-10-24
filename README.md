# Instruction

Clone both `plas22_src` and `plas2022.github.io` repositories.

`git clone https://github.com/plas2022/plas22_src.git`

`git clone https://github.com/plas2022/plas2022.github.io.git`

Next use Jekyll to compile `plas20_src`:

`bundle exec jekyll serve --destination [address of plas2022.github.io directory]`

Here we use `--destination` option to directly compile into the `plas2022.github.io` repo.

Finally, go to the `plas2022.github.io` repo and `git add`, `git commit` and `git push`.

# Structure of plas22_src

For updating the information of PC members, modify the `people.yaml` file in `_data` directory.

For adding the program update `program.yaml` in `_data` directory.

- Note: right now the sections "Program" and "Invited speaker" are commented out in the `index.html` file.
  

For updating the information about the dates and zoom/slack links, modify the `offerings.yaml` file in `_data` directory.

- Note: right now the part about "Zoom" and "Slack" links is commented out in the `index.html` file.
  

Any other information, is hard-codded inside `index.html`
