# My Blog Practice

A blog project created as part of the NPTEL Internship exercise.

## Project Structure

The project follows a standard blog folder structure:

- `assets/`: For storing static assets like images, CSS, and JavaScript files
- `content/`: For storing published blog posts
- `drafts/`: For storing draft blog posts
- `__tests__/`: Contains test files for the project

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run tests:
   ```bash
   npm test
   ```

## Development

- The project uses Node.js
- Tests are written using Jest
- CI/CD is configured using GitHub Actions

## CI/CD

The project includes a GitHub Actions workflow that:

- Runs on every push and pull request
- Executes the test suite
- Ensures code quality

## License

ISC
