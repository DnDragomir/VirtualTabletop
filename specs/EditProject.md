# Edit Project

Tags: edit, project

The project's creator must be able to edit a project's features <file:project-features>

## Navigation

Upon navigating to the project, an authorized user should be in edit mode by default.

* A project exists
* User must be logged in and authorized to edit the project.
* User navigates to the pre-existing project's landing page.
* Application loads the project editor.

## Resource Manager

Resources can be imported for use with other features.

* A tab is displayed to show assets available for use within the editor.
* An "import" button is displayed to allow for importing assets.

## Save Project

All changes made in the editor should be serialized, versioned, and saved.

* A User changes a serializable property of the map.
* The user interacts with the save feature.
* The project state is serialized into a file.
* The file is saved.