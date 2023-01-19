# Design-first approach with CADL

> Demonstrating how we can create an API with CADL

## Running the demo

```sh
# Installing dependencies
npm install

# Compile the CADL API defined in main.cadl
npm run compile

# View the generated OpenAPI v3 in the local Swagger UI
npm run ui

# Now you can access the Swagger UI using http://localhost:3355
```

## Viewing other examples

```sh
# Basic example
npx cadl compile 0-starting-point.cadl

# Consistency and reusability
npx cadl compile 1-consistency-and-reuse.cadl

# Error handling with error models
npx cadl compile 2-error-handling.cadl

# Securing the API
npx cadl compile 3-security-constraints.cadl

# Deprecating endpoints
npx cadl compile 4-deprecations.cadl

# Versioning
npx cadl compile 5-versioning.cadl

# Integration with Azure API Management
npx cadl compile 6-apim.cadl --emit @azure-tools/cadl-autorest
# Now you can view the generated OpenAPI v2 in https://editor.swagger.io/ and import it into your APIM instance
```