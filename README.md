# Signals Corps STIX 2.1 Objects

This repository holds generic STIX 2.1 Objects that are imported to different Signals Corps products.

* `extension-definition`
	* `extension-definition--349c1029-4052-4635-a064-263cb17290ea` (IBAN SCO)
	* `extension-definition--532ae28d-137b-4b89-afb7-9cf9b504191b` (Cryptocurrency SCO)
	* `extension-definition--604c32d5-20f5-4f93-8547-e490e512f8d0` (Detection Content Properties)
	* `extension-definition--6c453e0f-9895-498f-a273-2e2dda473377` (NVD CPEs Property)
	* `extension-definition--94f4bdb6-7f39-4d0a-b103-f787026963a6` (Sigma Rule Properties)
	* `extension-definition--abd6fc0e-749e-4e6c-a20c-1faa419f5ee4` (Credit Card SCO)
	* `extension-definition--b2b5f2cd-49e6-4091-a0e0-c0bb71543e23` (NVD CVE Properties)
	* `extension-definition--c8ea5ecb-f4a3-45e7-94de-9b9ba05161af` (MISP Warning Lists Properties)
* `identity`
	* `identity--38e71897-3405-4170-a35c-2f0988d21c35` (Vulmatch)
	* `identity--414184eb-06df-48d5-a281-50d8e2b17ffd` (Stixify)
	* `identity--94a7d6da-daa5-491b-97f4-ce202459395e` (cve2stix)
	* `identity--a99a2297-3044-4011-9a7e-2ff15e056b65` (Signals Corps)
	* `identity--acf55024-6bbe-486f-a27a-7967559324f4` (file2stix)
	* `identity--c2aceda2-0e46-431d-be40-7b4a4e797f81` (Demo identity)
	* `identity--dd3a1828-2912-4040-a61d-656adfc78ce5` (SIEM Rules)
	* `identity--df0d17d2-3638-4d7f-bd74-227d4cfd3c01` (Obstracts)

It also holds the schemas for all the `extension-definition` Objects as follows;

* `schemas`
	* `scos`
		* `credit-card` (for `extension-definition--abd6fc0e-749e-4e6c-a20c-1faa419f5ee4`)
		* `cryptocurrency` (for `extension-definition--532ae28d-137b-4b89-afb7-9cf9b504191b`)
		* `iban` (for `extension-definition--349c1029-4052-4635-a064-263cb17290ea`)
	* `properties`
		* `cpe` (for `extension-definition--6c453e0f-9895-498f-a273-2e2dda473377`)
		* `cve` (for `extension-definition--b2b5f2cd-49e6-4091-a0e0-c0bb71543e23`)
		* `misp-warning-list` (for `extension-definition--c8ea5ecb-f4a3-45e7-94de-9b9ba05161af`)
		* `sigma-rule` (for `extension-definition--94f4bdb6-7f39-4d0a-b103-f787026963a6`)

## Support

[Signals Corps are committed to providing best effort support via Slack](https://join.slack.com/t/signalscorps-public/shared_invite/zt-1exnc12ww-9RKR6aMgO57GmHcl156DAA).

If you notice a bug or have a feature request, [please submit them as issues on Github](https://github.com/signalscorps/cve2stix/issues).

## License

[MIT LICENSE](/LICENSE).

## Useful supporting tools

* [cti-stix2-json-schemas](https://github.com/oasis-open/cti-stix2-json-schemas): OASIS TC Open Repository: Non-normative schemas and examples for STIX 2