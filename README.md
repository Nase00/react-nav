## Getting started
```jsx
var React = require('react')
    , NavContainer = require('react-nav');

React.render(
    <NavContainer position={100}>
    	<a href="/"><i className="fa fa-home"></i>Home</a>
    	<a href="/"><i className="fa fa-home"></i>Services</a>
    </NavContainer>
    , document.getElementById('anchor')
);
```
Where position is the absolute value of pixels where the NavContainer will initially be rendered.