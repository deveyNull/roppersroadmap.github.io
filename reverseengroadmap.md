---
layout: page
title: Reverse Engineering Roadmap
permalink: roadmap/reverseEngineering
---

# How to Learn Reverse Engineering 

This is the first step of our reverse engineering roadmap. Roppers exists to make the next generation of RE devs, so this is an important part of the site that is constantly in motion.

After years of trying to teach students and trying to teach ourselves, we came up with a curriculum to learn C, Assembly, debugging, and reverse-engineering all at the same time. It is a lot of work, but is the best way to learn out there.

1. Finish the h0mbre C course as described : [here](roadmap/C)
2. Once you have finished that course, begin <https://github.com/hoppersroppers/nightmare>
   * The Nightmare course is our main binary exploitation track, but the first 4 chapters are about learning the tools and RE. Work throught the first 4 sections until you get to the overflows section, then come on back to RE. 
3. Now we work back through h0mbre C using GDB and Ghidra for every assignment. This takes a while, but is a really good way to get familar with how to do Linux reverse engineering and become comfortable with disassembly.

RE is all about reps and sets on really hard problems, so just get comfortable then start ripping CTF challenges until you are very very good at what you do.
## Malware RE

No question asked, the best free resource to learn Malware RE is from Azeria. 

1. https://malwareunicorn.org/workshops/re101.html#0
2. https://malwareunicorn.org/workshops/re102.html#0

After that, just start playing with real samples.

## Arm Resources

If you are trying to learn ARM, complete all of this, and then use these resources to get your brain into ARM syntax mode:

* [Azeria Labs](https://azeria-labs.com/writing-arm-assembly-part-1/)
* <https://developer.arm.com/documentation/102438/0100/Learning-about-the-instruction-set>

<hr>

<!--Mail chimp newsletter subscription-->
<div id="mc_embed_signup">
    <form action="https://gmail.us5.list-manage.com/subscribe/post?u=4d03cc5db483966f7e0fe17cc&amp;id=8d9620c4b7" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
        <div id="mc_embed_signup_scroll">
	        <h2>Join 5000 other subscribers to get updates about our courses and our organization!</h2>
            <div class="mc-field-group">
                <label for="mce-EMAIL">Email Address : </label>
                <input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL" style="width: 300px; margin: 10px; padding: 10px; border: 1px solid #ccc; border-radius: 5px; font-size: 14px;">
            </div>
            <div id="mce-responses" class="clear"></div>
            <div class="response" id="mce-error-response" style="display:none"></div>
            <div class="response" id="mce-success-response" style="display:none"></div>
        </div>    
        <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
        <div style="position: absolute; left: -5000px;" aria-hidden="true">
            <input type="text" name="b_4d03cc5db483966f7e0fe17cc_8d9620c4b7" tabindex="-1" value="">
        </div>
        <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button" style="background-color: #B5C9E2; border: none; padding: 10px 20px; border-radius: 5px; font-size: 16px; cursor: pointer;"></div>
    </form>
</div>

<script type='text/javascript' src='//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js'>

</script>
<script type='text/javascript'>(function($) {window.fnames = new Array(); window.ftypes = new Array();fnames[0]='EMAIL';ftypes[0]='email';}(jQuery));var $mcj = jQuery.noConflict(true);</script>
<!--End mc_embed_signup-->
