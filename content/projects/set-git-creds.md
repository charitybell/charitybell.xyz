---
title: 'Github Action: set-git-creds'
---

[set-git-creds][] is a [Github Action][] for adding github credentials to your git remote URL during a CI run. Adding credentials to your remote URL means you can seamlessly push to a repository during a CI run.

Charitybell uses this action in our [homebrew tap](../homebrew) for pushing git tags and commits made during CI runs. You can see how we use it in our [Github release workflow][]

{{< githubstars "charitybell/set-git-creds" >}}

[set-git-creds]: <https://github.com/charitybell/set-git-creds>
[Github Action]: <https://github.com/features/actions>
[Github release workflow]: <https://github.com/charitybell/homebrew-charitybell/blob/9a75fe99ee16feadcddaec67dae8284b8dc7e0d9/.github/workflows/release.yml#L48>
