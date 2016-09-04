Forked from https://github.com/jerik/mdCanvas

# Enhancement are:
 - Default markdown file is index.md
 - Section separation with "\n\n---\n\n"
 - Each section's first line is senction name which starts with any level header.
 - The first line of markdown file is project name which starts with any level header.
 - see example [index.md](index.md)

---

# mdCanvas
Create a Lean Canvas out of a markdown list 

## Examples
[Rendered lean canvas]( https://jerik.github.io/mdCanvas/mdCanvas.html ) based on this markdown file: [mdCanvas.md]( https://raw.githubusercontent.com/jerik/mdCanvas/master/mdCanvas.md )

## Getting started
1. Clone or download this git repository 
1. Edit `mdCanvas.md`
1. Fire up your browser and open `mdCanvas.html`

## How to use
### Write down your Lean Canvas in markdown
Create a markdown textfile `project.md` in the same directory as the `mdCanvas.html` file. 

### Fill the markdown file with content: 

	# Canvas
	Lean Canvas to save the earth

	# Problem
	1. How to save the earth

	# Customer-segment
	1. All people of the world
	1. Wildlife

	# Unique-Value-Proposition
	The time is **not in love** with us

	# Solution
	- Supply mankind with engouh food and housing
	- Create peace 
	- Dispose money and greed

	# Channels
	- Word of mouth

	# Cost-Structure
	- Smile and Conviction

	# Revenue-Stream
	- Better life
	- Peace and Harmony

	# Key-Metrics
	- Environmental pollution control
	- Food and housing control

	# Unfair-advantage
	- Goodlike status

### Open mdCanvas.html with your markdown textfile
URL: `/path/to/your/mdCanvas.html?md=project`

## Todos
- Check https://github.com/theInspiredOnes/bmc-generator, perhaps a better
  layout?
