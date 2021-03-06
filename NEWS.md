## 0.0.2 2021-06-18

* Create [RAML file](ramls/ldp.raml), and associated [JSON Schemas and example files](ramls), describing the WSAPI. Fixes #5.
* Write [WSAPI overview documentation](ramls/overview.md). Fixes #6.
* Set up automatic generation of WSAPI documentation. Fixes #8.
* Support `limit` parameter in query. Fixes #7.
* Update top-level [README.md](README.md), including links to autogenerated WSAPI documentation. Fixes #10.
* Quote column names in SQL queries. Fixes #12.
* Use exact matching instead of pattern matching. Fixes #13.
* Support `orderBy` in query structure. Fixes #14.
* Add "checkstyle" linting support (disabled) to the `pom.xml`. Fixes #9. Note that there are many lint errors: the plugin is disabled until I have time to look at these and decide which to fix and which are the result of silly rules.
* Initial release

