## CJKV Glyph Collection

This is a subproject of [Smaji CJKV](https://cjkv.smaji.org).

This repository is a collection of cjkv glyphs. The glyphs, after being encoded (assigned with a unicode compatible code), form a glyph library.

Based on this glyph library, a glyph info database is assembled, font files are generated and synchronized among users of this project.

Together with other subprojects, we resolve a long-standing issue, bridge the abyss between information interchange and professional publishing.


### Processing flow --- Add a new glyph

1.  create an issue and provide necessary information as described in step 2 and 3, collaborators will help submit a pull request for you

2.  upload the image of the glyph
    - You have basic image editing skills:
        -   preprocess the image:
        -   image is denosied
        -   the aspect ratio is 1:1
        -   the minimum size of the image is 256x256
        -   the format of the image
            - raster image: jpeg, bmp, png, netpbm; the color range of the image is bitmap(0-1 white & black) or graymap(0-255 or 0-65535 gray scale)
            - vector image: svg; the color range of the image is bitmap(0-1 white & black)

    -   You are not familiar with any image editors:
        -   wait for the collaborators to preprocess the image

3.  provide basic information of the glyph
    -   required:
        -   the source of the glyph
        -   whether the glyph is a variation of an already included character
        -   whether the glyph is a new character which has not included yet
    -   optional:
        -   input method code of zhengma, cangjie5 or other input method, collaborators will help submit a pull request in the [cjkv\_input\_method\_collection](https://github.com/smaji-org/cjkv_input_method_collection) repository
        -   other information

4.  the cjkv bot will verify the glyph with the glyph library and output recognization result as auxiliary information

5.  collaborators will verify the glyph manually

6.  discussing and modification

7.  assign a unicode compatible encoding and submit a pull request

8.  review and merge the pull request

### Processing flow --- Alter an existing glyph

1.  submit a pull request if all the requirements mentioned above are satisfied; or create an issue and provide necessary information, collaborators will help submit a pull request for you

2.  the cjkv bot will verify the glyph with the glyph library and output recognization result as auxiliary information

3.  collaborators will verify the glyph manually

4.  discussing and modification

5.  merge the pull request

### Processing flow --- Other issues

1. create an issue and let us know your suggestions or questions

