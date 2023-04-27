# Bug no.#001
### Description: deviceType attributes allows non-defined value

**Pre-condition:**
- Postman collection is imported, and test case `TrackEvent` should be available

**Step to reproduce:**
- Open the test case `TrackEvent`
- For the key `deviceType`, update value to something else other than `pc` or `mobile`
>   For example:
>   "deviceType": "test"
- Run the test

**Expectation:**
The return status should be `400`

**Actual result:**
The return status is `200`

