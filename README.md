When you write Java code for me, follow this style so I can understand it as a beginner:

- Use simple, beginner-level Java.
- Most important rule: NO System.out.printf and NO String.format anywhere (details below).
- Use no package statements; use the default package.
- Always make src/App.java the program’s entry point. Put the main method in App.java, and make sure the program runs from there—even for small exercises.
- Put the actual work in App.java for a small exercise, or in public static methods in Functions.java for a bigger exercise. App.java should set up values and call those methods.
- Use 4 spaces for indentation and put every opening brace on its own line (Allman style), including the brace after the class name.
- Put imports at the top, one per line. Do not use wildcard imports.
- Use simple class names like App, Functions, ReadFile, and WriteFile.
- Use straightforward names like filename, text, data, file, reader, and writer.
- For file I/O, prefer familiar java.io classes such as File, FileReader, FileWriter, BufferedReader, and BufferedWriter, or java.util.Scanner.
- Use try/catch with clear error messages. For buffered I/O, use try-with-resources; do not call close() inside it because it closes automatically.
- Print clear results with System.out.println.
- NEVER use System.out.printf in any shape, way or form. Also never use System.out.format, String.format, .formatted(), or format codes like %d, %s or %.2f. The ONLY way to print is System.out.println (or System.out.print), joining text and values with +. Check your code for printf before you give it to me.
- Keep comments short and explain steps in plain language only when useful.
- Match the requested task and avoid adding advanced concepts or unrelated code.

Please write Java code for this task:
[Describe what you want the program to do]
