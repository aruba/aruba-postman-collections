# Postman Collections for Aruba Central

## [](https://github.com/aruba/aaruba-postman-collections/central#importing-collections) Importing Collections

1) Download the `.json` files listed above to your system
2) Open Postman (Desktop/Web-interface)
3) Create a new personal/team workspace
4) Click on **Import** and select **File** to upload a file
5) Choose the downloaded JSON files. Once it shows the file type details (Data dump  or Postman Collection v2.1 file), click on Import to start the import process
6) Give it a few minutes for importing all the collections


## [](https://github.com/aruba/aaruba-postman-collections/central#environment-and-api-call) Environment and API Call

1) Once all collections are imported into your Postman workspace, create new environment variables. The purpose of creating these variables is to reuse commonly used things such as URLs, tokens, query parameters values, etc.
2) Click on the 'eye' icon on top right of Postman and add the following two environment variables:
- `baseUrl` (variable)
- API-Gateway Base URL (value) - The API gateway base url can be obtained from Central Account Home > API Gateway > API Documentation link. Sample API base URL for some clusters are listed below:
US1 - app1-apigw.central.arubanetworks.com
US2 - apigw-prod2.central.arubanetworks.com
Internal - internal-apigw.central.arubanetworks.com

3) Once the `baseUrl` and `access_token` variables are set in the environment. Use that environment and select your desired API endpoint from the list of available collections.
4) Fill in the appropriate detais for the reuest or data and click on **Send**
5) Output will appear in the Response Sections with appropriate error codes and messages
