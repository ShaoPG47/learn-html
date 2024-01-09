## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
<br> The action attribute in the form tag will point out the url that the username and password 
should be sent to.
2. What is the purpose of the _method_ attribute in the _form_ tag?
<br>It append the data to the url.
3. What is the purpose of the _name_ attribute in the _input_ tag?
<br>The name attribute will be the key of this data, while the value is the input data,
so that the website will clearly know which user sent what.
4. What is the purpose of the _type_ attrbute in the _input_ tag?
<br>It specifies the type of input
5. What is the purpose of the _label_ tag?
<br>It will label "password" on the input password, so that the website knows
which input is the password.
6. What is the purpose of the _required_ attribute?
<br>The required attribute state which elements/inputs must be fill out before
the data or form is submitted.

