# Changelog

## Unreleased

## 1.0.0 - 2021-05-27

* Add links to the file browser after exporting to PDF, HTML or XML
* Fix an issue when loading a layer from the locator bar, the style wasn't loaded before
* Update documentation https://docs.3liz.org/qgis-pgmetadata-plugin/
* Release on https://plugins.qgis.org

## 0.5.0 - 2021-02-19

* Review the full online documentation using a proper website
* Add a link to the plugin online help in the QGIS help menu
* Add a button to open the dock from the QGIS plugin menu
* Add a layer flattening the "dataset" table containing all links and contacts, easier to export all the catalog
* Improve the deployment of the plugin within an organization to hide and setup some tools in PgMetadata

## 0.4.0 - 2021-01-21

* Improve documentation user guide and schemaspy
* Save a metadata sheet as DCAT XML
* Add localized glossary labels and description : it, fr, es, de
* Display the translated HTML in the dock when available
* Add data_last_update in the HTML template
* Add some layers in the QGIS administration project

## 0.3.0 - 2020-12-14

* Update online documentation
* Add export as PDF/HTML button in the dock

## 0.2.2 - 2020-11-17

* Fix locator SQL query
* Add themes
* Update of the QGIS project

## 0.2.1 - 2020-11-16

* Improve HTML templates for making them compatible with Lizmap
* SQL - Fix calculate a spatial field with Z or M geometries
* SQL - Fix HTML generation for fields email and size
* Processing - Fix upgrade algorithm and add tests
* Fix bug with empty links when link has no mime or type - fixes #34
* SQL - Fix if the envelope is a point, or a line
* SQL - Add a view to query only valid dataset with the locator
* Fix running migrations in the Processing algorithm

## 0.2.0 - 2020-11-12

* Auto vacuum tables after install/upgrade of the database
* Add an option to auto open the dock from the locator
* Add a new field data_last_update
* Add an algorithm to set database connections for normal users
* Review default HTML templates
* Fix filter for QGS files in Processing

## 0.1.0 - 2020-11-03

* Automatically compute values from the table itself : feature count, CRS etc
* Improve QGIS form
* Improve the dock to display HTML metadata
* Use HTML templates stored in the database
* Display the layer geometry in the locator
* Add a flag to disable Processing algorithm if needed for non admin user

## 0.0.3 - 2020-10-20

* Add a dock displaying basic metadata information
* Fix file filter about QGS file selector
* Improve error reporting from the locator

## 0.0.2 - 2020-10-15

* Add French language

## 0.0.1 - 2020-10-14

* Provide a basic locator for adding layers
* Install the database schema
* Provide a QGIS project to edit the metadata
