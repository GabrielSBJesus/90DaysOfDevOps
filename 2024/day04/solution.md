# Solution: Basic Linux Shell Scripting for DevOps Engineers

**Tasks:**

- Explain in your own words and with examples what Shell Scripting means for DevOps.

In our DevOps days we need to know how to write scripts in *ShellScript* for almost tasks. Is a wonderful tool to
tasks that need automate.

Examples:

Creating AMI images using packer
Configuration management tools

- What is `#!/bin/bash`? Can we write `#!/bin/sh` as well?

#!/bin/bash is called a "shebang" and is used at the beginning of a script to specify the interpreter that should be used to execute the script. In this case, it tells the system to use the Bash shell.

Features: Bash (/bin/bash) has many additional features compared to the original Bourne shell (/bin/sh), including improved syntax, arrays, and more advanced control structures.

Compatibility: Scripts written for Bash might not work correctly if run with sh if they use features specific to Bash.

Linking: On many systems, /bin/sh is a symlink to a compatible shell (like bash or dash), so behavior might vary depending on the system's configuration.
- Write a Shell Script that prints `I will complete #90DaysOfDevOps challenge`.

![image](https://github.com/user-attachments/assets/6ac12016-eaaf-4b06-89f3-7abd8f0e9f08)

- Write a Shell Script that takes user input, input from arguments, and prints the variables.

![Screenshot from 2024-10-02 20-25-02](https://github.com/user-attachments/assets/8b1b2fc8-4b4a-4c92-971e-2bea3f31df3b)

- Provide an example of an If-Else statement in Shell Scripting by comparing two numbers.

![Screenshot from 2024-10-02 20-56-47](https://github.com/user-attachments/assets/26fcd408-e5cb-4289-bb89-54d1415ad93d)
