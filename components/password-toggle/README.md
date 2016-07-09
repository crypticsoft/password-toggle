# Polymer Element : Password Toggle

A toggle switch to show the text of a password field.

1.  Download and install from `bower` (use --save or --save-dev).

        `bower install crypticsoft/password-toggle`

2.  Include the component and specify a password selector, this example uses a data attribute:

        <password-toggle data-password-selector="input[data-is-password='true']"></password-toggle>
        <input type="password" name="password" data-is-password="true" value="123456">

3.  To preview the element, you can clone the repo (https://github.com/crypticsoft/password-toggle.git) and run:

        polymer serve

    Open `localhost:8080/components/password-toggle/demo/` in your browser. (Note that the path uses `password-toggle`—the
    component name listed in this element's `bower.json` file—rather than the actual directory name.)

If you're wondering what `polymer serve` does, see [Testing elements with local bower dependencies](https://www.polymer-project.org/1.0/docs/start/reusableelements.html#local-dependencies)
in the Polymer docs.
