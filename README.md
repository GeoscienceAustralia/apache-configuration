# Elvis Apache Configuration #
This is the Apache configuration for all apps deployed to the Elvis server.

On the EC2 instance of choice, from the ec2-user account to get  this do:
`git clone https://github.com/Tomella/apache-configuration.git`

If you have it already installed, from the home directory:
`bash apache-configuration/source/deploy`

## What have I just done? ##
That's copied the configuration files from the config directory to the Apache server's configuration directory and restarted the HTTPD daemon.

That should set up the virtual hosts and the relevant proxying to get the applications running nicely. It did at the point in time that this was written.