# React - Key things to remember

## Naming conventions
- Use .jsx extension for React components.
- **Entry point** for app is /app/index.jsx file.
- Root component name app is picked up from folder containing index.jsx file.
- PascalCase for component file names. Like GitHub.jsx component.
- Use PascalCase for referencing imported React components.
- Use camelCase for variable names representing instances of React compo-nents.
- **Entry point** for styles is /app/style.css file which imports the partials.

## Constructor and binding
- Constructors are a feature of ES6 classes. Constructor methods are called once per instance of a component.
- First statement in a construction is super(props) which passes the props within the inheritance tree.
- Use constructor to bind methods. This is better for performance as it is bound once and also when using  shouldComponentUpdate() method for shallow comparison in the child components.
- Use constructor to declare propTypes and set defaultProps.
- Setting default state can be done within the constructor.
