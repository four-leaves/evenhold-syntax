# evenhold-syntax theme

A short description of your theme.

![screenshots01](https://github.com/evenhold/evenhold-syntax/blob/master/screenshots/Screenshot%20from%202018-01-22%2018-31-47.png)

![screenshots01](https://github.com/evenhold/evenhold-syntax/blob/master/screenshots/Screenshot%20from%202018-01-22%2018-33-31.png)

## Getting starter
```bash
  # clone into
  ~/.atom/packages
```
## UI Integration

Open file init.coffee (edit >> init script...) and paste:
```coffee
  # ...
  document.body.classList.add('an-evenhold-ui'));
```
## Example init.coffee

```coffee


  # Your init script
  #
  # Atom will evaluate this file each time a new window is opened. It is run
  # after packages are loaded/activated and after the previous editor state
  # has been restored.
  #
  # An example hack to log to the console when each text editor is saved.
  #
  # atom.workspace.observeTextEditors (editor) ->
  #   editor.onDidSave ->
  #     console.log "Saved! #{editor.getPath()}"


  document.body.classList.add('an-evenhold-ui'));
```
