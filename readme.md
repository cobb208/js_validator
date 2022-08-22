# JavaScript Form Validator
[Author: cobb208@goodeveningtech](https://goodeveningtech.com)

## Basics

The TypeScript file *app.ts* includes the logic to run the form validator.

Any site you have a form on the script will autoload itself and latch onto the form. It will provide validation logic for:

- Minimum Input Length on Text
- Maximum Input Length on Text
- Email Validation (Regex)
- Will not allow form to submit without

It uses the HTML attributes: "min", "max", "required" to get the logic. If you do not set them it will not check them. 

This script will latch onto any form on the HTML page. It will not interact with hidden form fields.

## Html & CSS File
The HTML and CSS Files are there for demonstration purposes.

## Create the JavaScript File
This project uses snowpack to take the TypeScript and minify it into JavaScript.

```
npm install
npm run build
```

The compiled JavaScript file will be in the build folder. Have fun!


