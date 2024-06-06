# alfred-note-workflow

![Screenshot](https://github.com/alexchantastic/alfred-note-workflow/assets/604167/e8a3b741-9124-4ed1-b229-03435f861af7)

An [Alfred 5](https://www.alfredapp.com/) for adding a note to a file.

## Installation

1. [Download the workflow](https://github.com/alexchantastic/alfred-open-with-neovim-workflow/releases/latest)
2. Double click the `.alfredworkflow` file to install

Note that the [Alfred Powerpack](https://www.alfredapp.com/powerpack/) is required to use workflows.

## Configuration

- **File** - The file to write notes to
- **Date format** - The date format for the note timestamp (see [here](https://www.gnu.org/software/coreutils/manual/html_node/Date-format-specifiers.html) for valid formats)

## Usage

### Add a note

1. Use the keyword `no` to trigger the workflow
2. Enter the note you would like to add
3. Press `enter` to submit
4. The note will be added to the configured file with a timestamp

### Open notes in application

1. Use the keyword `ono` to trigger the workflow
2. Press `enter` to submit
3. The note file will open in the default application tied to the file type

### View/Edit notes in Alfred

1. Use the keyword `vno` to trigger the workflow
2. Press `enter` to submit
3. A text window will open showing the full note
4. `cmd+enter` will save changes to the note file. `enter` will add a new line. `esc` will exit the note viewer and discard any changes.

## License

Code released under the [MIT License](https://github.com/alexchantastic/alfred-note-workflow/blob/main/LICENSE).
