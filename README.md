# React-Redux Boilerplate
 Base React-Redux Boilerplate template
# Hooks, Lint and Prettify 
 This template comes with airbnb eslint rules, plus couple of my preferred standards. It also has a pre-commit hook setup that prettifies code before submission and will not let you commit with out fixes lint issues ( to bypass ``--no-verify``)

# Redux 
This has redux logger and thunk setup and a sample action and reducer

# Renaming files/folders
If you'd like to rename the folder structure, which I imagine you would since boilerplate is a terrible name for a main folder, replace the words boilerplate, with the new folder name:
1. In the `client\package.json` file change the lint script
      ```"lint": "eslint [folder name here]",```
2. Under `lint-staged` change  ```eslint [folder name]/src/ --fix"```
3. In the `client\webpack.config.js` change `MAIN_DIR_FOLDER` from `boilerplate` to the folder you want

#Server 
This has the ability to be setup with a node.js server, if you're looking for that please see other template
