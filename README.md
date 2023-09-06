# [0xblue2.github.io](https://0xblue2.github.io)
my attempt at blockchain stuff

made with mdbook using github pages + github actions:
- created repo with title = USERNAME.github.io
  - included root README, but I don't think it's necessary
  - I think making the title USERNAME.github.io automatically sets you up for github pages, but I might have missed something
  - https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- created `src/...`:
  - book.toml
  - SUMMARY.md
  - https://rust-lang.github.io/mdBook/guide/creating.html
- added mdbook github action to turn project files into build files that are served by pages
  - go to top bar -> Actions(has a triangle in circle, looks like play button)
  - should already show github pages as an action
  - click "New Workflow"
    - from there you can search "mdbook" or scroll down to the "Pages" section and manually look for mdbook actions
    - https://github.com/actions/starter-workflows/blob/main/pages/mdbook.yml
    - https://docs.github.com/en/actions/using-workflows/about-workflows#using-starter-workflows
   
Note: I did this in the wrong order, but I think it is the easiest way.
Note 2: If you're making a lot of edits, you can go to the mdbook github action workflow(called "Deploy mdBook site to Pages" by default I think) -> click 3 buttons -> disable workflow
