# PlantUML

https://plantuml.com/
https://pdf.plantuml.net/1.2020.22/PlantUML_Language_Reference_Guide_en.pdf

To render in VSCode, follow [this documentation](https://medium.com/@sadaf.cuagain/configuring-and-running-plantuml-with-vs-code-8f2f6e64bb8d). In a nutshell:
- Download PlantUML VSCode extension.
- Configure the extension (File -> Preferences -> Settings -> Extenstions -> PlantUML configuration):
    - Render: PlantUMLServer
    - Server: https://www.plantuml.com/plantuml
- Create a file with the following extension: `.wsd .pu .puml .plantuml .iuml`, and start writing a PlantUML diagram code there.
- Preview the diagram by opening the Command Pallete (`Ctrl+Shift+P`), type "PlantUML" in the search bar, then select "Preview Current Diagram".
- To include the diagram into a markdown file, type "PlantUML" in the search bar, then select "Generate URL for Current Diagram". Paste the resulting URL to the markdown file.

Example:

![sample-flowchart](https://www.plantuml.com/plantuml/png/HOsz2i9048JxVOeLcroH8chbWQG8s5Zu2aSo90kNFRaV96yld6AwcU5ZlZvb5tDPFHtoWXKy8XOFfsqesOk2Aa3NPmmZKkBEqdiH3su6Z98aA7U69N6ZmH0pynyzszhR6qUyuBBe_5sE3vcNV8_OzbjktEn4ZINez3DiI6Otd-oUBnMZ7ZgLrNy0 "sample-flowchart")

Drawback: You must update the URL everytime you make any change to the diagram code.