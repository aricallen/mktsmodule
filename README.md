# mktsmodule

Setup scaffolding for a node module with some base rules/settings I've found useful.
Also places the module name in important areas.

Files included:

├── .eslintignore
├── .eslintrc
├── .gitignore
├── .vscode
│   └── launch.json
├── LICENSE
├── README.md
├── jest.config.json
├── package.json
└── tsconfig.json

## Usage

```sh
yarn global add @aricallen/mktsmodule
cd <path/to/parent/dir>
mktsmodule --name=<module-name> [--scope=<scope>]
```