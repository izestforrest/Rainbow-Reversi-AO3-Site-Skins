# Reversi Base
This is the original Reversi color palette, but with all of my CSS edits applied.
> [!NOTE]
> This page is still in progress
#### Palette
From original: #333, #222, #2a2a2a, #555, #232323, #5998e6, #111, #eee, #fff, #F2EFEC
Added colors: #ccc, #2e2e2e, #303030, #2b2b2b, #262626

*Note: swapped the action borders and (darker) box-shadow colors with each other. Box-shadow in main is #232323 with a border of #2a2a2a, which doesn’t look good because the border is lighter than the inset shadow. Also swapped various other #000, #111, #222 with each other, or with #2a2a2a.


text color: #eee
link, .current color: #fff
main bkg: #333
actions border: #222
.mce-container: #F2EFEC

Changing:
actions border #2a2a2a L(16.5%) --> #222 L(13.3%)
fieldset bkg #2a2a2a L(16.5%)
hover color/bkg* #111/#000 L(6.7%)--> #2a2a2a L(16.5%)
actions bkg #555 L(33.3%)
actions box-shadow inset #232323 L(13.7%)
accent (works, hover, required) #5998D6 SL(60.4%, 59.4%)--> #D65E89 SL(59.4%, 60.4%)
span.question border #2a547c --> currentcolor
visited links, announcement stuff #999/#666 -> #CCC L(80%)
form required, span count color--> #CCC L(80%)
box-shadow: #000 -> #111 L(6.7%)
border-color #222 L(13.3%)--> #111 L(6.7%)
header, footer border--> #111 L(6.7%)
textarea, input--> #2e2e2e L(18%)
header, footer design--> #303030 L(19%)
header, footer bkg --> #2b2b2b L(17%)
header .primary bkg--> #262626 L(15%)
select, option bkg-> #CCC
select, option color-> #262626

*dropdown hover bkg, link hover color, .current color #111 L(6.7%) --> #2a2a2a L(16.5%)
.current bkg #000 --> #2a2a2a L(16.5%)
url("/images/skins/textures/tiles/black-noise.jpg") --> linear-gradient(#555, #2b2b2b)

## Changes
At some point, I plan to have a list of all of my changes here in this README. For now, all my changes can be viewed in the code, which is separated into 5 sections:

- Base code (revisions will be marked by a comment)
- General Site fixes
- Mobile-specific fixes
- Reversi fixes
- Personalization

Each section will be in comments - `/*CSS comments look like this*/`
