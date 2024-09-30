<a name="readme-top"></a>

# Working with environment variables flutter By Codefarmer

> In this video, we will see how to setup and use environment variables with Flutter. We will not be using any package to handle this.

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# Resources

Working with environment variables flutter By Codefarmer

- <https://www.youtube.com/watch?v=VPUz58Bcdp4>

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

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

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# Credits :two_hearts:

- Thiloka Viraj [@thilokaviraj](https://github.com/thilokaviraj)

  > [thilokaviraj.github.io](https://thilokaviraj.github.io) | [twitter.com/thilokaviraj](https://twitter.com/thilokaviraj) | [youtube.com/@thilokaviraj](https://youtube.com/@thilokaviraj)

- [Contributors](/../../graphs/contributors)

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# Get Involved :sparkles:

Get in touch with the project developers and the community through our [GitHub Discussions](/../../discussions) forum. View [contributing.md](/contributing.md) for information.

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# Issues :fire:

Bug reports and feature requests can be submitted on the [Github Issues](/../../issues).

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# Code of Conduct :thumbsup:

This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Code of Conduct](/code_of_conduct.md).

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# License :balance_scale:

### This work is distributed under the [Do What The F\*ck You Want To Public License](https://choosealicense.com/licenses/wtfpl/) License. See [license](/license.md) for more information.

### Permissions

- :white_check_mark: Commercial use
- :white_check_mark: Distribution
- :white_check_mark: Modification
- :no_entry: ~~Patent use~~
- :white_check_mark: Private use

### Conditions

- :no_entry: ~~Disclose source~~
- :no_entry: ~~License and copyright notice~~
- :no_entry: ~~Network use is distribution~~
- :no_entry: ~~Same license~~
- :no_entry: ~~State changes~~

### Limitations

- :x: Liability
- :no_entry: ~~Trademark use~~
- :x: Warranty

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# Copyright :copyright: :heart:

- Copyright © 2024 Thiloka Viraj [@thilokaviraj](https://github.com/thilokaviraj).
- Copyright © 2024 [Contributors](/../../graphs/contributors).

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---
