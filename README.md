# Instructions to upload a new Kibana 4 dashboard / update an existing one:
1. Export all the dashboards, visualizations, and searches that you would like to make available into a set of three json files.
2. Replace every instance of the space ID in each json with "SPACE_ID_PLACE_HOLDER". For example, rename: "4f33a37d-80be-487c-9bf8-2dbde1248bd9_Liberty-Memory-K4-20161204-experimental" to "SPACE_ID_PLACE_HOLDER_Liberty-Memory-K4-20161204-experimental"
3. Rename the json files to \<product\>-kibana4-dashboards.json, \<product\>-kibana4-visualizations.json, and \<product\>-kibana4-searches.json as appropriate.
4. If uploading a new Kibana 4 dashboard, create a folder with the name of the product and place the dashboards, visualizations, and searches json files in that folder. Or if updating an existing dashboard, simply replace the three existing json files. Note: the folder name and \<product\> must be exactly the same. For instance, the "twas-kibana4-visualizations.json" file should be placed in the "twas" folder.
5. Submit a pull request.

