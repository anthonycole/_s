Old Fashioned
===

Background
---
I've just started a new job at an agency and I've been looking around at different starter themes for WordPress. I need something that works for me and effectively allows me to cut down on my dev time and does things that I would normally do anyways.

My reasoning for forking _s by Automattic is that it is basic, doesn't really do anything funny, and just works. On top of that, I'm probably not opinionated enough to do my own markup yet. 

TL;DR - I want to make Forge (https://github.com/thethemefoundry/forge) for rapid build times. I don't want to over-railsify and over-complicate this. I  want to just build things faster.

Nice to haves.
---
- Forking _s by Automattic. It is basic, doesn't really do anything funny, and just works. I'm probably not opinionated enough to do my own markup yet.
- Introduce sass - with bourbon and neat as submodules - bourbon has awesome mixins, and neat has a grid framework that will make responsive stuff totes awes.
- Eventually possibly introducing coffeescript. Nothing is too insane with what we're working on to do with javascript, so this 
might not ever happen. 
- It would be totes awes to have an auto-minifcation gem or script in here as well as something that auto-compiled scss. I'm shite - at ruby, so I might take initiative to learn something here as I'm not a fan of the php stuff available for SCSS.

What I've done 
---
- Forked _s and modified namespaces.
- Included neat and bourbon

External Assets Used
---
- Bourbon - http://bourbon.io/
- Neat - http://neat.bourbon.io/

Planned Introductions
---
- Advanced Custom Fields (http://www.advancedcustomfields.com/)
- Typeplate (http://typeplate.com/)
- font-awesome (http://fontawesome.github.io/)
- web-fonts.scss (https://github.com/rosspenman/web-fonts.scss) - Awesome google fonts.
- A custom function for handling asset URLs

Todo
---
- More cleanup and removing things I deem unnecessary
- Modifying the markup in _s to allow for responsive breakpoints and mixing neat in.
- Adding a few templates - a ton of the designs that I've seen coming through, for instance, require an image grid. 
- Using composer to include advanced custom fields and maybe a few other nice-to-have plugins.
- Structure assets library like this - http://thesassway.com/beginner/how-to-structure-a-sass-project

What I want to focus on
---
- Making sure our build process becomes faster and therefore making a case my boss that using ThemeForest themes for everything 
isn't the best solution in the world
- Having theme options for minor layout changes.

What I want to not happen.
---
- Not having options for theme colours or logos or unenecessary things. I hate theme options unless they're completely necessary.
- Not having shortcodes. Shortcodes are evil. Well, maybe not. But I don't like shortcodes. 
- Not creating some rockstar theme that does everything. I want to build something that works well in an agency context.
- Not making this the most undeniably hipster-new-tech theme ever. Focus on getting things done. 

Conventions I'd like to follow
---
- BEM - to a degree. I'm probably going to mess this up the first time, but I think it should be best practice. A drop in library for different components or aspects of the site would be awesome
- https://github.com/csswizardry/CSS-Guidelines - should be followed. I think I'll add some hooks in here and there.