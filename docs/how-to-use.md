# How To Use

!!!
Capacitor is still in **early development**, and not yet for sale.

However, if you're interested in **beta testing** you can download for free via Apple's TestFlight [here](https://testflight.apple.com/join/05GvWETb).
!!!

When you first run Capacitor you'll be presented with a window like this:

![](/static/how-to-use-01.png)

As the window explains, simply drag a FCPXML file from Finder to the drop zone.

!!!
Currently Capacitor only supports `.fcpxml` files.<br />
Final Cut Pro Library Bundles (`.fcpxmld`) will be supported in a future beta.<br />
In the meantime, you can right-click on the Final Cut Pro Library Bundle and click **Show Package Contents** to access the FCPXML file.
!!!

When the FCPXML is loaded you'll be presented with something like this:

![](/static/how-to-use-02.png)

You can then select the FCPXML version you want to convert to from the Destination dropdown:

![](/static/how-to-use-03.png)

In this case I'm converting a `v1.11` FCPXML into a `v1.6` FCPXML that works with Final Cut Pro `v10.3`:

![](/static/how-to-use-04.png)

You can see the list of warnings of the things in the FCPXML that are not supported.

You can click **Cancel** to abort the conversion or **Export** to save a new FCPXML.

If you click **Export** you'll be asked where to save the new FCPXML:

![](/static/how-to-use-05.png)

After clicking **Export** the file will be converted, and you'll be presented with:

![](/static/how-to-use-06.png)

It's that simple! Capacitor will always export a valid FCPXML file.

Got ideas or questions? Post them on our [Discussions page](https://github.com/latenitefilms/capacitor/discussions)!