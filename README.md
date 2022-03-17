# libft
The purpose of this project was to reimplement some functions from several C libraries.

Platforms: MacOS, Ubuntu.

Reimplemented functions:
- atoi: converts the initial portion of the string to int representation;
- bzero: writes len (the first parameter) zero bytes to the massive (the second parameter);
- calloc: allocates space for number (the first paramenet) objects, each size bytes (the second parameter) in length;
- isalnum: tests if a character is a digit or a letter of the alphabet (ASCII);
- isalpha: tests if a character is a letter of the alphabet (ASCII);
- isascii: tests if a character is a symbol if ASCII table;
- isdigit: tests if a character is a digit (ASCII);
- isprint: tests if a character is a printing symbol (ASCII);
- itoa: converts a digit in int to a string representation;
- lstadd_back: adds new element (the second parameter) in the end if a list (the first parameter);
- lstadd_front: adds new element (the second parameter) as a first element of a list (the first parameter);
- lstclear: deletes all elements form a list;
- lstdelone: deletes an element (the first parameter) from a list using a function (the second parameter - pointer to function) to delete content of an element;
- lstiter: applyes a function (the second parameter - pointer to function) to content of each element of a list (the first parameter);
- lstlast: returns the last element of a list;
- lstmap: copies a list (the first paramenter) and applyes a function (the second parameter - pointer to function) to content of each element of a new list. If memory allocation is failed the function calls lstclear for new list with the third parameter as a fuction to delete content of each element;
- lstnew: creates a new element with content (a parameter);
- lstsize: counts number of elements in a list;
- memccpy: copies a massive (the second parameter) to a massive (the first perameter) len bytes (the third parameter) or while a character (the fourth parameter) isn't found;
- memchr: searchs in a massive (the first perameter) a character (the second parameter) in the first len bytes (the third parameter). If the caracter is found, the function returns a massive which begins with the character. Else the function returns NULL;
- memcmp: compares the first len bytes (the third parameter) of two massives (the first and second parameters) and returns a result of substruction the first different characters of zero if the massives are equal;
- memcpy: 
