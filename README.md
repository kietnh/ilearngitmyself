<!-- banner: can be a image or a large font-->
<h1 align="center" style="font-weight: bold; margin-top: 20px; margin-bottom: 20px;">ilearngitmyself</h1>
  
<!-- blurb: shortest possible summary (one line max) -->
<h3 align="center" style="font-weight: bold; margin-top: 20px; margin-bottom: 20px;">Brief description of ilearngitmyself.</h3>
  
<!-- badges: meaningful meta information (one line max), do NOT include anything immediately visible -->
<p align="center">
    <a href="#changelog"><img src="https://img.shields.io/github/release-pre/nqtronix/git-template.svg" alt="release: NA"></a>
    <a href="https://github.com"><img src="https://img.shields.io/badge/platform-github.com-blue.svg" alt="platform: github.com"></a>
    <a href="#status"><img src="https://img.shields.io/badge/status-maintained-green.svg" alt="status: maintained"></a>
    <a href="https://github.com/nqtronix/git-template/issues"><img src="https://img.shields.io/github/issues/nqtronix/git-template.svg" alt="issues: NA"></a>
    <a href="#license"><img src="https://img.shields.io/github/license/nqtronix/git-template.svg" alt="license: NA"></a>
</p>
  
<!-- quick links: local links (one line max) -->
<!-- Link to the (most important) h2 chapters, but do NOT link to anything visible without scrolling -->
<p align="center">
  <a href="#getting-started">Getting Started</a> •
  <a href="#documentation">Documentation</a> • 
  <a href="#support">Need Help?</a> •
  <a href="#about">About</a> •
  <a href="#license">License</a>
</p>
  
<!-- separate h2 chapters with white space: <br> -->
<br>
  
## Introduction
Generally I'd suggest to split the introduction into **two short paragraphs**:
  
1. Why does your project exist? What was the problem, that had to be addressed?
2. How does your project address that problem? What does it do in a nutshell?
  
The second paragraph should ideally start with the **PROJECT-NAME** in bold, followed by a verb describing what it does. Limit yourself to about 5 lines per paragraph.
 
<br>
  
## Key Features
 - **best of git:** embraces common design practices used in dozens of repositories
 - **skim-able:** most relevant info is visible at first glance
 - **pre-formatted**: the design is ready-to-use, just fill in your details
 - **self documenting:** instead of placeholders, this file contains details about itself
  
<br>
  
## Usage
Show what the module looks like in action, preferably with code snippets:
 
```sh
$ sudo echo "HELLO WORD"
```
This is post-code descriptive text.
 
<br>
  
## Getting Started
This section is written especially for everyone who is not familiar with the used tools. If you run into problems, please [ask for clarification](#get-help).<br>
 
### **Structure**
 
```
project root
├── docs/
│   ├── guide
│   │   ├── 01.Introduction.md
│   │   │
│   │   ...
├── functions/
│   ├── function_name/
│   │   ├── service.py
│   │   │   │
│   │   │   ...
│   │   ...
├── scripts/
│
├── source
│   │
│   ...
└── templates/
    │
    ├── aws-vpc.template
    │
    ├── bastion.template
    │
    ├── kinesis.template
    │
    ├── producer.template
    │
    ├── real-time-analytics-spark-streaming.template
    │
    ├── real-time-analytics-spark-streaming-default.template
    │
    └── san-dataloop-analytics-spark-streaming.yaml
```
<br>
 
### **Prerequisites**
 
- [Node.js](https://nodejs.org/en) (>= 8.9)
 
- [npm](https://www.npmjs.com/get-npm) version 3+ (or [yarn](https://yarnpkg.com/lang/en/docs/install/#mac-stable) version 1.16+) and [Git](https://git-scm.com/)
  ```sh
  npm install npm@latest -g
  ```
 
- JDK (>= 1.7)
  ```
  java install jdk
  ```
 
### **Installation**
 
1. Download **XYZ**
    ```sh
    $ curl xyz
    ```
 
2. Install **XYZ**
    ```sh
    $ install xyz
    ```
 
3. Run **XYZ**
    ```sh
    $ exec xyz
    ```
 
4. Extra steps
    ```sh
    $ clean-up xyz
    ```
 
<br>
  
## Documentation
 
### **API**
 
This section provides documentation on how each function in **PROJECT-NAME** works.
 
<br>
 
### **Configuration**
 
Any of API or software configurations hereabouts goes here.
 
<br>
 
### **Performance and testing**
 
Any of testing activities and reports goes here.
 
<br>
 
## Support
  
### **Get Help**
  
**You have a question or problem wasn't solved?** No worries! Just open up a new issue in the [GitHub issue tracker][git-issues]. Please provide all information to reproduce your problem. If you don't have a GitHub account, you can [contact](#contact) me directly.
  
<br>
  
### Contribute
  
**Spotted an error?** [Open an issue][git-issues] or submit a pull request.
  
We use [**Conventional Commits 1.0.0**][conventionalcommits.org]. The list below show how the commit message should structured:
```
fix:  fix patches a bug in codebase, correlates with PATCH
feat: introduce new feature to codebase, correlates with MINOR
feat(lang): add french language
refactor: drop support for Node 6
refactor!: BREAKING CHANGE introduce a breaking API change, correlates with MAJOR
docs: correct spelling of CHANGELOG
```
  
<br>
  
## About
  
### **Known Issues**
  
 - none (that are reported)
   
<br>
   
### **Planned Features**
  
 - Add a CONTRIBUTING.md file
   
<br>
  
### **Changelog**
This project uses [**Semantic Versioning 2.0.0**][semver.org]: `MAJOR.MINOR.PATCH.BUILD`. The list below is a summary about all significant improvements:
 
 - **0.1.0**
   - initial release
 - **0.1.1 (latest)**
   - latest release
  
<br>
  
### **Contact**
  
If you haven't done so already, please check out [Get Help](#get-help) for the fastest possible help on your issue. Alternatively you can get in touch with me by:
- Email: kiet@kietnh.com
- LinkedIn: http://linkedin.com/in/kiet
- Where I earn my $$$: https://www.upwork.com/fl/kietnh
  
<br>
 
## License
This project is proudly licensed under the [MIT license][git-license].
  
<br>
  
<!-- LINKS -->
<!-- in-line references: websites -->
[choosealicense.com]:https://choosealicense.com
[shields.io]:https://shields.io
[hackaday.io]:https://hackaday.io
[semver.org]:https://semver.org
[conventionalcommits.org]:https://conventionalcommits.org
[backToTopButton]:http://randojs.com/images/backToTopButton.png
   
<!-- in-line references to github -->
  
[git-profile]:https://github.com/nqtronix
[git-download]:https://github.com/nqtronix/git-template/archive/master.zip
[git-issues]:https://github.com/nqtronix/git-template/issues
[git-readme]:README.md
[git-license]:LICENSE.md
[git-contribute]:CONTRIBUTING.md
[git-badges]:badges.md
  
[git-repo-unittrace]:https://github.com/nqtronix/unittrace
[git-repo-fifofast]:https://github.com/nqtronix/fifofast
[git-repo-ahk-utf8-anywhere]:https://github.com/nqtronix/ahk-utf8-anywhere
