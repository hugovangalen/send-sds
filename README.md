Forked from [bsl/send-sds][1].

libmidisds is a command-line tool intended for interfacing
your Linux system with devices supporting the MIDI
Sample Dump Standard.

### Dependencies
* gcc
* make
* libasound
* libsndfile

### Commmand Line Interface
    $ midi-sds -l
    Dir Device    Name
    IO  hw:1,0,0  Elektron TM-1 MIDI 1

    $ midi-sds send hw:1,0,0 sample.{wav,flac,aiff,sds,...}

[1]: http://github.com/bsl/send-sds/
[2]: http://www.mega-nerd.com/libsndfile/
