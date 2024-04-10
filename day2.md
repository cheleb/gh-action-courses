
## Super linter

- [Super linter](https://github.com/github/super-linter) is a GitHub Action that runs a linter against code base.

slim-linter is a multi-language linter, that can be used to lint code in multiple languages.



### caching
 Is enabled by default, so it will cache the linter and the dependencies.

* No sensitive data should be stored in the cache.
* No (yet) secured scanning of the cache !

Restore keys are used to restore the cache, if main key is not found.

If cache is found, it will `cache-hit` variable will be defined.

--> Double check if the cache is used, by checking the logs.



## Protection rules

[RuleSet](https://docs.github.com/en/rest/reference/repos#protectionruleset) are the new way to define protection rules.


## Secret store

* Not that recommended to store secrets in the repository.

GITHUB_TOKEN is a special token, that is automatically created by GitHub, and is used to authenticate the GitHub Actions.

That what permission are for in the manifest files.


See https://github.com/marketplace/actions/create-github-app-token for more information and examples.



* deleted add the end of the workflow.

