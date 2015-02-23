Background
==========

These rules pertain to injection attempts I observed when my ISP deployed a system to conduct MiTM attacks against it's customers to inject corporate messaging into web pages (more detail on this can be found at: http://blog.squarelemon.com/blog/2014/10/29/corporation-in-the-middle/ (SecTor) and http://blog.squarelemon.com/blog/2014/12/29/bsides-toronto-video-and-slides/ (BSides Toronto))

Although these rules were derived from a specific attack type used by my ISP, I have attempted to write them generically so that they can apply to other implementations of MiTM attacks (with one notable exception, which is specific to the product being used - however this device is in wide deployment so it is probably still a valid rule).

2015-02-20 : Updates to test new superfish detection.  For more information see: http://blog.squarelemon.com/blog/2015/02/20/superfish-detection/

2015-02-23 : Added rule (sid 1000005) to add PrivDog detection (same technique as SuperFish).
