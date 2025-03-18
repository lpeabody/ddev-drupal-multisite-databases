# DDEV Drupal Multisite Databases

This is a DDEV addon that ensures a database exists for every valid multisite
directory (i.e. excluding `default` and `settings`).

- The database name is the same as the directory name.
- The database user and password are both `db`.

## Installation

Run the following command to install the addon:

```bash
ddev add-on get lpeabody/ddev-drupal-multisite-databases
```

After the addon is installed, run `ddev restart` to apply the changes.
