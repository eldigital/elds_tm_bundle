# ELDS Textmate Bundle with Snippets/Tools for Ruby on Rails Projects

## Why?
Now some bla bla follows....

We are working on Ruby on Rails projects for a long time now (especially on Textmate), and it turned out that repetitive things come in quite handy to be automated.
Every devs knows such situations where some things are being typed to many times. No one likes that.
At first, we figured out the 'head' part of AR models always get messed up by stuff like: associatons, validations, plugins etc thats why we decided to force everthing into a common schema.
Also we wanted to keep track about comments on the code, who made them and why. Why? Because if somebody changes logic at this point, its likely that should up the comments about the method. If this happens, they should at least leave an info about who end when.
All in all, not a big deal, but as the projects and teams grow, it got hard stick to these rules. that why we made it easy for everybody. A few simple tab triggers to follow -everything is fine.
Here we are....

## Tab Trigger helpers

#### `now`
Use the `now` tab trigger to insert something like `florianeck - Sat Sep  2 04:13:57 CEST 2017` at any point. We use this to make comments on codes trackable and other devs know who to ask if any questions occur

#### `arconf`
Adds a  section of comments to structure the head part of an AR model, works fine for us, improvements welcome.
````
    #= Model Description  (Replace with model name)
    #== Schema
    #
    #== Functionality

    #== Configuration

    #== Associations

    #== Plugins and modules
    #=== PlugIns
    #

    #=== include Modules
    #

    #== Konstanten
    #


    #== Validation
    # 

    #== Callbacks
    #
````

#### `bpr`
inserts a `binding.pry` where ever it is needed