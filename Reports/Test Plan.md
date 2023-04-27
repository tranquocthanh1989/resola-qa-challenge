## Purpose
- This test plan is acting as a guidline to verify the API Track Event which can be found [here].
- Specifically the test plan consists of test objects, assumption, test data preparation, list of test cases, risk management and high level estimation.
- We will frequently update the plan if there is any changes in specification and requirement.

## Test objects and approach
- The API Track Event is a POST method, so we will use a tool like Postman to submit the request multiple times with different input
- The test is considered to be done when we go through all the test cases and with PASSED status.
- A smoke test is conducted at the end of Sprint if we have time, and it will check the mix of actions that trigger this event/call.
> For examples User adds 4 items into the Cart, then remove 1, add another into Wishlist and submit the Cart.



## Assumption
- The API is called automatically when User perfomed some specific actions on the Front-end: add item into Cart, submit Cart
- All the values are defined as 'String' but not specific the lenght, so assumpt that max lenght is 60. Because most of them are ID which is usually around 24-32 chars
- All the values are already saved into Database

## Test data
- Should have a query into Database to get the actual data (format, pattern)

## Test cases
- Refer to this [file here]


## Estimation:
- 1 MD for execution all test cases also define automation test in Postman.

## Risk management:
- The Tester who reviewed this test cases are considered as the back-up resource
- If the endpoint is down, we will only test the happy cases
- Need to test with GUI later to see the API is triggered properly

[here]: https://resola.stoplight.io/docs/resola/e2bebaae60b45-track-event
[file here]: 
