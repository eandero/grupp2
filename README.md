grupp2

# HTML guidelines
* lowercase 
* proper indentation:
  ```html
  <!DOCTYPE html>
    <head>
      <title> Test </title>
    </head>
    <body>
      <h1> </h1> 
    <body>
    <footer>
    </footer>
  </html>
  ```
* descriptive commments in english:
  ```html
  <!-- example --> 
    code
  <!-- /example -->
  ```
 * semantic!
 * descriptive classes and IDs (don't use ID on multiple tags, is unique)
  
  # SASS guidelines: 
  * Watch one file:
    ```css
    sass --watch input.scss output.css 
    ```
  * Watch files: 
    ```css
    sass --watch public/stylesheets/sass:public/stylesheets. 
     ```
     That will monitor all .scss files in public/stylesheets/sass and write them out as .css to         public/stylesheets/
  * lowercase & camelcase
  * use different .scss files for different parts of the website:
    *navbar.scss
    *footer.scss
  * nesting indentation: 
    ```css
    .ul {
          .li {
              }
        }
     ```
  * descriptive commments in english:
    ```css
    /* comment goes here */
    ```
  * descriptive variable names
    ```sass
    $varName
    ```
  - whitespace!
  
  # JS guidelines: 
  * descriptive variable names
    ```javascript
    var variableName = ""
    ```
  * descriptive commments in english:
    ```javascript
    // single line comment
    /* multiple line comment */
    ```
  * proper intedention


