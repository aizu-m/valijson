# Plan

The road to full draft 2020-12 support.

## Prerequisites

* ~~Add `kDraft202012` parser mode~~
* ~~Update to latest version of JSON-Schema-Test-Suite~~
  * ~~Fix Draft7 `size/length` keyword failures~~
  * ~~Fix Draft3 `ref` failures~~
  * ~~Fix Draft4 `multipleOf` failures~~
  * ~~Fix Draft7 `type` failures~~
  * ~~Fix Draft7 `optionalFormat` failures~~

## General

* `format` behaviours (**in progress**)


## Non-annotation keywords

* ~~`$defs` alias/support~~
* ~~`prefixItems`~~
* ~~`items` alternative behaviour for 2020~~
* `$id` parsing
* `dependentRequired`
* `dependentSchemas`
* `minContains`/`maxContains`, may be achievable before full annotation support

## References

* `$ref` as applicator with siblings
* schema registry and canonical URI handling
* `$anchor` support
* compound schema documents
* remote reference cache improvements
* dialect switching for embedded/referenced schemas

## Annotation-aware keywords

* `unevaluatedItems`
* `unevaluatedProperties`
* `contains` evaluated-index annotations
* annotation propagation

## Dynamic references

* `$dynamicAnchor`
* `$dynamicRef`
* dynamic-scope evaluation
