<img src="http://www.maxthemes.com/images/zoomed-glasklarthd.jpg" width="200" />

All-Star Contributors
=====================================================================
I'm going to add a list of people here who go above and beyond the call of
duty when contributing to Glasklart.

  * @dreamnet (aka GKI) - You can find all of his amazing Glasklart
    icons here: http://glasklarthd.dreamnet.at. If you want one of them
    added to Glasklart proper, file a new icon request
    [issue](#new-icon-request).

  * @Tr1pTr0p - Has been instrumental in updating the larger Glasklart themes
    for iOS 5 including the Phone, the Lock Screen and the Calculator. The
    sheer number of hours it had to have taken to make all of those a reality
    should be known by all who love Glasklart.

  * @vinstic - Has contributed dozens of icons to the project.  Easy or hard,
    he handles them with ease.

Rising Stars
---------------------------------------------------------------------

  * @jimmyt650 - Is a recent addition to the regular icon contributors but in
    that time has added over three dozen icons to the repo.  He has also
    spearheaded the addition of a 'Clockify' theme.

  * @scottbuckley - Over the last few weeks, he has contributed over 40+ icons
    to the project, without people like him, Glasklart wouldn't be what it is
    today.

Make sure to show your appreciation to everyone on this list!

Overview
=====================================================================

Out-of-the-way transparent WinterBoard theme that let's you really
showcase your wallpaper. Glasklart is swedish, it means "clear as
glass".

Now includes 6600+ icons! 120 I created on my own, the rest has been
graciously crafted by the community.  In addition to that: custom
badges, lock screen skin, popup dialogs, SMS bubbles, calculator skin,
dialer skin, call skin and a lot of separate options for additional
customization.

This theme is for iPhone devices which are Retina-display compatible.
If you are looking for the non-Retina version,
[click here](https://github.com/glasklart/classic/downloads).

Either download from Cydia (search for Glasklart HD), or [click
here](https://github.com/glasklart/hd/tarball/master).

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
  * `Artwork URL` _eg: http://dioi4pcdjblhi.cloudfront.net/images/215cba7fab1a48a7bd511445c04c1193.jpg_ ([how do I find this?](#find-icon-graphics))

#### Find the App Metadata ####

In order to find all of the metadata we need, the easiest way is to
download [AppInfo](http://modmyi.com/cydia/package.php?id=37153) from Cydia.

Open it and choose the app you're requesting an icon for.  Example:

![AppInfo Image](https://dl.dropbox.com/s/x8a8epsv53443z3/appinfo-runkeeper-small.png)

Here is the list of information we need and the corresponding place on the screen to find it:

  * `Name`: _Name_
  * `Bundle ID`: _Id_
  * `iTunes ID`: _Item ID_
  * `PNG Icon Name`: _IconFiles_ (Copy the entire item even if it describes multiple icon names)

#### Find Icon Graphics ####

In order to find the source graphics for your icon, you may first want
to stop here: http://iextract.quadrat4.de

If you cannot find the graphics for your app, you will need to hunt
them down yourself and provide a link to the appropriate file.

The easiest way to provide us the image is to save the icon file to your
computer and use an app such as Dropbox or CloudApp to provide a public
URL to it.

### Example ###

To view an example icon request with all the necessary information,
view issue [#2](https://github.com/glasklart/hd/issues/2).

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

[Download the Icon Template](http://www.maxthemes.com/downloads/glasklart-template2.zip)

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
