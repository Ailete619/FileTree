# FileTree v0.3.3

File Tree is a little utility program allowing users to render the file hierarchy inside a directory to document projects.

The project was also started to test building React / TypeScript desktop applications with [tauri](https://tauri.app/).

## Version log

### 2022-07-29 v0.4.0
- Implement the application dropdown menu.
### 2022-07-28 v0.3.4
- Add menu item to set the root directory of the hierarchy displayed in the tree view.
- Fix error in the directory stack: a child directory was automatically displayed asselected if its parent had the same name.
- Fix error in the path breadcrumbs selection: empty pathFromRoot was displayed and selected as "/".
- Fix error in the path breadcrumbs selection: root was never selected
### 2022-07-27 v0.3.0
- Add a modal dialog to display the Root Directory selector.
- Implement an action on user selection of the Root Directory to initialize the Tree view.
### 2022-07-23 v0.2.0
- The Root Directory selector is functional but user selection does not result in an action ...
### 2022-07-18 v0.1.0
- The Tree view is functional but only displays the file hierarchy inside a hardcoded directory ...

## RoadMap

### v0.5
- export the hierarchy to HTML
### v0.6
- export the hierarchy to text
### v0.7
- add funtionality to grey out or hide files and directories
### v0.8
- 
