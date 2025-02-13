# im4java-examples

The example projects is to demonstrate the issues when using IM4Java/ImageMagick in Java/Kotlin projects.

Check [the original question](https://stackoverflow.com/questions/79435864/im4java-throws-exception-convert-im6-q16-no-decode-delegate-for-this-image-form) I posted on Stackoverflow.

To reproduce the issues, follow these steps.

1. Ensure the build environment is Ubuntu 24.04. 
2. Install ImageMagick via `sudo apt install imagemagick`.
3. Run the project folders via `./gradlew :app:run`.

On Windows, you can install WSL/Ubuntu as the development environment, and use VSCode as development tools, and connect WSL/Ubuntu via `code --remote wsl+Ubuntu /hantsy/yourname/projects`.


