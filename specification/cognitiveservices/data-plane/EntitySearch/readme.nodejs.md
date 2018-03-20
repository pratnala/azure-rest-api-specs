## Node.js

These settings apply only when `--nodejs` is specified on the command line.
Please also specify `--node-sdks-folder=<path to root folder of your azure-sdk-for-node clone>`.

``` yaml $(nodejs)
nodejs:
  package-name: azure-cognitiveservices-entitysearch
  output-folder: $(node-sdks-folder)/lib/services/entitySearch/lib
  override-client-name: EntitySearchAPIClient
```