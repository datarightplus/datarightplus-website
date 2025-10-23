---
layout: default
title: Library
---

# Ecosystem Profiles

Ecosystem profiles refer to groupings of separate but interweaving specifications into a single specification document with which a single consistent ecosystem can be deployed from.

## Australian CDR

The Australian CDR ecosystem profile targets the combining of DataRight+ specifications to produce a technically compatible outcome for participation in the Australian Consumer Data Right.

{% include spec_releases_table.html repo="datarightplus-cdr-profile" name="draft-authors-datarightplus-cdr-profile" releases="00:2024-04-03" %}

## Australian DataRight+

The Australian DataRight+ ecosystem profile introduces functionality beyond the Australian Consumer Data Right for the purposes of functionality beyond the mandate.

{% include spec_releases_table.html repo="datarightplus-dio-profile" name="draft-authors-datarightplus-dio-profile" releases="" %}

# Actions

## Bulk Transactions Detail V1

The Bulk Transaction Detail specification provides an asynchronous mechanism for downloading bulk Banking Transaction Detail records using the same input parameters as the List Banking Transactions endpoint. While implementing an action lodgement behaviour it is compatible with the CDR Data Sharing Arrangement.

{% include spec_releases_table.html repo="datarightplus-banking-bulk-transactions-v1" name="draft-authors-datarightplus-banking-bulk-transactions-v1" releases="" %}

## Sharing Arrangement V1

The Sharing Arrangement V1 specification is intended to be a like-for-like specification of the Data Standards specifying the mandated version of a CDR Data Sharing Arrangement. It includes provisions related to custom claims, obligations with respect to specific API endpoints and the supported data clusters (incorporated as oauth2 scopes).

{% include spec_releases_table.html repo="datarightplus-sharing-arrangement-v1" name="draft-authors-datarightplus-sharing-arrangement-v1" releases="00:2024-04-02" %}

## Sharing Arrangement V2

The Sharing Arrangement V2 specification is a next generation implementation of a data sharing arrangement. It is intended to achieve the same  objectives of Sharing Arrangement V1 but provide for an intent based pattern facilitating multiple authorisation patterns and lifecycle monitoring. 

{% include spec_releases_table.html repo="datarightplus-sharing-arrangement-v2" name="draft-authors-datarightplus-sharing-arrangement-v2" releases="" %}

## Energy Account Switch V1

The Energy Account Switch V1 specification provides a mechanism for initiating an energy account opening process at a target Provider. It is intended to be a first class action to be introduced into the Consumer Data Right.

{% include spec_releases_table.html repo="datarightplus-energy-account-switch-v1" name="draft-authors-datarightplus-energy-switch-v1" releases="" %}

# Data Resource Sets

## Common Resource Set

The Common Resource Set outlines the shared endpoints within DataRight+ and incorporates obligations of Providers and Initiators related to the shared resource server namespace.

{% include spec_releases_table.html repo="datarightplus-resource-set-common" name="draft-authors-datarightplus-resource-set-common" releases="00:2024-04-02" %}

## Banking Resource Set

The Banking Resource Set outlines the banking sector related endpoints within DataRight+ and incorporates obligations covering Provider and Initiator.

{% include spec_releases_table.html repo="datarightplus-resource-set-banking" name="draft-authors-datarightplus-resource-set-banking" releases="00:2024-04-02" %}

## Energy Resource Set

The Energy Resource Set outlines the energy sector related endpoints within DataRight+ and incorporates obligations covering Provider, Initiator, Electrical Authority and the Energy Plan Website.

{% include spec_releases_table.html repo="datarightplus-resource-set-energy" name="draft-authors-datarightplus-resource-set-energy" releases="00:2024-04-02" %}

# Information Security

## Security Profile: Baseline

Security Profile: Baseline edition is intended to be a compatible profile of the Data Standards presented as a profile of [Financial-grade API Security Profile 1.0 Part 2: Advanced]. This profile focuses primarily on the obligations between OP and RP with respect to authorisation requests and does so as an overlay on the underlying FAPI profile combined with the inclusion of permitted arrangement types within the CDR (currently one, the CDR Sharing Arrangement V1). It does not attempt to provide elaboration on registration protocols, certificate profiles, federation or other components.

{% include spec_releases_table.html repo="datarightplus-infosec-baseline" name="draft-authors-datarightplus-infosec-baseline" releases="00:2024-04-02" %}

## Admission Control: Baseline

Admission Control: Baseline edition is intended to be a Data Standards compatible specification of the ecosystem authority and related infrastructure. It includes provisions for metadata describing the participants, certificate authorities for ensuring mutual trust of the entire ecosystem and the use of software statement assertions to facilitate registrations between Initiator and Provider.

{% include spec_releases_table.html repo="datarightplus-admission-control-baseline" name="draft-authors-datarightplus-admission-control" releases="" %}

# Support

## DataRight+: Discovery

The DataRight+: Discovery specification describes a mechanism for resource endpoint and functionality discovery.

{% include spec_releases_table.html repo="datarightplus-discovery" name="draft-authors-datarightplus-discovery" releases="" %}

## DataRight+: Enhanced Endpoint Versioning

The DataRight+: Enhanced Versioning specification extends the versioning scheme used within the Consumer Data Right to versioned request and response payloads.

{% include spec_releases_table.html repo="datarightplus-enhanced-versioning" name="draft-authors-datarightplus-enhanced-versioning" releases="" %}

# Reference Documents

## Rosetta Stone

The Rosetta Stone is intended to provide a translation layer between DataRight+ documents and jurisdictional terms utilised in both legal frameworks and the ecosystem standards being used to drive them. The intent of delivering this informational document is to remove ambiguity from the broader specification set by isolating, generally legal, terms within a single document.

{% include spec_releases_table.html repo="datarightplus-rosetta" name="draft-authors-datarightplus-rosetta" releases="" %}

---

[Financial-grade API Security Profile 1.0 Part 2: Advanced]: https://openid.net/specs/openid-financial-api-part-2-1_0.html
[<i class="fa fa-github"></i> GitHub]: https://github.com/