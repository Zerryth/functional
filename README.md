## Dotnet
List of Pipelines, what yaml files they call, and test files they run.

### FunctionalTests
* Botbuilder-DotNet-Facebook-Functional-Tests-yaml
    * `botbuilder-dotnet-ci-facebook-test.yml` => `ci-build-steps.yml`
        * `FacebookChatTests.cs`
* BotBuilder-DotNet-Functional-Tests-Linux-yaml
    * `botbuilder-dotnet-functional-test-linux.yml` => `ci-build-steps.yml`
        * TestCategory: **FunctionalTest**  (that are not Adaptive)
            * `DirectLineClientTests.cs`
            * `DirectLineSpeechTests.cs`
            * `FacebookChatTests.cs`
            * `GetTokenRefreshTests.cs`
            * `JwtTokenExtractorTests.cs`
            