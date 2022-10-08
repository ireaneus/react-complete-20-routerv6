# react-complete-20-routerv6

## react-router-dom v6.4.1

- Navigate, Routes, Outlet
- <Outlet /> is used to display the nested route component

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
