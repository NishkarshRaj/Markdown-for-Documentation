# Markdown-for-Documentation
```
GitHub Readme used for documentation also used .md (markdown) files for documentation.
Note, for all webpages containing any number of md files, GitHub only renders the README.md file on current page if present.
```
**Note**   
```
Markdown files can include <html> language code as both are compatible.
```
## Table of Contents:

[1. Heading](https://github.com/NishkarshRaj/Markdown-for-Documentation/tree/master/Heading)

[2. Paragraph](https://github.com/NishkarshRaj/Markdown-for-Documentation/tree/master/Paragraph)

[3. Linebreak](https://github.com/NishkarshRaj/Markdown-for-Documentation/tree/master/Linebreak)

[4. Emphasis](https://github.com/NishkarshRaj/Markdown-for-Documentation/tree/master/Emphasis)

[5. Blockquote](https://github.com/NishkarshRaj/Markdown-for-Documentation/tree/master/Blockquote)

[6. Lists](https://github.com/NishkarshRaj/Markdown-for-Documentation/tree/master/Lists)

[7. Code](https://github.com/NishkarshRaj/Markdown-for-Documentation/tree/master/Code)

[8. Horizontal rules](https://github.com/NishkarshRaj/Markdown-for-Documentation/tree/master/Horizontal%20Rules)

[9. Links](https://github.com/NishkarshRaj/Markdown-for-Documentation/tree/master/Links)

[10. Images](https://github.com/NishkarshRaj/Markdown-for-Documentation/tree/master/Images)

[11. Escaping characters](https://github.com/NishkarshRaj/Markdown-for-Documentation/tree/master/Escaping%20Characters)

[12. Emojis](https://github.com/NishkarshRaj/Markdown-for-Documentation/tree/master/Emojis)

## How to Contribute

1. Fork the repository to your own GitHub account.

2. Clone the repository to your local machine
```
$ git clone "https://www.github.com/{Username}/Markdown-for-Documentation.git"
```
where username is your GitHub account username.

3. Create a branch where you can do your local work.
Never work on **master** branch as we do not allow master commits except by admins.
```
$ git branch {branchname}
$ git checkout branchname
```

4. Do your work and stage your changes.
```
$ git add <filename>
```

5. Commit you changes with a commit message containing your name, file(s) worked upon, changes added.
```
$ git commit -m "Name| files| Changes"
```

6. Push changes to your forked repository
```
$ git push -u origin branchname
```
7. Create a pull request to the upstream repository.

## Synchronize forked repository with Upstream repository

1. Create upstream as our repository
```
$ git remote add upstream "https://www.github.com/NishkarshRaj/Markdown-for-Documentation"
```

2. Fetch upstream changes in local machine
```
$ git fetch upstream
```

3. Switch to master branch
```
$ git checkout master
```

4. Merge changes in local machine
```
$ git merge upstream/master
```

5. Push changes to your forked GitHub repository
```
$ git push -f origin master
```

## References

[Markdown Guide](https://www.markdownguide.org/basic-syntax)

