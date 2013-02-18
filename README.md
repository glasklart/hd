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

Do you work better when you can see the end product _before_ you get the explanation
of how to do it? [Here's an example of a well done request.](https://github.com/glasklart/hd/issues/917)

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
  <dd>
    In AppInfo it is <strong>Item ID</strong><br/>
    If you are requesting a Cydia app, you do not have to supply an iTunes ID.
    <a href="#finding-blank-itunes-ids">What do I do if it's not a Cydia app, but is still blank?</a>
  </dd>
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

Attaching graphics to your request [is easy](https://f.cloud.github.com/assets/21/678/248aac6a-40a2-11e2-9a76-fd59ded28bbe.gif).
All you have to do is click on it and
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

#### Finding Blank iTunes IDs ####

The only reason we've found for a iTunes ID to be blank is if you've pirated the
app.  We don't condone piracy, but occasionally an app must be installed outside
of the App Store ecosystem. For example, if it was pulled from the store, or the
newest version has a bug that makes it unusable.

In those cases, to find the iTunes ID you'll want to:

* Open the iTunes Store
* Navigate to the app you're wanting to make a request for
* Right click on the name of the app
* Choose "Copy Link"
* Paste the link somewhere and look at it

The link will look something like this:

    https://itunes.apple.com/us/app/runkeeper-gps-track-running/id300235330?mt=8

The iTunes ID is everything after the 'id' and before the '?'. In this case:

    300235330

### Example ###

To view an example icon request with all the necessary information,
view issue [#917](https://github.com/glasklart/hd/issues/917).

Rename Icon Request
---------------------------------------------------------------------

If the icon has already been created, but information about it has
changed (potentially causing it not be themeing properly), enter an
issue title just as you would when creating an icon request:

    Runkeeper

You will need to provide basic icon information such as the `Bundle ID`,
`iTunes ID` and `PNG Icon Name` (see [New Icon Request](#new-icon-request)).

### Example ###

To view an example renaming request with all the necessary information,
view issue [#1](https://github.com/glasklart/hd/issues/1).

Icon Contributions
=====================================================================

Glasklart is a community effort, we can only continue being this successful with
your help!

Whether you are responding to an icon request made by someone else or submitting,
one for yourself, icon fulfillments require two pieces of information:

* The icon itself which [follows our guidelines](#guidelines) that is [attached to the request](#attaching-icons)
* A [preview of the icon](#previewing-icons)

__Only one icon should be attached per issue thread__ This helps us keep things
nice and organized.  If you submit more than one per thread, we'll still accept
them, but _please_ don't.  We're trying to keep things efficient now as well as
in the future.

Guidelines
---------------------------------------------------------------------

In order to create a Glasklart icon you will need Photoshop as well as the template
[here](http://glasklarthd.dreamnet.at/download/glasklarthd-template.zip).

Follow [this guide](http://glasklarthd.dreamnet.at/how-to-make-an-icon) to get you
started down the road to creating your very first Glasklart icon.

Attaching Icons
---------------------------------------------------------------------
Attach the icon to the issue by dragging and dropping the icon
file directly into the issue.

Alternatively you can click the 'choose an image' link and select it from your
hard drive.

![](https://f.cloud.github.com/assets/21/678/248aac6a-40a2-11e2-9a76-fd59ded28bbe.gif)

Look at the comment on [this issue](https://github.com/glasklart/hd/issues/917)
for a proper example of a well done icon fulfillment.

Previewing Icons
---------------------------------------------------------------------
In order for the team to determine if your icon is up to snuff, we need
to see it as it would be if it was being used in the Glasklart theme.

After attaching your contribution in the step above, you will see a URL
that looks similar to:

    https://f.cloud.github.com/assets/2156037/164687/960c3096-78d5-11e2-9c05-8ed4c5c4dbbf.png

In order to create a preview for that file, you'll need to add the following
line to your comment:

    ![](http://preview.dreamnet.at/?image=https://f.cloud.github.com/assets/2156037/164687/960c3096-78d5-11e2-9c05-8ed4c5c4dbbf.png)

Notice the first part will not change for any preview you create:

    ![](http://preview.dreamnet.at/?image=
    
The part after the equal sign is the URL that was created when you attached your
contribution.

If you do it correctly you will see something like this:

![Preview](http://preview.dreamnet.at/?image=https://raw.github.com/glasklart/hd/3c4aaa828ac3df12618ced3ba1485fc1296aa0b3/Glasklart%20Icons/Bundles/com.apple.Maps/Icon-57@2x.png)

Fulfilling Your Own Icon Requests
---------------------------------------------------------------------

If you are submitting an icon without a prior request, you should [go up to the
section on Icon Requests](#icon-requests) and follow all of those steps.

Then [go to the section on Icon Contributions](#icon-contributions) and follow
all of those steps.

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
