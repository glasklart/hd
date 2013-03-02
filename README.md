Overview
=====================================================================

Out-of-the-way transparent WinterBoard theme that lets you really
showcase your wallpaper. Glasklart is swedish, it means "clear as
glass".

Now includes 7000+ icons which have been
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

## Verify Icon Hasn't Already Been Submitted ##

Before _all_ icon requests, do the following:

### Step 1: Check For Existing Issues ###

Search the project's [issue tracker](https://github.com/glasklart/hd/issues)
for the app's name.

If it exists, add a comment describing what you think the problem is _to the
existing issue._ If the issue is currently closed, don't worry; if necessary,
we'll reopen it.

### Step 2: Check For Existing Icons ###

If `Check For Existing Issues` doesn't find anything, press `t` right now
to open Github's file finder. Type in the name of an app to see if it
exists.

If it does, fill out a [New Icon Request](#new-icon-request) and once
you're done with that, add a **separate** comment to the issue you just created
letting us know that you think there's a problem with the current icon.

If you have any additional information, such as how to fix the issue, we
would be grateful if you'd supply that.

### Step 3: Fill Out A 'New Icon Request' ###

If you still can't find the item, you are now able to fill out a typical
[New Icon Request](#new-icon-request). Only 1 icon request per issue.
__Issues with multiple icon requests will be closed.__

New Icon Request
---------------------------------------------------------------------

While we've tried to make this as simple a process as possible, tracking
down all the information needed for an icon request is not for the faint of
heart.  Please read _everything_ below before continuing.

**If your request does not meet our requirements, it _will be closed_.**

If the icon has not already been requested, enter an issue title with
**only** the name of the application, such as:

    Find My Friends

Do not enter anything like the following:

  * `Requesting Find Friends!!!!1!!`
  * `ZOMG I would <3 you forEVAH if you did this one! :)`
  * `I can't Find My Friends! Can you help!?!?!?`
  * `URGENT!! YOU MUST DO THIS FOR ME OR I'LL DIE OF DYSENTERY!`

**How do I find the exact name of my application?** Use the `Name` value
from [Step 2](#step-2-of-3-create-a-well-formed-request)

### Tracking Down Needed Information ###

We have made great strides in making this as painless a process as possible.  If you
follow the exact steps outlined below, you will have a valid request.  However, if
you do not give us an icon request in the exact format we're looking for, _your
request **will** be closed._

This is important because if we need to go back and run an automated script to
parse all of the issues and put them into a database, we need them to be consistently
formatted.  Thank you for your cooperation.

Because it's quite complex, it may be easier if we show you what [a properly executed
icon request looks like](https://github.com/glasklart/hd/issues/1297).

#### Getting Started with AppInfo ####

The easiest way to find all of the metadata we need is to
download [AppInfo](http://modmyi.com/cydia/package.php?id=37153) from Cydia.

#### Step 1 of 3: Find the iTunes ID ####

Open AppInfo and choose the app you're requesting an icon for.  Example:

![AppInfo Image](https://dl.dropbox.com/s/x8a8epsv53443z3/appinfo-runkeeper-small.png)

Locate the line that says `Item ID`.  That is the iTunes ID and it will be used in the
next step.

[What do I do if the Item ID is blank?](#troubleshooting-finding-blank-itunes-ids)

#### Step 2 of 3: Create a Well-Formed Request ####

<img src="http://dl.dropbox.com/u/1132018/itunes-artwork-crawler-step-1.png" width="200" align="right" />

1. Open [this page](http://getart.dreamnet.at) in a new tab.
2. Enter the iTunes ID you acquired from Step 1 in the field provided.
3. Press "Crawl data!"

Assuming the iTunes ID is valid, you'll see a page with a text field and a (hopefully)
giant image of the artwork.

Copy the entire contents of the text area and paste it into the issue you've opened.

**It is VERY important that you paste it _at the very top_ of the icon request.**

Once you've done that, there will be two lines that will not be filled out yet.

    iPhone Icon Name: ### THIS IS FOR GLASKLART MAINTAINERS DO NOT CHANGE THIS LINE ###

and

    Icon Names: ### PLEASE FILL THIS OUT ###

You're now ready for the final step.

#### Step 3 of 3: Find PNG Icon Names ####

Go back to AppInfo to your app and locate the entry for `IconFiles`.

Take this entire line and _exactly_ copy it onto the `Icon Names` line from
**Step 2**. For RunKeeper, the line would go from this:

    Icon Names: ### PLEASE FILL THIS OUT ###

to this:

    Icon Names: Icon.png | Icon@2x.png | Icon-72.png | Icon-Small.png | Icon-Small@2x.png

[What do I do if `IconFiles` is 'Unknown'?](#troubleshooting-finding-unknown-png-icon-names)

#### You're Done! ####

Hit 'Submit new issue' and we'll verify your request as soon as possible. Thanks
for helping to make Glasklart even more awesome!

#### Troubleshooting: Finding Unknown PNG Icon Names ####

If AppInfo tells you that `IconFiles` is 'Unknown', scroll down to the bottom
of that screen and tap 'Open in iFile'.

Once iFile opens, in the list of files should be a folder with the name of
your app (in the above example it would be `RunKeeper.app`). You'll want to
tap on that folder.

In the folder that opens, you'll see a long list of files.  You're looking for
one called `Info.plist`. Tap on that.

iFile will ask you what you want to open the file with. Choose 'Property List
Viewer'.

When Property List Viewer opens, scroll down until you find an entry called
`CFBundleIconFile`. The value on the righthand side is what you will enter for
the `PNG Icon Name` when creating your icon request.

#### Troubleshooting: Finding Blank iTunes IDs ####

The only reason we've found for AppInfo to have a blank `ItemID` field, is
if you've pirated the app.  We don't condone piracy, but occasionally an app
must be installed outside of the App Store ecosystem. For example, if it was
pulled from the store, or the newest version has a bug that makes it unusable.

In those cases, to find the iTunes ID you'll want to:

* Open the iTunes Store
* Navigate to the app you want to make a request for
* Right click on the name of the app
* Choose "Copy Link"
* Paste the link somewhere and look at it

The link will look something like this:

    https://itunes.apple.com/us/app/runkeeper-gps-track-running/id300235330?mt=8

The iTunes ID is everything after the 'id' and before the '?'. In this case:

    300235330

### Example ###

To view an example icon request with all the necessary information,
view issue [#1297](https://github.com/glasklart/hd/issues/1297).

Rename Icon Request
---------------------------------------------------------------------

Don't forget to first look for an existing issue [as described here](#verify-icon-hasnt-already-been-submitted).
If one already exists, add a comment letting us know what has changed.

If the icon has already been created, but information about it has
changed (potentially causing it not be theming properly), enter an
issue title just as you would when creating an icon request:

    Runkeeper

You will need to provide all icon information just as if you were
filling out a [New Icon Request](#new-icon-request).

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
_**DO NOT USE THE `preview` LAYER PROVIDED IN THE PSD!** That is provided
for **your** benefit when creating the icon. It should **not** be used for
the preview inside the issue._

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
If you find a problem like this or anything else, first [verify that an issue doesn't already
exist for your app](#verify-icon-hasnt-already-been-submitted). If it does, let us know what
has changed there.

If you cannot find an existing issue, _please open one_.  It's really easy!  Just
create something similar to [this](https://github.com/glasklart/hd/issues/3).

And thanks again for keeping Glasklart bug-free!
