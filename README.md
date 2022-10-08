# react-complete-20-routerv6

## react-router-dom v6.4.1

- Navigate, Routes, Outlet, useNavigate
- <Outlet /> is used to placeholder the nested route component
- useNavigate replaces useHistory (to, replace)

## App.jsx

```js
<Route path="/welcome" element={<Welcome />}>
  <Route path="new-user" element={<p>Welcome, new user!</p>}></Route>
</Route>
```

## Welcome.jsx

```js
  <Route path="/welcome" element={<Welcome />}>
    <Route path="new-user" element={<p>Welcome, new user!</p>}></Route>
  </Route>
```

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/vitejs-vite-qfreld)
