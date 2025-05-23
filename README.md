# 📚 Readability

This project analyzes the readability of a given block of text using the **Coleman-Liau index**, which estimates the U.S. grade level needed to understand the text.

## 🚀 Features

- Counts letters, words, and sentences in any input text
- Calculates average letters and sentences per 100 words
- Applies the Coleman-Liau formula to determine grade level
- Simple and fast command-line interface

## 🧠 How It Works

The program follows these steps:

1. Prompt the user for input text
2. Count:
   - **Letters**: alphabetical characters
   - **Words**: sequences separated by spaces
   - **Sentences**: ended by `.`, `!`, or `?`
3. Compute:
   - `L` = average letters per 100 words
   - `S` = average sentences per 100 words
4. Apply the Coleman-Liau formula:
   - index = 0.0588 * L - 0.296 * S - 15.8
5. Print the resulting grade level!

Video Demo:




https://github.com/user-attachments/assets/2cc848dd-c685-4796-aa62-f9b440fd3a87




