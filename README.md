# macos-phpswitch
Easily switch php version on mac when using brew.


**Installation:**

1.
``composer global require cino/macos-phpswitch``

2.
Make sure ~/.composer/bin is in your path.

**Usage**

``phpswitch 7.2``

Et voila, it installs php 7.2


**PHP 5.6, 7.0, 7.1 support**

To enable support for automated installing of deprecated versions add the following tap:

``brew tap exolnet/homebrew-deprecated``
