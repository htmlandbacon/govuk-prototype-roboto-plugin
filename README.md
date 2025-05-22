# govuk-prototype-roboto-plugin

Once installed this provides a layout to make the default font [Roboto](https://fonts.google.com/specimen/Roboto)

## Getting started

```
npm i https://github.com/htmlandbacon/govuk-prototype-roboto-plugin
```

## Configure your layout

In the same way as you can use an [unbranded layout](https://prototype-kit.service.gov.uk/docs/how-to-use-layouts) you can now make use of the roboto one:

```
{% extends "layouts/roboto.njk" %}
```

## Configure your layout - by class

If you want to change a current layout you can add the following:

```
{% set bodyClasses = "govuk-template__body--font-roboto" %}
```