# Verbal ![](images/verbal_64.png)
Verbal is a node-based conversation tool. I could not find a conversation tool that would be simple, flexible and open, so I made one myself. 

It is meant to be a tiny tool for gamejams and smaller projects.

### How it works ###

Use the [editor](http://jarnik.itch.io/verbal) to write the conversation and export it to a JSON file like this:
```json
[
   {"actions":["So what do you want?"],"id":1,"links":[2,3],"x":336,"y":6},
   {"conds":["I want to be a pirate!"],"id":2,"links":[6],"x":280,"y":284},
   {"conds":["Never mind, Im leaving."],"id":3,"x":917,"y":318}
]
```
Then load the JSON into your game using the library (see the examples) or just interpret the data any way you need.

### Library platforms ###

Supported: Haxe (OpenFL, HaxeFlixel), Unity 5

Planned: ? LOVE, ? GameMaker

Conversation tree example:

![Tree Conversation Example](images/screenshot_treeExample.png)

Used font: http://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=381

### Editor ###

Get it here (**Linux, Windows, Flash**): http://jarnik.itch.io/verbal

![Verbal editor](images/screenshot_verbalEdit.png)
