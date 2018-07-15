# PhotoPicker
Private image picker. Allow your users to select photo without giving access to Photo Library.

When performing trivial action like attaching media to a post or picking 
profile picture, user need to select image. This is simple and private on the web 
but very different on the App Store.

Problem I see is that many apps on the App Store refuse to use system 
`UIImagePicker` and instead ask users permission full access to their Photo Library. 

Not only it is unnecessary extra step but also often users need to navigate through 
custom often buggy and slow interface, and they have to trust app maker with all 
their photos. As we known every image contains GPS coordinates which means full
location history.

Often this can be avoided with pasting image, but sometimes the only truly private 
way to upload single image is using Safari.

This proof of concept demonstrates how easy is to use native `UIImagePicker`.