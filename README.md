# My Jetbrains Settings
I use [Material Theme](https://plugins.jetbrains.com/plugin/8006-material-theme-ui) and [Atom Material Icons](https://plugins.jetbrains.com/plugin/10044-atom-material-icons) and the theme is a modification of Monokai Pro

Other plugins:

- All IDEs:
  - [Code Screenshots](https://plugins.jetbrains.com/plugin/9406-code-screenshots)
  - [Save Actions](https://plugins.jetbrains.com/plugin/7642-save-actions) (No Rider, it already have good save action)

- Jetbrain:
  - [Minecraft development](https://plugins.jetbrains.com/plugin/8327-minecraft-development)

- Rider:
  - [XAML Styler](https://plugins.jetbrains.com/plugin/14932-xaml-styler)

# How to use
## CodeStyle.xml
File->Settings->Editor->Code Style->Scheme->3 dots->Import Scheme(->InteliJ IDEA Code Style XML)

You can use IntelliJ Code Style for any Jetbrains IDE, but it probably won't work properly.

## LayerSettings.DotSettings (CodeStyle for Rider and ReSharper)
File->Settings->Manage Layer->This Computer->Import from

### UnityFileLayout.xml
File->Settings->Editor->Code Style->C#->File Layout->Unity

You need copy the file to the field. This is probably included on LayerSettings.DotSettings.

## ColorScheme.icls
File->Settings->Editor->Color Scheme->Scheme->3 dots->Import Scheme(->InteliJ IDEA color scheme (.icls))

You can use IntelliJ or Rider Color Scheme for any Jetbrains IDE, but it probably won't work properly.

## Keymap.zip
File->Manage IDE Settings->Import Settings

I haven't tested it, but it will probably work in any Jetbrains IDE.

## Theme.xml
This requiere [Material Theme](https://plugins.jetbrains.com/plugin/8006-material-theme-ui)

File->Settings->Appearance & Behavior->Material Theme UI->Custom Theme->3 dots->Select XML file from Disk

or select Monokai Pro, is very similar (It may be the same, I'm not sure)
