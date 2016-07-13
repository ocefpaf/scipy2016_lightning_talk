% How to [conda-forge](https://conda-forge.github.io/)
%
% 2016 SciPy

---

# Community Powered Packaging with conda-forge

> - Don't ask what conda-forge can do for you
> - Ask what you can do for conda-forge ;-)

# 1) Browse for packages

![](images/package_list.png)

https://conda-forge.github.io/feedstocks.html

# 2) Cannot find the package you need? Send a PR!

> - The point of entry is [staged-recipes](https://github.com/conda-forge/staged-recipes)
> - The tooling lives in [conda-smithy](https://github.com/conda-forge/conda-smithy)
> - But what you really need is `conda smithy recipe-lint`
> - Remember to check the [example](https://github.com/conda-forge/staged-recipes/blob/master/recipes/example/meta.yaml) recipe before sending the PR

# The [linter](https://github.com/conda-forge/conda-forge-webservices/tree/master/conda_forge_webservices) in action

![](images/github_linter.png)

# 3) The recipe exists but it is outdate?

![](images/github_maintaince_changes.png)

# 4) Open issues

![](images/github_issues.png)

# Extra: forge like pro!

![](images/github_rerender.png)

```shell
conda smithy rerender
```

# How to find [us](https://github.com/orgs/conda-forge/people)?

[Github](https://github.com/conda-forge)

[Gitter](https://gitter.im/conda-forge/conda-forge.github.io)

[Mailing list](https://groups.google.com/forum/#!forum/conda-forge)

And help us to review new packages [staged-recipes](https://github.com/conda-forge/staged-recipes)
