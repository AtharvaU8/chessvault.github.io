## 🔒♟️Castle File
Castle File provides encryption and decryption of any file using chess in a gamified way. It can lock and unlock any file having any extensions such as .txt, .docx, .pdf, .jpg etc. It provides mechanism to encrypt the file with your own style of playing chess. This ensures the utmost security and privacy of your file in an unique and innovative way.

## F.A.Q

# Q.Why should you use Castle Fie for file encryption?

1. Human Element and Unpredictability
	- The sequence of moves becomes a part of the encryption key.
	- Adds an element of unpredictability.

2. Customization and Security
	- The encryption relies on both the chessboard state and move order, making it customisable.
	- Each encryption session produces a different depending on the moves, making brute-force attacks significantly more challenging.

3. Hybrid Encryption Approach
	- It complements traditional encryption algorithms rather than replace them
	- This combination increases security by adding a secondary key layer that’s user-dependent and interactive.

4. Educational and Interactive
	- It can serve as an educational tool to help users learn about encryption and chess concepts in a gamified way. 
	-It can also engage users, making security practices more interactive.

In summary, Castle File: chess-based file encryption stands out as an innovative, interactive, and user-customizable approach to securing data, where each encryption session is as unique as the game that produces it.

# Q.How do files get encrypted via chess?

The encryption relies on a combination of cryptographic methods and the unique game mechanics of chess. Here’s a deep dive into how the files get encrypted:

1. Understanding the Encryption Process
	- Step 1: The user starts a game on the chessboard and makes at least a minimum 4 moves. Each move modifies the board’s state.
	- Step 2: The sequence of moves is captured and converted into a cryptographic key.
	- Step 3: The generated key is then used in a standard encryption algorithm.

2. Example Process
	- User Move Sequence: e2e4, g8f6, d2d4, ...
	- Key Generation: Concatenate moves into a string e2e4g8f6d2d4..., hash it with SHA-256 to produce a 256-bit key.
	- AES Encryption: Encrypt the file using AES-256 with CBC mode, applying the generated key to scramble the file data.

# Q.Is the Key Safe and Secure? 

- The encryption key depends on the sequence of moves, which makes it unique and hard to replicate.
- Hashing for Consistency: Using a hash function like SHA-256 ensures that even a small change in the move sequence will produce a drastically different key.
- AES Security: AES is a robust encryption standard that has stood up to extensive cryptographic analysis, making it highly reliable for protecting sensitive data.

# Q.Does the Website Store the Encryption Key? 

- The website does not store the key or move sequence.
- This website is completely client side
- User Must Remember Moves: If users forget their exact sequence of moves, they lose the ability to decrypt.
