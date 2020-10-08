This is a fork of Reverse Subtitles Punctuation from BuSHari with some tweaks to work with Arabic subtitles in utf-8 form...


# Arabic Reverse Subtitles Punctuation

This project is a small python script for reversing the punctuation of an Arabic SRT subtitle. It is based on the Subtitle Workshop 2.61 feature with the same capabilities.

## Motivation

When I use any media streamer to stream movies to my TV, usually the Hebrew subtitles have reversed puncuation. This is due RTL nature of the hebrew language. This can drive me crazy, but than again, it is not easy to support RTL languages.

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
