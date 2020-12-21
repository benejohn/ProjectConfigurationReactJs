# ProjectConfigurationReactJs

<p>I have used "yarn create react-app NameOfProject --template=typescript" to create the project</p>
<p>Deleted some files dont used as favicoin.."
  
<p> First step is generate editorconfig in VsCode</p>
<b><p> added the lines in .editconfig</p></b>
<p>
"trim_trailing_whitespace = true
  
insert_final_newline = true

end_of_line = true" </p>

<h3>Configure Eslint and Prettier in ReactJs</h3>
<ol>
  <li>yarn add eslint -D</li>
  <li>Delete "eslintConfig" from package.json</li>
  <li>yarn eslint --init</li>
  <li>To check syntax, find problems, and enforce code style </li>
  <li>JavaScript modules (import/export)</li>
  <li>React</li>
  <li>Does your project use TypeScript? <b>YES</b></li>
  <li>Browser</li>
  <li>Use a popular style guide</li>
  <li>AirBnb</li>
  <li>JSON</li>
  <li>Would you like to install them now with npm? <b>NO</b></li>
  <li> Copy all extensions and use yarn to install</li>
  <li> <b>Only a Example, put -D at the end:</b>  "yarn add eslint-plugin-react@^7.21.5 @typescript-eslint/eslint-plugin@latest eslint-config-airbnb@latest eslint-plugin-import@^2.22.1 eslint-plugin-jsx-a11y@^6.4.1 eslint-plugin-react-hooks@ ^4 @typescript-eslint/parser@latest -D"</li>
  <li> Create .eslintignore and add some rules in .eslint.json</li>
  <li> add eslint-import-resolver-typescript as "yarn add eslint-import-resolver-typescript -D"</li>
  <li> add Prettier use "yarn add prettier eslint-config-prettier eslint-plugin-prettier -D"</li>
  <li> after it configure .eslintrc.json</li>
<ol>
  
<h2>I have uploaded some files to use in others projects</h2>
  
 
