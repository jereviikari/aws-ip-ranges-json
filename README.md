# AWS IP Ranges History Tracker
Amazon AWS provides a list of IP Addresses used by their various services. Specifically

 * CloudFront
 * EC2
 * Route53
 * S3

This live file is available directly from them [https://ip-ranges.amazonaws.com/ip-ranges.json](https://ip-ranges.amazonaws.com/ip-ranges.json), but they only provide the current listing, with no history of changes.

This Git repository tracks this file so that changes are easy to identify.  I've also split out the various services so that you can see the frequency of changes for each service.

Note that Amazon [does not recommend](https://forums.aws.amazon.com/ann.jspa?annID=2051) using this list for mission critical applications.  As such, this repository is *for informational purposes only*.


### AWS IP Ranges Resources

 * [ip-ranges.json](https://ip-ranges.amazonaws.com/ip-ranges.json) - live file
 * [AWS IP Address Ranges](http://docs.aws.amazon.com/general/latest/gr/aws-ip-ranges.html) - General Reference
 * [SNS Notification](https://aws.amazon.com/blogs/aws/subscribe-to-aws-public-ip-address-changes-via-amazon-sns/) - Subscribe to change notifications

