# npm-audit-to-report

A simple Go program that converts `audit.json` to an issue with Markdown

## Install

```bash
go install github.com/egorsmkv/npm-audit-to-report
```

## Usage

```
npm-audit-to-report [FLAGS]

  Flags:
       --version       Displays the program version string.
    -h --help          Displays help with available flag, subcommand, and positional value parameters.
    -i --audit-file    Path to the audit file (default: security-audit.json)
    -o --output-file   Path to the output file (default: security-audit.md)
```
