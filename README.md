# Audiocube Overtone Demos

Simple examples demonstrating how the device handling library for Percussa Audiocubes can be used to control Overtone based instruments and effects.

Currently requires the 0.1.2-SNAPSHOT version of the audiocube library at https://github.com/tomoinn/overtone.device.audiocubes

Examples require an Audiocube / OSC bridge server running sending messages to localhost:7000 and receiving on port 8000, this can be launched with e.g. `acosc.exe 127.0.0.1 7000 8000`