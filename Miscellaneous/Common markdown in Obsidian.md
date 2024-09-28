Obsidian, a popular note-taking and knowledge management application, uses Markdown as its primary format for creating and formatting notes. Here’s a guide to the common Markdown syntax used in Obsidian:

### Basic Text Formatting

- **Bold**: `**bold text**` or `__bold text__`
- **Italic**: `*italic text*` or `_italic text_`
- **Bold & Italic**: `***bold and italic text***` or `___bold and italic text___`
- **Strikethrough**: `~~strikethrough text~~`

### Headings

- **Heading 1**: `# Heading 1`
- **Heading 2**: `## Heading 2`
- **Heading 3**: `### Heading 3`
- **Heading 4**: `#### Heading 4`
- **Heading 5**: `##### Heading 5`
- **Heading 6**: `###### Heading 6`

### Lists

- **Unordered List**:
  - `- Item 1`
  - `* Item 2`
  - `+ Item 3`

- **Ordered List**:
  1. `1. Item 1`
  2. `2. Item 2`
  3. `3. Item 3`

- **Nested Lists**:
  - `- Item 1`
    - `  - Subitem 1.1`
      - `    - Subitem 1.1.1`

### Links and Images

- **Internal Link (to another note)**: `[[Note Name]]`
- **External Link**: `[Link Text](http://example.com)`
- **Link with Alias**: `[[Note Name|Alias Text]]`
- **Image**: `![Alt Text](image_url)`

### Blockquotes

- **Blockquote**: `> This is a blockquote.`

### Code

- **Inline Code**: `` `inline code` ``
- **Code Block**:
  \`\`\`
  ```
  code block
  ```
  \`\`\`

- **Code Block with Syntax Highlighting**:
  \`\`\`language
  ```
  code with syntax highlighting
  ```
  \`\`\`

### Tables

- **Table**:
  ```markdown
  | Header 1 | Header 2 | Header 3 |
  | -------- | -------- | -------- |
  | Row 1    | Data 1   | Data 2   |
  | Row 2    | Data 3   | Data 4   |
  ```

### Task Lists (Checkboxes)

- **Task List**:
  - `- [ ] Incomplete task`
  - `- [x] Completed task`

### Embedding and Linking Files

- **Embed Note**: `![[Note Name]]`
- **Embed Section of Note**: `![[Note Name#Section Title]]`
- **Embed Image**: `![[image.png]]`

### Footnotes

- **Footnote**:
  ```markdown
  Here is a statement.[^1]

  [^1]: This is the footnote.
  ```

### Math and LaTeX

- **Inline Math**: `$E = mc^2$`
- **Math Block**:
  \`\$\$
  $$
  E = mc^2
  $$
  \$\$

### Highlighting

- **Highlight**: `==highlighted text==`

### Comments

- **Comment** (not rendered in the final output): `%% This is a comment %%`

### Special Features in Obsidian

- **Tags**: `#tagname` (Tags can be added anywhere in the text)
- **YAML Frontmatter** (used for metadata):
  ```yaml
  ---
  title: My Note Title
  tags: [tag1, tag2]
  ---
  ```

These are the most common Markdown elements used in Obsidian, allowing you to format your notes effectively. Obsidian also supports various plugins that can extend Markdown functionality, so you can customize your workflow even further.

%% 
This is a comment box.
Everything inside these symbols will not be shown in the preview mode.
You can use this to add notes, reminders, or any text you don't want to appear in the final note.
%%
