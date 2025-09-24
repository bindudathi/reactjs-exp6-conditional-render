Conditional Rendering Example
This project demonstrates conditional rendering in React with Vite.
A toggle button is used to show or hide a component dynamically using React state (useState).

Screenshot
Below is a screenshot of the app running on http://localhost:5173/:

Conditional Rendering Screenshot

Explanation
When you click Show Component, a new component appears.
When you click Hide Component, the component disappears.
This is achieved using conditional rendering:
{isVisible && <MyComponent />}
# reactjs-exp6-conditional-render
