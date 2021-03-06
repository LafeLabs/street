[home](scrolls/home)

[http://localhost](http://localhost)

# README.md

[www.maplelawn.net](https://www.maplelawn.net)

[www.us29.xyz](https://www.us29.xyz)

# [street](https://github.com/LafeLabs/street/)

Goal: build a language of this place.

How to play:

1. follow the scrolls
2. answer the questions
3. write on cardboard with marker

Rules:

1. [everything replicates](scrolls/replicate)
2. [everything evolves](scrolls/evolve)
3. [everything dies](scrolls/destroy)

Influences:

 - [Zork/Adventure style text-based games](https://en.wikipedia.org/wiki/Zork)
 - [Letterboxing](https://en.wikipedia.org/wiki/Letterboxing_(hobby))
 - [Psychogeography](https://en.wikipedia.org/wiki/Psychogeography)
 - [Exquisite corpse](https://en.wikipedia.org/wiki/Exquisite_corpse)
 - [Chaos Magic](https://en.wikipedia.org/wiki/Chaos_magic)
 - [Pokemon Go](https://en.wikipedia.org/wiki/Pok%C3%A9mon_Go)
 - [Dungeons and Dragons](https://en.wikipedia.org/wiki/Dungeons_%26_Dragons)

[![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Kaypro_wikipedia.jpg/2560px-Kaypro_wikipedia.jpg)](https://en.wikipedia.org/wiki/Zork)

[![](https://upload.wikimedia.org/wikipedia/en/a/ac/Zork_I_box_art.jpg)](https://en.wikipedia.org/wiki/Zork)

[![](https://upload.wikimedia.org/wikipedia/commons/9/90/Liberatelondon.GIF)](https://en.wikipedia.org/wiki/Psychogeography)

[![](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bc/WorldWideLetterBox016.png/340px-WorldWideLetterBox016.png)](https://en.wikipedia.org/wiki/Letterboxing_(hobby))

[![](https://upload.wikimedia.org/wikipedia/en/9/90/Pok%C3%A9mon_Go_AR_Mode%2C_Dec_2017.png)](https://en.wikipedia.org/wiki/Pok%C3%A9mon_Go)

[![](https://upload.wikimedia.org/wikipedia/en/a/a1/Dungeons_%26_Dragons_Miniatures_2.jpg)](https://en.wikipedia.org/wiki/Dungeons_%26_Dragons)

[![](https://i.imgur.com/BbU0bAX.jpg)](https://www.trashrobot.org/)

For more information, see [www.trashrobot.org](https://www.trashrobot.org/).  

Text documents are called "scrolls" and are in [Markdown](https://daringfireball.net/projects/markdown/).

Links between scrolls are formed by simply making a markdown link which has "scrolls/" and then the scroll name. Click the pencil icon to edit a scroll, then the scroll icon to get back to the reader.


[scroll set replicator](scrollset.html)

[github repository for this](https://github.com/LafeLabs/street/)

[fork down](fork.html)

[replicator raw code](php/replicator.txt)

[copy.html](copy.html)

[dnagenerator.php](dnagenerator.php)

[code editor editor.php](editor.php)

[QR Code generator](qrcode.html)

link pink rgb: #ff2cb4


[http://localhost](http://localhost)

[set.html](set.html)

Edit icon:

[![](iconsymbols/edit.svg)](scrolleditor.php?scroll=README.md)

Scroll icon:

[![](iconsymbols/scroll.svg)](user.php?scroll=README.md)

To delete a scroll click the deleter icon:

[![](iconsymbols/delete.svg)](scrolldelete.html)

And delete any scroll.  Delete is forever in local instance.  At any time you can clear the whole system and replace it with the previous instance from another server by running replicator.php.  

Edit the source code to ALL code on this server using editor.php:

[editor.php](editor.php)

Generate QR codes to this server or any other server:

[qrcode.html](qrcode.html)

Generate the "[dna](data/dna.txt)" file which is used by replicator.php to clone to the next instance:

[dnagenerator.php](dnagenerator.php)

Convenient link to localhost:

[localhost/](http://localhost/)

To replicate this system, get a local web host with PHP working and copy the file [php/replicator.txt](php/replicator.txt) to a file in the main web directory called replicator.php and run it either from the command line using 

<pre>
php replicator.php
</pre>

or pointing a browser to [http://localhost/replicator.php](http://localhost/replicator.php)(DANGER!!! CLICK ONLY TO CLEAR AND REPLACE!)

For forking the development, get PHP working from the command line on your development machine, create a new directory for your new github repository, put replicator.php in the directory, run the replicator, and then run a local host using PHP by typing the following from the command line:

<pre>
php -S localhost:80
</pre>

Then point your browser to [http://localhost/](http://localhost/) to see your new local instance.  Edit. Create scrolls, destroy scrolls, link scroll, make the new dna using [dnagenerator.php](dnagenerator.php), push all your changes to github. 

Then use [editor.php](editor.php) to edit [php/replicator.txt](php/replicator.txt) so that both the url of the replicator.txt file and dna.txt file point to the global raw text URLs for your new repository on your github account.  You can also replicate this to a globally hosted domain, and edit the replicator there to replicate out.  Once your new replicator points to itself and it's DNA your new instance is self-contained and self-replicating.

[copy specific files from previous server with copy.html](copy.html)



