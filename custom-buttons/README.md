# Custom Buttons

In this task you will create customizable buttons with the power of CSS custom properties. You will turn the given file or [this codepen](https://codepen.io/nicokoenig/pen/MWadLEE) into [this codepen](https://codepen.io/nicokoenig/full/BaoEQoK).

https://user-images.githubusercontent.com/16404104/200178565-7955b256-c3f0-4508-b903-6a61191fe176.mov

## Rules

- Do not touch the HTML

## Todos

- Turn the standard buttons into buttons based on custom properties
- The button can be used in 3 different sizes (small, normal, large)
  - Small base size = `.75rem`
  - Normal base size = `1rem`
  - Large base size = `2rem`
- Use the already defined custom properties from the `:root` selector
  - Use the `--surface-color` custom property to define the background
  - Use the `--text-color` custom property to define the text color
  - Use the `--highlight-color` custom property to define the outline color
- The border should be 20% of the `--base-size`
- The padding for top and bottom should be 50% of the `--base-size` and the left and right values are 100% of the `--base-size`
- The button should have an outline when the button is focussed
  - The size of the `outline` should be the same as the `border`
  - The `outline` is only displayed when the button is `focussed`
- Invert the colors of background and text color when the button is clicked
