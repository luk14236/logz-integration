# logz-integration.py

This Python script integrates with Logz.io for logging purposes. It configures a logger to send log messages to a Logz.io account using the Logz.io Python Handler.

## Usage

1. **Dependency Installation:**
   - Install the `logzio-python-handler` and `tox` libraries by executing the provided commands.

2. **Running the Script:**
   - Set up your Logz.io API key in the `logz_token` variable.
   - The script configures a logger with Logz.io handler settings.
   - Log messages are sent to Logz.io with custom fields specified in the script.

## Requirements

- Python 3.x
- Libraries:
  - logzio-python-handler
  - tox

## Overview

This script sets up logging integration with Logz.io using the Logz.io Python Handler. It configures a logger to send log messages to a Logz.io account with specified settings.

## How It Works

- The script installs the `logzio-python-handler` and `tox` libraries.
- It defines a function `get_logger(logz_token)` to configure a logger with Logz.io handler settings.
- The logger is configured with a Logz.io handler that sends log messages to a Logz.io account.
- Log messages are formatted with custom fields and sent to Logz.io.
- Exception handling is supported, and exceptions are logged with additional context.
