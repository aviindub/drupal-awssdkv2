drupal-awssdkv2
===============

this is a fork from https://drupal.org/node/1865568 and supporting awssdk v2 . We here to continuous maintain on github and avoid duplication in drupal.org

Use the compatibility table to determine the approprate version of the module
and SDK found at http://drupal.org/node/1396596.

Place the approprate version of the AWS SDK for PHP in the libraries directory
within the site you are working. That may be 'default' or 'all' like the
following: sites/all/libraries or sites/default/libraries. The end result after
extracting the library should be sites/.../libraries/awssdk/sdk.class.php.

Configuration can be performed either using variables hardcoded into
settings.php or the UI. If you want to hardcode them then look at the UI for the
variable names. The basics are as follows.

$conf['aws_key'] = '...';
$conf['aws_secret'] = '...';
$conf['aws_account_id'] = '...';
$conf['aws_canonical_id'] = '...';

