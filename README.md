# 🔐 Caesar Cipher

A simple **Caesar Cipher** encryption and decryption program built with Python.

This project allows the user to:

* 🔒 Encode a message using a shift number.
* 🔓 Decode an encrypted message.
* 🔄 Restart the program and encrypt/decrypt another message.
* 🔤 Keep spaces, numbers, and symbols unchanged.
* 🔁 Handle shifts that go beyond the end of the alphabet.

## 🛠️ Concepts Used

This project helped me practice:

* Python Functions
* `for` loops
* `while` loops
* `if / else` statements
* Lists
* Strings
* `input()`
* String methods such as `.lower()`
* `alphabet.index()`
* Modulo `%`
* Function parameters
* Importing Python modules

## ⚙️ How It Works

The program uses the English alphabet:

```text
abcdefghijklmnopqrstuvwxyz
```

For encoding, each letter is shifted forward by the selected number.

For decoding, the shift is reversed.

For example, with a shift of `3`:

```text
a → d
b → e
c → f
```

The program also handles wrapping around the alphabet:

```text
z + 3 → c
```

This is achieved using the modulo operator:

```python
shifted_position %= len(alphabet)
```

## 🚀 Example

### Encode

```text
Type 'encode' to encrypt, type 'decode' to decrypt:
encode

Type your message:
hello world

Type the shift number:
3

Here is the encoded result: khoor zruog
```

### Decode

```text
Type 'encode' to encrypt, type 'decode' to decrypt:
decode

Type your message:
khoor zruog

Type the shift number:
3

Here is the decoded result: hello world
```

## 🔄 Restart Feature

After each operation, the program asks:

```text
do you want to go again?
```

Entering `yes` starts another encryption/decryption operation.

Entering `no` exits the program.

## 📁 Project Files

```text
Caesar-Cipher/
├── main.py
├── art.py
└── README.md
```

## 📚 What I Learned

This was one of my Python practice projects. It helped me understand how different Python concepts can work together to build a complete interactive program.

---

⭐ **If you like the project, feel free to star the repository!**

### 👨‍💻 Author

**Nour ELdeen**

Built with Python 🐍
