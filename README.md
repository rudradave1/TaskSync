# TaskSync

TaskSync is a Kotlin Multiplatform task management application supporting Android, iOS, web, and desktop platforms.

## Features

- Create, update, and delete tasks
- Filter tasks by status
- Synchronize tasks across devices using Firebase

## Setup

### Backend
1. Clone the repository: `git clone https://github.com/rudradave1/tasksync`
2. Navigate to the backend directory: `cd tasksync/backend`
3. Configure Firebase and update environment variables.
4. Run the server: `./gradlew run`

### Frontend
1. Open the project in IntelliJ IDEA.
2. Sync the project with Gradle.
3. Run the desired platform target (Android, iOS, web, desktop).

## Testing

- Run unit tests using: `./gradlew test`
- Integration tests can be run using the command: `./gradlew integrationTest`

## Assumptions

- The application assumes users have internet access for Firebase integration.
- User authentication is required to access task management features.

## License

This project is licensed under the MIT License.
