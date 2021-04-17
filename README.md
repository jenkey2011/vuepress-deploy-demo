# vuepress-deploy-demo

This repository is to test vuepress-deploy.

The following guides are based on some shared assumptions:

- Source code repository(`vuepress-deploy-demo`), we call it `A`
- Target repository(`vuepress-deploy-demo-target`), we call it `B`

There are three situations. Each situation corresponds to a deployment file. 

- `A` TO `A:gh_pages`: `deploy-to-current-repo-gh_pages.yml`
- `A` TO `B:master`: `deploy-to-other-repo-master.yml`
- `A` TO `B:custom_branch`: `deploy-to-other-repo-custom_branch.yml`

## Here we can see

- The action: [https://github.com/jenkey2011/vuepress-deploy-demo/actions](https://github.com/jenkey2011/vuepress-deploy-demo/actions)

- `A` TO `A:gh_pages`: [https://github.com/jenkey2011/vuepress-deploy-demo/tree/gh_pages](https://github.com/jenkey2011/vuepress-deploy-demo/tree/gh_pages)

- `A` TO `B:master`:[https://github.com/jenkey2011/vuepress-deploy-demo-target/tree/master](https://github.com/jenkey2011/vuepress-deploy-demo-target/tree/master)

- `A` TO `B:custom_branch`:[https://github.com/jenkey2011/vuepress-deploy-demo-target/tree/custom_branch](https://github.com/jenkey2011/vuepress-deploy-demo-target/tree/custom_branch)

- The GitHub Pages of the repository B： [https://jenkey2011.github.io/vuepress-deploy-demo-target/](https://jenkey2011.github.io/vuepress-deploy-demo-target/)
