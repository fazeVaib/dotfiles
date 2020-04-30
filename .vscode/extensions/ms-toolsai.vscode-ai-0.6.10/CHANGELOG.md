## Version 0.6.10
* Release date: March 12th, 2020
* Release status: Public preview
* Added support for managing environments and specifying them during experiment runs.
* Improved handling of dependent resources when deleting a workspace.
* Bug fixes


## Version 0.6.9
* Release date: February 18th, 2020
* Release status: Public preview
* Improved experience for creating computes and workspaces by allowing users to go back to previous steps to modify choices.
* Fixed issue that prevented paginated results from showing properly.
* Fixed issue that affected the VM size that users selected for newly created compute resources.

## Version 0.6.8
* Release date: December 5th, 2019
* Release status: Public preview
* Added support for downloading and streaming logs from experiment runs.
* Fixed issue that prevented the AML resources tree from showing all results for long lists of resources.

## Version 0.6.7
* Release date: November 4th, 2019
* Release status: Public preview
* Now uploading project files via the snapshots API when the project directory is larger than 25 MB.
* Added ability for users to select the tier (basic or enterprise) when creating a workspace.
* Added progress bar when editing compute resources and getting compute properties.
* Fixed a bug preventing users from running an experiment using the local compute.

## Version 0.6.6
* Release date: September 25, 2019
* Release status: Public preview
* Run status is now dynamically updated for experiments
* Fixed a bug that caused outputs from experiments to be unavailable.

## Version 0.6.5
* Release date: September 20, 2019
* Release status: Public preview
* View Notebook VM's associated with a workspace
* Bug fix to re-enable local Azure Experiment Runs

## Version 0.6.4
* Release date: September 16, 2019
* Release status: Public preview
* Bug fix to address inability to create workspaces in various worldwide locations

## Version 0.6.3
* Release date: September 11, 2019
* Release status: Public preview
* Internal refactoring and telemetry updates

## Version 0.6.2
* Release date: August 24, 2019
* Release status: Public preview
* Bug fix to support running experiment against existing workspace

## Version 0.6.1
* Release date: August 23, 2019
* Release status: Public preview
* Provide smart defaults for Azure ML resource names
* Batch Azure ML resource creation to final experiment submit
* Provide ability to view run status for Experiements and run configurations used
* Removal of Flask server for communicating with Azure ML service

## Version 0.6.0
* Quickly replaced with version 0.6.1. Version 0.6.0 still had some reliance on the Flask server.

## Version 0.5.0
* Release date: April 25, 2019
* Release status: Public preview
* Streamline experiment submission steps (more to come)
* Convert to using json rather than yaml for runconfig
* Provide default runconfig templates for common ML framework usage
* Bug fixes

## Version 0.4.5
* Release date: March 13, 2019
* Release status: Public preview
* Update Azure ML runtime dependency
* Many bug fixes and internal implementation improvements (more to come...)

## Version 0.4.0
* Release date: December 13, 2018
* Release status: Public preview
* "Active Experiment" and "Last Run" configurations instead of "Attach Folder"
* Fixed workflow for installing AzureML SDK for flask server use
* Compute-centric runconfig management
* Reduced workflow complexity
* Bug fixes

## Version 0.3.2
* Refocus extension to target Azure Machine Learning November 2018

## Version 0.3.1
* Release date: October 16, 2018
* Release status: Public Preview
* Bug fix to allow tags to be specified when creating Azure docker images or model deployments.
* Update Azure SDK dependency to fix inability to create a new runconfig file.

## Version 0.1.1
* Release date: Sep 25, 2017
* Release status: Public Preview

## What's new in this version
Initial Release
