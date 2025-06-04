This Python script securely generates a specified number of authentication codes (auth codes) with customizable length and minimum special character requirements. These auth codes are designed to serve as secure tokens or passwords, particularly useful for sensitive operations like domain transfers, API key generation, or user verification processes.

### Key Features

- **Configurable Quantity:** Easily specify how many unique auth codes to generate in one run.
- **Custom Length:** Define the exact length of each generated code (default is 16 characters).
- **Special Character Enforcement:** Ensure a minimum number of special characters per code (default is 2), enhancing password strength and complexity.
- **Secure Randomness:** Uses Python’s secrets module for cryptographically secure random choices, making the codes highly unpredictable and resistant to brute force attacks.
- **Character Set:** Codes include uppercase and lowercase letters, digits, and a custom set of special characters (! $ @ *), balancing usability and security.
- **Randomized Character Distribution:** Special characters and other characters are shuffled to avoid predictable patterns.
- **Practical Application:** Ideal for generating authorization codes or passwords required during domain transfer processes — where secure transfer keys are necessary to authorize the transfer between registrars, helping prevent unauthorized domain hijacking.
- **Flexible and Extendable:** You can easily modify the special characters set or adjust parameters to fit different security policies or application needs.

### Why Use Auth Codes for Domain Transfers?
In domain management, an auth code (also known as EPP code, transfer key, or authorization key) is a password-like token used to authenticate and approve the transfer of a domain name from one registrar to another. Generating strong, random, and secure auth codes helps:

- Prevent unauthorized domain transfers.
- Protect domain ownership.
- Comply with domain registry security standards.

Using this script, domain registrars or administrators can automate the generation of such auth codes with guaranteed complexity and randomness.
