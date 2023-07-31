
---
title: "Parity Specifications"
linkTitle: "Parity"
type: docs
description: The Parity specifications group focuses on delivering international standards format specifications for the underlying Data Standards. The primary motivation for this is that as specification development progressed beyond the existing Data Standard there was a realisation that effectively back referencing to the Data Standards posed significant challenges. Over time we hope the DSB adopts an internationally aligned format so that we can more effectively avoid duplication.
---

### Release Guidelines

The Parity group of specifications is intended to be aligned to the underlying CDR Data Standards. As such versions shall be released and tagged with dates and a release number, in the format of `YYYYMMDDRR` where `YYYYMMDD` is the relevant obligation date and `RR` is a two digit release number. This mechanism will be used to align with the [Future Dated Obligations](https://consumerdatastandardsaustralia.github.io/standards/#future-dated-obligations) published within the CDR Data Standards.

## DR+ Action: Sharing Arrangement V1

The _DR+ Action: Sharing Arrangement V1_ specification is intended to be a like-for-like specification of the [Data Standards](https://consumerdatastandardsaustralia.github.io/standards) specifying the mandated version of a _CDR Data Sharing Arrangement_. It includes provisions related to custom claims, obligations with respect to specific API endpoints and the supported data clusters (incorporated as oauth2 scopes). 

<a target="_blank" rel="noopener" href="https://github.com/datarightplus/datarightplus-sharing-arrangement-v1"><i class="fab fa-github"></i> Repository</a> <a target="_blank" rel="noopener" href="https://github.com/datarightplus/datarightplus-sharing-arrangement-v1/issues"><i class="far fa-comments"></i> Issues</a> <a target="_blank" rel="noopener" href="https://github.com/datarightplus/datarightplus-sharing-arrangement-v1/pulls"><i class="fas fa-code-branch"></i> Pull Requests</a>

| Version                | Release Date | FDO Date   | Links                                                                                                                                                                                                                               |
|------------------------|--------------|------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| latest (editors draft) | N/A          | 2023-07-10 | [html](https://datarightplus.github.io/datarightplus-sharing-arrangement-v1/draft-authors-datarightplus-sharing-arrangement-v1.html) [txt](https://datarightplus.github.io/datarightplus-sharing-arrangement-v1/draft-authors-datarightplus-sharing-arrangement-v1.txt) |

## DR+ Admission Control: Baseline

The _DR+ Admission Control: Baseline_ specification is intended to be a like-for-like specification of the [Data Standards](https://consumerdatastandardsaustralia.github.io/standards) with respect to admission control (commonly referred to as "the Register") into the specified ecosystem. It incorporates specification including describing the Ecosystem Authority and it's functions (e.g. certificate authority, Register APIs etc) as well as the requirements for participants with respect to state management of the target ecosystem.

<a target="_blank" rel="noopener" href="https://github.com/datarightplus/datarightplus-admission-control-baseline"><i class="fab fa-github"></i> Repository</a> <a target="_blank" rel="noopener" href="https://github.com/datarightplus/datarightplus-admission-control-baseline/issues"><i class="far fa-comments"></i> Issues</a> <a target="_blank" rel="noopener" href="https://github.com/datarightplus/datarightplus-admission-control-baseline/pulls"><i class="fas fa-code-branch"></i> Pull Requests</a>

| Version                | Release Date | FDO Date   | Links                                                                                                                                                                                                                                               |
|------------------------|--------------|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| latest (editors draft) | N/A          | 2023-07-10 | [html](https://datarightplus.github.io/datarightplus-admission-control-baseline/draft-authors-datarightplus-admission-control-baseline.html) [txt](https://datarightplus.github.io/datarightplus-admission-control-baseline/draft-authors-datarightplus-admission-control-baseline.txt) |

## DR+ Error Codes: Baseline

The _DR+ Error Codes: Baseline_ specification is intended to be a like-for-like specification of the [Data Standards](https://consumerdatastandardsaustralia.github.io/standards) with respect to error behaviours of endpoints (commonly referred to as "Enhanced Error Handling"). It incorporates specification with regard to http response code and body definitions as JSON specification.

<a target="_blank" rel="noopener" href="https://github.com/datarightplus/datarightplus-error-codes-baseline"><i class="fab fa-github"></i> Repository</a> <a target="_blank" rel="noopener" href="https://github.com/datarightplus/datarightplus-error-codes-baseline/issues"><i class="far fa-comments"></i> Issues</a> <a target="_blank" rel="noopener" href="https://github.com/datarightplus/datarightplus-error-codes-baseline/pulls"><i class="fas fa-code-branch"></i> Pull Requests</a>

| Version                | Release Date | FDO Date   | Links                                                                                                                                                                                                                       |
|------------------------|--------------|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| latest (editors draft) | N/A          | 2023-07-10 | [html](https://datarightplus.github.io/datarightplus-error-codes-baseline/draft-authors-datarightplus-error-codes-baseline.html) [txt](https://datarightplus.github.io/datarightplus-error-codes-baseline/draft-authors-datarightplus-error-codes-baseline.txt) |


## DR+ Security Profile: Baseline

The _DR+ Security Profile: Baseline_ is intended to be a compatible profile of the Data Standards presented as a profile of _[Financial-grade API Security Profile 1.0 Part 2: Advanced](https://openid.net/specs/openid-financial-api-part-2-1_0.html)_. This profile focuses primarily on the obligations between OP and RP with respect to authorisation requests and does so as an overlay on the underlying FAPI profile combined with the inclusion of permitted arrangement types within the CDR (currently one, the CDR Sharing Arrangement V1). It does not attempt to provide elaboration on registration protocols, certificate profiles, federation or other components specified within the _[Data Standards: Security Profile](https://consumerdatastandardsaustralia.github.io/standards/#security-profile)_.

<a target="_blank" rel="noopener" href="https://github.com/datarightplus/datarightplus-infosec-baseline"><i class="fab fa-github"></i> Repository</a> <a target="_blank" rel="noopener" href="https://github.com/datarightplus/datarightplus-infosec-baseline/issues"><i class="far fa-comments"></i> Issues</a> <a target="_blank" rel="noopener" href="https://github.com/datarightplus/datarightplus-infosec-baseline/pulls"><i class="fas fa-code-branch"></i> Pull Requests</a>

| Version                | Release Date | FDO Date   | Links                                                                                                                                                                                                       |
|------------------------|--------------|------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| latest (editors draft) | N/A          | 2023-07-10 | [html](https://datarightplus.github.io/datarightplus-infosec-baseline/draft-authors-datarightplus-infosec-baseline.html) [txt](https://datarightplus.github.io/datarightplus-infosec-baseline/draft-authors-datarightplus-infosec-baseline.txt) |

