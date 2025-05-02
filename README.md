# Note Tree Generator for Obsidian

This plugin for [Obsidian](https://obsidian.md) generates a structured tree based on internal links (`[[links]]`) found in your notes. It’s perfect for visualizing and exploring the connections between your notes.

## Features

* 🔍 Easily search through your notes
* 🌲 Automatically generate a structured tree from internal links
* 📋 Copy the tree to the clipboard or insert it directly into your editor
* 🔢 Automatic sorting and numbering of the structure
* 💻 Intuitive and user-friendly interface
* 🔗 Share connected notes by exporting them to a new folder
* ⚙️ Configurable title and heading level

## Commands

The plugin adds two commands to Obsidian:

* **Open Note Tree Generator**: Opens the plugin’s main interface
* **Generate tree from current note**: Generates a tree from the currently opened note and inserts the result into the editor

## Share Notes Feature

The new "Share Notes" feature allows you to:

1. Select a note as a starting point
2. Create a new folder at the root of your vault
3. Automatically export the selected note and all its linked notes
4. Preserve the original file structure

This feature is ideal for sharing specific subsets of your knowledge base without manually copying each note.

## Settings

The plugin offers the following configuration options:

* **Default sort**: Choose how to sort the notes in the list (default: by name)
* **Heading title**: Customize the title used for the tree heading (default: "Note Tree")
* **Heading level**: Set the Markdown heading level (default: H4)

## Installation

### From Obsidian Community Plugins

1. Open **Settings** in Obsidian
2. Go to **Community Plugins**
3. Search for "Note Tree Generator"
4. Click **Install**

### Manual Installation

1. Download the latest version of the plugin
2. Extract the files into your Obsidian plugins folder: `<vault>/.obsidian/plugins/note-tree-generator/`
3. Enable the plugin in Obsidian settings

## Troubleshooting ✅

- [x] **No global scroll**: The plugin is designed to allow scrolling only in the internal sections (Available Files and Preview), not in the main window.
- [x] **Note export issues**: If you encounter problems exporting notes, make sure you have write permissions at the root of your vault.
- [x] **Tree not displaying properly**: If the tree is not showing correctly, try adjusting the heading levels in the settings.

## Alternative

This plugin is an adaptation for Obsidian of the Python program [NoteTreeGenerator](https://github.com/detsneik/ntg4o), which was used to generate note trees based on links in markdown documents.
