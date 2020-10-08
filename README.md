This is a fork of Reverse Subtitles Punctuation from BuSHari (origanlly created by Asaf) with some tweaks to reverse Arabic subtitles without parentheses.


# Reverse Arabic Subtitles Punctuation

This project is a small python script for reversing the punctuation of an Arabic SRT subtitle. It is based on the Subtitle Workshop 2.61 feature with the same capabilities and Subtitle Edit.

## Motivation

Some streaming devices read arabic with RTL fine like my Playstation 4, but a because a lot of arabic subtitles are old-fashioned with reverse punctuation. it doesn't work with PS4, so a reverse needed.

And, they don't use RIGHT-TO-LEFT EMBEDDING Control Character (U+202B) which solve the language problems in all device that support UTF-8.
Sometimes the Arabic subtiltes have the parentheses in corect order but the other characters are reversed, so we need to reverse every special characters but the parentheses.
Subtitle Edit has a reverse punctuation feature, but it reverse every special character, this script will not reverse the parentheses.

## Installation & Usage

1. Install Python, 3 or above, in case you don't have it yet.
2. run:
    ```sh
    $ python rev.py <SRT_FILE>
    ```
3. If you want to create Context-Menu shortcut, run create_registry_file.py and run add_to_reg.reg. Note: this will only work on windows and if you not move the rev.py file. Run the create_registry_file.py at your final folder. Also, you still need python installed.

## History

no version yet :(

## License

See LICENCE file
