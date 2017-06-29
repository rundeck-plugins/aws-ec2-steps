Simple wrapper around [aws ec2 CLI](http://docs.aws.amazon.com/cli/latest/reference/ec2/) to expose subcommands as node steps.

The following steps are available:

* describe-instance-status (http://docs.aws.amazon.com/cli/latest/reference/ec2/describe-instance-status.html)
* start-instances (http://docs.aws.amazon.com/cli/latest/reference/ec2/start-instances.html)
* stop-instances (http://docs.aws.amazon.com/cli/latest/reference/ec2/stop-instances.html)


To build the plugin:

    zip -r aws-ec2-steps.zip aws-ec2-steps

To install the plugin:

    cp aws-ec2-steps.zip $RDECK_BASE/libext
    
## Example Job
