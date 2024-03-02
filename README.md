# 7-1 Sass Architecture
Completion requirements

## Objective
- Reorganize the Sass files of your sassy-blog project following the 7-1 Sass Architecture pattern. Enhance the project's styles by taking advantage of this organized structure.

## Part 1: Setup 7-1 Folder Structure
### Create the 7-1 Architecture Folders:
- In sassy-blog project, created the following folders: base/, components/, layout/, pages/, themes/, abstracts/, vendors/.
### Part 2: Organizing Existing Styles
#### Distribute Current Styles:
- Moved existing Sass code into the appropriate folders. For example, general typography styles to base/, reusable button styles to components/ etc.
### Part 3: Creating New Style Files
#### Expand Your Styles:
- Created new Sass files within these folders to expand project's styling.
- Ensured using Sass features like variables and mixins appropriately in these files.
### Part 4: Main Sass File
#### Set Up Main Sass File:
- Created a main.scss file at the root of Sass directory.
- Used @import statements to include all the Sass files from the 7-1 folders with right order of imports for proper cascading.
#### Test the Blog:

- Ensured that all Sass compiles correctly and the blog is responsive and functional.
