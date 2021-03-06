# Fireball Editor Examples

A collection of examples to demonstrate how basic components and scripting works in Fireball.

[Fireball](https://github.com/fireball-x/fireball) is a hackable game editor for creating mobile and HTML5 games, built with extremely extendable structure.

**Developed with Fireball v0.4.0**

If you're reading this doc in your local file system, go to https://github.com/fireball-x/examples for better reading experience.


## How To Use

You should get started by loading a scene from [/assets/scene](/assets/scene). Each scene has entities and components set up properly with a README entity that explain what we do here.

Then hit the play button at the top of the editor to see what it does. Then check out each entity and component to see how it's done.

Also you should read the source code of the component we created for the example. All of the source code files are filled with detailed comments.

## Examples

### Components

- [Static Sprite](/guides/components/static_sprite.md): basic sprite renderer example showing just a static sprite.
- [Sprite Animation](/guides/components/sprite_animation.md): play sprite animation on a sprite, automatically and with scripting.
- [Sliced Sprite](/guides/components/sliced_sprite.md): scale a sprite without losing border sharpness. Best use case is scalable UI backgrounds and buttons.
- [Bitmap Font](/guides/components/bitmap_font.md): display text using BitmapFont resources and change text content with scripting.
- [Dynamic Font](/guides/components/dynamic_font.md): display text using system font to avoid including a big font file in your game!
- [Simple Animation](/guides/components/animation.md): use Animation view to edit animation curve and change any component property value over time!
- [Spine Skeleton](/guides/components/spine_skeleton.md): learn how to import and play spine skeleton animation in Fireball.
- [Particle System](/)

### Gameplay

- [Entity Movement](/guides/gameplay/entity_movement.md): moves an entity from one position to another overtime, with the help of `Entity.animate` function.
- [Entity Movement with Update](/guides/gameplay/entity_movement_update.md): moves an entity from one position to another overtime. This time we hand crafted the position setting in `update` function called each frame.
- Keyboard Input: catch keyboard input with `Fire.Input.on('keydown')`.
- Character Controller: using Spineboy with skeleton animation, we move the character around with keyboard input. We show how to manipulate character moving speed with keyboard input and switch animation state with speed changes.

### UI

- [Basic UI Element](/guides/ui/basic_ui.md)
