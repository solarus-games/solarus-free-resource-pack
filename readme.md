# Creative Commons resource pack for Solarus

This repository provides free
musics, sounds, tilesets, sprites and scripts
for the
[Solarus engine](https://github.com/solarus-games/solarus).

You can use these resources if you want to develop a game with the
Solarus engine using free (as in freedom) assets.

- All data files that we created (other than Lua scripts) are licensed under
Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0).
http://creativecommons.org/licenses/by-sa/4.0/

- Lua scripts are licensed under the terms of the GNU General Public License
in version 3.

## Branches

Branch master always points to the latest release of this resource pack.

The latest resource pack release is always compatible
with the latest Solarus version.

Resources compatible with older versions or development versions of Solarus
live in their own branches.

## Importing resources from this pack into an existing quest

When you create a new quest with
[Solarus Quest Editor](https://github.com/solarus-games/solarus-quest-editor),
your data is initialized with a subset of free resources from this pack.

You can import more content from this pack into your quest if you want.
Here is how to proceed
(note that in future versions of Solarus Quest Editor, an import feature
will make the process easier):

- Make a backup of your quest.
- Copy the sprites/tilesets/musics/scripts files you want from the
  `data` directory of this resource to the `data` directory of your
  quest. Don't copy `project_db.dat`.
  (`project_db.dat` is the list of resources of your quest and you don't want
  to lose the existing ones.)
- Open your quest with
  [Solarus Quest Editor](http://www.solarus-games.org/development/quest-editor]).
- In the quest tree, all resources you just copied now appear with an
  interrogation mark icon.
  You can right-click them to add them to the quest.


