Experitest - Web Studio ansible role
=========

This role will install \ uninstall web studio for linux os hosts <br>

Role Variables
--------------

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| state | should the application be present or absent | present, absent | present | no |
| app_version | application version to install | string | master.34 | no |
| installation_root_folder | the root folder in which the application will be installed under web-studio folder | string | for linux: /opt/Experitest | no |
| custom_download_url | custom url to download the installation from (zip format) | string |  | no |
| clear_temp_folder | remove temp folder before installation | boolean | False | no |
| clear_before_install | remove old installation before install | boolean | False | no |

Example Playbook
----------------

#### [see working example](/example)
