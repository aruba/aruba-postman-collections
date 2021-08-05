# Postman Collections for Aruba Central

## [](https://github.com/aruba/aaruba-postman-collections/central#steps-to-import-central-collections) Steps to import Central Collections

1) Download the [central_api_postman.json]() to your system.
2) Open Postman (Desktop/Web-interface)
3) Create a new personal/team workspace.
4) Click on **Import** and select **File** to upload a file.
5) Choose the downloaded central_api_postman.json file. Once it shows the file type details (Data dump file), click on Import to start the import process.
6) Give it a few minuted for importing all the collections.


## [](https://github.com/aruba/aaruba-postman-collections/central#steps-to-make-api-calls) Steps to make API calls

1) Once all collections are imported into your Postman workspace, create new environment variables. The purpose of creating these variables is to reuse commonly used things.
2) Click on the 'eye' icon and add the following two environment variables:
- `baseUrl` (variable)
- API-Gateway Base URL (value) - The API gateway base url can be obtained from Central Account Home > API Gateway > API Documentation link. Sample API base URL for some clusters are listed below:
US1 - app1-apigw.central.arubanetworks.com
US2 - apigw-prod2.central.arubanetworks.com
Internal - internal-apigw.central.arubanetworks.com

3) Now the `baseUrl` and `access_token` variables are set in the environment. USe the environment and select your desired API call from any of the available collections.
4) Fill in the appropriate parameters for the reuest or data and click on **Send**.
