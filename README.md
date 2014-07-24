logstash-various
================

Various logstash import configs

These configs are all configured for stdin and for elasticsearch or stdout.

All files extract @timestamp from log lines, expecting them to be in UTC.

    $ cat file.log | logstash -f logstash-foo.conf

Please see the output{} section of the conf to configure the appropriate emitter.


