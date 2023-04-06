# Markdown Toolkit (MDTK)

MDTK is a helpful aid for authors who write Markdown, consisting of style rules, vocabulary, a recommended set of Visual Studio Code extensions, and a workspace file that sets the preferred defaults.

## How to Install MDTK

1. Install the required components:

    * [Visual Studio Code](https://code.visualstudio.com/)
    * [Vale CLI](https://docs.errata.ai/vale/install)
    * [Vale Extension](https://marketplace.visualstudio.com/items?itemName=errata-ai.vale-server)
    * [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
    * [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

1. Clone the repository to a folder on your workstation.
1. Open `mdtk.code-workspace` with Visual Studio Code. This workspace configures the correct options for Vale and the Markdown extensions.

The workspace opens [two roots](https://code.visualstudio.com/docs/editor/multi-root-workspaces).

* The `MDTK` root is where everything lives. It's where you go to change rules or vocabulary. I leave it collapsed most of the time.
* The `Markdown` root is restricted to the Markdown directory. I use it to reduce visual clutter when writing.

That's just how I work; feel free to add or remove roots to your workspace, you do you.

_Errors_ are underlined in red, _Warnings_ in yellow, and _Suggestions_ in blue. You can hover over the alerts for pop-up help. Open the _Problems_ tab to view the complete list of errors, warnings, and suggestions.
