```json
"features": {
    "ghcr.io/devcontainers/features/aws-cli:1": {} /* Add AWS CLI */,

    "ghcr.io/devcontainers-contrib/features/scala-sdkman:2": {
      "version": "3.3.4", // "latest", "x.y.z"
      "jdkVersion": "17", // "latest", "8", "11", "17"
      "jdkDistro": "tem" // https://sdkman.io/jdks
    } /* Add Scala SDKMAN */,

    "ghcr.io/devcontainers-contrib/features/scalacli-sdkman:2": {
      "version": "latest", // "latest", "x.y.z"
      "jdkVersion": "17", // "latest", "8", "11", "17"
      "jdkDistro": "tem" // https://sdkman.io/jdks
    } /* Add Scala CLI SDKMAN */,

    "ghcr.io/devcontainers/features/git:1": {} /* Add Git */
  },
```
