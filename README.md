List of completed tasks:

- Familiarized with the project structure (onboarding).
- Removed social networks: VK and Yandex.
- Moved sensitive information to a separate properties file.
- Refactored tests to use an in-memory database (H2) instead of PostgreSQL during testing.
- Wrote tests for all public methods of the ProfileRestController.
- Refactored the method com.javarush.jira.bugtracking.attachment.FileUtil#upload to use a modern approach for working with the file system.
- Added new functionality: tagging tasks (REST API + service implementation).
- Implemented time tracking: calculated how long a task remained in the "In Progress" and "Testing" states.
- Created a Dockerfile for the main server.
- Created a docker-compose file to run the server container alongside the database and NGINX.
