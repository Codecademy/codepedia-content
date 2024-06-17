---
Title: '.len()' # Required; the file name should be the same as the title, but lowercase, with dashes instead of spaces, and all punctuation removed
Description: 'Returns the number of characters of a string.' # Required; ideally under 150 characters and starts with a present-tense verb (used in search engine results and content previews)
Subjects: # Please only use Subjects in the subjects.md file (https://github.com/Codecademy/docs/blob/main/documentation/subjects.md). If that list feels insufficient, feel free to create a new Subject and add it to subjects.md in your PR!
  - 'Code Foundations'
Tags: # Please only use Tags in the tags.md file (https://github.com/Codecademy/docs/blob/main/documentation/tags.md). If that list feels insufficient, feel free to create a new Tag and add it to tags.md in your PR!
  - 'Numbers'
  - 'Functions'
  - 'Strings'
CatalogContent: # Please use course/path landing page slugs, rather than linking to individual content items. If listing multiple items, please put the most relevant one first
  - 'learn-lua'
  - 'paths/computer-science'
---

The `.len()` function returns the complete number of characters contained in a string.

## Syntax

```shell
string.len(string)
```

## Example

```lua
town = "Llanfairpwllgwyngyllgogerychwyrndrobwllllantysiliogogogoch"
lenExample = string.len(town)
print(townLength)
```

Output:

```shell
58
```