# android notes for rahul pandey's course:

20 apr 2023 midnight coding

create an app with empty activity. it's a view activity on linux

an activity is like a page of a website. It has one main activity. there is a main activity xml file with the layout info. layouts also have design view.

an activity is a window, or a box that goes on top of the screen. the UI box.

A view is a small box for buttons, text etc.

R.layout.activity_main points to the xml file

layouts: linear layout horizontal to put things horizontally

card view is a material design element

recycler view

padding, margin in 8dp dps

layout gravity for aligning thins. center, bottom, start etc

layout weight for putting things side by side. 1, 1 gravity is like css grid

set the id naming scheme like this:

text view: tvName
recycler view: rvName

set the identical item ids to different ids from xml or design view

background color attribute set to a default seconday variant

?attr/colorSecondaryVariant

private lateinit var rvBoard: RecyclerView

this is a private variable, late initialize, define the varial with type

after the main activity is initiated, setContentView()

assign the variables with a special method: findViewById(R.id.tvNumMoves)