<!-- DO NOT EDIT THIS FILE! -->
<!-- Instead edit recipe/cakephp4.php -->
<!-- Then run bin/docgen -->

# cakephp4

[Source](/recipe/cakephp4.php)



* Require
  * [`recipe/common.php`](/docs/recipe/common.md)
* Config
  * [`shared_dirs`](#shared_dirs)
  * [`shared_files`](#shared_files)
* Tasks
  * [`deploy:init`](#deployinit)
  * [`deploy:run_migrations`](#deployrun_migrations)
  * [`deploy`](#deploy)

## Config
### shared_dirs
[Source](/recipe/cakephp4.php#L11)

* Overrides [`shared_dirs`](/docs/recipe/common.md#shared_dirs) from `recipe/common.php`

CakePHP 4 Project Template shared dirs

### shared_files
[Source](/recipe/cakephp4.php#L17)

* Overrides [`shared_files`](/docs/recipe/common.md#shared_files) from `recipe/common.php`

CakePHP 4 Project Template shared files


## Tasks
### deploy:init
[Source](/recipe/cakephp4.php#L25)

Create plugins' symlinks

### deploy:run_migrations
[Source](/recipe/cakephp4.php#L32)

Run migrations

### deploy
[Source](/recipe/cakephp4.php#L41)

Main task

This task is group task which contains next tasks:
* [`deploy:prepare`](/docs/recipe/common.md#deployprepare)
* [`deploy:vendors`](/docs/recipe/deploy/vendors.md#deployvendors)
* [`deploy:init`](/docs/recipe/cakephp4.md#deployinit)
* [`deploy:run_migrations`](/docs/recipe/cakephp4.md#deployrun_migrations)
* [`deploy:publish`](/docs/recipe/common.md#deploypublish)

