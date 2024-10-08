# Grouping (Stacked Columns)
[<Badge type="tip">Type: ColumnGrouping</Badge>](../types/TypeAlias.ColumnGrouping)


<!--@include: ../parts/column.group.md-->

Columns in RevoGrid can be defined as either regular columns or grouped columns (stacked columns). To create a stacked column, simply define it as a group. Check the interfaces for more information.

Here's an example demonstrating how to define both regular and grouped columns:

```typescript
const columns: ColumnGrouping[] = [
  { name: 'Name', prop: 'name' }, // Regular column

  // Stacked column group
  {
    name: 'Personal',
    children: [
      { name: 'Eyes', prop: 'eyeColor' }, // Regular column within the group
      { name: 'Company', prop: 'company' }, // Regular column within the group
    ]
  }
];
```