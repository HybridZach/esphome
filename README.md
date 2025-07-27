# ESP Home Builds

Here you can find my various esphome builds I wish to make public.

# Clarke AC

The sample YAML includes pronto codes for IR remote control of this specific model.

This will **not** work with *any* AC manufactured by Clarke Air.

The model number in question is `Clarke AC7050 3-1 AC 7000BTU`.

## Assumptions and configurations

You will need to modify a few things in the YAML first.

1. Your IR pin at the top of the file under substitutions.
2. [All passwords go in your secrets file][1].
3. This assumes you are using a **ESP32-C6FH4** chipset
(Personally I am using a M5Stack NanoC6)

[1]: https://esphome.io/guides/yaml.html#secrets-and-the-secrets-yaml-file