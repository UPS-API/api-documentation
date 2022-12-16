# UPS API Documentation
This respository contains OpenAPI Specifications for the APIs on developer.ups.com. 

These files can be used in conjunction with various plugins and packages to generate models for UPS API request and response objects. 

All of our APIs are secured with with OAuth 2.0 protocol and require an access token to transact with. Access tokens can be generated through two different grant types, either Client Credentials (OAuth ClientCredentials) or Authorization Code (OAuth AuthCode). The grant type is based on how you will transact with UPS APIs, whether your application will represent a single entity or multiple users. For more information please check the links below:
 
 [Client Credentials](https://developer.ups.com/en-us/oauth-client-credentials) 
 
 [Authorization Code](https://developer.ups.com/en-us/oauth-authorization-code)

## License

Copyright 2022 UPS.

Code licensed under the MIT License: <http://opensource.org/licenses/MIT>