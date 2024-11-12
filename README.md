# Password Generator

## Overview
The **Password Generator** program is a Python script that generates customized passwords by combining names and years from provided text files. This tool can be useful for creating predictable but unique passwords based on user-specific data, often used for testing or simulation purposes in penetration testing environments.

## Features
- **Name and Year Combination:** Generates passwords by combining names with years.
- **Randomized Output:** Shuffles combinations for added randomness.
- **Customizable Output:** Allows the user to specify the number of passwords generated.

## Requirements
- Python 3.6 or higher

## Getting Started

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/dawishcyber/Password-Generator-Project.git
   cd Password-Generator-Project
   ```
2. Ensure you have the required files:
   - `names.txt` - a file containing names (one name per line)
   - `years.txt` - a file containing years (one year per line)

### Usage

1. Run the program:
   ```bash
   python password_generator.py
   ```
2. When prompted, provide:
   - Path to the file containing names (e.g., `names.txt`).
   - Path to the file containing years (e.g., `years.txt`).
   - Number of passwords you wish to generate.

3. The program will generate the specified number of passwords and save them in `generated_passwords.txt`.

### Example
Given a `sierra_leone_names.txt` file containing:
```
Alice
Bob Smith
```
and a `years_list.txt` file containing:
```
1980
1990
```
Running the program with `num_passwords = 4` might generate:
```
alicesmith1980
bobsmith1980
alicesmith1990
bobsmith1990
```

## Error Handling
The program includes error handling for:
- Missing files
- Invalid file paths
- Non-numeric or negative values for the number of passwords

## Contributing
Feel free to submit issues or pull requests if you find bugs or want to improve the tool!

```



