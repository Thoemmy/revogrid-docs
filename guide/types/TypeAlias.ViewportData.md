[@revolist/revogrid](README.md) / ViewportData

# Type Alias: ViewportData

```ts
type ViewportData: {
  segmentSelectionStore: Observable<SelectionStoreState>;
  slot: SlotType;
  style: {};
 } & RevogrOverlaySelection & Pick<JSXBase.HTMLAttributes<HTMLRevogrOverlaySelectionElement>, "ref"> & Pick<JSXBase.HTMLAttributes<HTMLRevogrDataElement>, "ref"> & RevogrData;
```

## Type declaration

| Name | Type | Description | Defined in |
| ------ | ------ | ------ | ------ |
| `segmentSelectionStore` | [`Observable`](TypeAlias.Observable.md)\<[`SelectionStoreState`](TypeAlias.SelectionStoreState.md)\> | Selection connection | [src/types/viewport.interfaces.ts:51](https://github.com/revolist/revogrid/blob/db3bbd7b3dfb60c01decc2efa78ae175ced1baa0/src/types/viewport.interfaces.ts#L51) |
| `slot` | [`SlotType`](TypeAlias.SlotType.md) | Slot to put data | [src/types/viewport.interfaces.ts:54](https://github.com/revolist/revogrid/blob/db3bbd7b3dfb60c01decc2efa78ae175ced1baa0/src/types/viewport.interfaces.ts#L54) |
| `style` | \{\} | - | [src/types/viewport.interfaces.ts:55](https://github.com/revolist/revogrid/blob/db3bbd7b3dfb60c01decc2efa78ae175ced1baa0/src/types/viewport.interfaces.ts#L55) |

## Defined in

[src/types/viewport.interfaces.ts:49](https://github.com/revolist/revogrid/blob/db3bbd7b3dfb60c01decc2efa78ae175ced1baa0/src/types/viewport.interfaces.ts#L49)
