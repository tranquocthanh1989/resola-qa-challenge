# _resola-qa-challenge_

## How to execute the test cases
In order to run the test case, we need **setup Postman:**
  - Please download the application [here] 
  - Install it, also create an account

**And here is the steps to execute test in Postman:**
- Download the Postman collection [postman-collection]
- Click `Import` button
> ![image](https://user-images.githubusercontent.com/131781585/234875001-bf0e5c54-762c-4baa-a472-683d0066669b.png)`
- Point to the downloaded JSON
- In the `resola-qa-challenge` collection, make sure you can see the request `Track Event` and `Track Event - bad request`
- In the `resola-qa-challenge`, select the `ooo` icon and select `Run collection`
> ![image](https://user-images.githubusercontent.com/131781585/234877096-160e9baa-770e-4518-bf05-bc7eeb94a51b.png)

## Personal evaluation

For the Track Event API:
- I think we should set the `userId` as a required field since the whole API relating to actions from User. It is better to know who did it.

[here]: https://www.postman.com/downloads/
[postman-collection]: https://github.com/tranquocthanh1989/resola-qa-challenge/blob/main/resola-qa-challenge.postman_collection.json
