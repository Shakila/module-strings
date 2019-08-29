# Module Overview

The `wso2/strings` module provides an API to do string validations and string operations from Ballerina.

**String Validations**

Currently, following string validations are supported through this module.

 - Email validation.
 - IP validation.
 - Check existence of IP in the IP list.
 - URL validation.

## Compatibility

|                             |       Version               |
|:---------------------------:|:---------------------------:|
| Ballerina Language          | 0.992.0                     |

## Sample

Following is a simple Ballerina program for validating the *Email address*.

```ballerina
import ballerina/log;
import wso2/strings;

public function main () {
    boolean validationRes = strings:isEmail("joe@wso2.com");
    log:printInfo("Result of the email validation is: " + validationRes);
}
```
