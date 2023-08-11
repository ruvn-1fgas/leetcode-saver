## LeetCode Saver

LeetCode Saver is a tampermonkey script that helps you save your LeetCode solutions to your local machine.

Script saves task and description to a folder in the Downloads directory, with the following structure:

```
Downloads
└── LeetCode
    └── {task difficulty}
        ├── {task name}.md
        └── {task name}.{correct lang extension}
```

## Installation
To install the script, you need to install the [Tampermonkey](https://www.tampermonkey.net/) extension for your browser. Then, you can install the script by clicking [here](https://greasyfork.org/ru/scripts/472921-leetcode-solution-s-saver)

## Usage
Before using the LeetCode Saver, you need to configure your Tampermonkey settings. Specifically, you need to add the following file extensions to the Whitelisted File Extensions list in the Downloads Beta section. This will allow the script to download files with these extensions to your local machine.

```
/\.(cpp|java|py|sql|c|cs|js|rb|sh|swift|go|py|scala|kt|sql|sql|html|py|rs|php|ts|rkt|erl|ex|dart|py|js|js|md)/
```

To use the script, you need to go to the LeetCode task page and click the "Download" button. The script will then save the task and description to your Downloads directory.

## License
LeetCode Saver is released under the [MIT License](LICENSE).