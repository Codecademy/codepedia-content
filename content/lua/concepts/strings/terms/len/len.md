---
Title: '.len()'
Description: 'Returns the number of characters that exist in a specific string.'
Subjects:
  - 'Code Foundations'
  - 'Computer Science'
Tags:
  - 'Numbers'
  - 'Functions'
  - 'Strings'
  - 'Characters'
CatalogContent:
  - 'learn-lua'
  - 'paths/computer-science'
---

The **`.len()`** method returns the number of characters that exist in a specific string.

## Syntax

```shell
string.len(s)
```
Replace `s` with your string.

An empty string `""` would output `0`.

## Example

The following example demonstrates the usage of the `.len()` method:

```lua
town = "Llanfairpwllgwyngyllgogerychwyrndrobwllllantysiliogogogoch"
lenExample = string.len(town)
print(lenExample)
```

Output:

```shell
58
```

## Codebyte Example

```codebyte/lua
v1 = "Hi"
v2 = "Hello!"
v3 = "How are you doing!?"

print(string.len(v1))
print(string.len(v2))
print(string.len(v3))
```