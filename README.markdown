DejalButtonCell
===============

DejalButtonCell simple override to return the full frame instead of the actual title frame, to avoid drawing issues in a sidebar.


Donations
---------

I wrote DejalButtonCell for my own use, but I'm making it available for the benefit of the macOS developer community.

If you find it useful, a donation via PayPal (or something from my Amazon.com Wish List) would be very much appreciated. Appropriate links can be found on the Dejal Developer page:

<http://www.dejal.com/developer>


Latest Version
--------------

You can find the latest version of this code via the GitHub repository:

<https://github.com/Dejal/DejalButtonCell>


Requirements
------------

- Xcode 4 or later.
- Should work with all versions of macOS.
- Should work with or without ARC.


Features
--------

- Adds a viewDelegate property to the view.
- If set, a `-view:hitTest:withEvent:hitView:` method is invoked on the delegate.
- That delegate method can return the passed view to act normally, or return nil to ignore the tap.


Usage
-----

Include the DejalButtonCell.h and DejalButtonCell.m files in your project.


License and Warranty
--------------------

This code uses the standard BSD license.  See the included License.txt file.  Please also see the [Dejal Open Source License](http://www.dejal.com/developer/license/) web page for more information.

You can use this code at no cost, with attribution.  A non-attribution license is also available, for a fee.

You're welcome to use it in commercial, closed-source, open source, free or any other kind of software, as long as you credit Dejal appropriately.

The placement and format of the credit is up to you, but I prefer the credit to be in the software's "About" window or view, if any. Alternatively, you could put the credit in the software's documentation, or on the web page for the product. The suggested format for the attribution is:

> Includes DejalButtonCell code from [Dejal](http://www.dejal.com/developer/).

Where possible, please link the text "Dejal" to the Dejal Developer web page, or include the page's URL: <http://www.dejal.com/developer/>.

This code comes with no warranty of any kind.  I hope it'll be useful to you, but I make no guarantees regarding its functionality or otherwise.


Support / Contact / Bugs / Features
-----------------------------------

I can't promise to answer questions about how to use the code.

If you create an app that uses the code, please tell me about it.

If you want to submit a feature request or bug report, please use [GitHub's issue tracker for this project](https://github.com/Dejal/DejalButtonCell/issues).  Or preferably fork the code and implement the feature/fix yourself, then submit a pull request.

Enjoy!

David Sinclair  
Dejal Systems, LLC


Contact: <http://www.dejal.com/contact/?subject=Dejal+View&ref=dejalbuttoncell>  
More open source projects: <http://www.dejal.com/developer>  
Open source announcements on Twitter: <http://twitter.com/dejalopen>  
General Dejal news on Twitter: <http://twitter.com/dejal>

