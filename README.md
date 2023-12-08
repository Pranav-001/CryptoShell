# CryptoShell
Enhance data security effortlessly with our CLI-based encryption/decryption program, ensuring robust protection for your files.

## Getting Started

### Prerequisites

- Python 3.10
- colorama library (`pip install colorama`)


## Commands

### `hash`

Generate a hash of the input text using a specified hashing algorithm.

**Syntax:**

```bash
Hash <InputText> <Algorithm>
```

### `encode`

Encode the input text using a specified encoding algorithm.

**Syntax:**

```bash
Encode <InputText> <Algorithm>
```

### `decode`

Decode the input text using a specified decoding algorithm.

**Syntax:**

```bash
Decode <InputText> <Algorithm>
```

### `help`

Display usage information for the available commands.

**Syntax:**

```bash
help
```

### `exit`

Exit the CryptoShell.

**Syntax:**

```bash
exit
```

## Example Usage

### Encoding

```bash
Encode HelloBase64 base64
```

### Decoding

```bash
Decode SGVsbG9CYXNlNjQ= base64
```

### Hashing

```bash
Hash HelloSHA256 sha256
```

## Available Algorithms

- Encoding: {a85, base16, base32, base64, base85, hexlify}
- Decoding: {a85, base16, base32, base64, base85, hexlify}
- Hashing: {blake2b, blake2s, md5, sha1, sha224, sha256, sha384, sha3_224, sha3_256, sha3_384, sha3_512, sha512}


## Notes

- Ensure that Python 3.10 is installed.
- The colorama library is required for a better command-line interface.

Feel free to explore the capabilities of CryptoShell and experiment with different algorithms for encoding, decoding, and hashing your text!
