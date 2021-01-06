What is react?
  - React is a declarative efficient, and flexible JavaScript Library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called components

  React has a few different kinds of Components, React.Component subclasses,

  Example of React.Component

  class ShoppingList extends React.Component {
  render() {
    return (
      <div className="shopping-list">
        <h1>Shopping List for {this.props.name}</h1>
        <ul>
          <li>Instagram</li>
          <li>WhatsApp</li>
          <li>Oculus</li>
        </ul>
      </div>
    );
  }
}

// Example usage: <ShoppingList name="Mark" />

We use components to tell React what we want to see on the screenn. WHen our data changes, React will efficiently update and rerender our components.

Components take in parameters called props(properties), and returns a hierarchy of views to display via the render method.

Render retruns a descriptioon of what you want to see on the screen. React takes the description and displays the results. Render returns a React element, which is a lightweight description of what to render.