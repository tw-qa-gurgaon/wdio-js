# Introduction

This a bare minimum framework setup of WebdriverIO for QA Recruitment Workshop

## Tests Covered:

* UI

## Framework/Languages used:

* Webdriverio
* JS

## Design Pattern used:
* Page Object Model _(POM)_

## Prerequisite:
* npm - 7.24.0
* node - 16.10.0

## Steps to Run:

1. Clone GIT repository in named directory.

   **_Run:_**
    ```
     > cd ~/workspace/
     > mkdir <wdio-js_directory_name>
     > cd <wdio-js_directory_name>
     > git clone https://github.com/tarunmaini16/wdio.git
    ```     
2. Install all dependencies -

   **_Run:_**
    ```
        > cd ~/workspace/<wdio-js_directory_name>/wdio
        > npm install
     ```       
   **Note**:This will install all dependencies project will be using for executing.


3. To run test -

   **_Run:_**
    ```
    > cd ~/workspace/<wdio-js_directory_name>/wdio
    > npx wdio run wdio.conf.js
    ```
    - This will run all tests under wdio directory
    
## Author

* Tarun Maini

## References

* https://webdriver.io/
