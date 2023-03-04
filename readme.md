
# memory leaks
lots of these errors in the browser console
```
Opa has received 500 logs without a consumer - maybe you loaded Opa.js inside of an IFrame? The logs are now cleared to prevent memory leaking
Opa has received 500 logs without a consumer - maybe you loaded Opa.js inside of an IFrame? The logs are now cleared to prevent memory leaking
Opa has received 500 logs without a consumer - maybe you loaded Opa.js inside of an IFrame? The logs are now cleared to prevent memory leaking
```

the following gets logged in the console just before the deletion test
```
[9192:4856:0304/155223.542:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435864, max_buffer_size=268435456
[9192:4856:0304/155223.542:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435855, max_buffer_size=268435456
[9192:4856:0304/155223.542:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435838, max_buffer_size=268435456
[9192:4856:0304/155223.542:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435863, max_buffer_size=268435456
[9192:4856:0304/155223.542:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435854, max_buffer_size=268435456
[9192:4856:0304/155223.542:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435838, max_buffer_size=268435456
..
192:4856:0304/155223.544:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435838, max_buffer_size=268435456
[9192:4856:0304/155223.544:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435863, max_buffer_size=268435456
[9192:4856:0304/155223.544:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435855, max_buffer_size=268435456
[9192:4856:0304/155223.544:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435838, max_buffer_size=268435456
[9192:4856:0304/155223.544:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435863, max_buffer_size=268435456
[9192:4856:0304/155223.544:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435854, max_buffer_size=268435456
[9192:4856:0304/155223.544:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435971, max_buffer_size=268435456
[9192:4856:0304/155223.545:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435829, max_buffer_size=268435456
[9192:4856:0304/155223.545:ERROR:http_connection.cc(111)] Too large write data is pending: size=268435946, max_buffer_size=268435456
```