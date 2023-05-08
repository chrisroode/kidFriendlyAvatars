
Kid Friendly Avatars

A simple repository of kid friendly avatar pics.

These line art paths were derived from the noto emoji font.
https://fonts.google.com/noto/specimen/Noto+Emoji

The purpose of this repository is to provide colorized images of multiple formats featuring a 1:1 aspect ratio circle icon image for user account avatars.

There is a need to protect identities of minors on educational sites.  This provides a safe way for students to customize their profile without publishing personal photographs, or potentially offensive material on their student profiles.  If you would like to contribute, please read the formatting guidelines, look at the template document, and then jump on in and start coloring!  it's fun, really it is!



Formatting Guidelines:

- /src folder shall contain subfolders for particular categories:
    - Animals
    - Sports
    - Activities
    - Performing Arts
    - Things That Go
    - Outdoors
    - Other
- /src/MasterTemplate.svg: Contains the base image with a clipping circle.  Image size is 512px by 512px.  clipping circle is 510x510 px.
    - There are collections of unused paths in this document that are hidden.  Open up the "layers and objects" tool in inkscape to browse through the emoji that still need to be implemented.

To make a new avatar:
1) Make a copy of MasterTemplate.svg in the appropriate folder, with the appropriate name.  If you are making a variation on an existing avatar, append "-01" to the file name...I.E. shark.svg exists, so add shark-01.svg instead of overwriting existing files.
2) Create your avatar:
    - Follow the existing aesthetic to match other avatars:
        - gentle low detail background with a subtle hint of setting.
        - maintain the solid contour lines provided by noto-emoji.
        - color transparent areas in solid colors.
4) Group the paths for the drawing into a group with the same name as the avatar.
5) Use the circle in the template to clip the group to draw within the circle.
6) Remove unused paths and objects from the new avatar.
7) Create a 512x512 png image in the dist folder with the same subfolder structure, and same file name.  



