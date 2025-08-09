# config-cache-compatibility

First, clone my branch of Quarkus fork:
```bash
git clone -b all-tasks-cc-compatible --single-branch git@github.com:reaver585/quarkus.git
```

In settings.gradle, replace the `[PATH_TO_WHERE_YOU_CLONED_MY_BRANCH]` with the path to the cloned repository.

Then, try running for example:
```bash
./gradlew :quarkusDev --info --configuration-cache-problems=fail --configuration-cache
```