# Building the Products Application

I used this API: https://dummyjson.com/

1. Create main page components (`Dashboard`, `About`, `Products`, `Product`)
2. Define routes for them using `BrowserRouter`, `Routes`, and `Route`
3. Make a navigation bar with `NavLink`s
4. Create `ProductsContext` and `ProductsProvider`
5. Wrap the application in the Provider
6. Define state values in Provider with `useState`
7. Set the state data in Provider with `useEffect` and `fetch` (note the `utils` file with the `handleFetch` helper)
8. `Products` as a directory of product pages
   - Use context to get the fetched data
   - [Render a list](https://react.dev/learn/rendering-lists) of `Link`s to for each fetched product
9. `/products:id` ➡ `Product` to render a single product
   - Grab the dynamic segment of the URL (`id`) with `useParams()`
   - Get the current product from the context
   - Render the product's data!
