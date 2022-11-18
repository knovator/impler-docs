---
description: >-
  Impler provides the @impler/react a react library that helps to add an import
  widget in your application
---

# 🌐 React Component

Let's do a quick review of how to use `@impler/react` library in your application.

## Add Script

You copy this snippet to your code before the closing body tag.

{% code overflow="wrap" %}
```html
<script type="text/javascript" src="https://embed.impler.io/embed.umd.min.js" async></script>
```
{% endcode %}

It will add `impler` variable in `window`, so you can call its `init` and `show` method.

## Install the Package

Add `@impler/react` in your application by running the following command.

```bash
npm i @impler/react
# or
yarn add @impler/react
```

## Add Import Button

Now add `Import` Button from `@impler/react` which opens Widget.

```html
import { Import } from '@impler/react';

<Import
    projectId="<PROJECT_ID>"
    template="<CODE_OR_ID>" /* optional */
    accessToken="<SECRET>" /* required if API is authenticated */
/>
```

### Props

<table><thead><tr><th>Prop</th><th>Type</th><th data-type="checkbox">Required</th><th>Description</th></tr></thead><tbody><tr><td>projectId</td><td>string</td><td>true</td><td>Id of the project created from API</td></tr><tr><td>template</td><td>string</td><td>false</td><td>Id or Code of the Template you want to Import</td></tr><tr><td>accessToken</td><td>string</td><td>false</td><td>Provide security Token if APIs are secured with <code>ACCESS TOKEN</code></td></tr><tr><td>authHeaderValue</td><td>string</td><td>false</td><td>Authentication value to authenticate webhook while sending imported data</td></tr><tr><td>extra</td><td>string / json</td><td>false</td><td><code>String</code> or <code>JSON Object</code> to pass while sending imported data</td></tr></tbody></table>

Your app is now ready to import data,&#x20;
