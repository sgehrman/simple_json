## 1.1.3 - 01/08/2021
* Support de-serialization using `typeName`.

## 1.1.2 - 08/31/2020
* Support `Duration` class serialization.

## 1.1.1 - 07/09/2020
* Add `verbose` option for logging.

## 1.1.0 - 07/09/2020
* Fix bug with list serialization.

## 1.0.2 - 07/02/2020
* Handle `null` values on both serialization and de-serialization.

## 1.0.1 - 07/01/2020
* Update the `serialize` method API by removing the generic type parameter from `JsonMapper`.

## 1.0.0 - 07/01/2020
* Update the `serialize` method API by removing the generic type parameter. The runtimeType is used to match the correct mapper.

## 0.4.0 - 07/01/2020
* Support serializing and deserializing of lists. `deserializeList<T>` method was removed. Use the normal `deserialize<T>` (where T is a type of `List<Type>`) method instead.

## 0.3.0 - 07/01/2020
* Support serializing and deserializing of lists. Deserializing requires the actual item type so a new `deserializeList<T>` method was added.
* Cleanup of API and internal usages. 

## 0.2.2 - 06/24/2020
* Keep version in sync with `simple_json`. 

## 0.2.1 - 06/24/2020
* Update README. 

## 0.2.0 - 06/24/2020
* Add support for custom json mapper and converters. 

## 0.1.6 - 06/15/2020
* Fix unintentionally hidden annotations.

## 0.1.5 - 06/15/2020
* Add enum annotations. `JsonEnumProperty` (with alias `JEnumProp`) and `EnumValue`.

## 0.1.4 - 06/15/2020
* Fix bug `JObj` const constructor.

## 0.1.3 - 06/15/2020
* Fix bug with not revealing the new annotations.

## 0.1.2 - 06/15/2020
* Add `JObj` as an alias to `JsonObject` and `JsonProperty` (with `JProp` alias) for controlling class property options.

## 0.1.1 - 06/15/2020
* Add example project.

## 0.1.0 - 06/15/2020
* Initial release.
