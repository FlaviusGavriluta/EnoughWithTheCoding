# Enough with the coding

## Story

You and your friends were excited about becoming a programmer, but more and more, you feel an urge to do something more calm and chill.
The solution came like a flash: You should become postmen.

Codecool has taught you that nowadays every job has some digital connection, so you googled it and found the Postman Collaboration Platform for API Development. It seems like a good fit for the job...

## What are you going to learn?

- call APIs without writing code
- test APIs

## Tasks

1. As a user, I would like to have `Postman` downloaded an installed on my machine.
    - On `Ubuntu`, `Postman` is listed on the `Show Applications` list.
    - On `macOS`, `Postman` can be found in the `Applications` folder.

2. Create a new collection with the name `Postman repositories` and an empty description.
    - A collection with the name `Postman repositories` exists.
    - The collection's description is empty.

3. Add a request to the `Postman repositories` collection with the name `Postman Inc.` and description `GitHub`.
    - A request called `Postman Inc.` added to the `Postman repositories` collection.
    - The request's description is `GitHub`.

4. Set the `User-Agent` header of the `Postman Inc.` request to one that represents the operating system you use.
    - The `User-Agent` key is set on the `Headers` tab to one for the used operating system.

5. Use `GET` as the default HTTP request method for `Postman Inc.`
    - The HTTP request methods drop down list shows `GET`.

6. Get the repositories of the `postmanlabs` GitHub user.
    - The request URL is set to `https://api.github.com/users/postmanlabs/repos`.

7. Test if the response status is `OK`.
    - When I click on the `Send` button and I'm on the `Test Results` tab,
I should see `[PASS] Status OK`.

8. Test if the response time is less than `900ms`.
    - When I click on the `Send` button and I'm on the `Test Results` tab,
I should see `[PASS] Response time is less than 900ms`.

9. Test if the response has a `JSON body`.
    - When I click on the `Send` button and I'm on the `Test Results` tab,
I should see `[PASS] JSON Body`.

10. Test if all the repositories in the response has `postmanlabs` as the owner.
    - When I click on the `Send` button and I'm on the `Test Results` tab,
I should see `[PASS] Owner is "postmanlabs"`.

11. Export the `Postman repositories` collection with recommended settings.
    - There is a Postman export file of the `Postman repositories` collection
named `Postman repositories.postman_collection.json` pushed into the repository.

## General requirements

None

## Hints

- User-Agent examples can be found [HERE](project/curriculum/materials/pages/general/user-agent.md)

## Background materials

- <i class="far fa-exclamation"></i> [Installing Postman on Linux](https://learning.postman.com/docs/getting-started/installation-and-updates/#installing-postman-on-linux)
- <i class="far fa-exclamation"></i> [Installing Postman on Mac](https://learning.postman.com/docs/getting-started/installation-and-updates/#installing-postman-on-mac)
- <i class="far fa-book-open"></i> [Writing tests for Postman requests](https://learning.postman.com/docs/writing-scripts/test-scripts/)
- <i class="far fa-book-open"></i> [Postman test script examples](https://learning.postman.com/docs/writing-scripts/script-references/test-examples/)
- <i class="far fa-book-open"></i> [HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
