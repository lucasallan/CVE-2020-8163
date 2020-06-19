# CVE-2020-8163
CVE-2020-8163 - Remote code execution of user-provided local names in Rails

Remote code execution of user-provided local names in Rails < 5.0.1

There was a vulnerability in versions of Rails prior to 5.0.1 that would
allow an attacker who controlled the `locals` argument of a `render` call.

This vulnerability has been assigned the CVE identifier CVE-2020-8163.

Versions Affected:  rails < 5.0.1
Not affected:       Applications that do not allow users to control the names of locals.
Fixed Versions:     4.2.11.2

### Vulnerable app:

I've included a vulnerable app that can be used for testing purposes. The vulnerable endpoint is: `main/index`

