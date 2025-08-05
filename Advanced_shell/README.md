# Advanced Shell Scripting Project
==========================

## Project Overview
This repository contains a collection of shell scripts designed to automate Pokémon API interactions, demonstrating advanced shell scripting techniques including data manipulation, parallel processing and error handling.

## Tasks Overview

The project consists of five mandatory tasks that progressively build upon each other:

### Task 0: API Request Automation
- Implements error logging to `errors.txt`.
- Saves response to `data.json`.
- Automates retrieval of Pikachu's data from the Pokémon API.

### Task 1: Extract Pokémon Data
- Formats output in human-readable format.
- Uses text manipulation tools (jq, awk, sed) to extract specific fields.
- Example: "Pikachu is of type Electric, weighs 6kg, and is 0.4m tall."

### Task 2: Batch Pokémon Data Retrieval
- Stores responses in individual JSON files.
- Retrieves data for multiple Pokémon.
- Implements rate limiting with configurable delays.

### Task 3: Summarize Pokémon Data
- Includes comprehensive error handling.
- Calculates average height and weight.
- Generates CSV reports from JSON files.

### Task 4: Error Handling and Retry Logic
- Enhanced error logging.
- Maximum 3 attempts per request.
- Adds retry mechanism for failed requests.

### Task 5: Parallel Data Fetching
- Maintains data consistency.
- Proper background process management.
- Implements parallel processing for faster data retrieval.

## Prerequisites
- jq for JSON parsing.
- sed for string manipulation.
- curl for HTTP requests.
- Bash shell environment.
- awk for text processing.

## Directory Structure
```plaintext
Advanced_shell/
├── apiAutomation-0x00      # Task 0 script
├── data_extraction_automation-0x01  # Task 1 script
├── batchProcessing-0x02   # Task 2 script
├── summaryData-0x03       # Task 3 script
└── batchProcessing-0x04   # Task 5 script
```

## Usage Instructions
Each script is documented individually with usage examples and expected outputs. Refer to the specific task directory for detailed usage instructions.

## Error Handling
All scripts implement robust error handling with:
- Retry mechanisms where applicable.
- Log file management.
- Custom error messages.
- Exit status checking.

## Contributing
Contributions are welcome! Please ensure all pull requests:
- Maintain documentation.
- Pass all test cases.
- Include proper error handling.
- Follow existing coding standards.