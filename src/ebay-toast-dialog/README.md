# EbayToast

## EbayToast Usage

```react
<EbayToast open a11yClosetext="Close EbayToast">
    <h1>Hello World</h1>
</EbayToast>
```

## Attributes

Name | Type | Stateful | Required | Description
--- | --- | --- | --- | ---
`open` | Boolean | Yes | No | Whether drawer is open.
`a11yCloseText` | String | No | Yes | A11y text for close button and mask.
`animated` | Boolean | Yes | No | Renders the dialog with an animation. Note that the dialog will always be present in the DOM

## Events

Event | Data | Description
--- | --- | ---
`onShow` |  | drawer opened
`onClose` |  | drawer closed
