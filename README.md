# Library

This repository is used to collect reusable parts of the design process for software development.

## Drawio

Draw io allows the import of libraries to the system. These files are saved as xml files that can be used to build a collection of reusable parts. SVG's can be used to build libraries, however some unpleasant configuration needs to be done to a SVG file to allow for styling inside a drawio file.

## SVGs

Some design system publish svg assest to be used for design. For instance Azure publishes a collection of svg files that can be used to create architecture diagrams, data flow diagrams and system diagrams. SVGs can be used in many different tools as they are a specific implementation of the SML standard. SVGs can be infinately scaled and styled with CSS.

## PlantUML

PlantUML allows for the styling of its diagrams in a construct they refer to as themes. Themes are published on GitHub and it is possible to create customized themes. PlantUML runs on Java and is feature rich for creeating diagrams such as:

- Entity Diagrams
- Sequence Diagrams
- Sequence diagram
- Usecase diagram
- Class diagram
- Object diagram
- Activity diagram (Beta) (Find the legacy syntax here)
- Component diagram
- Deployment diagram
- State diagram
- Gantt diagram
- And More

## Lunacy

Lunacy is a vector graphic design software for UI/UX and web design. Lunacy is completely free for personal and commercial use. Lunacy makes it easy to mock up UI prototypes and UX interactions for web design on multiple device targets

## Color Pallet

[Coolors](https://coolors.co/345995-03cea4-ffe882-fb4d3d-ca1551)

## Tree

```bash
.
├── drawio
├── lunacy
├── node_modules
├── plantuml
├── scripts
└── svg
```

### VsCode Extensions

Extensions can be installed from the command line

```bash
# bash/Gitbash
code --install <extension-1> <extension-2>

# Example:
code --install hediet.vscode-drawio jock.svg
```

or you can intall an ectension manually by using a extension's id in the search feild for vscode:

```bash
@id:Hediet.vscode-drawio @id:jock.svg
```

Here are some extensinos that can be useful for design tasks.

```json
{
  "recommendations": [
    "jebbs.plantuml",
    "jock.svg",
    "tyriar.sort-lines",
    "johnpapa.vscode-peacock",
    "pkief.material-icon-theme",
    "yzhang.markdown-all-in-one",
    "hediet.vscode-drawio",
    "bpruitt-goddard.mermaid-markdown-syntax-highlighting",
    "bierner.markdown-mermaid",
    "editorconfig.editorconfig"
  ]
}
```
