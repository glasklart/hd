Overview
=====================================================================

Out-of-the-way transparent WinterBoard theme that let's you really
showcase your wallpaper. Glasklart is swedish, it means "clear as
glass".

Now includes 7200+ icons which have been
graciously crafted by the community.  In addition to that: custom
badges, lock screen skin, popup dialogs, SMS bubbles, calculator skin,
dialer skin, call skin and a lot of separate options for additional
customization.

Either download from Cydia (search for 'Glasklart'), or [click
here](https://github.com/glasklart/hd/tarball/master).

Contributors
=====================================================================
Our contributors are who makes Glasklart the best theme for iPhone.
Without them, Glasklart would have died long ago. Please take a moment
to [look over our list of contributors](https://github.com/glasklart/hd/graphs/contributors).

Make sure to show your appreciation to everyone on this list!

How You Can Help Make Glasklart More Awesome
=====================================================================
Whether it's requests, contributions or bugs, thanks to everyone who
helps make Glasklart the best, most complete theme on the internet.

  * [Submitting an Icon Request](#icon-requests)
  * [Contributing an Icon](#icon-contributions)
  * [Submit a Bug](#submitting-a-bug)
  * or our favorite option... submit a pull request!

Installation
=====================================================================

After you manually install or (preferrably) install via Cydia, you will
probably want to do the following:

  1. Connect to the filesystem (iFile, SSH, etc)
  2. Navigate to `/System/Library/PrivateFrameworks/MobileIcons.framework/`
  3. Rename `AppIconMask.png` to `AppIconMask-backup.png`

This is optional, however if you choose not to do this, the icons will
show up against a black graphic.

Note: There is a side effect that this makes unchanged icons squared.
Unfortunately, at this time, this is the only solution.

Icon Requests
=====================================================================

Before _all_ icon requests, do the following:

Search to see if the icon has already been created.

  * Google for: `"your app's name" intitle:glasklart intitle:theme site:macthemes.net/forum`
  * Press 't' right now to open Github's file finder. Type in the name of an app to see if it exists
  * Search the project's [issue tracker](https://github.com/glasklart/hd/issues)

If the icon exists:

  * Is it not working?  Maybe it's a bug!  Create an issue something like issue [#3](https://github.com/glasklart/hd/issues/3)

If the icon does not exist:

  * Create a [new icon request issue](#new-icon-request). Only 1 icon
    request per issue.  __Issues with multiple icon requests will be
    closed.__

New Icon Request
---------------------------------------------------------------------

While we've tried to make this as simple a process as possible, tracking
down all the information needed for an icon request is not for the faint of
heart.  Please read _everything_ below before continuing.

**If your request does not meet our requirements, it _will be closed_.**

If the icon has not already been requested, enter an issue title with
only the name of the application such as:

    Find My Friends

Do not enter anything like the following

  * `Requesting Find Friends!!!!1!!`
  * `ZOMG I would <3 you forEVAH if you did this one! :)`
  * `I can't Find My Friends! Can you help!?!?!?`
  * `URGENT!! YOU MUST DO THIS FOR ME OR I'LL DIE OF DYSENTERY!`

[How do I find the exact name of my application?](#find-the-app-metadata)

### Tracking Down Needed Information ###

There are a few specific pieces of information we'll need in order for
the icon request to be valid.

__If you do not provide the exact information described here, in the exact format
described here your request will be rejected.__

This is important because if we need to go back and run an automated script to
parse all of the issues and put them into a database, we need them to be consistently
formatted.  Thank you for your cooperation.

  * `Name` _eg: RunKeeper - GPS Running, Walking, Cycling and more!_ (This is the __exact__ name that should be displayed in the issue's title. [how do I find this?](#find-the-app-metadata))
  * `Bundle ID` _eg: RunKeeperPro_ ([how do I find this?](#find-the-app-metadata))
  * `iTunes ID` _eg: 300235330_ ([how do I find this?](#find-the-app-metadata))
  * `PNG Icon Names` _eg: Icon.png | Icon@2x.png | Icon-72.png | Icon-Small.png | Icon-Small@2x.png_  ([how do I find this?](#find-the-app-metadata))
  * `Artwork` ([how do I find this?](#find-icon-graphics))

#### Find the App Metadata ####

In order to find all of the metadata we need, the easiest way is to
download [AppInfo](http://modmyi.com/cydia/package.php?id=37153) from Cydia.

Open it and choose the app you're requesting an icon for.  Example:

![AppInfo Image](https://dl.dropbox.com/s/x8a8epsv53443z3/appinfo-runkeeper-small.png)

Here is the list of information we need and the corresponding place on the screen to find it:

<dl>
  <dt>Name:</dt>
  <dd>In AppInfo it is also called <strong>Name</strong></dd>
  <dt>Bundle ID:</dt>
  <dd>In AppInfo it is simply <strong>Id</strong></dd>
  <dt>iTunes ID:</dt>
  <dd>In AppInfo it is <strong>Item ID</strong></dd>
  <dt>PNG Icon Name:</dt>
  <dd>
    In AppInfo it is <strong>IconFiles</strong><br/>
    Copy the entire item even if it describes multiple icon names<br/>
    <a href="#finding-unknown-png-icon-names">What do I do if it says 'Unknown'?</a>
  </dd>
</dl>

#### Icon Graphics ####

##### Finding Them #####

We require source artwork that is at least a 512px by 512px.  __This. Is. Required.__
for your icon to be fulfilled.

The best way is to do a [Google Image Search](http://images.google.com) like so:

`RunKeeper App Icon`

That will usually result in a good set of results.  In the case that your image is
not large enough, remember that you can click on an image and select "More Sizes".
Sometimes this will give you access to bigger images.

##### Attaching Graphics To Your Request #####

Attaching graphics to your request is easy.  All you have to do is click on it and
drag it to the tab where you've started your issue.  If you drop it on top, it will
automatically be uploaded and attached.

Alternatively, you can save the icon to your hard drive, then click the 'choose an
image' link in the area below your request to select it.  It will upload it and
include it in your issue.

**_Note: We no longer accept images attached via Dropbox, Photobucket, Imgr, CloudApp, etc._**

#### Finding Unknown PNG Icon Names ####

If AppInfo tells you that *IconFiles* is 'Unknown', scroll down to the bottom
of that screen and tap 'Open in iFile'.

Once iFile opens, there should be a folder with the name of your app (in the
above example it would be `RunKeeper.app`). You'll want to tap on that folder.

In the folder that opens, you'll see a long list of files.  You're looking for
one called `Info.plist`. Tap on that.

iFile will ask you what you want to open the file with. Choose 'Property List
Viewer'.

When Property List Viewer opens, scroll down until you find an entry called
`CFBundleIconFile`. The value on the righthand side is what you will enter for
the `PNG Icon Name` when creating your icon request.

### Example ###

To view an example icon request with all the necessary information,
view issue [#917](https://github.com/glasklart/hd/issues/917).

Rename Icon Request
---------------------------------------------------------------------

If the icon has already been created, but the spelling has changed,
enter an issue title with both names such as:

    "Runkeeper Free" renamed to "Runkeeper"

You will need to provide any information that has changed from the
current icon as it is in Glasklart such as the `Bundle ID` or
`PNG Icon Name` (see "New Icon Request" below).

### Example ###

To view an example renaming request with all the necessary information,
view issue [#1](https://github.com/glasklart/hd/issues/1).

Icon Contributions
=====================================================================

Glasklart is a community effort, we can only continue being this successful with
your help!

Responding to Icon Requests
---------------------------------------------------------------------

If you are responding to an icon request made by someone other than yourself,
attach the icon to the issue like so:

    Fulfillment URL: http://url.to/your/file.png

### Guidelines ###

Icons will be accepted if they meet the following guidelines:

#### Format ####

Icons should be attached in any of the following formats:

 * PNG
 * EPS
 * SVG
 * PSD

#### Size ####

The file should be 512px by 512px at a minimum

#### Orientation ####

The icon should be _centered_ on a _transparent_ canvas like [this](https://github.com/dreamnet/glasklart-HD-iPad3/blob/master/Icon%20Source%20Examples/com.atebits.Tweetie2.png)
or [this](https://github.com/dreamnet/glasklart-HD-iPad3/blob/master/Icon%20Source%20Examples/com.apple.AppStore.png).

_Note: There is no maximum size (although 1024px by 1024px is plenty)._

#### Preview ####

You should include a preview of your icon so it can be looked over by the rest of the community by applying
the template [here](http://glasklarthd.dreamnet.at/download/glasklarthd-template.zip).

Include it by using the following line when you submit your fulfillment.

    ![](http://preview.dreamnet.at/?image=http://url.to/your/file.png)

Which will display something like:

![Preview](http://preview.dreamnet.at/?image=http://glasklarthd.dreamnet.at/theicons/10/icon1/icon@2x.png)

__Only one icon should be attached per issue thread__ This helps us keep things
nice and organized.  If you submit more than one per thread, we'll still accept
them, but _please_ don't.  We're trying to keep things efficient now as well as
in the future.

Fulfilling Your Own Icon Requests
---------------------------------------------------------------------

If you are submitting an icon without a prior request, you should go up to the
section on "Icon Requests" and follow all of those steps.

The obvious exception is the `Artwork URL` which is not necessary since you will
be providing the Glasklart themed icon instead.

Templates
---------------------------------------------------------------------

### Glasklart Icon Template ###

[Download the Icon Template](http://glasklarthd.dreamnet.at/download/glasklarthd-template.zip)

Please, please, read the README included with the template for information on how
to set up your device for theming and how to use Bundles.

### Glasklart GUI Templates ###

[Glasklart Dialer Template](http://www.maxthemes.com/downloads/glasklart-dialer.zip)
This allows you to make a transparent dialer with the background of your choice. This
should be relatively self explanatory for the average Photoshop user with knowledge of the
iPhone. Needless to say, it's not for everyone.

[Glasklart Dock Flow Photoshop Template](http://www.maxthemes.com/downloads/glasklart-dock-flow-template.zip)

[Glasklart GUI Elements Photoshop Template](http://www.maxthemes.com/downloads/glasklart-elements.zip)

Tutorials
---------------------------------------------------------------------

[Glasklart Icon Video Tutorial](http://www.youtube.com/watch?v=49rMynz3mtk) made by kyle1320

[Glasklart Icon Tutorial](http://www.maxthemes.com/downloads/glasklart-icons-tutorial.zip) made by Filip Smitz, aka Colorblind

Submitting a Bug
=====================================================================

Sometimes app makers change the icon names that they use and doing so breaks Glasklart.
Sometimes Apple changes the names of images they use within iOS and doing so breaks Glasklart.
If you find a problem like this or anything else, _please file a bug_.  It's really easy!  Just
create something similar to [this](https://github.com/glasklart/hd/issues/3).

And thanks again for keeping Glasklart bug-free!
