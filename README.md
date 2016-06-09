# jhu-aspace-search-identifier

Plugin based on Duke's aspace-search-identifier, which:

- **aspace-search-identifier**: Adds Identifier column to search result and browse screens

JHU's version makes the following changes:

- **removes audit info column from search result and browse screen (more horizontal screen space desired by users)
- **styles the view/edit buttons on search result and browse screns to conform with ASpace default display

To install plugin:

   1. Stop the application
   2. Move the individual plugin directories into the archivesspace/plugins directory
   3. Modify config.rb (in archivesspace/config) to list aspace-search-identifier
   4. Run /archivesspace/scipts/setup-database.sh
   5. Restart the application /archivesspace/archivesspace.sh