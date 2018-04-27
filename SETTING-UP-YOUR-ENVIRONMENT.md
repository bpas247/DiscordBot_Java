# Setting Up Your Environment

**NOTE** This page assumes you have already read the [Prerequisites](README.md#prerequisites) section.

## Setting up Gradle

Gradle is a quite simple tool to use, after it is set up properly. In order to check to see if it is properly set up, type into the command line:

    gradle

The result should be along the lines of:

    > Task :help

    Welcome to Gradle 4.5.1.

    To run a build, run gradle <task> ...

    To see a list of available tasks, run gradle tasks

    To see a list of command-line options, run gradle --help

    To see more detail about a task, run gradle help --task <task>

**Note** if an error occurs, make sure to add Gradle's file path to the `PATH` variable in your system's environment. If that still doesn't fix the problem, then verify that you installed Gradle correctly.

Once Gradle is set up, it's time to get a local copy of the repository to your system.

## Getting a local copy of the repository

[Fork](https://help.github.com/articles/fork-a-repo/) this repository.

Open the command line (or terminal in Linux) and find a safe place to put your local copy of the repository.

Clone the forked repository:

    git clone https://github.com/[YOUR_USERNAME_HERE]/DiscordBot_Java

## Building the environment

Open the command line (or terminal in Linux) and navigate to the repository's directory.

Type in the following command:

    gradle build

**Optional** If you are using IntelliJ, run the following command:

    gradle idea

**Note** You might need to import the project as a Gradle project when you open IntelliJ.
