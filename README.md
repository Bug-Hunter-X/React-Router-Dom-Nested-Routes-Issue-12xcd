# React Router Nested Route Bug

This repository demonstrates a common issue with nested routes in React Router Dom v6 and a solution.

## Bug Description:

The nested route for the contact form does not render correctly. The parent route renders, but the child route does not.  The issue is related to how nested routes are defined and handled within the `Route` component. The improper use of nested routes leads to unexpected behavior and prevents the correct rendering of the nested component. 

## Solution:

The solution involves reviewing the route structure and ensuring the path definitions are accurate for both parent and child components, and that the nesting is correctly defined within the Route component.  A nested route should be correctly defined within the parent Route's element prop.