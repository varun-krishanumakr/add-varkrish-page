# How to edit your personal page

1. Fork the group website repo https://github.com/uw-echospace/group-website (the "upstream")
2. Create a branch with a meaningful name, such as `add-ID-page` where `ID` is your github account or UW NetID
3. Find your UW NetID under `/content/authors/NETID`
4. Edit `/content/authors/NETID/_index.md`
    - Update various standard fields
    - Add a blurb about yourself and your project(s) below the `---` line
5. Replace `/content/authors/NETID/avatar.jpg` with your picture
6. Create a PR to the `master` branch of the upstream repo
7. Check page build results at the [testing page](https://uw-echospace.github.io/testview/author/MYNAME/) where `MYNAME` is a string with your names connected with hyphens
8. Push any changes to the same branch. Each push will trigger a new build and deployment. Wait for a few minutes to check the testing page for the changes. Repeat this step until you’re happy with the outcome.
9. Tag @leewujung to merge your PR to master. Once merged, your info will be updated on the official page.

