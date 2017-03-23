# penguin-saved-indicator

## Installation

	$ npm i -S penguin-saved-indicator

Then edit your `package.json` file to include the component.

```json
{
  "penguin": {
    "components": {
      "SavedIndicator": "penguin-saved-indicator"
    }
  }
}
```

## Usage

```html
<p data-component='SavedIndicator'>
  <strong>Successfully saved!</strong>
</p>
```

This component shows its target element after the page/object was successfully saved. It hides it after a timeout that can be specified in the props.

### Props

  * `timeout` (number) - Number of milliseconds that the element. Default is `2000`.