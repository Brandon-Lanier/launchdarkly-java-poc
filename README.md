
## Build instructions

This project uses [Gradle](https://gradle.org/). It requires that Java is already installed on your system (version 8 or higher). It will automatically use the latest release of the LaunchDarkly SDK with major version 6.

1. Create a .env file in the root directory. Request SDK key from team members and input SDK_KEY={thesdkkey} into the .env.

2. On the command line, run `./gradlew run` (or, on Windows, `gradlew run`).

You should see these messages:
`"Feature flag qr_code is <true/false> for Java-User"`
`"Feature flag background-color is <flag-variation> for Java-User"`

You can login to the LaunchDarkly app and turn the QR flag on and off for the "java-test-user" target.
You can also change which background-color is being served to this user by adding "java-test-user" to whichever color variation you choose.
