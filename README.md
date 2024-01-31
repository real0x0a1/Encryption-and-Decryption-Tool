# Encryption And Decryption Tool

This C++ program provides a simple file encryption and decryption tool using XOR encryption.

## Usage

1. **Compile the Program:**

   ```bash
   g++ EncryptionDecryptionTool.cpp -o EncryptionDecryptionTool
   ```

2. **Run the Program:**

   ```bash
   ./EncryptionDecryptionTool
   ```

3. **Choose Operation:**

   - Enter `1` to encrypt a file.
   - Enter `2` to decrypt a file.

4. **Enter File Details:**

   - Enter the input file name.
   - Enter the output file name.
   - Enter the encryption/decryption key.

5. **Example:**

   ```bash
   File Encryption/Decryption Tool
   1. Encrypt
   2. Decrypt
   Enter your choice: 1
   Enter input file name: input.txt
   Enter output file name: encrypted_output.txt
   Enter encryption/decryption key: my_secret_key
   ```

6. **Output:**
   - The program will display a success message after encryption or decryption.

## Error Handling

- If there is an error opening the files, an error message will be displayed.
- If an invalid choice is entered, an error message will be shown.

## Notes

- The program uses XOR encryption with a provided key for both encryption and decryption.
- Make sure to remember the encryption key for later decryption.

## How to Run

To run this program:

1. Make sure you have a C compiler installed on your computer.
2. Copy the code into a file with a `.cpp` extension, for example, `EncryptionDecryptionTool.cpp`.
3. Open a terminal or command prompt and navigate to the directory where your file is located.
4. Compile the program by entering: `g++ EncryptionDecryptionTool.cpp -o EncryptionDecryptionTool`
5. Run the compiled program: `./EncryptionDecryptionTool`

Or you can run this program also using:

```bash
   make EncryptionDecryptionTool
```

---

