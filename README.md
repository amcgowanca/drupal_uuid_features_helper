## UUID Features Helper

A helper module that assists in ensuring the portability of exported data using Drupal 7's [UUID Features](http://drupal.org/project/uuid_features) contributed module.

### Installation
#### Common Installation

* Download the module and place within the `sites/all/modules` directory.
* Install the module either via the Administration or by using Drush (e.g. `drush en uuid_features_helper -y`).

#### As part of Drush Make

This project can be downloaded and used within a Drush make file like any other contributed module. The difference is that this module exists on GitHub instead of Drupal.org. Within your `drupal-org.make`, the UUID Features Helper module can be defined as a project. This is done with:

```
projects[uuid_features_helper][type] = "module"
projects[uuid_features_helper][download][type] = "git"
projects[uuid_features_helper][download][url] = "git@github.com:amcgowanca/drupal_uuid_features_helper.git"
projects[uuid_features_helper][download][tag] = "7.x-0.1"
```

**Note:**

* This module is downloaded using Git.
* This module will be downloaded as the tagged release version 7.x-0.1.

### License

The UUID Features Helper is licensed under the [GNU General Public License](http://gnu.org/licenses/gpl-2.0.html) version 2.