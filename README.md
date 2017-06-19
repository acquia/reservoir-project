This is a Composer-based installer for the [Reservoir](https://github.com/acquia/reservoir) Drupal distribution. Welcome to the future!

## Get Started
```
$ composer create-project acquia/reservoir-project MY_PROJECT
```
Composer will create a new directory called MY_PROJECT containing a ```docroot``` directory with a full Reservoir code base therein.

## Source Control
When you set up the project, Composer will create a file called ```composer.lock```, which is a list of which dependencies were installed, and in which versions. **Commit ```composer.lock``` to source control!** Then, when your colleagues want to spin up their own copies of the project, all they'll have to do is run ```composer install```, which will install the correct versions of everything in ```composer.lock```.
