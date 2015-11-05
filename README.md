This package provides a YouTube node type with a pure TypoScript rendering.

## Installation

Run `composer require sfi/youtube` from Neos root folder and you are done -- now you should see the YouTube content node type when creating new node.

No need to include TypoScript, it is included automatically.

## Settings

| Setting | Description | Defaults |
|---------|-------------|----------|
| className | Class name for wrapping div | `YouTube` |
| embedParams | Youtube embed url parameters. [Read the docs](https://developers.google.com/youtube/player_parameters#Parameters) | `rel=0&amp;showinfo=0` |
