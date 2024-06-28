
# Project Title
## Ethical Disclaimer
This project is for educational and research purposes only. Any misuse of the code for malicious purposes is strictly prohibited. The authors are not responsible for any damage caused by the misuse of this code.
## Description
This project is a comprehensive collection of cryptographic tools and modules implemented in C++. It includes various cryptographic algorithms, hash functions, and supporting utilities, organized into distinct modules. The project is structured to facilitate modular development and testing within Visual Studio.

## Project Structure
- **Proj.sln**: Solution file for Visual Studio.
- **s.txt**: Metadata or notes.
- **Babyk/**: Core cryptographic implementations.
  - `another.cpp`, `another.h`: Additional cryptographic functionalities.
  - `args.cpp`, `args.h`: Argument parsing for cryptographic functions.
  - `debug.cpp`, `debug.h`: Debug utilities.
  - `entry.cpp`: Entry point for Babyk.
  - `memory.cpp`, `memory.h`: Memory management utilities.
  - `queue.cpp`, `queue.h`: Queue utilities.
  - **ecc/**: Elliptic curve cryptography implementations.
    - `curve25519-donna.cpp`, `curve25519-donna.h`
  - **eSTREAM/**: eSTREAM cryptographic functions.
    - `ecrypt-config.h`, `ecrypt-machine.h`, `ecrypt-portable.h`, `ecrypt-sync.h`, `hc-128.cpp`
  - **hash/**: Hash functions.
    - `crc32.cpp`, `crc32.h`, `sha512.cpp`, `sha512.h`
  - `Babyk.vcxproj`, `Babyk.vcxproj.filters`, `Babyk.vcxproj.user`: Visual Studio project files.
- **builder/**: Builder module.
  - `builder.vcxproj`, `builder.vcxproj.filters`, `builder.vcxproj.user`
  - `curve25519-donna.cpp`, `curve25519-donna.h`, `Source.cpp`
- **Decryptor/**: Decryptor module.
  - `args.cpp`, `args.h`: Argument parsing for decryption.
  - `Decryptor.vcxproj`, `Decryptor.vcxproj.filters`, `Decryptor.vcxproj.user`: Visual Studio project files.
  - `entry.cpp`: Entry point for Decryptor.
  - `memory.cpp`, `memory.h`: Memory management for Decryptor.
  - `queue.cpp`, `queue.h`: Queue utilities.
  - **ecc/**: Elliptic curve cryptography for Decryptor.
    - `curve25519-donna.cpp`, `curve25519-donna.h`
  - **eSTREAM/**: eSTREAM cryptographic functions for Decryptor.
    - `ecrypt-config.h`, `ecrypt-machine.h`, `ecrypt-portable.h`, `ecrypt-sync.h`, `hc-128.cpp`
  - **hash/**: Hash functions for Decryptor.
    - `crc32.cpp`, `crc32.h`, `sha512.cpp`, `sha512.h`
- **test/**: Testing utilities.
  - `main.cpp`: Main test file.
  - `ntruenc.lib`, `ntru_crypto.h`, `ntru_crypto_drbg.h`, `ntru_crypto_error.h`, `ntru_crypto_platform.h`: Libraries and headers for testing.
  - `test.vcxproj`, `test.vcxproj.filters`, `test.vcxproj.user`: Visual Studio project files for testing.

## Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone https://github.com/maxamin/Babyk-RWSC.git
   ```
2. **Open the solution**:
   Open `Proj.sln` in Visual Studio.
3. **Build the solution**:
   Build the entire solution from Visual Studio or use the command line.

## Usage
### Running Babyk
1. **Configure arguments**: Modify `args.cpp` and `args.h` as needed.
2. **Build and run**: Execute the Babyk project in Visual Studio.

### Running Decryptor
1. **Configure arguments**: Modify `args.cpp` and `args.h` in the Decryptor directory.
2. **Build and run**: Execute the Decryptor project in Visual Studio.

### Running Tests
1. **Setup**: Ensure `ntruenc.lib` and related headers are correctly linked.
2. **Build and run**: Execute the `test` project in Visual Studio.

## Modules Description
### Babyk
Implements various cryptographic algorithms and utilities, including elliptic curve cryptography and hashing functions.

### builder
A module responsible for building and possibly compiling cryptographic components.

### Decryptor
Focuses on decryption utilities and functionalities.

### test
Contains testing utilities and configurations to validate the cryptographic implementations.

## Building and Testing
1. **Build**: Use Visual Studio to build individual projects or the entire solution.
2. **Run Tests**: Use the `test` project to run predefined tests and validate functionality.

## Contributing
Please follow standard contributing guidelines:
1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request.

# Donation:

[Binance_ID:271854090]

Buy Me a Coffee: [Buy Me a Coffee](https://buymeacoffee.com/maxamin)

Ba9chich : [ba9chich.com/UL-Tunisia](https://ba9chich.com/UL-Tunisia)

# [Pray for peace to 🇵🇸]
