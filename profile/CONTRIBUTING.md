# Contributing to WFP-VAM Projects 

> [!IMPORTANT]  
> **FOR WFP STAFF**
> 
> Make sure to [setup your account](https://github.com/WFP-VAM/ram-data-science-tools-docs/blob/main/docs/how-to/set-up-github-account.md) and request to be added to the WFP-VAM GitHub organization

Thank you for your interest in contributing to our projects. If you're interested in contributing or collaborating on our projects, please follow our guidelines outlined in the CONTRIBUTING file in each repository.

> [!NOTE]
> **WORK IN PROGRESS**

## Getting started
Make sure you have: 
- Created a GitHub account
- Installed Git on your work laptop
- *(Optional)* Installed GitHub Desktop on your computer laptop.

If you need a refresher on GitHub, review [this guide](https://www.freecodecamp.org/news/guide-to-git-github-for-beginners-and-experienced-devs/). [GitHub Docs](https://docs.github.com/en/get-started/start-your-journey/about-github-and-git) is also an excellent point to start!

## Best practices
- In WFP we use git for version control. All code that could ever need to be read by others should be in a shared repository. 

### Do not commit secrets
- `.gitignore` should be used to prevent adding sensitive, large or unnecessary files to the git index. 
- Only use git to version plain text files such as code syntax, txt, and csv. Do not commit proprietary file types such as excel, word or STATA files.
- Use templates for your specific language to simplify your life
- If you committed files you shouldn't have to, make sure to remove the files and rewrite history using a tool like [git-filter-repo](https://github.com/newren/git-filter-repo)
- If you made a mistake with Git (we've all been there), [here's how to fix your mistake](https://ohshitgit.com/)

### Contributing to an existing repository
- All new work should be created in a dedicated feature branch. 
- If you're contributing to a WFP project, prefer submit your work via a feature branch in the same repo as the original, instead of forking the repository and pulling a PR from there. Instead, fork repositories if the project is maintained outside of WFP (e.g. other UN agency, open source library).
- Main branches should always be protected to avoid direct commits.
- The code changes should always be exposed via a PR into main. In all but the most urgent or trivial cases, the PR should be reviewed and approved before merging.

### License
- Always add a license to all your repositories! Licenses define what can and cannot be done with your code, including  redistribution, modification, commercial use etc.
- In WFP we use [GNU Affero GPL 3.0](https://www.gnu.org/licenses/agpl-3.0.en.html)

### Branches
- Make small, logically coherent, frequent commits, with helpful commit messages.
- Use [conventional commits](https://www.conventionalcommits.org) for your commit messages and branch names
- [GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow) should be preferred

### Documentation
- Make sure your repo(s) have a README file with documentation to understand, install and run your projects
- Make  sure your repo is licensed under the GNU Affero General Public License v3.0 license.
- *(Optional)* Include a CONTRIBUTING guideline if you would like to attract collaborators

### Versioning
- Use [Semantic Versioning](https://semver.org/) conventions to version your code version
- Make sure to tag your code in GitHub
- Use Releases every time you release a major version of your tools

## Projects currently open for contribution:
- [RAM Resource Scripts](https://github.com/WFP-VAM/RAMResourcesScripts)

## Resources
- [Git Best Practices to Start Using in Your Next Commit](https://sourcelevel.io/blog/7-git-best-practices-to-start-using-in-your-next-commit)
- [Git Commit Best Practices](https://gist.github.com/luismts/495d982e8c5b1a0ced4a57cf3d93cf60)
