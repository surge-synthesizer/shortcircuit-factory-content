# Factory Content for Shortcircuit XT

Yup, that's what it is!

Very soon, you will be able to get a beta build of Surge Synth Team's creative sampler Shortcircuit XT, which is very
exciting!
So what's this? Well, other SST synths come with factory patches bundled in the installer, but a sampler calls for a
slightly different strategy since a patch comes with, well, samples. We don't want to maintain a huge library of 3rd
party patches here, and be responsible for the licencing etc etc. But we do want to provide a small set of factory
content. Which in the interest of keeping the Shortcircuit XT installer reasonably small, will be provided by this repo
as a separate download.

## Contributing

So far there's not much here. But we do have a strategy we're converging on. Something like this:

- Make samples of your own in some way that ensures you have full rights to use them as you wish, and that you are
  willing to share under a CC0-licence. By submitting your samples here you are making them available under CC0
  in perpituity.
- Alternatively, use samples which already exist out there, and which are unambiguously* licenced in a way that permits
  free redistribution.
- Use those samples to make an interesting or useful or great-sounding shortcircuit part or multi.
- Submit those here, adhering to the folder structure described below.

* There must be absolutely no question about this. The Surge team are all volunteering their time to the project for
fun, and dealing with licence issues is very much the opposite of fun for most of us. So we would like all the samples
used here to be more explicitly licenced than "they said it's ok to use" or the like. A clear CC0 note or equivalent release 
from the sample author is required for a sample to be merged into this repo, and should be part of the submission.

If this all sounds great, and you're thinking you wanna prepare some very meticulously crafted parts/multis for
submission, that's great! Just please first come have a chat with the team about your intentions so we know we're on the
same page, no one else is working on the same idea, etc etc.

You can do that either by making an issue here or joining the [surge synth team discord](https://discord.gg/RcHTt5M55M)
and checking in, preferably in the #sc-content-sharing channel.

## The file structure

So, here's the plan:

- Make your part or multi locally
- Press "Save (Part-or-Multi) with collected samples"
- Go and find the resulting folder. You should have "YourThing.scp" or "YourThing.scm" and "YourThing Samples"
- If you want to work directly with git
   - fork this repo 
   - Take the .scp or .scm file and samples directory and copy it into YourFork/Content/Parts or /Multis respectively. 
     So you should have `Content/Parts/YourThing.scp" and "Content/Parts/YourThing Samples/..."
   - git commit on a branch and send a PR
 - If you dont want to work with git
   - hop into the #shortcircuit-content-sharing channel in our discord
   - Talk to us about how to share a zip containing the .scp/.scm and " Samples" directory with us
   - Then we will fork and merge as above. 

## Licensing

All the sample, scp, and scm files available here are licenced under
the [CC0](https://creativecommons.org/public-domain/cc0/)-licence.  
