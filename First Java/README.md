## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

## Common Java and Git Commands

This section lists some common Java and Git commands that can be helpful for backend and full-stack development.

### Java Commands

*   `javac <source-file.java>`: Compiles a Java source file.
    *   Example: `javac HelloWorld.java`
*   `javac -d <output-directory> <source-file.java>`: Compiles a Java source file and places the compiled `.class` file in the specified directory.
    *   Example: `javac -d bin src/HelloWorld.java`
*   `java <classname>`: Runs a compiled Java class (assuming it's in the current directory or classpath).
    *   Example: `java HelloWorld`
*   `java -cp <path-to-classes> <classname>`: Runs a compiled Java class, specifying the classpath.
    *   Example: `java -cp bin HelloWorld`
*   `java -jar <jar-file.jar>`: Runs a packaged Java application.
    *   Example: `java -jar myapplication.jar`

### Git Commands

*   `git clone <repository-url>`: Copies a remote repository to your local machine.
*   `git status`: Shows the status of changes as untracked, modified, or staged.
*   `git add <file>`: Adds a file to the staging area.
*   `git add .`: Adds all new and modified files to the staging area.
*   `git commit -m "<commit-message>"`: Records the staged changes with a descriptive message.
*   `git pull`: Fetches changes from the remote repository and merges them into your current branch.
*   `git push`: Uploads local branch commits to the remote repository.
*   `git branch`: Lists all local branches.
*   `git checkout <branch-name>`: Switches to the specified branch.
*   `git merge <branch-name>`: Merges the specified branch into the current branch.
*   `git log`: Shows the commit history.
