# S3 Error: The difference between the request time and the current time is too large

fatal error: An error occurred (RequestTimeTooSkewed) when calling the ListObjectsV2 operation: 
The difference between the request time and the current time is too large.

You need to update the time on the AWS server and Local machine. Best way to do is to run ntpdate command to sync time.

Solution:

`sudo ntpdate -u in.pool.ntp.org`