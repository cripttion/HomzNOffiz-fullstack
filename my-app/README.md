ProductList Component
This is a React functional component that displays a list of products. It imports the necessary Bootstrap components like Container, Row, Col, Form, and ListGroup to create a responsive layout.

The component uses the useState hook to manage two filters for the products: categoryFilter and priceFilter. When the user selects a category or price range from the dropdown menus, the corresponding state is updated with the selected value.

The filteredProducts array is created by filtering the products array based on the selected filters. If a category or price range is selected, only the products that match the selected filter are displayed. Otherwise, all products are displayed.

The filtered products are displayed in a ListGroup component. Each product is displayed in a Col component with a width of 3, which means that there are four products displayed in each row. The product image, name, description, and price are displayed inside a ListGroup.Item component.

The component also applies some custom styles to the product image and the ListGroup.Item component to ensure that they are displayed correctly. The product image is given a fixed height of 200 pixels, while the ListGroup.Item component has a fixed height of 400 pixels and a border radius of 10 pixels.

Overall, this component provides a simple and user-friendly way to filter and display a list of products.