drupal-sync
===========

Ansible role to synchronize Drupal files and db using drush.

Intended to be used in playbooks along with [drupal-perms](https://github.com/Wtower/ansible-drupal-perms)
to properly synchronize a deployment.

Add the role `drupal_sync` (see examples).

Variables:

- `drupal_sites`: Configuration dictionary (see examples)
- `site`: Index in `drupal_sites` to the particular Drupal site
- `dest`: 'staging' or 'prod' to indicate direction

Playbook examples
-----------------

See folder `examples/`:

- `drupal_back_sync.yml` is an example of a playbook
- `drupal_sites.yml` is a configuration sample
