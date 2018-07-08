# Telephone-Keypad
A program that given a "phone number" prints a sorted list of all possible words generated from a telephone keypad.

`words_list.txt` is a txt file each line of which is a word. 

## Examples

Git clone the repository and run the code in the terminal.

1. Return "abt", "abu", "abv", "act", "bat", "cat", and "cav" for "228".

```
python telephone_keypad.py "228" < words_list.txt
```

2. Return None if there are no possible words.

```
python telephone_keypad.py "6502227795" < words_list.txt
```