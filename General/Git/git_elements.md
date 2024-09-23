# Git Elements

This is an overall dictionary of git elements commonly used in projects hosted in this repository, as well as description on how to execute similar actions.

## Submodules

Submodules are external repositories linked to a repository in a way that you can checkout, read, interact, and modify its contents. This is a great and efficient way to work with multiple projects or merging ones.

I use submodules in [Compendium](https://github.com/vega-star/compendium) as a way to link multiple repositores into an accessible hub, as GitHub directs the user to the source repository instead of duplicating the contents. 

To add submodules into your repository, you should execute this command under the root folder of the project:

```bash
git submodule add [[REPO_URL]] [[FOLDER_PATH]]
```

Simple as that. Try it!