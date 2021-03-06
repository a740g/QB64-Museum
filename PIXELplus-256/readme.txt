
I, Chris Chadwick, first released PIXELplus 256 as shareware back in 1995.
It's likely that you have never heard of it before as at the time I was
not on the Internet, and so could only distribute it through a shareware
library, here in the UK.

"Why not try and sell it now, using the Internet?", you maybe asking.
Well, I'm (now) not sure there would be a big enough market for such a
product, although maybe I'm wrong. I've seen several other *similar*
products available FREE on the Internet <sound of a sinking heart!>,
so there would be little point, I think, charging for mine! Besides,
I myself use several FREEWARE products from other authors, which I
find *very* useful, so I figure, why not try and give something back? :)

Since getting on the Internet I have noticed there is still a large
interest in programming with QBASIC, QuickBASIC etc., and have read
several newsgroup postings asking how bitmapped graphics can be
implemented into peoples programs. I, therefore, have decided to
release PIXELplus 256 as FREEWARE in the hope that some/many people find a
use for this application, which took me a very long time to develop
(two years, during which time it had many changes and tweaks!).

***** PIXELplus 256 is now FREEWARE, as of 9th October, 1997 *****
You are free to use and distribute it in any way you see fit, on the
condition NO CHARGE is made for any part of the entire PIXELplus 256 package.
Also, please DO NOT try to pass off anything (including the example graphics
provided) contained in the PIXELplus 256 package as your own work (as if
you would ;) . Please give credit where it's due: a simple mention in your
programs would be nice. I would also like to know what you think of
PIXELplus 256; to know someone is making use of something that took *MUCH*
effort to produce would be great! Send me a short e-mail, if you can find
the time, to:

chris.chadwick@dial.pipex.com  or  xjk18@dial.pipex.com

NOTE: please study the code in USERSUBS.BAS in order to find out how
to use the routines contained within it. All this information (and alot
more in 200 pages!) is contained within the PIXELplus 256 Users Manual,
which I sent to registered users. Unfortunately, there is no 'electronic'
version of this manual, so I can not include it as part of the FREEWARE
PIXELplus256 package - perhaps someone would like to type one up into a
*useable* text document!?.
However, I do still have *a few* manuals (which I also wrote and produced,
taking even MORE time) left over. If you feel you would like one (first
come, first served!), send me an e-mail, BUT I will have to make a charge
for them to cover costs etc. the amount being dependent on where you live,
for shipping reasons.

Disclaimer: You use PIXELplus 256 at your own risk. I, Chris Chadwick,
will take NO responsibility for any damage or loss of data etc. that
may be incurred by installing/using this software. As FREEWARE, I offer
no liability to provide maintenace of the software or technical support.

NOTE: Although PIXELplus 256 is FREEWARE, I still hold the copyright on
the ENTIRE PIXELplus 256 package, and I DO NOT relinquish this copyright.
I have simply decided to allow anyone to use the package, for no charge.

The following document was provided with the shareware version
of PIXELplus 256 to show how to get PIXELplus 256 graphics into peoples
programs etc...

-----------------------------------------------------------------------------

                   ***  PIXELplus 256 User Information  ***

                    PIXELplus 256 - Shareware version 1.0
             Copyright (C)1995 Chris Chadwick (Somerset, England)
                             All rights reserved.

----------
 CONTENTS
----------

 1)  Overview
 2)  PIXELplus 256 Features
 3)  System Requirements
 4)  Files and Directories
 5)  PIXELplus 256 File Formats
 6)  Starting PIXELplus 256
 7)  Considerations for User's with Slower Machines
 8)  Setup Configuration Files
 9)  Working in BASIC
         - Using DATA Files
         - User Subroutines
         - Adding the User Subroutines to Your Own BASIC Programs
         - Adding the User Subroutines to Existing QuickBASIC &
           VB for MS-DOS Programs
         - Adding the User Subroutines to Existing QBASIC Programs
         - Initializing and Using Images, Palettes and Screen Designs
         - Using Image Array Index Listings
10)  Registering PIXELplus 256 (removed for FREEWARE version)


--------------
 1 - Overview
--------------

Although the BASIC programming language provides a way of
displaying bitmapped images via the PUT(graphics) statement,
the only way to actually design such images was by first using
simple graphics commands (LINE, PAINT, CIRCLE etc.), and then
using the GET(graphics) statement. PIXELplus 256 was produced
to solve this problem, allowing the easy (and fun) creation of
256 colour bitmapped graphics, specifically designed for use with
the PUT(graphics) statement.

PIXELplus 256 is a boon for any BASIC programmer who wants
to add colourful, bitmapped graphics to their own programs.
Using the advanced Image Editor, create sprites, icons,
character sets, animations or any other type of image you
require. The Screen Designer makes it easy to compose screen
layouts - game levels, title screens etc. - using images
created with the Image Editor.

Finished images and screen designs can be displayed in your
own programs that use BASIC screen mode 13 - the popular
320x200, 256 colour VGA graphics mode. A set of BASIC user
subroutines (USERSUBS.BAS) are also provided, making it easy
to incorporate PIXELplus 256 images, palettes and screen designs
into your own programs. BASIC's own PUT(graphics) statement is
used to display images, eliminating the need for non-BASIC library
routines. This makes it possible to use PIXELplus 256 images with
BASIC interpreters, such as QBASIC.


----------------------------
 2 - PIXELplus 256 Features
----------------------------

PIXELplus 256 supports many powerful features:

 ? Full mouse control with the easy-to-use Graphical User
   Interface.

 ? 18 Flexible Drawing Tools:
   Scissors, Paste Brush, Special Effects Brush, Flood Fill,
   Tile Fill, Gradient Fill, Paintbrush, Pixel Pointer,
   Air Brush, Eraser, Circle/Ellipse, Filled Circle/Ellipse,
   Gradient Circle/Ellipse, Box, Filled Box, Gradient Box,
   Line, Curve. Plus Colour Sampler (always available).

 ? 14 Special Effects:
   BRIGHT, DARK, TINT, FUR, MIX, SOFT, UNZAG, HOLLOW, TILE,
   XOR, GREY, SWEEP, SWAP, EDGE

 ? Multiple Zoom Levels: Great for doing detailed, close-up
   work. All Drawing Tools work at all zoom levels, too!

 ? Palette Tools: Giving full control over the colour palette.
   Alter individual colours, create colour gradients etc.

 ? Integrated Animation Tester: Now you can check images
   animate properly, while you're designing them.

 ? User-defined Gradient Styles: Design your own gradient styles
   to use with tools that use a colour gradient.

 ? Screen Designer: Makes composing screen layouts easy!
   Now there's no need to work out the actual screen
   coordinates where you want images displayed in your own
   programs.


-------------------------
 3 - System Requirements
-------------------------

To ensure PIXELplus 256 runs correctly, your computer should
conform to the following specifications:

 ? IBM or compatible PC. 386 or better recommended.

 ? 512K free conventional memory.

 ? VGA graphics card and colour monitor.

 ? Hard disk.

 ? Microsoft compatible mouse with up-to-date driver.


---------------------------
 4 - Files and Directories
---------------------------

Having installed PIXELplus 256 onto your hard disk, you will
notice that five subdirectories have been created within
the main PP256 directory. They are used to help keep the various
files created by PIXELplus 256 organized. The five
subdirectories and their usage is detailed below:

Subdirectory    Usage
------------    -----
  IMAGES        Contains all image files created with the
                Image Editor, including:
                ? Standard format image files which will
                  usually have the default .PUT file name
                  extension.
                ? Image files that have been saved as DATA in
                  ASCII text format which will usually have the
                  default .BAS file name extension.

  PALETTES      Holds all colour palette files. Files with
                a .APF (Associated Palette File) file name
                extension are palettes that belong to the
                specific image files of the same base name
                (e.g. SPRITES.APF would hold the palette for
                the images in file SPRITES.PUT). Palette
                files available for general use are also
                stored here and will usually have the
                default .PAL file name extension.

  SCREENS       Contains all screen design files created
                with the Screen Designer, including:
                ? Standard format screen design files which
                  will usually have the default .DES file
                  name extension.
                ? Screen design files that have been saved as DATA
                  in ASCII text format which will usually have the
                  default .BAS file name extension.
                ? Screen design files that have been saved in memory
                  image (screen snapshot) format which will usually
                  have the default .IMG file name extension.

  GRADS         Holds all the Image Editor gradient style
                files which will include 32 standard styles
                plus any user-defined styles. Note that
                gradient style files should not be renamed
                or deleted from DOS - unwanted user-defined
                gradient styles can be removed from within
                the Image Editor itself, while files with
                extensions from .000 to .031 are required
                for PIXELplus 256 to start.

  CLIPS         Contains all the Image Editor Clipboard files
                which will usually have the default .CLP file
                name extension.

Note: Do not rename or delete any of the above subdirectories
otherwise PIXELplus 256 will not start.


--------------------------------
 5 - PIXELplus 256 File Formats
--------------------------------

PIXELplus 256 produces image, palette and screen design files in
various formats. To help clarify the use of these files in your own
BASIC programs, the following table details the format of each file
type produced.

                Default   Subdirectory                                See
  File Type    Extension   Stored In             File Format          Note
-------------  ---------  ------------  ----------------------------  ----
Image            .PUT       IMAGES      BLOAD (7 byte header + data)   -
Image+Palette    .BAS       IMAGES      ASCII (BASIC source code)      1
Palette          .APF       PALETTES    Binary                         2
Palette          .PAL       PALETTES    Binary                         -
Screen Design    .DES       SCREENS     BLOAD (7 byte header + data)   -
Screen Design    .BAS       SCREENS     ASCII (BASIC source code)      -
Screen Design    .IMG       SCREENS     BLOAD (7 byte header + data)   3

Notes:
1) Image files that have been saved as BASIC DATA statements will
   only include a further set of DATA statements for the associated
   palette if the images use a non-standard palette.
2) .APF is a special palette file name extension used by PIXELplus 256
   to associate palette files to particular image files.
3) Screen designs that have been saved in this format are simply screen
   image snapshot files and don't contain individual screen design item data.

Note also that the Image Editor Clipboard files - stored in the CLIPS
subdirectory - are the same as standard (.PUT) images files except
that they only ever contain a single image.


----------------------------
 6 - Starting PIXELplus 256
----------------------------

First, make sure you're in the PIXELplus 256 main directory
by typing CD \PP256 followed by ENTER. If you installed
PIXELplus 256 to a different directory, simply substitute
\PP256 with the name of that directory.

Note that the Image Editor/Animation Tester and Screen Designer
are two separate programs (PP.EXE and SD.EXE respectively).
This makes it possible to start either program directly from
the DOS prompt, in addition to being able to invoke the Screen
Designer from within the Image Editor and vice versa.

The following table details how to start PIXELplus 256 from
the DOS prompt:

Enter this:             To do this:
-----------             -----------

    PP                  Start the PIXELplus 256 Image Editor.

    PP ImageFileName    Start the Image Editor and open the
                        image file specified by "ImageFileName".
                        This must be an existing image file
                        that resides in the IMAGES subdirectory.
                        If you don't specify an extension in
                        "ImageFileName" then the default for
                        image files (.PUT) is assumed.

    SD                  Start the Screen Designer. Once loaded,
                        you will be asked to specify an image
                        file to use with the Screen Designer.

    SD ImageFileName    Start the Screen Designer and load the
                        image file specified by "ImageFileName".
                        This must be an existing image file
                        that resides in the IMAGES subdirectory.
                        If you don't specify an extension in
                        "ImageFileName" then the default for
                        image files (.PUT) is assumed.

    DEMO                Run the demonstration program - just a
                        small example of what can be achieved
                        using PIXELplus 256. The image files
                        used by this demo are stored in the
                        IMAGES subdirectory and have a .DEM
                        file name extension - you can open and
                        view them from within the Image Editor.
                        However, renaming, deleting or significantly
                        altering any of these files will stop
                        the demo from running properly.


----------------------------------------------------
 7 - Considerations for User's with Slower Machines
----------------------------------------------------

User's running PIXELplus 256 on slower machines (386SX or
below) should note the following points and tips on
improving performance:

 ? Turn off the "Preview image" option when using the File/Load Clipboard...
   command in the Image Editor. This will sometimes enable
   you to select a file from the list box more quickly.

 ? Change the Drawing Tool view to outline mode. Do this by
   pressing SPACE, while pointing on the Edit Grid.

 ? When playing animations in the Animation Tester, the
   frame update is synchronized with the monitor in order
   to achieve smooth, flicker-free animation. However, in
   certain situations, flicker may occur or the animation
   may only be partially displayed, or even not visible at
   all. This is because your computer can't update each frame
   of the animation quickly enough to keep up with the monitor
   synchronization. Such problems will only usually occur if
   you are animating large images at high speed. Increasing
   the "Delay" or reducing the size of images will usually help
   alleviate any problems.

 ? Some internal operations may take a short time to complete,
   such as doing a large gradient fill. During this time, you
   may mistakenly think your computer has locked-up. In such
   cases, keep an eye on the Status Bar for messages telling
   you what's happening.


-------------------------------
 8 - Setup Configuration Files
-------------------------------

Both the Image Editor and the Screen Designer maintain a small
configuration setup file (PP256_ED.SET and PP256_SD.SET
respectively). This ensures certain features of PIXELplus 256
are kept at their latest setting, and are not reset to a
default every time you start PIXELplus 256. Information held
in these files includes Drawing Tool set up status, View menu
option settings and the various special effect, Air Brush and
brush strength values (used by Paintbrush, Line, Box etc.).
The latest Image Editor Clipboard image is also maintained in
a file called CLIPBRD.CLP.

Tip: If you want to reset the Image Editor or the Screen Designer
to their default settings, simply delete the appropriate setup
file from the DOS prompt before starting PIXELplus 256.


----------------------
 9 - Working in BASIC
----------------------

First of all, it should be noted that PIXELplus 256 produces files
specifically compatible for use with the more recent versions of
Microsoft BASIC: QBASIC, QuickBASIC and Visual BASIC for MS-DOS. Most
people will at least have QBASIC as this comes as part of the more
recent versions of MS-DOS. Also, the supplied user subroutine file,
USERSUBS.BAS (discussed later in this section), was written to be directly
compatible with QBASIC, QuickBASIC and Visual BASIC for MS-DOS - all
discussions in this section assume you will be working with one of these
versions of BASIC.

While all PIXELplus 256 files should be compatible with other dialects
of BASIC, you may need to manually add line numbers to files created with
the File/Save as DATA... command, as well as making other minor alterations
to USERSUBS.BAS. Even so, some older dialects of BASIC will not be compatible
for the simple reason that they do not provide access to VGA screen modes.

This section contains all the information you need to incorporate and use
images, palettes and screen designs in your own programs. If you are unsure
about the use of any BASIC statements or concepts used in this section,
consult your BASIC manual or your BASIC's online Help for an explanation.

Using DATA Files
----------------
Images and screen designs that have been saved as DATA need to
be incorporated into the module-level code of your program
before they can be used. The following list details several ways
this can be achieved when using QuickBASIC or Visual BASIC for
MS-DOS. QBASIC users may only use option 3:

 1) Use the $INCLUDE metacommand to have the required file included
    into the module-level code of your program.
 2) Load/Add the file to your program, then select and copy the
    required DATA statements. Next, paste the DATA statements at
    the desired position in the module-level code. Once this is
    done, unload the DATA file from your program.
 3) Load the file on it's own, then select and copy the required
    DATA statements. Next, open your program and paste the DATA
    statements at the desired position in the module-level code.

Note: There is a limit to the number of DATA items you can have in
the module-level code of your program. If you are using large
image/screen design files, you may have to initialize them from
the actual files (.PUT/.DES) themselves, instead of from DATA
statements. Details of this are given later in this section.

User Subroutines
----------------
The file USERSUBS.BAS is provided as part of PIXELplus 256 and
contains ready-written subroutines that allow images, palettes and
screen designs to be incorporated into your own programs.

Adding the User Subroutines to Your Own BASIC Programs
------------------------------------------------------
Before you can use the user subroutines, you need to make them part of
any program that you want to use them in. The easiest way to do this
is when you are starting a new program from scratch, as you can
simply load USERSUBS.BAS and then continue building your program
in the usual way. When doing so, remember to save your program under a
new name otherwise you might accidentally overwrite the original USERSUBS.BAS
file - in fact, it's probably a good idea to make a working copy of
USERSUBS.BAS in the directory you use when working in BASIC.

The way you can incorporate the user subroutines into your existing programs
depends on which version of BASIC you are working in:

Adding the User Subroutines to Existing QuickBASIC & VB for MS-DOS Programs
---------------------------------------------------------------------------
Incorporating the user subroutines into your existing QuickBASIC
and Visual BASIC for MS-DOS programs can be achieved easily as both
these versions of BASIC allow USERSUBS.BAS to be added directly to the
currently loaded program: in QuickBASIC, choose File/Load File...; in
Visual BASIC for MS-DOS, choose File/Add File... Doing so will add
USERSUBS.BAS as a separate module in your program. If necessary, you can
move the routines to different program modules in the usual way.

Adding the User Subroutines to Existing QBASIC Programs
-------------------------------------------------------
Adding the user subroutines to your existing QBASIC programs is a little
more complicated as QBASIC doesn't provide a way of directly adding
two program files together. However, the user subroutines can be
copied from USERSUBS.BAS - one at a time - and then pasted into your own
program code by following the procedure below:

 1) In QBASIC, open USERSUBS.BAS and move to a subroutine that you
    want to use in your own program.
 2) Select the entire routine code (from DEFINT A-Z to END SUB) and
    choose Edit/Copy.
 3) Open your program.
 4) Create a new (dummy) subroutine by selecting Edit/New SUB... and give
    it a meaningless name such as "xxx".
 5) Select the entire new routine code, then choose Edit/Paste. This will
    automatically replace the newly created subroutine with the one
    copied from USERSUBS.BAS.

Repeat all the above steps for every user subroutine you want to use in
your own program.

Note: Remember to copy the DesignType definition across if you are
going to use the screen design routines.

Initializing and Using Images, Palettes and Screen Designs
----------------------------------------------------------
Before you can use images, palettes and screen designs in your
own programs, the relevant data must be placed into arrays of an
appropriate data type - integer arrays for images, long integer
arrays for palettes and DesignType arrays for screen designs.
USERSUBS.BAS contains three subroutines to initialize arrays with
images, palettes and screen designs:

  SUB InitImageData (FileName$, ImageArray%())
  SUB InitPaletteData (FileName$, PaletteArray&())
  SUB InitDesignData (FileName$, DesignArray() AS DesignType)

All three subroutines require two parameters: the first, FileName$,
is the name of file to be loaded into the array - this must include
the path to the file if it does not reside in the current directory.
Alternatively, using an empty string ("") as the FileName$ parameter
will cause the required data to be read from module-level DATA statements.

The second parameter is an array of an appropriate data type. This array
must be initially created at module-level so that it can be passed to
the appropriate routine where it is set to the correct size and filled
with the required data. Consider the example module-level code below:

    SCREEN 13

    REDIM DemoImages%(1 TO 1)
    CALL InitImageData("C:\PP256\IMAGES\DEMO.PUT", DemoImages%())

    REDIM DemoPalette&(1 TO 1)
    CALL InitPaletteData("C:\PP256\PALETTES\DEMO.APF", DemoPalette&())

    REDIM DemoDesign(1 TO 1) AS DesignType
    RESTORE DesignData
    CALL InitDesignData("", DemoDesign())

Note: The initial SCREEN 13 statement selects the 320x200, 256 colour
VGA graphics mode. This is essential as PIXELplus 256 images, palettes
and screen designs can only be used when in this screen mode.

REDIM is used to ensure the created arrays are dynamic; REDIM SHARED
can be used instead if you want all other subroutines and functions in
your program to have access to the arrays. Alternatively, you can use
the SHARED statement in any subroutines/functions that you want to
have access to specific arrays.

Notice that the example code above shows how to initialize a screen design
array from module-level DATA statements (not shown) as opposed to
loading data directly from file. The RESTORE statement preceding
the CALL to InitDesignData ensures the correct DATA statements are
read; of course, the actual DATA statements must have previously
been incorporated into the program by using one of the methods detailed
in the above section, "Using DATA Files".

Continuing on from the above example, the next thing to do is change
the current colour palette to the one now held in the DemoPalette&
array - the associated colour palette needed to display the images held in
the DemoImages% array. This is achieved by using the following statement:

    PALETTE USING DemoPalette&

Now that the required colour palette is being used, we can display any
of the images held in the DemoImages% array - let's say it contains ten
images - by using the PUT(graphics) statement. For example:

    PUT (0, 0), DemoImages%(1), PSET

This displays the first image held in the DemoImages% array - the
first image in any image array always starts at subscript 1. However,
displaying any of the other nine images presents a problem as we
need to know the array subscript where they are stored. One way to
find the start subscript of each image is to print out an image array
index listing from the PIXELplus 256 Image Editor (see "Using Image Array
Index Listings" at the end of this section). Alternatively, we can
use another USERSUBS.BAS subroutine:

    SUB MakeImageIndex (ImageArray%(), IndexArray%())

The MakeImageIndex subroutine allows us to create an index array
that holds the start subscript of every image held in an image array.
The first parameter is the image array that you want to make an
index for. The second parameter is an integer array that is to be
used to hold the image index - again, this array must be initially
created at module-level so that it can be passed to the MakeImageIndex
routine:

    REDIM ImageNo%(1 to 1)
    CALL MakeImageIndex(DemoImages%(), ImageNo%())

Now we can display any of the ten images by specifying the index
number of the image, instead of having to specify the actual image
array subscript - ImageNo%(1) holds the start subscript for image 1,
ImageNo%(2) holds the start subscript for image 2 etc. The following
code would display all ten images:

    PUT (0, 0), DemoImages%(ImageNo%(1)), PSET
    PUT (10, 0), DemoImages%(ImageNo%(2)), PSET
    PUT (20, 0), DemoImages%(ImageNo%(3)), PSET
    PUT (30, 0), DemoImages%(ImageNo%(4)), PSET
    PUT (40, 0), DemoImages%(ImageNo%(5)), PSET
    PUT (50, 0), DemoImages%(ImageNo%(6)), PSET
    PUT (60, 0), DemoImages%(ImageNo%(7)), PSET
    PUT (70, 0), DemoImages%(ImageNo%(8)), PSET
    PUT (80, 0), DemoImages%(ImageNo%(9)), PSET
    PUT (90, 0), DemoImages%(ImageNo%(10)), PSET

Finally, to display the screen design held in the DemoDesign array,
we can use the following user subroutine:

    SUB DisplayDesign (DesignArray() AS DesignType, ImageArray%(), ImageIndex%(), ClsAction%)

The DisplayDesign subroutine requires four parameters: the first
is a DesignType array holding the screen design to be displayed;
the second is an integer array holding the images to be use for
displaying the screen design; the third is the image index array
for the images being used; the fourth is an integer value which
dictates whether or not the screen is cleared before the screen
design is displayed - any non-zero value causes the screen to be
cleared. So, to display the screen design, use:

    CALL DisplayDesign(DemoDesign(), DemoImages%(), ImageNo%(), 1)

Note that this example tells DisplayDesign to clear the screen
before displaying the screen design. However, using a value of zero
for the ClsAction% parameter allows you to overlay a screen design on
the existing screen image, or display more than one design on-screen
at the same time.

A design that has been saved as a screen snapshot - using the
File/Save as Screen... command in the Screen Designer - can be displayed
simply by loading it directly back to the screen using the BLOAD
statement. For example:

    BLOAD "C:\PP256\SCREENS\SNAPSHOT.IMG"

Note: If the screen snapshot you want to load uses a different palette
to the current one, remember to change to the required palette
beforehand, as previously explained. The required palette file will be
the one used by the images that were used to create the screen design.

Using Image Array Index Listings
--------------------------------
As explained earlier in this section, using the PUT(graphics) statement
to display an image requires that you specify the subscript of where
the image is stored, within the image array. As such, you can either
use an image index array (detailed above), or you can make use of an
image array index listing. The latter can be printed from within the
Image Editor by selecting File/Print Index..., when you have the required
image file loaded.

Among other things, an image array index listing shows the subscript
values required to display each and every image contained in the file
(or as many as you specified to be included on the listing). When using
the PUT(graphics) statement, you can either specify these values directly,
or, more usefully, you could assign them to constants in order to give
them more meaningful names. For example, if you had a file containing
images of all the pieces of a chess set, you could assign the relevant
subscript values to constants, as follows:

    CONST WHITEPAWN% = 1, WHITEROOK% = 131
    CONST WHITEKNIGHT% = 261, WHITEBISHOP% = 391
    CONST WHITEQUEEN% = 521, WHITEKING% = 651
    CONST BLACKPAWN% = 781, BLACKROOK% = 911
    CONST BLACKKNIGHT% = 1041, BLACKBISHOP% = 1171
    CONST BLACKQUEEN% = 1301, BLACKKING% = 1431

Now, displaying the image of any of the twelve chess pieces simply
involves specifying the required constant in a PUT(graphics) statement;
for example, to display the image of the white queen:

    PUT (32, 32), ChessImages%(WHITEQUEEN%), PSET

Space is provided on an image array index listing for you to supply
description/comments for each image, which you can write in as you view
the images in the Image Editor.

Other information contained on an image array index listing includes
the amount of memory used by each image, as well as their exact dimensions.



< end of text >
