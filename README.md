# PhotoPicker
Private image picker. Allow your users to select photo without giving access to Photo Library.

When performing trivial action like attaching media to a post or picking 
profile picture, user needs to select image. This is simple and private on the 
web but very different on the App Store.

Problem I see is that many apps on the App Store refuse to use system 
`UIImagePicker` and instead ask users for full access to their Photo Library. 

Not only it's unnecessary extra step, but also often users need to navigate through 
custom buggy and slow interface, and they have to trust app maker with all 
their photos. As we know, every image contains GPS coordinates which means full
location history.

Often this can be avoided with pasting image, but sometimes the only truly private 
way to upload single image is using Safari.

![Screenshot with image placeholder and button][1]

This proof of concept demonstrates how easy is to use native `UIImagePicker`.

[1]: ui.png