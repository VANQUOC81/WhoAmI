# VANQUOC's Version 2.0 Website

## Who Am I
Welcome to my personal website, http://www.vanquoc.com/. The website is a landing page for clients whom wish to contact me for project work.

## FILE STRUCTURE
- index.html holds the entire content
- css/styles.css custom css styling
- js/scripts.js custom js code
- images folder contains all the images
- The rest are files specific to different frameworks and dependencies

## FRAMEWORKS & DEPENDENCIES
- Bootstrap https://getbootstrap.com/
- jQuery https://jquery.com/ 
- jQuery Easing https://jqueryui.com/easing/
- Font Awesome for icons https://fontawesome.com/

## ENVIRONMENT
- The website is hosted on the Azure Static Web Apps service
- Continuous Integration (CI) happens via GitHub Action Workflow which builds the source
- Continuous Delivery (CD) happens via GitHub Action Workflow that after CI triggers deployment on an Azure staging/test environment
- Continuous Deployment (CD) happens via GitHub Action Workflow after closing of Pull Request triggers deployment on an Azure prod environment
