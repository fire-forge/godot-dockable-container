# Dockable Container
Docking panels Container addon for [Godot](https://godotengine.org/).

![](screenshots/video1.gif)

It is composed of a Container script and layout Resources in a binary tree
structure that store panels division direction and size as well as tab indices
and what tab is currently selected. As layout information are Resources, it's
easy to save/load them.

Child Controls are only moved visually and have their NodePaths and position in
parent maintained.


## Plugin
Enable `Dockable Container` plugin at `Project -> Project Settings -> Plugin`
to edit the layout directly in the inspector! It also registers the
`DockableContainer` node and the layout Resource types.

![](screenshots/video-editor.gif)


## Theming
Panels are actual `TabContainer` instances, split handles use `VSplitContainer` and
`HSplitContainer` theme configurations, drop preview uses `TooltipPanel/panel` StyleBox.
Tabs alignment and rearrange group are exported in DockableContainer.


## TODO
- Add way to specify icon and custom name for tabs, based on a property or method on children
- Document how to use
- Web build on GitHub pages and link here on README
