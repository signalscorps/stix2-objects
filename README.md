# Signals Corps STIX 2.1 Objects

This repository holds generic STIX 2.1 Objects that are imported to different Signals Corps products.

## Signals Corps Identities

* [Signals Corps](/identity/signals-corps-master/identity--a99a2297-3044-4011-9a7e-2ff15e056b65/20220101000000000.json) (`identity--a99a2297-3044-4011-9a7e-2ff15e056b65`)
* [Signals Corps demos](/identity/signals-corps-demo/identity--c2aceda2-0e46-431d-be40-7b4a4e797f81/20220101000000000.json) (`identity--c2aceda2-0e46-431d-be40-7b4a4e797f81`
* [Vulmatch](/identity/vulmatch/identity--38e71897-3405-4170-a35c-2f0988d21c35/20220101000000000.json) (`identity--38e71897-3405-4170-a35c-2f0988d21c35`
* [Stixify](/identity/stixify/identity--414184eb-06df-48d5-a281-50d8e2b17ffd/20220101000000000.json) (`identity--414184eb-06df-48d5-a281-50d8e2b17ffd`
* [Obstracts](/identity/obstracts/identity--df0d17d2-3638-4d7f-bd74-227d4cfd3c01/20220101000000000.json) (`identity--df0d17d2-3638-4d7f-bd74-227d4cfd3c01`
* [SIEM Rules](/identity/siem-rules/identity--dd3a1828-2912-4040-a61d-656adfc78ce5/20220101000000000.json) (`identity--dd3a1828-2912-4040-a61d-656adfc78ce5`
* [file2stix](/identity/file2stix/identity--acf55024-6bbe-486f-a27a-7967559324f4/20220101000000000.json) (`identity--acf55024-6bbe-486f-a27a-7967559324f4`
* [cve2stix](/identity/cve2stix/identity--94a7d6da-daa5-491b-97f4-ce202459395e/20220101000000000.json) (`identity--94a7d6da-daa5-491b-97f4-ce202459395e`
* [cpe2stix](/identity/cpe2stix/identity--eca04b00-3750-4752-9a28-fc3f112a1ff3/20220101000000000.json) (`identity--eca04b00-3750-4752-9a28-fc3f112a1ff3`)

## New SCOs

### Bank Account SCO

`extension-definition--349c1029-4052-4635-a064-263cb17290ea`

This extension creates a new SCO that can be used to represent bank account details.

* [Extension Definition](/extension-definition/new-sco/bank-account/extension-definition--349c1029-4052-4635-a064-263cb17290ea/)
* [Schema](/schemas/new-sco/bank-account/schema.json)
* [Example SCO](/schemas/new-sco/bank-account/example.json)

### Credit Card SCO

`extension-definition--abd6fc0e-749e-4e6c-a20c-1faa419f5ee4`

This extension creates a new SCO that can be used to represent credit cards.

* [Extension Definition](/extension-definition/new-sco/credit-card/extension-definition--abd6fc0e-749e-4e6c-a20c-1faa419f5ee4/)
* [Schema](/schemas/new-sco/credit-card/schema.json)
* [Example SCO](/schemas/new-sco/credit-card/example.json)

### Cryptocurrency Transaction SCO

`extension-definition--bef728e0-53cb-11ed-bdc3-0242ac120002`

This extension creates a new SCO that can be used to represent cryptocurrency transactions.

* [Extension Definition](/extension-definition/new-sco/cryptocurrency-transaction/extension-definition--bef728e0-53cb-11ed-bdc3-0242ac120002/)
* [Schema](/schemas/new-sco/cryptocurrency-transaction/schema.json)
* [Example SCO](/schemas/new-sco/cryptocurrency-transaction/example.json)

### Cryptocurrency Wallet SCO

`extension-definition--532ae28d-137b-4b89-afb7-9cf9b504191b`

This extension creates a new SCO that can be used to represent cryptocurrency wallets.

* [Extension Definition](/extension-definition/new-sco/cryptocurrency-wallet/extension-definition--532ae28d-137b-4b89-afb7-9cf9b504191b/)
* [Schema](/schemas/new-sco/cryptocurrency-wallet/schema.json)
* [Example SCO](/schemas/new-sco/cryptocurrency-wallet/example.json)

### User Agent SCO

`extension-definition--6cea4dc9-9517-44b8-b021-ae82e2f1de43`

This extension creates a new SCO that can be used to represent user agents used in HTTP request. It is designed to be used when the Network Traffic SCO with HTTP request extension cannot be used due to lack of request information needed for the required properties.

* [Extension Definition](/extension-definition/new-sco/user-agent/extension-definition--6cea4dc9-9517-44b8-b021-ae82e2f1de43/)
* [Schema](/schemas/new-sco/user-agent/schema.json)
* [Example SCO](/schemas/new-sco/user-agent/example.json)

## Property Extensions

### CPE Extension

`extension-definition--6c453e0f-9895-498f-a273-2e2dda473377`

This extension extends Software SCOs with NVD CPE fields to support NVD enrichments.

* [Extension Definition](/extension-definition/property-extension/cpe-extension/extension-definition--6c453e0f-9895-498f-a273-2e2dda473377/)
* [Schema](/schemas/property-extension/cpe-extension/schema.json)
* [Example Software SCO Extension](/schemas/property-extension/cpe-extension/example.json)

### CVE Extension

`extension-definition--b2b5f2cd-49e6-4091-a0e0-c0bb71543e23`

This extension extends Vulnerability SDOs with NVD CVE fields to support NVD enrichments.

* [Extension Definition](/extension-definition/property-extension/cve-extension/extension-definition--b2b5f2cd-49e6-4091-a0e0-c0bb71543e23/)
* [Schema](/schemas/property-extension/cve-extension/schema.json)
* [Example Vulnerability SDO Extension](/schemas/property-extension/cve-extension/example.json)

### Sigma Rule Extension

`extension-definition--94f4bdb6-7f39-4d0a-b103-f787026963a6`

This extension extends Indicator SDOs with a Sigma Rules broken out into individual properties, instead of being packed as JSON escaped YAML in the pattern field which is not human readable which is very likely to cause encoding and decoding issues.

* [Extension Definition](/extension-definition/property-extension/sigma-rule-extension/extension-definition--94f4bdb6-7f39-4d0a-b103-f787026963a6/)
* [Schema](/schemas/property-extension/sigma-rule-extension/schema.json)
* [Example Indicator SDO Extension](/schemas/property-extension/sigma-rule-extension/example.json)

### Warning List Extension

`extension-definition--c8ea5ecb-f4a3-45e7-94de-9b9ba05161af`

This extension extends Indicator SDOs with Warning List (aka whitelist) match information. It assumes whitelists are in MISP Warning List format.

* [Extension Definition](/extension-definition/property-extension/warning-list-extension/extension-definition--c8ea5ecb-f4a3-45e7-94de-9b9ba05161af/)
* [Schema](/schemas/property-extension/warning-list-extension/schema.json)
* [Example Indicator SDO Extension](/schemas/property-extension/warning-list-extension/example.json)

### Vulnerability Pattern Extension

`extension-definition--b463c449-d022-48b7-b464-3e9c7ec5cf16`

This extension extends Indicator SDOs with the information about which CPEs (referenced in the pattern property) are actually vulnerable.

* [Extension Definition](/extension-definition/property-extension/vulnerability-pattern-extension/extension-definition--b463c449-d022-48b7-b464-3e9c7ec5cf16/)
* [Schema](/schemas/property-extension/vulnerability-pattern-extension/schema.json)
* [Example Indicator SDO Extension](/schemas/property-extension/vulnerability-pattern-extension/example.json)

## Support

[Signals Corps are committed to providing best effort support via Slack](https://join.slack.com/t/signalscorps-public/shared_invite/zt-1exnc12ww-9RKR6aMgO57GmHcl156DAA).

If you notice a bug or have a feature request, [please submit them as issues on Github](https://github.com/signalscorps/cve2stix/issues).

## License

[MIT LICENSE](/LICENSE).

## Useful supporting tools

* [cti-stix2-json-schemas](https://github.com/oasis-open/cti-stix2-json-schemas): OASIS TC Open Repository: Non-normative schemas and examples for STIX 2