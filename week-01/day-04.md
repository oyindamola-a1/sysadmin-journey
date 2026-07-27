Today's lesson was about **BASIC PATTERNS** 

Regular expressions are patterns that only certain commands are able to interprete. They can be expanded to match certain sequences of characters in text.

**ANCHOR CHARACTERS**
- They are one of the regular expressions that can be used to narrow search results.
- The first anchor character [ ^ ] is used to ensure that a pattern appears at the beginning of the line.
- The second anchor character [ $ ] can be used to ensure a pattern appear at the end of the line, thereby, efficiently reducing the search results.

  **MATCH A SINGLE CHARACTER WITH [ . ]**

  One of the most useful expression is the period [ . ] character, it will match any character except for the new line character.

   **MATCH A SINGLE CHARACTER WITH [ ]**

  The square brackets [ ] match a single charcter from the list of possible character contained within the brackets.

  **NOTE**; Do not mistake [ ^ 0-9 ] to match lines which do not contain numbers.

  When other expression characters are placed inside of square brackets, they are treated as literal characters.

  **MATCH A REPRESENTED CHARACTER OR PATTERNS WITH [ * ]**
