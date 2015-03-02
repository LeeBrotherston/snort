Background
==========

These rules pertain to injection and MiTM attempts on your network connection.

Initially the rules were derived from a project I undertook when I observed when my ISP deployed a system to conduct MiTM attacks against it's customers to inject corporate messaging into web pages (more detail on this can be found at: http://blog.squarelemon.com/blog/2014/10/29/corporation-in-the-middle/ (SecTor) and http://blog.squarelemon.com/blog/2014/12/29/bsides-toronto-video-and-slides/ (BSides Toronto))

Although these rules were derived from a specific attack type used by my ISP, I have attempted to write them generically so that they can apply to other implementations of MiTM attacks (with one notable exception, which is specific to the product being used - however this device is in wide deployment so it is probably still a valid rule).

Since then however this started to grow as I discover other interception techniques for which snort/suricata rules can be written.  This now includes rules for Superfish (http://blog.squarelemon.com/blog/2015/02/20/superfish-detection/) and Privdog (http://blog.squarelemon.com/blog/2015/02/23/privdog-detection/)

Feedback
========

These rules are written based on my personal observations an deployments.  Feedback from others who deploy these rules (both positive and negative) can help to improve them.  I can improve against false positives and can mark rules as "good" with validation from others.  Please feel free to give me feedback either via github or twitter (https://twitter.com/synackpse).
