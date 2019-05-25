# Standardized Controls
A place to play around a little bit with controls to see if there is a better path forward

# Overview
We've begun doing research into the state of web platform controls. There were many things that I knew anectdotally
from my years of interactions with web developers. However, anectdotes don't inform the best path forward, so we've 
been digging deeper.

This repo will be used to **explore** some of the primary controls shipped by browsers and how we could do this in a standardized
manner (assuming this is possible). I'll continue to add buckets of issues, with sub-topics that have to be address in order
for us to see this to fruition.

# How it will work
We will take existing legacy controls and based on user feedback and testing we'll derive the top pain points to begin
addressing them with new modern variants that address the needs of web developers. As the pattern to bringing a new control
to the platform becomes more clear, I'll continue to update these steps.

Build each component with React, Vue, Angular, Lightning and web components. Detail what is missing. It would also be good to create an idealized version of what you would want the web components version to look like.

# Key pillars for a solid control that web developers will use
In discussions, customer & partner discussions, and surveys there are a few key aspects that we must deliver in order
for the native components and controls that the platform delivers to be heavily utilized.

* They need to be customizable
* Extensibility needs to be possible
* Behavior hook or adjustments needs to be possible
* State management across component, even in a composite component, is possible
* Expectation from developers that it "just works" (<-- we need to bring the magic back, even if built on primitives)
* Accessibilty, focus and other foundational items work as expected

# Controls to standardize (initial thinking)
**Note: This is not where controls or components will be standardized but will be the repo where the agreed upon solution will be stored**
* `<dropdown>` (modern replacement for select)
* `<file>` (modern replacement for input type="file")
* `<toggle>` (proposal from Google is [here](https://github.com/tkent-google/std-switch)

# Moving this to a standards body
Once I get buy in (actively working on this now) from other browser vendors, web developers, frameworks, design systems I'll
move this repo to the location that makes the most sense.