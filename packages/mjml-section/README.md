## mjml-section

Sections are intended to be used as rows within your email.
They will be used to structure the layout.

```xml
<mjml>
  <mj-body>
    <mj-section full-width="full-width" background-color="red">
      <!-- Your columns go here -->
    </mj-section>
  </mj-body>
</mjml>
```

<p align="center">
  <a href="https://mjml.io/try-it-live/components/section">
    <img width="100px" src="https://mjml.io/assets/img/svg/TRYITLIVE.svg" alt="try it live" />
  </a>
</p>

The `full-width` property will be used to manage the background width.
By default, it will be 600px. With the `full-width` property on, it will be
changed to 100%.

<aside class="notice">
  <b>Inverting the order in which columns display:</b> set the `direction` attribute to `rtl` to change the order in which columns display on desktop. Because MJML is mobile-first, structure the columns in the <b>order you want them to stack on mobile</b>, and use `direction` to change the order they display <b>on desktop</b>.
</aside>

<aside class="warning">
  Sections cannot be nested into sections. Also, any content in a section should also be wrapped in a column.
</aside>

attribute           | unit        | description                    | default value
--------------------|-------------|--------------------------------|---------------
background-color    | color       | section color                  | n/a
background-repeat   | string      | css background repeat          | repeat
background-size     | percent/px  | css background size            | auto
background-url      | url         | background url                 | n/a
border              | string      | css border format              | none
border-bottom       | string      | css border format              | n/a
border-left         | string      | css border format              | n/a
border-radius       | px          | border radius                  | n/a
border-right        | string      | css border format              | n/a
border-top          | string      | css border format              | n/a
css-class           | string      | class name, added to the root HTML element created | n/a
direction           | string      | ltr / rtl                      | ltr
full-width          | string      | make the section full-width    | n/a
padding             | px          | supports up to 4 parameters    | 20px 0
padding-bottom      | px          | section bottom offset          | n/a
padding-left        | px          | section left offset            | n/a
padding-right       | px          | section right offset           | n/a
padding-top         | px          | section top offset             | n/a
text-align          | string      | css text-align                 | center
vertical-align      | string      | css vertical-align             | top

