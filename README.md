<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# GitLab for YunoHost

[![Integration level](https://dash.yunohost.org/integration/gitlab.svg)](https://dash.yunohost.org/appci/app/gitlab) ![Working status](https://ci-apps.yunohost.org/ci/badges/gitlab.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/gitlab.maintain.svg)

[![Install GitLab with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gitlab)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install GitLab quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Git-repository manager providing wiki, issue-tracking and CI/CD pipeline features

**Shipped version:** 15.11.2~ynh1

**Demo:** https://gitlab.com/explore

## Screenshots

![Screenshot of GitLab](./doc/screenshots/GitLab_running_11.0_(2018-07).png)

## Disclaimers / important information

### Configuration

How to configure GitLab: 

- With the GitLab admin panel.
- By editing the configuration file `/etc/gitlab/gitlab-persistent.rb` (use `sudo gitlab-ctl reconfigure` after any modification of this file).

### Multi-users support

* Are LDAP and HTTP auth supported? **Yes**
* Can the app be used by multiple users? **Yes**

### Limitations

* GitLab is not compatible with 32-bit architectures.

## Documentation and resources

* Official app website: <https://gitlab.com>
* Official admin documentation: <https://docs.gitlab.com/>
* Upstream app code repository: <https://gitlab.com/gitlab-org/omnibus-gitlab - https://gitlab.com/gitlab-org/gitlab>
* YunoHost documentation for this app: <https://yunohost.org/app_gitlab>
* Report a bug: <https://github.com/YunoHost-Apps/gitlab_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/gitlab_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/gitlab_ynh/tree/testing --debug
or
sudo yunohost app upgrade gitlab -u https://github.com/YunoHost-Apps/gitlab_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
