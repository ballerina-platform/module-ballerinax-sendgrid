_Author_:  Ravindu Heshan\
_Created_: 2024/10/30\
_Updated_: 2024/10/22\
_Edition_: Swan Lake

# Sanitation for OpenAPI specification

This document records the sanitation done on top of the official OpenAPI specification from SendGrid. 
The OpenAPI specification is obtained from (TODO: Add source link).
These changes are done in order to improve the overall usability, and as workarounds for some known language limitations.

1. 
2. 
3. 

## OpenAPI cli command

The following command was used to generate the Ballerina client from the OpenAPI specification. The command should be executed from the repository root directory.

```bash
bal openapi -i docs/spec/openapi.yaml --mode client --license docs/license.txt -o ballerina --use-sanitized-oas
```
Note: The license year is hardcoded to 2024, change if necessary.
