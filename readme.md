*mirinzzica* is a fork of Mirin Template that only add some things frequently used in modfiles, such as pre-made definemods and pre-added plugins.  
This does not modify the core of the template and thus *this shouldn't be considered a separate template*, but more of an "addon" of some sort.  
This means that you'll only really need to copy over the `lua` and `plugins` folder into your fresh modfile.

# Mirin Template
[NotITG](https://notitg.heysora.net) is a fork of OpenITG designed to make it easier for mod file creators to implement their ideas. The [Mirin Template](https://www.github.com/XeroOl/notitg-mirin) provides functions that allow creators to use NotITG express their mod ideas and bring them to life in the game.

* **Simple to learn**: Designed with a goal of avoiding unintuitive edge cases in NotITG.
* **Excellent performance**: Optimized code runs quickly compareed to other templates.
* **Theme independent**: Mirin Template creates a separate environment for mod code that is kept separate from themes.
* **Powerful abstractions**: Includes a powerful system that allows users to create custom modifiers.

```lua
-- turn on invert
ease {0, 1, outExpo, 100, 'invert'}
-- turn off invert
ease {7, 1, outExpo, 0, 'invert'}
```
Read the documentation at https://xerool.github.io/notitg-mirin
