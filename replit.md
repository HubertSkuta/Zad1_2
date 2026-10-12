# Imported Java/Maven project

## Run on Replit

This project is a Java console application. Its entry point is
`src/main/java/Main.java`, which prints a greeting and then exits.

- Run the configured `Start application` workflow to execute it.
- Build and test manually with `mvn test`.
- Run the entry point directly with `javac -d . src/main/java/Main.java && java -cp . Main`.

The Java toolchain and Maven are provided by the `java-graalvm22.3` Replit
module. No secrets or external services are required.

## Expected result

Press **Run** to compile and execute the program. The Console displays
`Hello world JPWP2!`, then the workflow finishes normally. This is a console
application, so there is no web preview or listening port.

`mvn test` builds successfully, but there are currently no active tests.
