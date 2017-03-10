# 100 Days of Code Log

**Start Date** 25 Feb 2017

**End Date** ...

**Xtra Days to add** 1

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

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

<hr	/>

### Day 14: March 12. Sunday

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

<hr	/>

### Day 15: ...

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

<hr	/>

### Day 16: ...

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

<hr	/>

### Day 17: ...

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

<hr	/>

### Day 18: ...

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

<hr	/>

### Day 19: ...

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

<hr	/>

### Day 20: ...

**Today's Progress**: ...

**Thoughts:** ...

**Link to work:** [link-to-work](#)

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