# Changelog

## [2.1.0](https://www.github.com/fortify/FortifyToolsInstaller/compare/v2.0.0...v2.1.0) (2021-09-28)


### Features

* Add integrity check for downloaded tool bundles ([7c4253a](https://www.github.com/fortify/FortifyToolsInstaller/commit/7c4253a2bd4014ee71bcfb7a2b345ad28416e963))

## [2.0.0](https://www.github.com/fortify/FortifyToolsInstaller/compare/v1.1.0...v2.0.0) (2021-08-26)


### ⚠ BREAKING CHANGES

* General: Renamed FORTIFY_TOOLS_DIR input variable to FORTIFY_TOOLS_HOME for consistency
* General: Removed FORTIFY_TOOLS_BIN_DIR input variable, as each tool now uses it's own bin-directory
* FoDUploader: Moved bin-script to tool-specific bin directory
* FoDUploader: Removed all output variables, as they are not needed when invoking the tool using the provided bin script
* FortifyVulnerabilityExporter: Moved bin-script to tool-specific bin directory
* FortifyVulnerabilityExporter: Removed all output variables, as they are not needed when invoking the tool using the provided bin script
* ScanCentral Client: Removed all output variables, as they are not needed for invoking the tool

### Bug Fixes

* General: Bin-directories from latest FTI run are now always added to the front of the path, to make sure appropriate version is being run if FTI is invoked multiple times with different tool versions ([e3efa57](https://www.github.com/fortify/FortifyToolsInstaller/commit/e3efa574f9bcc2ff69f21de7c2c598865f601a0e))


### Code Refactoring

* FoDUploader: Moved bin-script to tool-specific bin directory ([e3efa57](https://www.github.com/fortify/FortifyToolsInstaller/commit/e3efa574f9bcc2ff69f21de7c2c598865f601a0e))
* FoDUploader: Removed all output variables, as they are not needed when invoking the tool using the provided bin script ([e3efa57](https://www.github.com/fortify/FortifyToolsInstaller/commit/e3efa574f9bcc2ff69f21de7c2c598865f601a0e))
* FortifyVulnerabilityExporter: Moved bin-script to tool-specific bin directory ([e3efa57](https://www.github.com/fortify/FortifyToolsInstaller/commit/e3efa574f9bcc2ff69f21de7c2c598865f601a0e))
* FortifyVulnerabilityExporter: Removed all output variables, as they are not needed when invoking the tool using the provided bin script ([e3efa57](https://www.github.com/fortify/FortifyToolsInstaller/commit/e3efa574f9bcc2ff69f21de7c2c598865f601a0e))
* General: Removed FORTIFY_TOOLS_BIN_DIR input variable, as each tool now uses it's own bin-directory ([e3efa57](https://www.github.com/fortify/FortifyToolsInstaller/commit/e3efa574f9bcc2ff69f21de7c2c598865f601a0e))
* General: Renamed FORTIFY_TOOLS_DIR input variable to FORTIFY_TOOLS_HOME for consistency ([e3efa57](https://www.github.com/fortify/FortifyToolsInstaller/commit/e3efa574f9bcc2ff69f21de7c2c598865f601a0e))
* ScanCentral Client: Removed all output variables, as they are not needed for invoking the tool ([e3efa57](https://www.github.com/fortify/FortifyToolsInstaller/commit/e3efa574f9bcc2ff69f21de7c2c598865f601a0e))

## [1.1.0](https://www.github.com/fortify/FortifyToolsInstaller/compare/v1.0.0...v1.1.0) (2021-08-25)


### Features

* Add support for verifying output variables ([d3cebfd](https://www.github.com/fortify/FortifyToolsInstaller/commit/d3cebfd87b441552fc519693b294ff9250ab6c9e))
* Allow individual tool installation directories to be overridden ([afd5707](https://www.github.com/fortify/FortifyToolsInstaller/commit/afd5707eff3ecbfb7a0d85f62c5c1ead83372f1e))


### Bug Fixes

* Remove obsolete info from usage information ([995f270](https://www.github.com/fortify/FortifyToolsInstaller/commit/995f27008c2149234ed1b56bab21c5ca1a598aff))

## [1.0.0](https://www.github.com/fortify/FortifyToolsInstaller/compare/v0.0.5...v1.0.0) (2021-08-13)


### Miscellaneous Chores

* release 1.0.0 ([d8bc1ce](https://www.github.com/fortify/FortifyToolsInstaller/commit/d8bc1ce11952b757163316698fc3da27e76cd7d8))

### [0.0.5](https://www.github.com/fortify/FortifyToolsInstaller/compare/v0.0.4...v0.0.5) (2021-08-13)


### Miscellaneous Chores

* release 0.0.5 ([881ea3c](https://www.github.com/fortify/FortifyToolsInstaller/commit/881ea3c02be252fb19884d0ddd0433194b99ae32))

### [0.0.4](https://www.github.com/fortify/FortifyToolsInstaller/compare/v0.0.3...v0.0.4) (2021-08-13)


### chore

* release 0.0.4 ([11bfa51](https://www.github.com/fortify/FortifyToolsInstaller/commit/11bfa517335d87772982330e8f5c18a5d1ee1980))

### [0.0.3](https://www.github.com/fortify/FortifyToolsInstaller/compare/v0.0.2...v0.0.3) (2021-08-13)


### chore

* release 0.0.3 ([aa4a7fe](https://www.github.com/fortify/FortifyToolsInstaller/commit/aa4a7fef5fa35257fea139f1f9c67e730c38bedb))

### [0.0.2](https://www.github.com/fortify/FortifyToolsInstaller/compare/v0.0.2...v0.0.2) (2021-08-13)


### chore

* release 0.0.2 ([cd5f9bf](https://www.github.com/fortify/FortifyToolsInstaller/commit/cd5f9bf627a8759a0b3ea3f4df373a734c15f8ca))

### [0.0.2](https://www.github.com/fortify/FortifyToolsInstaller/compare/v0.0.1...v0.0.2) (2021-08-13)


### chore

* release 0.0.2 ([b085f9f](https://www.github.com/fortify/FortifyToolsInstaller/commit/b085f9f2cb1701c454a0da84aecab6e2df01b782))

### 0.0.1 (2021-08-13)


### chore

* release 0.0.1 ([fe6978e](https://www.github.com/fortify/FortifyToolsInstaller/commit/fe6978e1a7015a718fa108789cf04018101a6e94))
