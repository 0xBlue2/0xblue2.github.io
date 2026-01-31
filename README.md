# [0xblue2.github.io](https://0xblue2.github.io)

Website that uses github pages + mdbook

mdbook Docs: https://rust-lang.github.io/mdBook/

Here's how I remember making this website, but some of the steps could be wrong:

- created a repository with title "USERNAME.github.io"
  - included a README.md file in the root, but I don't think it's necessary
  - I think making the title USERNAME.github.io automatically sets you up for github pages, but I might have missed something
  - docs here: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- created a directory called `src` with the following contents:
  - book.toml
  - SUMMARY.md
  - more docs here: https://rust-lang.github.io/mdBook/guide/creating.html
- added a mdbook github action to run mdbook + tell github to serve the generated files
  - go to the top bar -> Actions(has a triangle in circle, looks like play button)
  - might already show github pages as an action
  - click the green button "New Workflow"
    - from there you can search "mdbook" or scroll down to the "Pages" section and manually look for mdbook actions
    - https://github.com/actions/starter-workflows/blob/main/pages/mdbook.yml
    - https://docs.github.com/en/actions/using-workflows/about-workflows#using-starter-workflows
   
Note 1: If you're making a lot of edits and don't want the live site to update each time, you can go disable all worflows in the repository settings:

Instructions here: https://github.com/orgs/community/discussions/58971
