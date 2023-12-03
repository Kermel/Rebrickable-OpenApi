# Rebrickable-OpenApi
Publicly available Rebrickable.com APIv3 OpenAPI specification enhanced with return value schemas for better client's code generation

The great LEGO source webpage www.rebrickable.com offers a comprehensive API in OpenApi format (https://rebrickable.com/api/). The only issue is that for the API operations provided
within the APIv3 swagger specification (available here: https://rebrickable.com/api/v3/swagger/?format=openapi) there are no return types defined so the produced JSON is not 
very useful for client code generation.

This is an attempt to fill this gap and to define the return value schemas.

So far I have created the return types for the "lego" part of the API. I have not created anything for the "users" part (as I do not need it for my project as of now). Feel free to contribute.
