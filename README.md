![Reservoir - Drupal distribution](https://raw.githubusercontent.com/acquia/reservoir-project/assets/reservoir.png)

# Reservoir: Composer installer

This is a Composer-based installer for the [Reservoir](https://github.com/acquia/reservoir) Drupal distribution.

---

## Get started
```
$ composer create-project acquia/reservoir-project MY_PROJECT --stability=alpha
```
Composer will create a new directory called `MY_PROJECT` containing a `docroot` directory with a full Reservoir codebase therein.

## Source control
If you peek at the `.gitignore` we provide, you'll see that certain directories, including all directories containing contributed projects, are excluded from source control.

When you set up the project, Composer will create a file called `composer.lock`, which is a list of which dependencies were installed and in which versions. **Commit `composer.lock` to source control!** Then, when your colleagues want to spin up their own copies of the project, all they'll have to do is run `composer install`, which will install the correct versions of everything in `composer.lock`.
