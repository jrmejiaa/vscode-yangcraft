# YANGCraft - syntax highlighter and snippets  

Yet Another Extension for VS Code to work with YANG. This extension is a syntax highlighter for YANG data modeling files. Besides that, it also uses some useful snippets when writing YANG models.

## Features

### Snippets

The following snippets are available once the extension is enabled: 

| **Snippet Name**               | **Call Name**       |
|--------------------------------|---------------------|
| module                         | `module`            |
| import                         | `import`            |
| typedef                        | `typedef`           |
| feature                        | `feature`           |
| identity                       | `identity`          |
| grouping                       | `grouping`          |
| container                      | `container`         |
| container with when statement  | `when-container`    |
| rpc                            | `rpc`               |
| leaf-list                      | `leaf-list`         |
| list                           | `list`              |
| leaf                           | `leaf`              |
| presence                       | `presence`          |
| config                         | `config`            |
| uses                           | `uses`              |
| description`                   | `description`       |

### Syntax Highlight

The YANG modeling looks like this with the extension

![YANG module section](assets/syntax_highlight_1.png)

![YANG grouping section](assets/syntax_highlight_2.png)

## Requirements

This extension does not have any third-party dependency. It should work out-of-the box if you have a up-to-date VS Code.

## Known Issues

TBD

## Acknowledgement 

- I was upon the work of [`marko2276`](https://github.com/marko2276) and their VS Code extension to create this one. Many thanks! 