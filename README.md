# My Project

This is a description of my project. Below is a tree diagram created using Mermaid:

```mermaid
graph TD
  138692395095504["form"]:::customStyle;
  138692395095584["part: def"]:::customStyle;
  138692395095504 --> 138692395095584;
  138692395095664["apply"]:::customStyle;
  138692395095584 --> 138692395095664;
  138692395095744["identifier: f"]:::customStyle;
  138692395095664 --> 138692395095744;
  138692395095824["arguments"]:::customStyle;
  138692395095664 --> 138692395095824;
  138692395095904["identifier: n"]:::customStyle;
  138692395095824 --> 138692395095904;
  138692395095984["part: _"]:::customStyle;
  138692395095504 --> 138692395095984;
  138692395096064["form"]:::customStyle;
  138692395095984 --> 138692395096064;
  138692395096144["part: if"]:::customStyle;
  138692395096064 --> 138692395096144;
  138692395096224["operator: <="]:::customStyle;
  138692395096144 --> 138692395096224;
  138692395096304["identifier: n"]:::customStyle;
  138692395096224 --> 138692395096304;
  138692395096384["number: 1"]:::customStyle;
  138692395096224 --> 138692395096384;
  138692395096464["part: _"]:::customStyle;
  138692395096064 --> 138692395096464;
  138692395096544["number: 1"]:::customStyle;
  138692395096464 --> 138692395096544;
  138692395096624["part: else"]:::customStyle;
  138692395096064 --> 138692395096624;
  138692395096704["operator: *"]:::customStyle;
  138692395096624 --> 138692395096704;
  138692395096784["identifier: n"]:::customStyle;
  138692395096704 --> 138692395096784;
  138692395096864["apply"]:::customStyle;
  138692395096704 --> 138692395096864;
  138692395097024["identifier: f"]:::customStyle;
  138692395096864 --> 138692395097024;
  138692395097184["arguments"]:::customStyle;
  138692395096864 --> 138692395097184;
  138692395097344["operator: -"]:::customStyle;
  138692395097184 --> 138692395097344;
  138692395097504["identifier: n"]:::customStyle;
  138692395097344 --> 138692395097504;
  138692395097664["number: 1"]:::customStyle;
  138692395097344 --> 138692395097664;

classDef customStyle fill:#lightgray,stroke:#333,stroke-width:2px;

```

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#ffcc00', 'secondaryColor': '#ffcc99', 'tertiaryColor': '#ffe5cc'}}}%%
mindmap
  root((Root))
    sub1((Subnode 1))
      subsub1((Subnode 1.1))
      subsub2((Subnode 1.2))
    sub2((Subnode 2))
      subsub3((Subnode 2.1))
      subsub4((Subnode 2.2))
```

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#ffcc00', 'secondaryColor': '#ffcc99', 'tertiaryColor': '#ffe5cc'}}}%%
flowchart TD
  A[Root] --> B[Subnode 1]
  A --> C[Subnode 2]
  B --> D[Subnode 1.1]
  B --> E[Subnode 1.2]
  C --> F[Subnode 2.1]
  C --> G[Subnode 2.2]
```


## Welcome to Old GitHub Pages

You can use the [editor on GitHub](https://github.com/sfkleach/scratch/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

(Causing rebase to be non-trivial. Now hack this - for squashing. Hacked again for reviewing the remote repo extension from Microsoft.)

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/sfkleach/scratch/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
