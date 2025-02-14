# im4java-examples

The example projects demonstrate ImageMagick and Java integration with IM4java and JMagick.

| Project Name | Description   |
|--------------|---------------|
| im4javademo  | Im4java Java Examples|
| im4javademo-kotin| IM4java Kotlin Examples|
| jmagickdemo| JMagick Java Examples|
 
There is a wired issue I found using IM4java in a Kotlin project, check [the original post](https://stackoverflow.com/questions/79435864/im4java-throws-exception-convert-im6-q16-no-decode-delegate-for-this-image-form) on StackOverflow.

## Prerequisites
All these projects used Gradle as a building tool and tested against Java 21 on Ubuntu 24.04. Due to both IM4Java and JMagicks depending on `ImageMagick`, before running the projects, you have to install `openjdk-21-jdk`, `imagemagick`, `libjmagick6-jni` packages.

```bash
sudo apt install openjdk-21-jdk imagemagick libjmagick-jni
```

# Build

1. Check out the source codes.
2. Add a test-purpose JPEG image to the project root folder, and rename it to `test.jpg`.
3. Open a terminal, switch to the project root folder, run `./gradlew clean :app:run`.

On Windows, you can install WSL/Ubuntu as the development environment, and use VSCode as the code editor.
* Enable Hyper-V virtual manager in the Windows system.
* Install `WSL` and `Ubuntu` from the Microsoft Store or `winget` command line.
* Start `Ubuntu` from the start menu and initialize the Ubuntu system. Follow the above guide to install the required packages in Ubuntu.
* Install VSCode with Remote Development extension pack.
* Open a terminal, such as PowerShell, connect WSL/Ubuntu via `code --remote wsl+Ubuntu /home/yourname/projects`.


