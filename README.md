# pioneer_python_cli

==================

Barebones python command-line interface (CLI) for controlling an Internet-connected Pioneer AVR (Receiver/Amp).

Tested on a Pioneer SC-1222-K Amp.

Disclaimer: *Use at your own risk.*

## Usage:

1. Find out your AVR's IP address.
2. Run "python3 telnet.py <ipaddress>".

## Some commands:

- `up`              [volume up]
- `down1            [volume down]
- `<integer>`       [if positive, increase volume this number of times, capped at 5]
- `-<integer>`      [if negative, decrease volume this number of times]

- `<input_name>`    [switch to given input]
- `mode`            [cycle through stereo and surround audio modes]
- `status`          [print status]

- Use control-D to exit.
