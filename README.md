# ReactRants [![GitHub license](https://img.shields.io/badge/license-GLWTPL-blue.svg)](https://github.com/me-shaon/GLWTPL/blob/master/NSFW_LICENSE) [![Coverage Status](https://img.shields.io/badge/coverage-100%25-yellow.svg)]() [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]() [![first-timers-only Friendly](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](http://www.firsttimersonly.com/) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/SaadAAkash/Compiler-Linux-GIT-AWS-Essentials/graphs/commit-activity) [![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/) [![made-with-love](https://img.shields.io/badge/Made%20with-Love-1f425f.svg)](https://saadaakash.bitbucket.io/)
Rants & Rumblings on React. Codes of some boilerplate projects, concepts and others.

####  Components & States

 * Everything in React is a component,  and these usually take the form of JavaScript classes.
 * A componenet should return a ```render()``` which returns HTML code
 * A component can be created by extending upon the React-Component class.
 * Importing babel is required, as React uses JSX to write markup, to transform this JSX into plain JavaScript, so that the browser can understand it.
 * ```Hello``` is a component, ```ReactDOM.render()``` method is used connect our ```Hello``` component with the entry point for the app ```(<div id="root"></div>)``` below:
  
   ```
   class Hello extends React.Component {
        render() {
            return <h1>Hello world!</h1>;
        }
    }
    ReactDOM.render(
        <Hello />, 
        document.getElementById("root")
    );
   ```
 * 
 
