# Table: gui

Table containing functions for modifying the menu GUI.

## Functions (6)

### `add_submenu(sub_name)`

- **Parameters:**
  - `sub_name` (string): Name of the tab to get.

- **Returns:**
  - `submenu`: A tab instance which corresponds to the submenu in the GUI.

**Example Usage:**
```lua
tab = gui.add_submenu(sub_name)
```


### `show_message(title, message)`

Shows a message to the user with the given title and message.

- **Parameters:**
  - `title` (string)
  - `message` (string)

**Example Usage:**
```lua
gui.show_message(title, message)
```

### `show_warning(title, message)`

Shows a warning to the user with the given title and message.

- **Parameters:**
  - `title` (string)
  - `message` (string)

**Example Usage:**
```lua
gui.show_warning(title, message)
```

### `show_error(title, message)`

Shows an error to the user with the given title and message.

- **Parameters:**
  - `title` (string)
  - `message` (string)

**Example Usage:**
```lua
gui.show_error(title, message)
```

### `is_open()`

- **Returns:**
  - `bool`: Returns true if the GUI is open.

**Example Usage:**
```lua
bool = gui.is_open()
```
