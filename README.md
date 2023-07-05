

# MyCLI - Node.js CLI Translator

MyCLI is a command-line interface (CLI) tool built with Node.js that allows you to translate a sentence from English to another language. This tool provides a simple and efficient way to perform translations without the need for manual lookups or online translation services.

## Installation

To install MyCLI, follow these steps:
* Clone the repository or download the source code:
```bash
git clone https://github.com/KPkm25/my-cli
```

* Navigate to the project directory:
```bash

cd my-cli
```
* Install the dependencies using npm:
```bash

npm install
```
* If you want to use MyCLI globally, you can install it as a global package:
```bash

npm install -g
```
    
## Usage

Once MyCLI is installed, you can use it by executing the following command in your terminal:

```bash

mycli -l <target-language> -s "<sentence>"
```
Replace ``` <target-language>``` with the desired language code and ```<sentence>``` with the sentence you want to translate.

**Example:**

```bash

mycli -l french -s "hello world"
```
This command will translate the sentence "hello world" to French.


## Deployment errors

During the deployment process of MyCLI, it is possible that users may encounter certain errors, particularly related to npm package dependencies. These errors could arise due to changes in the npm ecosystem, including deprecated features or outdated versions of the installed dependencies.

Verify the installed packages against the ones in the repository.
Some common version control errors are due to the ```figlet``` package and the ```google-translate-api```

## Screenshots

![Home](https://github.com/KPkm25/my-cli/blob/main/mycli_home.png?raw="true")

![Execution](https://github.com/KPkm25/my-cli/blob/main/mycli_exec.png?raw="true")
