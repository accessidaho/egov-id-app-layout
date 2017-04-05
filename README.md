# \<id-app-layout\>

Idaho application layout

## Installation

Add the following to bower.json.

```JSON
{
  "id-app-layout": "https://github.com/accessidaho/egov-id-app-layout.git"
}
```

## Usage

Import the element:

```html
<link rel="import" href="bower_components/id-app-layout/id-app-layout.html">
```

Add the element and set properties:

```html
<id-app-header
  background-image="/images/idaho-seal.png">
</id-app-header>

<id-app-footer
  name="name"
  url="url"
  address="address"
  phone="phone"
  email="email">
</id-app-footer>
```

## Styling

`<id-app-layout>` provides the following custom properties for styling:

Custom property | Description | Default
----------------|-------------|----------
`--id-header-background-color` | Default header background color | #fff
`--id-pre-footer-background` | Default pre footer background color | #0c1e38
`--id-footer-background` | Default footer background color | #0e2340
