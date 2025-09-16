# HW2 - Shell Script

## Key Tasks

* **API Automation:** Wrote a POSIX-compliant shell script (`/bin/sh`) to automate interactions with a RESTful API endpoint.
* **Dynamic Problem Solving:** The script fetches tasks from a server, dynamically parses them, and executes one of three different problem-solving routines based on the task type:
    1.  **Static Response:** Submits a predefined string answer.
    2.  **Math Solver:** Parses a simple arithmetic expression, calculates the result, and submits the answer.
    3.  **Password Cracking:** Deciphers a string by repeatedly applying a substitution cipher (`tr`) within a loop until the correct plaintext is found.
* **Robust Input Handling:** Implemented command-line argument parsing using `getopts` to accept a task ID and type, including a help flag (`-h`) for usage instructions.
* **Data Validation:** Performed multiple layers of validation, including checking for correct command-line arguments, verifying that the task type from the API matches the user's input, and using regular expressions (`grep`) to ensure problem formats were valid before processing.


## Skills Demonstrated

* **Shell Scripting:** Write scripts for `/bin/sh` using core utilities, variables, `if/elif/else` conditionals, `case` statements, and `for` loops.
* **REST API Interaction:** Use of **`curl`** to perform **`GET`** and **`POST`** requests, manage HTTP headers (`-H`), and send JSON payloads (`-d`).
* **Text & Data Processing:**
    * **`jq`**: Parsing and extracting data from **JSON** responses.
    * **`awk`**: Performing arithmetic calculations on string data.
    * **`grep`**: Using **regular expressions** for input validation and pattern matching.
    * **`tr`**: Executing character-based translation for cryptographic tasks.
* **Automation & Scripting Logic:** Designing an automated workflow that can handle variable inputs and execute different logic paths accordingly.
* **Error Handling:** Writing a resilient script that validates inputs, checks for mismatches, and redirects error messages to standard error (`>&2`) for proper diagnostics.

## Notes
https://sun-ski-6a4.notion.site/HW2-Shell-Script-113768cf5f3580a4b90de89e56df1870?source=copy_link
