# Helm Dev Extension

Helm Dev is the VSCode extension for developing helm charts. It includes its own snippets as well as suggestions from Helm Intellisense extension and snippets from istio-snippets extension.

## Installation

Download latest release: [LINK](https://github.com/digitalstudium/helm-dev-ext/releases/latest).
Then open VSCode, press Ctrl+Shift+X, then press `...` "View and More Actions...", then press "Install from VSIX..." and choose downloaded extension. That's it!

## Usage
Create helm chart, go to templates/something.yaml, type some helm construction, say "define", press tab and you'll see the snippet expanded.
Helm Intellisense helps you to get values from values.yaml file, like `.Values.foo`

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[UNLICENSE](https://unlicense.org/)