Maven based pipeline which:

* creates a new version then builds and deploys the project into the maven repository
* runs an integration test in the **Test** environment
* stages the new version into the **Stage** environment
