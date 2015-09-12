[Original Readme](https://github.com/amlcurran/ShowcaseView/blob/master/README.md)
====

Usage
====

To use ShowcaseView, use the Builder pattern.

As an example:

~~~
new ShowcaseView.Builder(this)
    .setTarget(new ActionViewTarget(this, ActionViewTarget.Type.HOME))
    .setContentTitle("ShowcaseView")
    .setContentText("This is highlighting the Home button")
    .hideOnTouchOutside()
    .initExtraButtons(2) // add two additional buttons
    .build();
~~~

This library is distributed under an Apache 2.0 License.
