Your goal is to set up an NPM project which will lint and prettify the code in index.js.

You are being supplied the configuration files for EsLint and Prettier ./.prettierrc & ./.eslintrc. Run ls -a in terminal to see invisible files are there. You do not need to make any changes to them.

Configure the NPM project
Install the proper node modules.
prettier Note: you'll need to use Prettier version 2.5.1
eslint version - 8.8.0
eslint-config-prettier to turn off ESLint reult that conflict with Prettier(compatible version: 8.3.0)
eslint-plugin-prettier@4.0.0 which runs Prettier as an ESLint rule
Write scripts that run eslint and prettier.
Run the scripts to find the errors in index.js
Fix the errors and run the scripts again until the code is clean.