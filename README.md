# Fortune Teller

Fortune Teller is a small JavaScript command-line program that prints one randomly selected fortune each time it runs.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Security](#security)
- [How to Contribute?](#how-to-contribute)
- [What's Next?](#whats-next)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Author](#author)

## About

The application defines five fortunes, generates a random number from 1 through 5, and logs the corresponding fortune to the console.

## Features

- Selects a fortune at random.
- Includes five built-in fortune messages.
- Runs entirely from the command line.
- Requires no external packages or services.

## Tech Stack

- JavaScript
- Node.js

## Architecture

The application consists of a single script:

1. Defines the available fortune messages.
2. Generates a random integer between the configured minimum and maximum values.
3. Maps the generated number to a fortune.
4. Writes the selected fortune to standard output.

## Project Structure

```text
fortuneTeller/
├── script.js    # Application entry point
└── README.md    # Project documentation
```

## Getting Started

### Prerequisites

Install a current version of [Node.js](https://nodejs.org/).

### Run the application

From the project directory, run:

```bash
node script.js
```

Run the command again to receive another randomly selected fortune.

## Configuration

No external configuration is required.

To change the fortunes or random selection range, update the values in `script.js`. Keep the minimum and maximum numbers aligned with the available fortune conditions so that every possible random value selects a message.

## Security

This project does not process user input, store data, use credentials, or communicate with external services. Keep Node.js updated when running the application locally.

## How to Contribute?

1. Fork the repository.
2. Create a branch for your change.
3. Update the script and documentation as needed.
4. Run `node script.js` to verify the application prints a fortune.
5. Open a pull request describing the change.

## What's Next?

Potential enhancements include:

- Store fortunes in an array to simplify adding new messages.
- Let users provide a custom list of fortunes.
- Add automated tests for random selection behavior.
- Add a simple browser interface.

## License

No license file is currently included in this repository. Add a license before distributing or reusing the project under defined terms.

## Acknowledgements

Built as a simple JavaScript exercise demonstrating random selection and console output.

## Author

Jack Sawyer
