# Redmine List of compatible plugins

[![Run Tests](../../workflows/Tests/badge.svg)](../../actions?query=workflow%3ATests)

This list should get you the information, which plugins are compatible with each other and works with current Redmine versions.

## Redmine plugins with tests

If a redmine plugin includes tests (unit, functional or integration tests) and the plugin is compatible with the other plugins here, it should be listed in this list.

### Test environment

- Redmine: 4.1.x and Master
- Ruby: 2.4.x and 2.6.x
- Database: MySQL and PostgreSQL  Ruby `>= 2.4.10`

### Compatible plugins

- [additional_tags](https://github.com/AlphaNodes/additional_tags)
- [additionals](https://github.com/AlphaNodes/additionals)
- [redmine_code_review](https://github.com/haru/redmine_code_review)
- [redmine_dmsf](https://github.com/danmunn/redmine_dmsf)
- [redmine_git_hosting](https://github.com/jbox-web/redmine_git_hosting)
- [redmine_issue_evm](https://github.com/momibun926/redmine_issue_evm)
- [redmine_ref_issues](https://github.com/AlphaNodes/redmine_ref_issues)
- [redmine_messenger](https://github.com/alphanodes/redmine_messenger)
- [redmine_privacy_terms](https://github.com/AlphaNodes/redmine_privacy_terms)
- [redmine_saml](https://github.com/AlphaNodes/redmine_saml)
- [redmine_theme_changer](https://github.com/haru/redmine_theme_changer)
- [redmine-view-customize](https://github.com/onozaty/redmine-view-customize)
- [redmine_xls_export](https://github.com/two-pack/redmine_xls_export)

## Redmine plugins without tests

All plugins should have tests. Some don't - sadly. If it is manually comfirmed, that this plugins are working with all plugins listed here, it is listed in this list.

- [sidebar_hide](https://gitlab.com/bdemirkir/sidebar_hide)
- [redmine_lightbox2](https://github.com/paginagmbh/redmine_lightbox2)
- [redmine_issue_open_date](https://github.com/southbridgeio/redmine_issue_open_date)
- [redmine_issue_view_columns](https://github.com/kenan3008/redmine_issue_view_columns)
- [redmine_wysiwyg_editor](https://github.com/taqueci/redmine_wysiwyg_editor)

## Rules

- if a plugin is not compatible with one other plugin in this list, it'll be removed
- all plugins should fullfill tests for defined environments above (redmine version, ruby version and databases)
- The plugin should have tests. If not, only manuall tested plugins should be added to _Redmine plugins without tests_
- Only plugins, which can be automatically downloaded (for tests) are listed
- Tests are run once a day. If tests fail for a plugin, it'll be dropped from this list.
- This plugin should be maintained. Archived repositories on github means, there are not maintained.

## Help us

Please provide a PR of your Redmine plugin or the exiting list.
Your PR should include:

- Change for README.md
- Change for .github/workflows/tests.yml to run test of your plugin
