### [Walrus Sites Provenance](https://github.com/zktx-io/walrus-sites-provenance)
---

A GitHub Actions-based workflow that enables verifiable static site deployments to [Walrus Sites](https://wal.app). It automatically builds the site, generates a `.intoto.jsonl` provenance file, signs it using [Sigstore](https://sigstore.dev), and uploads both the site and provenance data, ensuring tamper-resistant and traceable deployments.

## Tooling Category
- [ ] SDKs  
- [ ] Visualization  
- [ ] Cli Tools  
- [x] Walrus Sites

## Homepage or Repo or Download Link  
- [GitHub Repository](https://github.com/zktx-io/walrus-sites-provenance)  
- [GitHub Marketplace](https://github.com/marketplace/actions/walrus-sites-provenance)
- [Docs](https://docs.zktx.io/slsa/walrus-sites-provenance.html)

## Features
- Generates signed `.intoto.jsonl` provenance file
- Supports GitHub OIDC or GitSigner-based PIN approval
- Fulfills SLSA Level 3 provenance guarantees
- Seamless integration with Walrus Sites deployments
- Automatically embeds provenance in `.well-known/`
- Compatible with verification via [notary.wal.app](https://notary.wal.app)

## Documentation or Tutorial
- [Getting Started Guide](https://github.com/zktx-io/walrus-sites-provenance#readme)  
- [Example Deployment Repo](https://github.com/zktx-io/walrus-sites-provenance-example)
- [Docs](https://docs.zktx.io/slsa/notary.html)

## Latest Version Number of Walrus Tested On
mainnet