<p align="center">
  <a href="#" rel="noopener">
 <a href="https://ibb.co/V3zLJZ8"><img src="https://i.ibb.co/PtPrFn8/In-Shot-20241202-025141849.png" alt="In-Shot-20241202-025141849" border="0" width="150"></a>
</p>

<a href="https://castlefile.xyz" style="color:#000"><h3 align="center">castlefile.xyz</h3></a>

---

[Castle File](https://castlefile.xyz) provides encryption and decryption of any file using chess in a gamified way. It can lock and unlock any file having any extensions such as .txt, .docx, .pdf, .jpg etc. It provides mechanism to encrypt the file with your own style of playing chess. This ensures the utmost security and privacy of your file in an unique and innovative way.

## Usage

![how-to-use-gif](https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExZTNiZmgyMDlpMW94MzBkOGIxNXQ3ajB0dndnaXUyMzJ1eGt5dDJnaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/GLHzWE2rWQUugtxMl5/giphy.gif)

<br>

## Features 

### Functionality 

- Secure multiple file encryption/decryption with chess moves.
- complements traditional encryption algorithms rather than replace them.
- Engage users, making security practices more interactive.
- Chess Moves Suggestion 

Castle File: chess-based file encryption stands out as an innovative, interactive, and user-customizable approach to securing data, where each encryption session is as unique as the game that produces it.

### File Encryption Process via chess

The encryption relies on a combination of cryptographic methods and the unique game mechanics of chess. Here’s a deep dive into how the files get encrypted:

1. Understanding the Encryption Process
	- Step 1: The user starts a game on the chessboard and makes at least a minimum 4 moves. Each move modifies the board’s state.
	- Step 2: The sequence of moves is captured and converted into a cryptographic key.
	- Step 3: The generated key is then used in a standard encryption algorithm.

2. Example Process
	- User Move Sequence: e2e4, g8f6, d2d4, ...
	- Concatenate moves into a string e2e4g8f6d2d4..., hash it with SHA-256 to produce a 256-bit key.
	- Encrypt the file using AES-256 with CBC mode, applying the generated key to scramble the file data.

### Safety and Security

- The encryption key depends on the sequence of moves, makeing it unique and hard to replicate.
- Hash function SHA-256 for Encryption Key Generation.
- AES with CBC mode for File Encryption. 
  
### Privacy 

- The website does not store the key or move sequence.
- This website is completely client side
- If user forget their exact sequence of moves, they lose the ability to decrypt.
