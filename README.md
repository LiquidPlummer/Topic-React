# React Week
Kyle Plummer - Substitute Trainer  
kyle.plummer@revature.com


## Agenda
### 12/15/21
#### Topics:
 - [JSX/TSX](./fundementals/react-jsx-tsx.md)
 - [Props & State](./fundementals/react-props-state.md)
 - [Hooks](./fundementals/react-hooks.md)
 - [Routing](./fundementals/react-routing.md)
 - [Events](./fundementals/react-events.md)
 - [Containment and Specialization](./fundementals/react-containment-specialization.md)
   - [Higher Order Components](./fundementals/react-HCO.md)

#### Lab:
Build a Celsius-Fahrenheit converter. Create a new react app and add several components. You will need one component for Fahrenheit and another for Celsius. These will need to be nested within a parent component. Each component requires a text field to display the current tempreture and an input field to input a new tempreture. Whenever a tempreture is inputted in either component, it should send that information to the parent, perform a conversion from one scale to the other, and update both components to display the correct tempretures.
 - You will want to "lift state", that is, pass a callback function down to the children components. Those functions should modify the state of the parent.
 - You can use the default "App" component as the parent


#### Project Time:
If you finish the lab, or decide your time is better spent on your current project, feel free to work on P1 instead.
  
---

### 12/16/21:
 - [Flux design Pattern](./redux/react-flux.md)
 - [Destructuring - JS Syntax](./misc/advanced-js.md#destruction-assignment)
 - [Redux](./redux/redux.md)
   - Actions
   - Reducers
   - Store
   
#### Lab:
Refactor the Celsius-Fahrenheit converter to use the flux design pattern and a redux store for transferring the data between components. The parent component which contains the Celsius and Fahrenheit views should be the view-controller in our flux design.

#### Project Time:
If you finish the lab, or decide your time is better spent on your current project, feel free to work on P1 instead.

---

### 12/17:21:
 - AJAX
 - Axios
 - Fetch
 - Jest
