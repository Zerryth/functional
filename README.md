# Functional Tests

## Dotnet
List of Pipelines, what yaml files they call, and test files they run.

[Dotnet Functional Test Pipelines in Azure DevOps](https://fuselabs.visualstudio.com/SDK_v4/_build?view=folders&treeState=XERvdE5ldCRcRG90TmV0XEZ1bmN0aW9uYWxUZXN0cw%3D%3D)

* Botbuilder-DotNet-Facebook-Functional-Tests-yaml
    * `botbuilder-dotnet-ci-facebook-test.yml`
        * `FacebookChatTests.cs`
* BotBuilder-DotNet-Functional-Tests-Windows-yaml
    * `botbuilder-dotnet-functional-test-windows.yml`
        * TestCategory: **FunctionalTest**
            * `DirectLineClientTests.cs`
            * `DirectLineSpeechTests.cs`
            * `FacebookChatTests.cs`
            * `GetTokenRefreshTests.cs`
            * `JwtTokenExtractorTests.cs`
* BotBuilder-DotNet-Functional-Tests-Linux-yaml
    * `botbuilder-dotnet-functional-test-linux.yml`
        * Test: same tests as we run in windows (see BotBuilder-DotNet-Functional-Tests-Windows-yaml pipeline)
* BotBuilder-Dotnet-Slack-Functional-Tests-yaml
    * `botbuilder-dotnet-ci-slack-test.yml`
        * `SlackClientTest.cs`

*Note*: All the test yamls call `ci-build-steps.yml`
