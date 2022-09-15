### Why should you read this?

You should read this repository if you want to get others interested in a CS related piece of work you've done. After you've been working with a project for a while, it may be that you know how your project works and more importantly, you know why your project matters. That said, if you want your work to gain a wider audience and more users, you need to convey that how and why to others. This repository provides a few strategies to complete that task in the form of an example `README` you create for a personal project on GitHub.

### Why you should not read this?

You want to write a CS paper. The skills of writing expressively should aid you in writing an academic paper, but that is a different task that would need further skills ontop of what you learn here. You can treat this as a primer, but academic writing is beyond the scope of this document. 

### Conveying the how

Any CS project you complete does something. For example, you may have a built a website that tracks flights around the world. You might want to use that website as a side project for an employer. The employer will want to know how the website works, and they ask you if you have any documentation covering the website. 

You set about creating a `README.md` file to share with the GitHub repository behind the website. You stare at your screen for 15-20 minutes...blinking...and then you start writing from memory how the repository works. Do you think this is a good approach? 

As a first go, it might be! Often it is helpful to start with brainstorming and writing down your thoughts. However, this should not be the end. Often your first draft will be a linear log of waht you did and from your perspective and with your background knowledge. This is useful but not sufficient. After all, you don't want to share a list of things you did but a document stating how you achieved your ultimate goal. 

Below is a process that you can use to help with writing. 

[1] Create a first rough draft of what you want to say. Don't spend more than an hour or two and don't worry if it makes perfect sense. The purpose of this is to get your thoughts moving and recall the things you did. 

[2] Read your first draft again and pause. Consider if it would make sense to an outside reader. If you have someone you are working with or can trust as a reviewer, ask for their initial feedback.

[3] Create a diagram showing how your project works in detail. Don't simply write something that looks like the below: 

```
Server --> API --> Client
```

When working on your diagram try to think about what makes your design unique or what are the key choices in your design that lets your project work. In short, your figure should clearly show what you achieved. 

It should also show who the users of your project are. This will be important in the following steps and the why section of this guide.

[4] Write a new draft your `README` centered on the figure you made. Walk through the figure from the perspective of the developer using examples to illustrate points. It is also helpful to walk through the figure from the perpsective of the user. 

[5] Pause! You've now got a description of how your project works. That said, your `README` isn't yet done. When ready, go to the next section. 

### Conveying the why

Look at your `README` again from the perspective of someone who has never seen your project. It should now explain how your project works, but a new reader won't necessarily know why they should use the project. 

To do this, you'll want to add another section above what you wrote for the how (which you can title as a `Technical Details` section of the overall `README`)

First, include a brief `Background` section that gives the context on the problem that your project solves. Make sure you include information describing how the problem arose and clearly state what the the difficulties resulting from the problem for the intended users of your project. 

Next, include a `My Project` section which should be appropriately titled for whatever your project is. For example, if your `Background` section covered the difficulties of knowing if your friend arrived at their destination on time when flying, you might call this section `My FlightTracker`. Under this section, include an overview of your achievements. That is explain what your project does to solve the problem and highlight any advantages to your project versus other existing solutions. Maybe your flight tracker refreshes faster than other options or has the ability to send SMS text alerts for a particular flight. 

### What Your file Looks Like at the End

`Background`

Info on how a problem arose and the difficulties it causes users. 

`My Project`

A section that covers your solution to the problem described in background any unique advantages it has versus peer solutions. 

`Technical Details`

A section that includes a detailed figure describing you achieve your solution as highligted in `My Project`

### Disclaimer

This repository is a work in progress. It is created by the community of students part of the CS@CU MS Bridge program. If you have suggestions or edits, please feel free to fork this repository and suggest changes via a pull request. You can also reach out to invidual contributors to provide feedback. 
