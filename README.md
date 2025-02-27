# Educational Ransomware Simulation

## Overview
This repository contains two Python scripts for simulating ransomware encryption and decryption processes for educational purposes. The `ransom.py` script encrypts files in its directory, while `ransomdecrypter.py` decrypts them. This simulation is designed to provide practical insights into how ransomware operates and to enhance understanding of file encryption and decryption.

**Disclaimer:** This code is strictly for educational purposes. Creating, distributing, or using ransomware for malicious purposes is illegal and unethical.

## Requirements
- Python 3
- `cryptography` Python library

To install the required library, run: `pip install cryptography`

## Files
1. `ransom.py` - Encrypts files in its directory.
2. `ransomdecrypter.py` - Decrypts files encrypted by `ransom.py`.
3. `generatedkey.key` - Stores the encryption key (created by `ransom.py`).

## Usage

### Encryption
1. Place the `ransom.py` script in a directory with files you wish to encrypt.
2. Run the script: `python3 ransom.py`
3. Encrypted files and the `generatedkey.key` will be generated in the same directory.

### Decryption
1. Ensure `ransomdecrypter.py` and `generatedkey.key` are in the same directory as the encrypted files.
2. Run the script: `python3 ransomdecrypter.py`
3. Files will be decrypted and restored to their original state.

