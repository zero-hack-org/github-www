![Static Badge](https://img.shields.io/badge/Ballerina-2201.7.1-1ab3ab)
<br/>
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/zero-hack-org/svg-parser)
![GitHub repo size](https://img.shields.io/github/repo-size/zero-hack-org/svg-parser)
<br/>
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
<br/>
[![codecov](https://codecov.io/gh/zero-hack-org/module-zerohack-github/branch/main/graph/badge.svg?token=263B3XC36E)](https://codecov.io/gh/zero-hack-org/module-zerohack-github)
<br/>
![Twitter Follow](https://img.shields.io/twitter/follow/y_morimoto_dev?style=social)

## svg-parser

Ballerina Lang SVG Parser

### Usage

1. Generate Config.toml

   ```bash
   cp BaseConfig.toml Config.toml
   ```

2. Custom Config.toml
   | Argument name | Description |
   | ------------------ | ---------------------------------------------------- |
   | svg_parser.port | Custom port |
   | [zerohack.github](https://central.ballerina.io/zerohack/github).githubUsername | Your github username |
   | [zerohack.github](https://central.ballerina.io/zerohack/github).githubPersonalAccessToken | Your [github personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#about-personal-access-tokens) |

3. Start up application

   ```bash
   bal run
   ```

4. Demo Request

   ```bash
   curl -i http://localhost:8080
   ```

### Useful links

- Discuss code changes of the Ballerina project via [yuya-morimoto@zero-hack.jp](yuya-morimoto@zero-hack.jp).

### License

This project is licensed under the Apache-2.0 License, see the [LICENSE](./LICENSE) file for details