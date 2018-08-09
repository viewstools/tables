# @viewstools/tables

Tables wrapper around
[react-virtualized](https://github.com/bvaughn/react-virtualized)
with an API closer to what Views would use internally.

We expose two components `Table` and `Column`. They only work in React DOM for
now. [Contribute here for React Native support](https://github.com/viewstools/morph/issues/132).

Use it like:
```
import { Table, Column } from '@viewstools/tables/dom'

const data = [{
  name: 'Mary',
  location: 'Somewhere',
}, {
  name: 'Bob',
  location: 'Wherever',
}]

<Table from={data}>
  <Column key="name" />
  <Column key="location" />
</Table>
```

License MIT.
(c) 2018 UXtemple Ltd.
