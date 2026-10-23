# Security API

The API receives an HTTP request.
The application validates the access token.
The controller processes the request.
The API returns a response.

Details regarding API response format:

The API gives a HTTP respoonse in JSON file. It gives relavent responses susch as 400 for bad request, 200 for success or 401 for unauthorized etc accordingly.


Types of Validations:

1. Authentication Validation: Based on the type of user and their work, users can sign in and access the API.

2. Authorization Validation: Based on the permissions assigned to their respective roles, callers are validated to ensure they have access to the API.

3.Certificate Validation: Validates the certificates used for secure communication, if applicable.

4. Token Expiration Validation: Checks whether the access token has expired or is still valid.

5. Token Signature Validation: Verifies the token signature to ensure the token is valid and has not been modified.

So, these are some of the validations we use to secure our API. //

