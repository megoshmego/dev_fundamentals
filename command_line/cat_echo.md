The transcript introduces two commands: "cat" and "echo" in the context of manipulating files and outputting text in the terminal.

1. "cat" command:
The "cat" command is used to view the contents of a file or concatenate multiple files and display their contents. It stands for "concatenate." By running the "cat" command followed by the name of a file, you can print the content of that file to the terminal.

Example:
```
cat app.js
```

2. "echo" command:
The "echo" command is used to print text or variables to the terminal. It repeats back whatever text or variable you provide as an argument.

Example:
```
echo kitten
```

Additionally, the transcript demonstrates the usage of the redirect operator (">") to redirect the output of the "echo" command into a file. This allows you to add text to a file directly from the command line.

Example:
```
echo "butters is chicken" > butters.txt
```

It's important to note that using the redirect operator with a single ">" overwrites the content of the file. To append the content to an existing file, you can use the append operator (">>").

Example:
```
echo "butters is chicken and he is cool" >> butters.txt
```

The transcript also mentions escaping special characters in the text provided to the "echo" command if necessary.

Overall, the "cat" command is useful for viewing file contents, and the "echo" command, along with redirection, provides a convenient way to add or create simple text files from the command line.