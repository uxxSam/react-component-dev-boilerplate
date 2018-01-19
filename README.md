# react-component-dev-boilerplate
Convenient boilerplate for developing React component (not the complete app!)

How to use:
1. Develop your component in the react-component-dev folder. 
  a. cd react-component-dev
  b. npm i
     npm run build
     npm link
2. Test and use your component using the react-component-project-test folder.
  a. cd react-component-project-test
  b. npm install
     npm link react-fancy-component
     (or whatever your component is named)
3. `npm start` in both folder to start developing, webpack will automatically update when the component is changed.
4. Happy hacking
