# Hover Transitions

In this task you will use transitions. You will start with the given file or [this codepen](https://codepen.io/nicokoenig/pen/xxbvyga) and enhance it to look like [this codepen](https://codepen.io/nicokoenig/full/NWPQObr).

https://user-images.githubusercontent.com/16404104/200179202-b5efdf92-7ec1-422d-af2b-b651ba2648b2.mov

## Todos

- Add a title and a paragraph to the main element
  - Give both elements some text
- Add a background color or and background image that covers the square (you can use [fillmurray](https://www.fillmurray.com/) or [placekitten](https://placekitten.com/))
- Title and paragraph are only visible when the square is hovered
- Use transitions to animate the change between shown and hidden state

## Hints

- Distribution of the title and description element can be done with flexbox
- Place the title and the description with `transform: translateY()` outside of main. 

```css
main h2 {
	transform: translateY(-100%);
}
```
- Use `overflow: hidden` for main, so that title and description are not shown.
- When main is hovered, remove the tranformation, so that title and the description are shown.

```css
main:hover h2 {
	transform: none;
}
```
