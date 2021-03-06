# Template Extension Specification

- **Title:** Template
- **Identifier:** <https://stac-extensions.github.io/template/v1.0.0/schema.json>
- **Field Name Prefix:** template
- **Scope:** Item, Collection
- **Extension [Maturity Classification](https://github.com/radiantearth/stac-spec/tree/master/extensions/README.md#extension-maturity):** Proposal
- **Owner**: @your-gh-handles @person2

This is the place to add a short introduction.

- Examples:
  - [Item example](examples/item.json): Shows the basic usage of the extension in a STAC Item
  - [Collection example](examples/collection.json): Shows the basic usage of the extension in a STAC Collection
- [JSON Schema](json-schema/schema.json)

## Item Properties and Collection Fields

| Field Name  | Type                      | Description |
| ----------- | ------------------------- | ----------- |
| new_field   | [XYZ Object](#xyz-object) | **REQUIRED**. Describe the required field... |
| another_one | \[number]                 | Describe the field... |

### Additional Field Information

#### new_field

This is a much more detailed description of the field `new_field`...

### XYZ Object

This is the introduction for the purpose and the content of the XYZ Object...

| Field Name  | Type   | Description |
| ----------- | ------ | ----------- |
| x           | number | **REQUIRED**. Describe the required field... |
| y           | number | **REQUIRED**. Describe the required field... |
| z           | number | **REQUIRED**. Describe the required field... |

## Relation types

The following types should be used as applicable `rel` types in the
[Link Object](https://github.com/radiantearth/stac-spec/tree/master/item-spec/item-spec.md#link-object).

| Type                | Description |
| ------------------- | ----------- |
| fancy-rel-type      | This link points to a fancy resource. |
