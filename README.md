# Dummy App

This app is for demo purposes only, showing some issue with Karma when trying to load the UI5 resources served by the UI5 Tooling (incl. Proxy). There are ways around this but I'd love to know what'd be the "best" or ... most solid way of doing it. Here I want to specifically demonstrate the, by BAS scaffolded "SAP Fiori Freestyle" application using the LTS version (1.71.XX) of UI5 as this issues just recently came up working in another project.

## Reproducing the Issue

Just install all the dependencies (`npm i`) and run
```bash
npm run karma
```

More info can be found in: https://answers.sap.com/questions/13665378/ui5-karma-config-404-on-ui5-resource-load.html

## Application Details
|                                                                                                |
| ---------------------------------------------------------------------------------------------- |
| **Generation Date and Time**<br>Fri Jun 24 2022 14:52:29 GMT+0000 (Coordinated Universal Time) |
| **App Generator**<br>@sap/generator-fiori-freestyle                                            |
| **App Generator Version**<br>1.6.3                                                             |
| **Generation Platform**<br>SAP Business Application Studio                                     |
| **Floorplan Used**<br>simple                                                                   |
| **Service Type**<br>None                                                                       |
| **Service URL**<br>N/A                                                                         |
| **Module Name**<br>project1                                                                    |
| **Application Title**<br>App Title                                                             |
| **Namespace**<br>                                                                              |
| **UI5 Theme**<br>sap_fiori_3                                                                   |
| **UI5 Version**<br>1.102.1                                                                     |
| **Enable Code Assist Libraries**<br>False                                                      |
| **Add Eslint configuration**<br>False                                                          |

## project1

A Fiori application.

### Starting the generated app

- This app has been generated using the SAP Fiori tools - App Generator, as part of the SAP Fiori tools suite.  In order to launch the generated app, simply run the following from the generated app root folder:

```bash
    npm start
```

#### Pre-requisites

1. Active NodeJS LTS (Long Term Support) version and associated supported NPM version.  (See https://nodejs.org)
