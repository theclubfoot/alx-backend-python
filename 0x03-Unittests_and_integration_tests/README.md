## 0x003. Unittests and Integration Tests

## Description

Unit tests are automated tests that check individual units or components of a software system, such as functions or classes, to ensure that they work as expected in isolation.

Integration tests are tests that check how different units or components of a software system work together. They verify that the interactions and data flow between components are correct and the overall system behaves as expected.
```
–unittest — Unit testing framework
–unittest.mock — mock object library
–How to mock a readonly property with mock?
–parameterized
–Memoization
–The difference between unit and integration tests.
–Common testing patterns such as mocking, parametrizations and fixtures

```
---

## Tasks

+ [x] [0. Parameterize a unit test](./test_utils.py)

   + Familiarize yourself with the utils.access_nested_map function and understand its purpose. Play with it in the Python console to make sure you understand.

+ [x] [1. Parameterize a unit test](./test_utils.py)

   + Implement TestAccessNestedMap.test_access_nested_map_exception. Use the assertRaises context manager to test that a KeyError is raised for the following inputs (use @parameterized.expand):

+ [x] [2. Mock HTTP calls](./test_utils.py)

   + Familiarize yourself with the utils.get_json function.

+ [x] [3. Parameterize and patch](./test_utils.py)

   + Read about memoization and familiarize yourself with the utils.memoize decorator.

+ [x] [4. Parameterize and patch as decorators](./test_client.py)

   + Familiarize yourself with the client.GithubOrgClient class.

+ [x] [5.  Mocking a property](./test_client.py)

   + memoize turns methods into properties. Read up on how to mock a property (see resource).

+ [x] [6. More patching](./test_client.py)

   + Implement TestGithubOrgClient.test_public_repos to unit-test GithubOrgClient.public_repos.

+ [x] [7. Parameterize](./test_client.py)

   + Implement TestGithubOrgClient.test_has_license to unit-test GithubOrgClient.has_license.
+ [x] [8. Integration test: fixtures](./test_client.py)

    + We want to test the GithubOrgClient.public_repos method in an integration test. That means that we will only mock code that sends external requests.

+ [x] [9. Integration tests](./test_client.py)

   + Implement the test_public_repos method to test GithubOrgClient.public_repos.

---

## Author

**Lawrence Adams** - [theclubfoot](https://github.com/theclubfoot)
