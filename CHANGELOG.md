# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased]
### Added
- Changelog file

### Changed
- Update dependency (JointJS library): from 0.9.6 to 2.0.1
- Improved alignment of the 'D' symbol in a dependency link
- Improved fit-to-content feature when saving the model as image
  - Now it is also applied for the SVG file
  - Now it also trims empty space on the left and the top of the model
  - Now it is a bit tighter (less empty space)
- Improved handling of element focus:
  - Rectangle around the element to indicate that it is selected
  - The 'delete element' button was removed, to prevent accidental deletes
  - Fixed some bugs that could cause (i) accidental delete and (ii) blocked UI when adding a link
  - The user can now de-select an element (ESC or click on empty space)
  - Auto-focus on an element when adding it 
  
### Fixed
- Fix limitation of 1.5mb for downloading PNG file on Chrome
- Fix incorrect behavior of changing focus when hovering over an actor
- Fix desync: when changing the label of a node through double click, the properties table wasn't updated

## [Release v1.0.0] - 2017-03-19
- First release