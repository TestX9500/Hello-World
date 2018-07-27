# Well beautiful, this is stupid thing to do for a checklist, just thought of pointing that out

Checklist **Code Submission Template Question** | **Notes**
------------ | ------------ | -------------
[X] | I have ensured my commit message includes the rational for the change. | Describe the rationale for the change.
[ ] | I have ensured my commit message includes root cause and description of the fix. | If a defect then describe the root cause and description of fix.
[ ] | I have updated any documentation (HLD/DD/Test Plan) to reflect any changes in behavior. | We want the prompt for the developer to take action. If applicable then answer yes with JIRA ID. 
[ ] | If my change crosses multiple repos then I have ensured special handling/coordination. | Example: PR could depend on another PR crossing repos. Some ECUs have this condition such as ECG.
[ ] | I have built and tested this change locally.
[ ] | I reviewed the current unit tests to cover this change and added new tests as required. 
[ ] | I have added details to the JIRA of the tests performed. | Example: Ran the full unit test suite. Describe the required testing for this change. (Required testing before and after submission.)
[ ] | I have ensured that strategies are in place for backwards compatibility between changes spread among multiple repositories or involving public APIs. | Example: To make reviewer notice if compatibility is broken then to look at other things and consider them.
[ ] | I have ensured that if these changes impact multiple ECUs then these changes have been coordinated.
