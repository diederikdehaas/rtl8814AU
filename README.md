# rtl8814AU

It looks like the fine people over at `aircrack-ng` have a rtl8814AU repo:
https://github.com/aircrack-ng/rtl8814au

They know what they're doing and seem to properly maintain them :)  
You should use that one instead of this repo.

## previous contents:

This repository contains a driver for the rtl8814AU chipset.  

The original downloaded archive indicated that kernels till version 5.1 are supported.  
With some adjustments I've made it work till 5.5, but it fails to compile against 5.6 (on Debian).

I don't have a device with this chipset, just happen to stumble upon the driver.  
That is one of the reasons I have no intention of spending time on it.  

You're of course free to use it, fork it and all the other freedoms granted to you by the [LICENSE](LICENSE).  
But don't expect me to spend time on it.

The best you (all) can do is:
- find someone who is willing and capable to maintain a repo for the 8814AU chipset
- create a community repo where you pool resources together to make the best of it. You're free to use anything from this repo to achieve that.

This is nothing personal or something like that.
My time is limited and maintaining this/a driver repo is not the best use of my time. I'm not dumb, but I'm not a C coder, let alone a kernel hacker.
