# BASAL_PA-1
#Problem1_ALPHABET_SOUP
#This program takes a word as input and returns its letters arranged in alphabetical order.

#Defines a function named 'alphabet_soup' that accepts a string (word) and returns a string (the word’s letters sorted alphabetically).

#'sorted()' sorts the characters in the word.
#The 'key=str.lower' ensures that sorting is case-insensitive (so 'A' and 'a' are treated the same).
#The result is a list of characters in alphabetical order.

#Joins the sorted list of characters back into a single string without spaces ('' is the separator).

#Problem2_EMOTICON_PROBLEM
#This program replaces specific words in a sentence with their corresponding emoticon symbols.

#Defines a function named 'emotify' that accepts a string (sentence) and returns a string (the modified sentence with words converted into emoticons).

#A dictionary 'emoticons' is created with key-value pairs:
#"smile" → ":)"
#"grin" → ":D"
#"sad" → ":("
#"mad" → ">:("

#The function loops through each word and its corresponding symbol in the dictionary using .items().

#For each word: sentence.replace(word, symbol) replaces the lowercase version.
#.replace(word.capitalize(), symbol) ensures that capitalized words (e.g., "Smile") are also replaced.

#Finally, the function returns the modified sentence with the appropriate emoticons.

#Problem3_UNPACKING_LIST_PROBLEM
# Example: Unpacking a list into variables in Python

# Define a list with six elements

# Unpack the list:
# - 'first' gets the first element
# - 'last' gets the last element
# - '*middle' collects all the elements in between into a new list

# Print the unpacked values
# Output: 1
# Output: [2, 3, 4, 5]
# Output: 6
