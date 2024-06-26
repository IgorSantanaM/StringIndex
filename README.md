# String Index Methods Example

This C# program demonstrates various string indexing and searching methods using the `StringIndexMethods` class.

## Overview

The `StringIndexMethods` class operates on the string `"abcdefghijklmabcdefghijklm"` and performs several operations to locate characters and substrings, including:

- Using `IndexOf` and `LastIndexOf` to find characters in a string.
- Using `IndexOf` and `LastIndexOf` to find substrings in a string.
- Using `IndexOfAny` and `LastIndexOfAny` to find occurrences of characters from an array in a string.

### Methods Used

1. **IndexOf**
   - Searches for the first occurrence of a character or substring in the string.
   - Syntax: `string.IndexOf(char value)` or `string.IndexOf(string value)`.

2. **LastIndexOf**
   - Searches for the last occurrence of a character or substring in the string.
   - Syntax: `string.LastIndexOf(char value)` or `string.LastIndexOf(string value)`.

3. **IndexOfAny**
   - Searches for the first occurrence of any character from an array in the string.
   - Syntax: `string.IndexOfAny(char[] anyOf)`.

4. **LastIndexOfAny**
   - Searches for the last occurrence of any character from an array in the string.
   - Syntax: `string.LastIndexOfAny(char[] anyOf)`.

## How to Use

1. **Compile and Run the Program:**
   - Ensure you have a C# compiler installed.
   - Compile the program using `csc StringIndexMethods.cs`.
   - Run the program with `StringIndexMethods.exe`.

2. **Output:**
   - The program will output the index positions of various characters and substrings within the string `"abcdefghijklmabcdefghijklm"`.

### Example Output

