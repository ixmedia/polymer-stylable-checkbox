# stylable-checkbox

A checkbox that can actually be styled!


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Using the Element

Just put those tags in the `<head>`:
`<script src="../webcomponentsjs/webcomponents-lite.js"></script>`
`<link rel="import" href="../stylable-checkbox/stylable-checkbox.html">``
And then you will be able to use the `<stylable checkbox>` as if it were an normal input checkbox
Example: `<stylable-checkbox name="formInputName" value="someValue" checked></stylable-checkbox>`


## Playing With the Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/stylable-checkbox/`
