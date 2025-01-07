Tags are keywords or topics that help you quickly find the notes you want.

## Add a tag to a note

To create a tag, enter a hash symbol (`#`) in the editor, followed by a keyword. For example, `#meeting`.

You can also add tags using the `tags` [property](https://help.obsidian.md/Editing+and+formatting/Properties). Tags in YAML should always be formatted as a list:

```yaml
---
tags:
  - recipe
  - cooking
---
```

## Find notes using tags

To find notes using the [Search](https://help.obsidian.md/Plugins/Search) plugin, use the `tag` [search operator](https://help.obsidian.md/Plugins/Search#Search%20operators) in your search term, for example `tag:#meeting`.

You can also search for tags by clicking on them in your notes.

To find notes using the [Tags view](https://help.obsidian.md/Plugins/Tags+view) plugin, select **Tags: Show tags** in the [Command palette](https://help.obsidian.md/Plugins/Command+palette), and then select the tag you want to search for.

## Nested tags

Nested tags define tag hierarchies that make it easier to find and filter related tags.

Create nested tags by using forward slashes (`/`) in the tag name, for example `#inbox/to-read` and `#inbox/processing`.

Both the [Search](https://help.obsidian.md/Plugins/Search) and [Tags view](https://help.obsidian.md/Plugins/Tags+view) plugins support nested tags.

## Tag format

You can use any of the following characters in your tags:

- Alphabetical letters
- Numbers
- Underscore (`_`)
- Hyphen (`-`)
- Forward slash (`/`) for [Nested tags](https://help.obsidian.md/Editing+and+formatting/Tags#Nested%20tags)

Tags must contain at least one non-numerical character. For example, #1984 isn't a valid tag, but [#y1984](https://publish.obsidian.md/#y1984) is.

Tags are case-insensitive. For example, [#tag](https://publish.obsidian.md/#tag) and [#TAG](https://publish.obsidian.md/#TAG) will be treated as identical.

Note

Tags will display with the casing they are first created with in the [Tags view](https://help.obsidian.md/Plugins/Tags+view).  
For example, creating [#Tag](https://publish.obsidian.md/#Tag) and then [#TAG](https://publish.obsidian.md/#TAG) will display [#Tag](https://publish.obsidian.md/#Tag) for both.

Tags can't contain blank spaces. To separate two or more words, you can instead use the following formats:

- [#camelCase](https://publish.obsidian.md/#camelCase)
- [#PascalCase](https://publish.obsidian.md/#PascalCase)
- [#snake_case](https://publish.obsidian.md/#snake_case)
- [#kebab-case](https://publish.obsidian.md/#kebab-case)