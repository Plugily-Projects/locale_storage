# Locale storage repository
This repository is meant to be used only by localization services like POEditor.

Repository is automatically hooked with plajer.xyz web localization service.

# How to read locale versions?
Check locale_data.yml file in corresponding project.

**valid-version** represents version that plugin can use, if plugin version is lower than the one written there webservice
will deny update request and locale won't be updated for requesting plugin

**locale.version** represents actual version of localization, if locale of plugin is lower than the one written there webservice
will allow to update locale from this repository if **valid-version** check is passed
