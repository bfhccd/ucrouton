# ucrouton
A Crouton Linux update script

## How to run this script
To update your chroot, first download the most recent [crouton file](https://goo.gl/fd3zc "crouton file") to your Chrome OS Downloads directory. Then open the [Chrome OS Shell](https://software.intel.com/en-us/blogs/2014/08/18/two-simple-ways-to-get-to-the-chrome-os-shell) and from your Downloads directory, run the command ``` sh ucrouton chrootname ```,
where chrootname is the name of your chroot. Some examples are trusty, xenial and stretch. Check [Crouton's documentation](https://github.com/dnschneid/crouton) for details.
You may issue arguments to update multiple chroots, like this ``` sh ucrouton trusty xenial ```.
