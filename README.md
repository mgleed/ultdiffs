# ultdiffs

`diff`'s in HTML format for Smash Ultimate patches. 

I decompile the NRO character files, reference each character's motion_list.bin file, and parse the output to be readable.

Some functions may not be available for every character. I do not guarantee these diff files are comprehensive, but nearly all relevant frame/hitbox data should be included.

I've attempted to add commentary with `;`, and lines with `realFrame` are where I've attempted to compute realtime frames. Some of these may be broken, so be sure to check. Hopefully will be improved in the future. 

In 2.0.0, some functions were introduced that altered how some data is referenced. Many hitbox parameters, for example, may have previously had integers or decimals replaced with `?`. These should hopefully also be fixed in the future.
