# Malware Scanner

Malware Scanner is a Python program that scans a directory or a set of directories for known malware using their hashes.
You can also find the use of the tool on my youtube address.

## Installation

1. Clone the repository:
    ```
    git clone https://github.com/HalilDeniz/MalwareScanner.git
    ```
2. Install the required packages:
    ```
    pip install -r requirements.txt
    ```

## Usage

1. Run the program:
    ```
    python malwarescanner.py
    ```
2. The program will ask for the directory or directories to scan.
3. The program will then scan the specified directories and output any identified malware to the console.

## How it works

The program calculates the MD5, SHA1, and SHA256 hashes of each file in the specified directories. It then compares the hashes to a list of known malware hashes. If a file matches a known malware hash, the program outputs the name of the file and the type of malware it is associated with.

## Configuration

### Hashes

The list of known malware hashes is stored in the `hashes.txt` file. You can add or remove hashes from this file to update the list of known malware.

### Malware Classification

The program categorizes malware based on its hash. The `malware_classification` dictionary in the `malwarescanner.py` file maps hash values to malware types. You can add or remove mappings from this dictionary to classify additional types of malware.

### Directories to Scan

The `directories_to_scan` list in the `malwarescanner.py` file determines which directories the program will scan for malware. By default, the list includes the root directory of the C: drive on Windows and the root directory of the filesystem on Linux.

## Contributing
Contributions are welcome! To contribute to MalwareScanner, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Open a pull request in the main repository.


## Contact

- LinkedIn: https://www.linkedin.com/in/halil-ibrahim-deniz/
- TryHackMe: https://tryhackme.com/p/halilovic
- Instagram: https://www.instagram.com/deniz.halil333/
- YouTube: https://www.youtube.com/c/HalilDeniz
- Denizhalil: https://denizhalil.com/
- Email: halildeniz313@gmail.com

## License

[MIT License](LICENSE)
