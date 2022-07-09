# Material React Table

<a href="https://npmjs.com/package/material-svelte-table" target="_blank_">
  <img alt="" src="https://badgen.net/npm/v/material-svelte-table" />
</a>
<a href="https://npmjs.com/package/material-svelte-table" target="_blank_">
  <img alt="" src="https://img.shields.io/npm/dm/material-svelte-table.svg" />
</a>
<a href="https://bundlephobia.com/result?p=material-svelte-table" target="_blank_">
  <img alt="" src="https://badgen.net/bundlephobia/minzip/material-svelte-table@latest" />
</a>
<a href="https://github.com/KevinVandy/material-svelte-table" target="_blank_">
  <img alt="" src="https://img.shields.io/github/stars/KevinVandy/material-svelte-table.svg?style=social&label=Star" />
</a>

---

## About

> This project is still in alpha

- A fully featured Material UI V5 implementation of Tanstack Svelte Table V8
- Written from the ground up in TypeScript
- All internal Svelte Material UI components are easily customizable

Join the [Discord](https://discord.gg/5wqyRx6fnm) server to join in on the development discussion or ask questions

<!-- View the [Docs Site](https://www.material-svelte-table.com/) -->

<!-- See all [Props and Options](https://www.material-svelte-table.com/docs/api) -->

---

<!-- ## Quick Examples

 - [Basic Table](https://www.material-svelte-table.com/docs/examples/basic/) (See Default Features)
 - [Minimal Table](https://www.material-svelte-table.com/docs/examples/minimal/) (Turn off Features)
 - [Advanced Table](https://www.material-svelte-table.com/docs/examples/advanced/) (See some of the Advanced Features)
 - [Remote Data](https://www.material-svelte-table.com/docs/examples/remote/) (Server-side Pagination, Sorting, and Filtering)
 - [React Query](https://www.material-svelte-table.com/docs/examples/react-query/) (Server-side Pagination, Sorting, and Filtering)
 - [Virtualized Rows](https://www.material-svelte-table.com/docs/examples/virtualized/) (20,000 rows at once!)

View additional [storybook examples](https://www.material-svelte-table.dev/) -->

---

## Features (All Features work and are MVP, but are still being polished)

_All features can easily be enabled/disabled_

- [] < 35kb gzipped - [Bundlephobia](https://bundlephobia.com/package/material-svelte-table)
- [] Advanced TypeScript Generics Support (TypeScript Optional)
- [] Click To Copy Cell Values
- [] Column Actions
- [] Column Grouping (Group By and Aggregates)
- [] Column Hiding
- [] Column Ordering via Drag'n'Drop
- [] Column Pinning
- [] Column Resizing (work in progress)
- [] Customize Icons
- [] Customize Styling of internal Mui Components
- [] Data Editing (3 different editing modes)
- [] Density Toggle
- [] Detail Panels
- [] Filtering and multiple built-in filter modes
- [] Full Screen mode
- [] Global Filtering (Search across all columns, rank by best match)
- [] Header Groups & Footers
- [] Localization (i18n) support
- [] Manage your own state
- [] Pagination (supports client-side and server-side)
- [] Remote/Server-side sorting and filtering supported
- [] Row Actions
- [] Row Numbers
- [] Row Selection (checkboxes)
- [] SSR compatible
- [] Sorting
- [] Theming (Respects your Material UI Theme)
- [] Toolbars (Add your own action buttons)
- [] Tree Data / Expanding Sub-rows
- [] Virtualization (svete-virtual)

---

## Getting Started

### Installation

1. Install Peer Dependencies (Material UI V5)

```bash
TODO
```

2. Install material-svelte-table

```bash
npm install material-svelte-table
```

> _`@tanstack/svelte-table`, `@tanstack/svelte-virtual`, and `@tanstack/match-sorter-utils`_ are internal dependencies, so you don't need to install them yourself.
<!-- 
---

### Usage

> Read the full usage docs [here](https://www.material-svelte-table.com/docs/usage/)

```jsx
import React, { useMemo } from 'react';
import MaterialReactTable from 'material-svelte-table';

export default function App() {
  const columns = useMemo(
    () => [
      {
        accessorKey: 'name', //simple recommended way to define a column
        header: 'Name',
        muiTableHeadCellProps: { sx: { color: 'green' } }, //custom props
      },
      {
        accessorFn: (row) => row.age, //alternate way
        id: 'age', //id required if you use accessorFn instead of accessorKey
        header: 'Age',
        Header: <i style={{ color: 'red' }}>Age</i>, //optional custom markup
      },
    ],
    [],
  );

  //simple data example
  //Check out https://www.material-svelte-table.com/docs/examples/remote for a more realistic example
  const data = useMemo(
    () => [
      {
        name: 'John',
        age: 30,
      },
      {
        name: 'Sara',
        age: 25,
      },
    ],
    [],
  );

  return (
    <MaterialReactTable 
      columns={columns} 
      data={data} 
      enableColumnOrdering //enable some features
      enableRowSelection 
      enableStickyHeader
   />
   );
}
```

_Open in [Code Sandbox](https://codesandbox.io/s/simple-material-svelte-table-example-t5c3ji)_

--- -->

## Contributors

<a href="https://github.com/kevinvandy/material-svelte-table/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=kevinvandy/material-svelte-table" />
</a>

PRs are Welcome, but please discuss in [GitHub Discussions](https://github.com/KevinVandy/material-svelte-table/discussions) or the [Discord Server](https://discord.gg/5wqyRx6fnm) first!

