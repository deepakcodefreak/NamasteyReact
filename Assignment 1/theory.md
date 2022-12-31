
1. Why React is called as React ? 

    React was designed to allow developers to react to the state/data changes in application and update the UI accoridingly in declarative and effective manner.


2. What is the difference between React and ReactDOM ? 

    React package holds the react source for components, state, props all the code that is react.
    Whereas ReactDOM as the name suggests, it is the glue between react and DOM. It helps to render react apllication on browser DOM. The reason both where     seperated is - react is not limited to only broswer. We also have react native, React 3d and much more might be coming come in future. So it does to       makes any sense to ship DOM related code when you are on mobile app and not to ship mobile app realted code when you are on broswer. Therefore both         were seperated out.

3. What is difference between react.development.js and react.production.js files via CDN?

    'react.development.js' is the complete code as it it written and hence it is bigger in size whereas 'react.production.js' is the minified version of react because it is supposed to be used on production.
