# Smart Filter for Power BI

Smart Filter by OKViz works like an observer, showing the current filters set in the report page, or like a slicer, allowing you to choose records from a drop-down list or search by typing a few letters. This has been modified by nishchhal to cater delimiter and contains filter using Advanced Filter API.

![alt tag](screenshot.png)

NOTE: Comment out following in node_modules/powerbi-models/dist/models.js
if (extractedConditions.length > 2) {
    throw new Error("AdvancedFilters may not have more than two conditions. You passed: " + conditions.length);
}


### Copyrights

Copyright (c) 2016-2017 OKViz - trademark of SQLBI Corp.

See the [LICENSE](/LICENSE) file for license rights and limitations (MIT).