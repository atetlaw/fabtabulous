
# Fabtabulous!

Simple tabs using Prototype

In this simple tab implementation you identify a block element (by ID) that has a bunch of anchor elements which become tabs.

    new Fabtabs('tabs');

The anchors must link to IDs within the page e.g.

    <a href="/page.html#something">link</a>

The element at #something should be a block element and that becomes the tab body. The rest is CSS.