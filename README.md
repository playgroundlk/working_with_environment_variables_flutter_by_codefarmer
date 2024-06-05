# Working with environment variables flutter By Codefarmer

> In this video, we will see how to setup and use environment variables with Flutter. We will not be using any package to handle this.

# Usage

- Load environment variables from file.

  ```
  flutter run --dart-define-from-file=lib/config/config.json
  ```

- Setup VSCode Debugger to autoload the env file. add `toolArgs` parameters `--dart-define-from-file` `PATH/TO/ENV/FILE` to launch.json file.

  ```
  {
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [
      {
        "name": "development",
        "request": "launch",
        "type": "dart",
        "toolArgs": [
          "--dart-define-from-file",
          "lib/env/development.env"
        ]
      },
      {
        "name": "production",
        "request": "launch",
        "type": "dart",
        "flutterMode": "release",
        "toolArgs": [
          "--dart-define-from-file",
          "lib/env/production.env"
        ]
      },
      {
        "name": "working_with_environment_variables_flutter (profile mode)",
        "request": "launch",
        "type": "dart",
        "flutterMode": "profile"
      },
      {
        "name": "working_with_environment_variables_flutter (release mode)",
        "request": "launch",
        "type": "dart",
        "flutterMode": "release"
      }
    ]
  }
  ```

# Resources

> Working with environment variables flutter By Codefarmer

- https://www.youtube.com/watch?v=VPUz58Bcdp4

# Author

> I am Programmer

- https://iamprogrammer.lk

# License

> This is free and unencumbered software released into the public domain.

- [Unlicense - Public Domain](https://opensource.org/license/unlicense)
