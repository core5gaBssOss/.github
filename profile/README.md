# AI-Boosted 5G-Advanced Core, BSS and OSS

An open-source 5G Core, charging and BSS implementation in modern C++, targeting 3GPP Release 19
(5G-Advanced). Every Network Function's API is generated from the official 3GPP OpenAPI YAML.

- **5G Core:** NRF, AMF, SMF, UPF, PCF, UDM, UDR, AUSF and Release 19 NFs, over HTTP/2 SBI with
  mTLS and OAuth2.
- **Charging and BSS:** the CHF of TS 32.290/32.291, with Diameter Gy, Sy and CAMEL/CAP, and TM
  Forum SID-aligned BSS services.
- **OSS:** an operator console, performance counters and alarms.
- **AI:** NWDAF analytics and AI-assisted charging decisions. The model advises; a deterministic
  engine decides.

It is a reference implementation that aims at production grade, and it is not deployable in
production yet.

| Repository | What |
|---|---|
| [core5gaBssOss](https://github.com/core5gaBssOss/core5gaBssOss) | The code, Helm charts and documentation |

Licensed under Apache-2.0. Report vulnerabilities privately, as described in the
[security policy](https://github.com/core5gaBssOss/core5gaBssOss/security/policy).
