# Change Log
All notable changes to this project will be documented in this file

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## 4.0.0
### Changed
 - Upgrade formio.js to 4.x branch to enable templating.

## 3.0.1
### Added
 - url property for when using form instead of src.

## 3.0.0
### Changed
 - Change formio.js version to 3.0.0 now that it is released.

## 2.1.1
### Fixed
 - Destroy event on form builder component.

## 2.1.0
### Added
 - Form Builder component

## 2.0.4
### Fixed
 - Prop type for i18n.

## 2.0.3
### Changed
 - Upgrade core renderer from 2.10.1 to 2.20.4

## 2.0.2
### Changed
 - Rebuild for failed build.

## 2.0.1
### Fixed
 - Allow adjusting submission while form is being created

## 2.0.0
### Changed
 - Renderer now based on formio.js Core Renderer.

### Removed
 - All helper libraries.

## 1.4.2
### Changed
 - Fire edit grid open event on componentDidMount instead of componentWillMount.

## 1.4.1
### Fixed
 - HTML output of editgrid header

### Added
 - Footer for editgrid

## 1.4.0
### Added
 - Time component
 - EditGrid component

## 1.3.14
 - Fix default formatting of empty custom error validation.

## 1.3.13
### Fixed
 - Disable datagrid buttons when form is read only.
 - Don't fire change events for readOnly forms.

## 1.3.12
### Added
 - Events that fire when select lists open or close.
 - Event that fires on add/remove from datagrid.
 - Event that fires on loadMore for selects.

## 1.3.11
### Reverted
 - Reverted revert of change to datagrids delete value.

### Fixed
 - Calculated Select values could return something other than an array which caused an error.

## 1.3.10
### Reverted
 - Reverted change to setting values that attempted to fix deleting rows in datagrids issue that had a lot of side effects.

### 1.3.9
### Fixed
 - Fix MinLength calculation for datagrids.
 - Fixed error about setState in select component.
 - Scenario where updating a form doesn't always set the values.

### Changed
 - Replace full lodash with individual functions.

## 1.3.8
### Fixed
 - Datagrids with select components dependent on external data weren't updating when the data updated.

## 1.3.7
### Changed
 - Datagrid headers won't render if there are no labels.

## 1.3.6
### Fixed
 - Deleting rows in datagrids didn't clear components properly.

## 1.3.5
### Fixed
 - Fix performance of datagrids with large data.

## 1.3.4
### Added
 - Onchange event will fire for input fields after 500ms of no typing instead of only on blur.

## 1.3.3
### Added
 - Expose mixins as exports to ease creation of custom components.

## 1.3.2
Changed
 - Text inputs will fire change events on blur now instead of on change. Change events were too slow in redux.

## 1.3.1
### Fixed
 - Fixed tests dealing with input mask change and missing onChange events.

### Removed
 - Removing tests that don't work with current libraries.

## 1.3.0
### Changed
 - Swapped react-input-mask for react-text-mask for input masks.
 - Improved performance of input masks.
