# 100 Days of Code Log

**Start Date** 25 Feb 2017

**End Date** ...

**Xtra Days to add** 2

**Inspiration** Many things, but basically I have a myriad of projects/ideas/things I would - and I'm currently trying - to learn and this became a nice little way to not only keep track of everything I'm doing but also to be accountable for it.

Thanks to this [post](https://medium.freecodecamp.com/join-the-100daysofcode-556ddb4579e4#.ykokqrmvf) for the idea, inspiration and motivation.


## Log

### Day 0: Feb 25. Saturday

**Today's Progress**: Spent time implementing styles and mockups in an Open Source Project I'm contributing on. Learn about Less, typography, mixin creation, and of course  `LESS`.

**Thoughts:** Feels good to be back at coding.

**Link to work:** Project is on pvt on github. But I'll be adding a gist or a `less-boilerplate` repo in the near future to keep track of my learning `less`. Until now, been using `css` and `scss/sass`.

<hr	/>

### Day 1: Feb 26. Sunday

**Today's Progress**: Finish the Splash Screen on the Open Source project I 'm contributing on. Reorganization of stylesheets in a component base structure. Using my [scss-boilerplate](https://github.com/dantesolis/scss-boilerplate) as starting point, but doing it in `Less`

**Thoughts:** Learning more about `flex`, `less` imports and `mixins`. Will be creating a `less-boilerplate` in the following days

**Link to work:** idem DAY-0

<hr	/>

### Day 2: Feb 27. Monday

**Today's Progress**: Worked on 30DaysOfJs flex panels. Setting up the project on codepen. Once it's done, I will create a simple site and make it life.
Also worked on logging my codewars kata completions. Check it at **DAILY-XTRA.md**

**Thoughts:** Learning about sass, styles, typography/fonts. Today was just the pen set up. Tomorrow begins the real work.

**Link to work:** [pen](https://codepen.io/intercoder/pen/KWpEow?editors=1100)

<hr	/>
 
### Day 3: Feb 28. Tuesday

**Today's Progress**: Working on 30DaysOfJs flex panels. Fixing some minor bugs and getting my panels to work and my text to center. Need to still work on it.

**Thoughts:** I actually learnt that when using transitions I can not only specify each individual property I want to change, but how I want it to change it. Before I just used to do `transition: all ...`

**Link to work:** [pen](https://codepen.io/intercoder/pen/KWpEow?editors=1100)

<hr	/>

### Day 4: March 1. Wednesday

**Today's Progress**: Today just had time worked on the [Day 4: March 1. Wednesday](DAILY-XTRA.md) kata.

**Thoughts:** Tired today, but will be adding an extra day to my log


<hr	/>


### Day 5: March 2. Thursday

**Today's Progress**: Almost done with the flex panels. Have a small little bug with toggling the `'open-active'` class and the function that calls it `toggleActive`.

**Thoughts:** Loving the `transitionend` and all other EventHandlers in Js both for messing with css and just all around. Events and it's props are becoming less frightening for me.

**Link to work:** [pen](https://codepen.io/intercoder/pen/KWpEow?editors=1100)

<hr	/>


### Day 6: March 3. Friday

**Today's Progress**: Finally fixed the bug with the transitions in the flex panels. Right now, just cleaning the codepen and the repo. But main parts finished. Just making sassy... Get it?

**Thoughts:** Need to find out more about how to add comments in `SASS`. Learnt about `evt.propertyName` to be able to see which transitions are strating/finishing when `transitionend` hits.

**Link to work:** [codepen]([pen](https://codepen.io/intercoder/pen/KWpEow?editors=1100)), [gh-repo](#)

<hr	/>


### Day 7: March 4. Saturday

**Today's Progress**: Worked on an Open "Source Project" (Stori-2). Implemented the signup page mock up in `Less`. Almost done, needs some work.

**Thoughts:** Not always easy to get styles exactly the way you want them. One thinks one knows flex well, but still have tons to learn. Although `flex` makes every thing easier.

**Link to work:** repo set to pvt

<hr	/>

### Day 7: March 5. Sunday

**Today's Progress**: Working through [Modern React with Redux](https://www.udemy.com/react-redux/learn/v4/overview) Udemy course by Stephen Grider

**Thoughts:** Learning about the difference between a 'factory' and an 'instance' of a class. This would come accross as basic to some, but I failed an interview question because of this. A [Medium post](https://medium.com/javascript-scene/javascript-factory-functions-vs-constructor-functions-vs-classes-2f22ceddf33e#.dggo1kfq7) about it.

**Link to work:** none at the moment

<hr	/>

### Day 8: March 6. Monday

**Today's Progress**: Finished implementing styles for the SignUp screen on Stori-2 (Open Source project) in less. Finished Section 1 of the [Modern React with Redux](https://www.udemy.com/react-redux/learn/v4/overview) Udemy course. Started Section 2.

**Thoughts:** Have to do a work-around on selecting the `::-webkit-input-placeholder` pseudo-class for changing the color of the text. Had created a `less` mixin but is not taking it. Need to debug it. 

**Link to work:** none at the moment

<hr	/>

### Day 9: March 7. Tuesday

**Today's Progress**: Finished Section 2 of the [Modern React with Redux](https://www.udemy.com/react-redux/learn/v4/overview) Udemy course. Finished React part of the course. Now to start on redux.

**Thoughts:** I love React and its "simplicity". I still get a bit confused when state and/or props are hand down from parent to child and/or with the use of callbacks from child to parent to handle state.

**Pros:** Better grasp on the difference between a 'functional component' (one that just takes data and displays it) vs. a 'class based component' (one which handles state).

**Cons:** Need to get better at handling states, props and event changes.

**Goal:** Will write used acquired knowledge to create a 1 page application that will display all of my simple js projects (cssvars, flexpanels, browser, fartkit, ...). **App must be ready and "live" by Day 14: March 12. Sunday**

**Link to work:** [link-to-work](#)

<hr	/>

### Day 10: March 8. Wednesday

**Today's Progress**: Finished Section 3 of the [Modern React with Redux](https://www.udemy.com/react-redux/learn/v4/overview) Udemy course. 

Installed `webpack for my new simple-js project **flexpanels**. CodePen and Link to follow in the next couple of days.

**Thoughts:** Learnt about redux. Also learnt about `git clone --depth <depth> -b <branch> <repo_url>` for cloning repos with no commit history.[SO](http://stackoverflow.com/questions/29368837/copy-a-git-repo-without-history) answer

**Link to work:** [flexpanel-repo](https://www.github/dantesolis/flexpanels)

<hr	/>

### Day 11: March 9. Thursday

**Today's Progress**: Added `webpack.config.js` to the flexpanels mini site. Thinking about changing the app completely into a mini react app. Need to debug the `webpack` error.

**Thoughts:** Having problems with the `webpack.config.js`, keep getting a `Invalid configuration object. Webpack has been initialised using a configuration object that does not match the API schema.- configuration.resolve.extensions[0] should not be empty.` error.

Learnt about `git rebase -i HEAD~my_commit_number` to be able to change a commit message after it has been pushed.

**Link to work:** [flexpanel-repo](https://github.com/dantesolis/flexpanels/tree/feature/webpack)

<hr	/>

### Day 12: March 10. Friday

**Today's Progress**: 

- Debugged my webpack error from Day 11 on the flex panels mini site. Can see it on my local machine.

- Section 1 & 2 of [Webpack 2: The Complete Developer's Guide](https://www.udemy.com/webpack-2-the-complete-developers-guide/learn/v4/content) Udemy Course. 

- Worked on the flexpanels mini site.

**Thoughts:** 

*@webpack:* Started with a google search of my error which took me [here](http://stackoverflow.com/questions/42060243/invalid-configuration-object-webpack-has-been-initialised-using-a-configuration). But this just gave me a new `webpack.config.js`, after some more searching came to this [here](https://webpack.js.org/configuration/resolve/#resolve-extensions), which shows me that `module.resolve.extensions: ['', '.js', '.jsx']` becomes `module.resolve.extensions: ['*', '.js', '.jsx']` in `webpack 2.x.x`.

**Link to work:** [flexpanel-repo](https://github.com/dantesolis/flexpanels/)


<hr	/>

### Day 13: March 11. Saturday

**Today's Progress**: Created the panels component. Passing style and additional content as props. 

**Thoughts:** Learning the difference on how to pass styles and content as `pops` between functional and class based components.

**Link to work:** [flexpanel-repo](https://github.com/dantesolis/flexpanels/tree/feature/panels-component)

<hr	/>

### Day 14: March 12. Sunday

**Today's Progress**:
- Created a footer component on the flexpanels mini site.
- Began Section 3 [Webpack 2: The Complete Developer's Guide](https://www.udemy.com/webpack-2-the-complete-developers-guide/learn/v4/content) Udemy Course.

**Thoughts:** About to apply styles into my React components, thinking about using cssvars. 

**Link to work:** [flexpanel-repo](https://github.com/dantesolis/flexpanels/tree/feature/panels-component)

<hr	/>

### Day 15: March 13. Monday

**Today's Progress**: - Continued working on Section 3 [Webpack 2: The Complete Developer's Guide](https://www.udemy.com/webpack-2-the-complete-developers-guide/learn/v4/content) Udemy Course.

**Thoughts:**
- Decided to push myself and use `css variables` for my css.
- Webpack is no longer as scary as I thought it would be or it was the first time I used it 6 months ago.

I'm using what I'm learning in this course to do another simple CSS &amp; JS simple site *famous **calculator** start project* that everyone begins with.

**Link to work:** [calculator-repo](https://github.com/dantesolis/calculator)

<hr	/>

### Day 16: March 14. Tuesday

**Today's Progress**: 
- Worked on Section 3 [Webpack 2: The Complete Developer's Guide](https://www.udemy.com/webpack-2-the-complete-developers-guide/learn/v4/content) Udemy Course. [calculator-repo](https://github.com/dantesolis/calculator)

**Thoughts:**
- Learnt a bit more about `npm peer dependencies` and how to debug errors after encountering a bug when installing one of the `node packages` that was not backwards compatible. Google if your friend.
- Helpful command to delete a file | folder mistakenly added to git `git rm -r --cached what_i_want_to_remove`. Have used it 5 - 6 times in the last year. Here is a [gist](https://gist.github.com/dantesolis/217118b096072e14b9c80733ba82d58e) with the instructions.

**Link to work:** See *Today's Progress*

<hr	/>

### Day 17: March 15. Wednesday

**Today's Progress**:
- Installed all `webpack loaders` that handle my stylesheets in the project.
- Created roadmap for 2017. Will pushing to github in the next couple of days. 

**Thoughts:** Today was a brainstorming day.

**Link to work:** None

<hr	/>

### Day 18: March 16. Thursday

**Today's Progress**:
- Finished Section 3 of [Webpack 2: The Complete Developer's Guide](https://www.udemy.com/webpack-2-the-complete-developers-guide/learn/v4/content) Udemy Course. [calculator-repo](https://github.com/dantesolis/calculator).
- Set up style loaders, but getting a `webpack compile error` from the `main.sass` file. Perhaps sass file not properly passing through the loader?



**Thoughts:** Experimenting with `css grids` module and `css-vars` on the calculator project I'm creating as I follow this course. Link to work [flexpanels-repo/sass-loader](https://github.com/dantesolis/flexpanels/tree/feature/sass-loader)

**Link to work:** [calculator-repo](https://github.com/dantesolis/calculator)

<hr	/>

### Day 19: March 17. Friday

**Today's Progress**:
- Worked on flexpanels and fixed the `BUG` from **Day 18**; turns out I had forgotten to run `webpack` for compilation 🙃. This solved the bug, but presented another issue: *App is not autoreloading after compilation?* [flexpanels-repo](https://github.com/dantesolis/flexpanels).
- Started Section 4 of [Webpack 2: The Complete Developer's Guide](https://www.udemy.com/webpack-2-the-complete-developers-guide/learn/v4/content) Udemy Course. [calculator-repo](https://github.com/dantesolis/calculator).

**Thoughts:** Sometimes the bugs are just the silliest things to solve (flexpanels). Nothing like stepping a way from the problem a bit and then coming back with a fresh mind.

**Link to work:** See *Today's Progress*

<hr	/>

### Day 20: March 18. Saturday

**Today's Progress**: 
- Fixed the *App is not autoreloading after compilation?* error I was having on 👆*Day 19*. Problem was with the `publicPath` in the `webpack.config.js` file; changed it from `publicPath: '/'` to `publicPath: '/build'` to hit the `bundle.js` and `styles.css`. [flexpanels-repo](https://github.com/dantesolis/flexpanels).
- Finished Section 4 and started Section 5 on [Webpack 2: The Complete Developer's Guide](https://www.udemy.com/webpack-2-the-complete-developers-guide/learn/v4/content) Udemy Course. [calculator-repo](https://github.com/dantesolis/calculator).

**Thoughts:** Small bugs like this is what drive you nots. 

**Link to work:** See *Today's Progress*

<hr	/>

### Day 21: ...

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

<hr	/>

### Day 22: ...

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

<hr	/>

### Day 23: ...

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

<hr	/>

### Day 24: ...

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

<hr	/>

### Day 25: ...

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

<hr	/>