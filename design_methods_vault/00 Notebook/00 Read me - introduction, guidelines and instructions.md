---
tags:
  - "#notebook/help"
  - ignored
aliases:
  - help
  - introduction
  - inscript
  - readMe
description:
---

The goal of this obsidian notebook is to be a living collection of design methods, concepts and methodologies, with descriptions, examples and relation to other methods, concepts and methodologies. 

This is further enhanced by Obsidians amazing "Graph view" which allows us to create views like this, to explore relevant concepts and methods, when looking for the right tool for the job.

A full view of the methods as of 20231229

![[Pasted image 20231229190446.png]]
And a local graph view showing 3 deep links for the note [[Facilitation]]
![[Pasted image 20231229190528.png]]
and updated view as of 20240210 
![[Pasted image 20240210184213.png]] 

You can use this notebook in two different ways
1. Online through // insert linked // 
	1. This has not yet been implemented but the plan is to use https://obsidian.md/publish
	2. The webview does not support Dataview without some significant work, which makes automatic lists of concepts/methods like: [[03 Map of Double Diamond Methods 💎💎]] and [[03 Map of Double Diamond Concepts 💎💎]]  only available by downloading the vault and running it locally with Obsidian
2. Running it locally  [Obsidian](https://obsidian.md/) by downloading or cloning the [Github repository](https://github.com/AkselNLadegaard/design_methods_map) 

## Obsidian 
If you decide to use the notebook with Obsidian which we highly recommend, as it is a neat tool, and it allows you to contribute your amazing insights, then there is a little bit of a learning curve. For in obsidian pretty much anything is possible, but some things might be a little unintuitive. 
There are a great short YouTube tutorials and the wiki is great: https://help.obsidian.md/Home 

If you get stuck please do not hesitate to reach out to one of the maintainers :) 

## How to contribute 
We would love for you to add methods, concepts, links, tagging etc.. to contribute do the following: 
1. Install git
2. Clone the github repository
3. Open it with obsidian 
	1. For some features you have to enable community plugins in settings, especially dataview is critical. 
4. Create a new branch with a relevant name
5. Make your changes, adding methods etc.
6. Commit your changes to the branch
7. Push your changes 
8. Create a pull request 
9. Get your contributions reviewed, make relevant changes, recommit and push 
10. Your contributions gets accepted and merged into the main branch

**Git is a little daunting at first, but it is for now the best way of managing this project. There are countless guides on the internet, videos etc.. explaining how to od it, if you get stuck try a chatbot (chatgpt, bard or similar) or reach out to one of the maintainers**

You can get far with: https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging 


## How to add a design method/concept/methodology or similar

1. Create a new file 
2. Input the relevant template using the keyboard shortcut crtl+m or 
3. Fill it out!


Pleas remember to 
1. Tag it relevantly! See [[02 Tagging]] for existing tags, and feel free to add your own! 

2. Link it to relevant concepts and methods, even if they haven't been written yet!
	1. For existing concepts and methods see [[01 Map of Design Concepts and Principels]] and [[02 Map of Design Methods]] or just browse the project! 


# Meanderings and thoughts on figuring out how to structure this 
## Ways of structuring design methods 


We can categorise  design methods by
* Design phase
* Design methodology 
* By form of data 
	* Quantitative 
	* Qualitative
* Duration?
* Creative approach 
	* Analytical 
	* Generative 
	* Experimental
* Origin?
* 


## What we want 

>**We want an expandable database/notebook of design that allows us to describe, relate and show examples of design methods, concepts and methodologies.** 
- It show allow overviews of concepts and methods from different methodologies, like the double diamond
- It show enable graphical visualisation of the contents
- Expanding the database of knowledge should increase its value, not diminish it 

## How to do some of this in obsidian

Briefly covered here:
1. Markdown
2. Graph view
3. Linking 
4. Tagging 
5. Folders (with caution please)


#### Markdown
Obsidian uses markdown, it takes a little to get used to! 


#### Graph view
Press crtl+g for the big graph view or access it through the command pallette crtl+p

Play around with display, forces, groups and filters! 

**Remember to use the local graph view with depths larger than 1, it is way more useful**
crt+shift+g for the local graph view
#### Links: 
You can use brackets to make a link to another note, it opens a really nice search function making it easy. You can also link to a note that has not been written yet, then when it is written the link becomes active! 
```
[[link to a note goes here]]

Use double square brackets: [[]]
```
and it then looks like [[00 Read me - introduction, guidelines and instructions]]

Protip, hover and press crtl (or change they shortcut) to preview the content of the note ;) 

Linking creates value in obsidian as it shows up as a link in graph views 


2. Tags

Add all tags in the header under tags. 

To add a header to a new note, just use the **template** "New note template" by pressing crtl+m or *insert template *through the command palette 

4. Folders (with a little caution please)

Why can't you just use folders?

1. Folders are hierarchal 
	1. This invariably leads to either either: duplication of notes or a enforcing single insufficient taxonomy.
	2. Hierarchy conflicts with the the purpose of this 'database'/notebook which is to support multiple different taxonomies of design without duplication of notes.  

But some hierarchy is necessary for making this maintainable so:

**When can you use folders to organise notes into:**
	1. Description
	2. Concepts
	3. Methods
	4. Methodologies 
	5. Workshops
	6. Templates

1. **Description:** is for notes like this, describing the purpose of the notebook, how to use it and other "meta" stuff
2. **Concepts**, is for different concepts (especially design concepts), for example [[Redundancy]]  
3. **Methods**: is for design methods, like [[Service blueprint]] 
4. **Methodologies**: are for the overarching frameworks and approaches that govern design, like eco-design, agile design
5. **Workshops**: for collection of methods and concepts relevant to specific workshops or specific types of workshops. These can also be workshop plans
6. **Templates**: mainly for making maintaining this notebook more convenient. But it is also for small outlines for how to use some methods, there can be multiple templates per concept, method or methodology. 
