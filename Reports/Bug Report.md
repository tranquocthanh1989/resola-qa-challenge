# Bug no.#001
### Description: Optional attributes do not accept NULL value

**Pre-condition:**
- Postman collection is imported, and test case `TrackEvent_API_200_1` should be available

**Step to reproduce:**
- Open the test case `TrackEvent_API_200_1`
- For the key `anonymousId`, update value to NULL to make it look like this
>   "anonymousId": null
- Run the test

**Expectation:**
The return status should be `200`

**Actual result:**
The return status is `400`
> ![image](https://user-images.githubusercontent.com/131781585/234882107-7fc73e48-aecd-49d3-8956-8ce6dafebe5f.png)

**Note**:
- The same issue with key `userId`
