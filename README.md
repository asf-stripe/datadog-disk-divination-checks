# Some disk metrics plugins for the datadog agent

I kinda want to know about the health of my home system, so I wrote
these checks. They kinda measure the right thing for the disks that
I'm running, but your requirements may differ, so please use with
caution, and evaluate what metrics and values make sense for your 
setup!

Also, these checks rely on `sudo`, so you will need a sudoers file.
One is provided in examples/.
