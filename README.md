# Dropdown Component

A searchable dropdown component with support for single/multiple selection, portals, and customizable rendering.

## Props
- `options`: Array of objects with `value` and `label` properties.
- `multiple`: Boolean to enable multiple selection.
- `searchable`: Boolean to enable search functionality.
- `portal`: Boolean to render the dropdown in a portal.
- `renderOption`: Function to customize option rendering.
- `toggleFeatures`: Object to toggle features like search.

## Usage
```jsx
<Dropdown
  options={[{ value: "1", label: "Option 1" }]}
  multiple={false}
  searchable={true}
  portal={true}
/>
