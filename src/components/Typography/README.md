## Typography

### Markup

```html
<m-typography>
    <m-typo-display :level="4">Display 4</m-typo-display>
    <m-typo-headline>Headline</m-typo-headline>
    <m-typo-title>Title</m-typo-title>
    <m-typo-subheading :level="1">Subheading 1</m-typo-subheading>
    <m-typo-body :level="2">Body 2</m-typo-body>
    <m-typo-caption>Caption</m-typo-caption>
    <m-typo-button>Button</m-typo-button>
</m-typography>
```

### Slots

| Slot | Prop dependencies | Description |
|------|-------------------|-------------|
| default | - | typography content |

## MBody

### Props

| Prop | Type | Default | Required | Description |
|------|------|---------|----------|-------------|
| level | Number | - | true | body level could be 1 or 2 |
| adjustMargin | Boolean | true | - | adjust margins to other elements |

### Slots

| Slot | Prop dependencies | Description |
|------|-------------------|-------------|
| default | - | content |

## MButton

### Props

| Prop | Type | Default | Required | Description |
|------|------|---------|----------|-------------|
| adjustMargin | Boolean | true | - | adjust margins to other elements |

### Slots

| Slot | Prop dependencies | Description |
|------|-------------------|-------------|
| default | - | content |

## MCaption

### Props

| Prop | Type | Default | Required | Description |
|------|------|---------|----------|-------------|
| adjustMargin | Boolean | true | - | adjust margins to other elements |

### Slots

| Slot | Prop dependencies | Description |
|------|-------------------|-------------|
| default | - | content |

## MDisplay

### Props

| Prop | Type | Default | Required | Description |
|------|------|---------|----------|-------------|
| level | Number | - | true | display level could be between 1 and 4 |
| adjustMargin | Boolean | true | - | adjust margins to other elements |

### Slots

| Slot | Prop dependencies | Description |
|------|-------------------|-------------|
| default | - | content |

## MHeadline

### Props

| Prop | Type | Default | Required | Description |
|------|------|---------|----------|-------------|
| adjustMargin | Boolean | true | - | adjust margins to other elements |

### Slots

| Slot | Prop dependencies | Description |
|------|-------------------|-------------|
| default | - | content |

## MSubheading

### Props

| Prop | Type | Default | Required | Description |
|------|------|---------|----------|-------------|
| level | Number | - | true | subheading level could be 1 or 2 |
| adjustMargin | Boolean | true | - | adjust margins to other elements |

### Slots

| Slot | Prop dependencies | Description |
|------|-------------------|-------------|
| default | - | content |

## MTitle

### Props

| Prop | Type | Default | Required | Description |
|------|------|---------|----------|-------------|
| adjustMargin | Boolean | true | - | adjust margins to other elements |

### Slots

| Slot | Prop dependencies | Description |
|------|-------------------|-------------|
| default | - | content |

### Reference

- https://github.com/material-components/material-components-web/tree/master/packages/mdc-toolbar
