# Unofficial research fork

This repository is an unofficial research fork of [AIDEFEND AI Defense Framework](https://github.com/edward-playground/aidefense-framework), created by Edward Lee. It does not imply collaboration, affiliation, or endorsement by the upstream author.

**Upstream baseline:** [0508e69287ed5ad44f9b7cc9a047b381a181290d](https://github.com/edward-playground/aidefense-framework/commit/0508e69287ed5ad44f9b7cc9a047b381a181290d).

## Local changes

The following files contain localized illustrative examples:

| File | Modification |
| --- | --- |
| `kids/kids-main.js` | English and Chinese introductions use generic AI-assistant examples. |
| `tactics/detect.js` | One demonstration host filter uses `assistant.example` as a synthetic placeholder, with an explicit instruction to configure approved service domains. |
| `tactics/harden.js` | One defensive prompt-test fixture addresses a generic assistant. |
| `tactics/model.js` | One illustrative service-catalog record uses a synthetic service ID and the example domains `assistant.example` and `api.assistant.example`. |

Synthetic domains are documentation placeholders, not operational detection coverage or provider mappings. Review and replace them with authorized environment-specific records before operational use. The surrounding algorithms are retained; the examples are not claims of tested production defenses.

Each modified source file carries a modification notice. Original license files, copyright notices, source attribution, and inherited commit history are preserved.

## Attribution and licenses

AIDEFEND AI Defense Framework, created by Edward Lee, https://aidefend.net, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

Framework content and data remain subject to [LICENSE-CONTENT](LICENSE-CONTENT). Software remains subject to [LICENSE](LICENSE), except where another notice applies. See [LICENSING.md](LICENSING.md), [NOTICE](NOTICE), [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md), and [TRADEMARKS.md](TRADEMARKS.md). These local changes do not remove third-party rights, grant trademark rights, or establish official status.
