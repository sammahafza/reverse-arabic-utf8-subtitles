This is a fork of Reverse Subtitles Punctuation from BuSHari with some tweaks to work with Arabic subtitles in utf-8 form...


# Reverse Arabic Subtitles Punctuation

This project is a small python script for reversing the punctuation of an Arabic SRT subtitle. It is based on the Subtitle Workshop 2.61 feature with the same capabilities.

## Motivation

Subtitle Workshop has a reverse punctuation feature, but it's only works correctly in Windows-1256 (ANSI) and not in UTF-8. Becuase in UTF-8 we don't need to swap brackets, only other symbols.

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
