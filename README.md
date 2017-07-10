# After School App - Montgomery Co. MD

**URL:** [After School App](https://rhyanvargas.github.io/after-school-web-app/)

**Developed By:** [Rhyan V Web Solutions](https://rhyanvargas.github.io/rvwebsolutions/)

## Credits

Built using the [Base](https://github.com/CloudCannon/base-jekyll-template) template created by [CloudCannon](http://cloudcannon.com/).

## License

This project and all of its assets are available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT). Please refer to the **LICENSE.md** of this project for additional details. Thanks!

## Git workflow (cheatsheet)

**BEFORE WORKING ON ANY CHANGES**
1. `git checkout gh-pages`
2. `git pull` : update the gh-pages branch to most up to date
3. `git checkout {branchName}` : switch to your branch. A branch should represent work on a specific feature or page. Any config or core changes can be made from `your-name` branch.
4. `git merge gh-pages` : merge the most up-to-date product from `gh-pages` into `{branchName}`

**AFTER MAKING CHANGES**
1. On your branch you made changes to, `git add .` : add all files and changes to staging.
2. `git commit -m {your-commit-message}` : commit changes.
3. `git push`: pushes it to `{branchName}`
4. `git checkout gh-pages`
5. `git merge {branchName}` : merge the most up-to-date product from `{branchName}` into `gh-pages`
6. `git push`: pushes it to `gh-pages`
