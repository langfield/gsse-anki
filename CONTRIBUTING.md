# Standardisation and collaboration protocols

## Tag structure
- Structure tags as follows: `GSSE::{{discipline}}::{{chapter}}::{{subsections}}` e.g. `GSSE::Anatomy::Introduction_to_regional_anatomy::1._Tissues_and_structures::Bone::Development`. Should mirror the idea of a breadcrumb trail
- If you are tagging cards by [syllabus yield](https://www.surgeons.org/-/media/Project/RACS/surgeons-org/files/exams/gsse/cur_2011-08-09_anatomy_syllabus_final_for_web.pdf?rev=f1f590a3c92546f6bcdbc9f6ad9d2245&hash=018DB58536FCBF515DD4066F84C4BC4E), use this schema: `GSSE::!YieldLevel::{{YieldCategory}}`, replacing `{{YieldCategory}}` with `Essential` (for +++), `Desirable` (for ++) or `NonCore` (for +)

## Card types and note models
- Use the following note models for each basic type. Make them however you want but ensure that you convert the type before exporting to me.
    - Basic: (doesn't matter, shouldn't use these if possible)
    - Cloze: `Cloze-chrisc-ff04e`
    - Image Occlusion: (doesn't matter)
    - Cloze Overlapper: `Cloze (overlapping)-chrisc`
- Why these types specifically?
    - The types with my name on them have leech highlighting and clickable tags built in to the template (you still need to download the [Clickable Tags](https://ankiweb.net/shared/info/1739176371) addon ofc...)
    - I didn't consider this enough of a problem for Image Occlusions which is why I haven't developed similar templates for them
    
## Before sending final products to me
- It's generally better (and faster) to make cards for the entirety of Last's and tag each card by yield either afterwards or during the process, rather than omitting content based on yield. A recurring theme throughout later medical training is recalling earlier stages of it, and this also applies to using Last's for subspecialised exams - more detail on this rationale is given in the [FAQ](./faq.md).
- Do a self-audit first. Make sure all the cards are S20 compliant as per the [style guide](https://newageoflight.github.io/gsse-anki/style-guide/) and the already-audited cards in the deck.
- Tag your cards! Follow the scheme I've already outlined.

## Export settings
- If you're not confident with Git or Github, I'd prefer you export an APKG and send it to me for integration. Nonetheless, I still encourage everyone to learn.
- If exporting an APKG: make sure you uncheck "Include scheduling information". We aren't learning in sync so this is unnecessary.
- If exporting to CrowdAnki:
    - ALWAYS integrate the changes from the latest commit first! Import the CrowdAnki folder into your Anki.
    - Once you are sure you have, select the parent folder (i.e. the `gsse-anki` repository) and export here! Don't export into the `Anki_for_GSSE` deck folder otherwise you'll get a deck inside a deck

## The absolute basics of using Git, Github and Github Desktop
VIDEO TUTORIAL COMING SOON

### Resources
- A short introduction to [Git in 100 seconds](https://www.youtube.com/watch?v=hwP7WQkmECE)
- Get a feel for the basics of Git using [this tutorial](https://guides.github.com/activities/hello-world/)
- I highly recommend you learn the [basic vocabulary of Git](https://guides.github.com/introduction/git-handbook/)
- [Other good resources made by Github](https://try.github.io/)
