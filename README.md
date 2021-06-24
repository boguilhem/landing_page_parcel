# landing_page_parcel

## Installing local requirements for development

run:
`$ npm install`

to install all dependencies of the package.json file

## To clean dist folder

Parcel doesn't delete/replace the dist folder automatically. You can delete it
manually or run the following command:

`$ npm run clean`

## Building the project as development

Run the following command on the root of project folder:

`$ npm run build-dev`

## Running the project as development on server

Run the following command on the root of project folder:

`$ npm run start`

## For deployment

Use the following command on root of project folder for production mode:

`$ npm run build`

## Compiled Package

The compiled package (.js and .css) minified(on development) and not minified(on production) can be found inside the
dist folder
