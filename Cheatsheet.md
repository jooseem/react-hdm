# React.js Cheatsheet für die Übung am 12.04

### State:
```javascript
var MyButton = React.createClass({
			
      getInitialState: function(){
      	return {
        	name: 'Peter'
        };
      },
			
      render: function(){
      	return <button>{this.state.name}</button>;
      }
});
```
#### state setzen:
```javascript
this.setState({ name:'Jon' });
```