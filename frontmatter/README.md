# common

A repository for commonly-used DITA files that can be incorporated into other repositories via Git Submodules

## How to Use

This repository can be used within other repostiories as a [Git Submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules).  As a submodule, this repository's content will magically appear as a subdirectory within your git repository.

1. Using a terminal from within your Git repository: `git submodule add https://github.com/intel-restricted/documentation.books.design-kits.common.git common`.  It is important provide the name *common* at the end of the command, else the submodule directory shall have the full name of the repository 🤮.
2. This repository shall not be available within your repostory as `common`.  You may update common references in your ditamaps to point to the appropriate file(s) within this location.
3. Stage and commit your changes using your preferred method.  From a terminal this would be `git add -A` to add all changed files, `git commit -m "type a commit message here"` to commit change and finallly `git push origin {your-branch-name}` to push your changes back to GitHub
4. That's it!

## Further Reading

* [Git Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) - Official Documenation
