# PassGen

A simple JavaScript function that generates a random password based on customizable rules — length, and which character sets to include (lowercase, uppercase, numbers, symbols).

## How It Works

`PassGen` builds a pool of allowed characters based on which options you enable, then randomly picks characters from that pool to build a password of the length you specify.

## Error Handling

- Returns a message if `length` is 0 or less.
- Returns a message if no character set is selected.

