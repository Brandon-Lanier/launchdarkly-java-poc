
## Build instructions 

This project uses [Gradle](https://gradle.org/). It requires that Java is already installed on your system (version 8 or higher). It will automatically use the latest release of the LaunchDarkly SDK with major version 6.

1. Create a .env file in the root directory. Request SDK key from team members and input SDK_KEY={thesdkkey} into the .env.

2. On the command line, run `./gradlew run` (or, on Windows, `gradlew run`).

You should see the message `"Feature flag qr_code is <true/false> for this context"`.

You can login to the LaunchDarkly app and turn the flag on and off for the "java-test-user" target.
