# HTML Forms

The [HTML `form` element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form) represents a section of interactive controls for submitting information.

There are many different types of information you may want to collect from users, text-based answers, numbers, files, checkboxes, date, email, etc. It is important to specify the type of information you are collecting to make it easier for the computer to parse or translate the information and determine next actions.

To collect all of this information, we use the `input` element and specify the type of information by using the `type` attribute.

Let’s take a look at a few examples of how the `input` element is used for a variety of types of information.
=======
- `<input type=”text”>`: The type `text` is used to take in a single-line text field. The `placeholder` attribute allows us to provide default text to display in the text field when empty.
- `<input type=”button”>`: The type `button` is used to create a clickable rectangular button. Alternatively, most developers use the `<button>` element instead.
- `<input type=”checkbox”>`: The type `checkbox` creates default boxes that are checked (ticked) when selected.

- `<input type=”number”>`: The type `number` takes in a number input. By default the `number` type allows only integers unless otherwise specified by the use of the `step` attribute.
- `<input type=”radio”>`: The type `radio` creates a clickable circular button, or a radio button. They act similarly to the `checkbox` type.
