[![Join the chat at https://gitter.im/vic10us/cc-form](https://badges.gitter.im/vic10us/cc-form.svg)](https://gitter.im/vic10us/cc-form?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) 
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/vic10us/cc-form)

# \<cc-form\>

<!--
```
<custom-element-demo>
  <template is="dom-bind">
    <link rel="import" href="cc-form.html">
    <cc-form></cc-form>
  </template>
</custom-element-demo>
```
-->
```
<cc-form></cc-form>
```

# A Polymer CreditCard Element
*_add a little pzazz to the mundane task of entering your credit card info on a website_*

Demo and API docs: _https://vic10us.github.io/cc-form/components/cc-form/_

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/cc-form/`, where `cc-form` is the name of the directory containing it.


## Testing Your Element

Simply navigate to the `/test` directory of your element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/cc-form/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.
