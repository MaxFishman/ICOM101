# Flexbox

Flexbox is a layout module in CSS that makes it easy to create flexible and responsive designs. It allows elements within a container to be aligned in a row or a column, and to be distributed evenly within the container.

## Example

Here is an example of how to use Flexbox to align elements horizontally:

```css
.container {
  display: flex;
  justify-content: center;
}

.element {
  flex: 1;
}
```

In this example:

- The container is set to `display: flex` to activate Flexbox.
- The `justify-content` property is set to `center` to align the elements within the container horizontally.
- The `flex` property on the elements is set to `1` to distribute them evenly within the container.
