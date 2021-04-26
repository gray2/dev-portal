# [Creative Web Dev Portal]

A basic collection of everything I worked on while taking my Creative Web Development Tools class this past semester (Spring 2021). The class was definitely challenging, but the collaborative aspects of it all made things more manageable.

* Homepage: [https://html5boilerplate.com/](https://html5boilerplate.com/)
* Source: [https://github.com/h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate)
* Twitter: [@h5bp](https://twitter.com/h5bp)

## Assignment Summaries

### Bash.ME
Getting introduced to working with the new format, our job was to make a basic introductory page using only the terminal and get it uploaded to the CU server. It's essentially a "Hello, World!"

### Commitment
Our job was to build a basic HTML site and get into the habit of committing our work to GitHub regularly. So, we had to make a page with a minimum of 100 commits to GitHub. We were given free reign over what we could make, so I made a "stream-of-consciousness" type of thing that I made up as I went along.

### Exquisite Corpse
The code editor we used in the class, Atom, has collaborative capabilities. So, our assignment was to work with a group of 2-3 other people to write a story in the typical "exquisite corpse" format while avoiding overwriting each other's work. My group and I wrote a simple sci-fi story.

### Parallax Narrative
This was by far one of the most challenging assignments we were given. We had to build a narrative that took advantage of parallax scrolling. I ended up having to restart my project over several times due to formatting issues, since the starter code was in a grid layout, and I'm much more accustomed to working with flexboxes. As a final addition, we were instructed to connect our site with Google Analytics and then share our finished work with as many people as possible.

### Custom HTML Boilerplate
This was probably my favorite assignment, since I love messing with HTML/CSS layouts. We were given the task of creating a custom HTML5 boilerplate that would act as a starting point for any and all future projects. Using SASS/SCSS instead of traditional CSS, the overall workflow is much more efficient, since you don't need to manually put in all of your stylings or functions. Everything from functions, to base layout, to customizations all has a separate .scss file, keeping everything organized. My boilerplate consists of a basic flexbox layout with the option to include parallax scrolling. There's everything you'd need for a simple site, from favicons to a 404 page.

### Google Analytics
Taking the data collected from the parallax narrative assignment, Google Analytics shows a basic overview of some trends in the demographics of people who visited or engaged with the site. I don't have much of a social media presence, but dropped the link into a few discord servers that I'm in. I only reached 36 people in total, but I don't really care about the numbers aspect of it. I'm more just happy that people saw something I made and were able to engage with it in some way. And hey, who doesn't love a good pancake recipe? 

### Creative Project
Our final project was to pick a library from the node.js modules and build just about whatever we wanted with it. Since this was my first time working with the node library, I picked the most commonly used modules - express and mongoose. My initial goal was to build a basic to-do list that had an option to sort the items in the list by the date or time they needed to be completed by. I was able to get the basic to-do list working and had it connected to a Mongo database, but getting the application to pull information from the database was much easier said than done.

Each time I tried to run the function to pull the date or time associated with an entry, the entire application would break. I tried remaking the function several times, but the mongoose "sort" function just refused to cooperate. Since I couldn't even get the id of an entry to be returned after several troubleshooting sessions and countless hours on stackoverflow, I decided to take a step back.

Even though I was unable to get my application to sort the tasks, I was still able to explore the capabilities of mongoose and express. Hopefully I can build my skills with the two further and maybe come back to this project at a later date!


## Browser support

* Chrome *(latest 2)*
* Edge *(latest 2)*
* Firefox *(latest 2)*
* Internet Explorer 11
* Opera *(latest 2)*
* Safari *(latest 2)*

*This doesn't mean that HTML5 Boilerplate cannot be used in older browsers,
just that we'll ensure compatibility with the ones mentioned above.*

If you need legacy browser support you can use [HTML5 Boilerplate v6](https://github.com/h5bp/html5-boilerplate/releases/tag/6.1.0) (IE9/IE10)
or [HTML5 Boilerplate v5](https://github.com/h5bp/html5-boilerplate/releases/tag/5.3.0)
(IE 8). They are no longer actively developed.

## Documentation

Take a look at the [documentation table of contents](dist/doc/TOC.md). This
documentation is bundled with the project which makes it available for offline
reading and provides a useful starting point for any documentation you want to
write about your project.

## Contributing

Hundreds of developers have helped to make the HTML5 Boilerplate. Anyone is
welcome to [contribute](.github/CONTRIBUTING.md), however, if you decide to get
involved, please take a moment to review the [guidelines](.github/CONTRIBUTING.md):

* [Bug reports](.github/CONTRIBUTING.md#bugs)
* [Feature requests](.github/CONTRIBUTING.md#features)
* [Pull requests](.github/CONTRIBUTING.md#pull-requests)

## Custom Additions
* Parallax layout
* SCSS + CSS formatting
* Custom icon + favicon
* Basic flexbox layout
* Simple color scheme that is easily editable

## License

The code is available under the [MIT license](LICENSE.txt).
