# JSONSchemas

Public repository of generated Neos JSON schemas.

## What are JSON Schemas?

JSON Schemas are files which describe the layout and schema of a JSON file. You can use them to Generate Code, Validate JSON etc.

## Why are these here?

When creating headless configuration files, or Neos Client generator files you might be unsure what you can do. These files are designed to fix this :)

## How can I use these?

We recommend using VS Code to edit your JSON files, it will then be automatic! See [VSCode's guide](https://code.visualstudio.com/Docs/languages/json#_json-schemas-and-settings) for more information. There are other tools you can use but we've had mixed success with these. The JSON Schema website has a [list of tooling](https://json-schema.org/implementations.html).

## What schemas do you have?

- [NeosHeadlessConfig.schema.json](schemas/NeosHeadlessConfig.schema.json) - For [headless configuration](https://wiki.neos.com/Headless_Client/Configuration_File)
- [NeosConfig.schema.json](schemas/NeosConfig.schema.json) - For [Neos client configuration files](https://wiki.neos.com/Startup_Config_File)

## Where can I learn more?

Head to the official [JSON Schema website](https://json-schema.org/)!

## Why are you using draft-04 schemas?

Our [JSON Schema generator](https://github.com/RicoSuter/NJsonSchema) only supports [draft-04](https://github.com/RicoSuter/NJsonSchema/issues/574) right now. Please help it reach 06/07 support :)
