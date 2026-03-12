# Renovate Config

Shared renovate config. See https://docs.renovatebot.com/config-presets/

Configurations:
* ```github>acbgbca/renovate``` Default configuration with sensible defaults
* ```github>acbgbca/groupAll``` Groups all dependency updates together. Useful if conflicts and issues are not expected
* ```github>acbgbca/groupAllNoTests``` Same as group all except with tests disabled, as Renovate won't auto-merge if there are no automated tests
* ```github>acbgbca/groupNonMajor``` Groups all non-major dependencies together (feature, patch, and digest). Major updates will be in a separate PR