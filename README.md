# Crypto Audits 

[MIT license with attribution](https://github.com/electric-capital/crypto-audits-draft/blob/main/LICENSE)

🌲 Crypto Audits is a mapping for sharing data around audit reports and bug bounties for crypto protocols and tying them to protocol websites. All of the protocols are specified in [TOML](https://github.com/toml-lang/toml) configuration files.

This repository is not complete, and hopefully it never is as there are new audit reports and bug bounties being published every day. We are looking for help from the community to help us grow this initiative.

## How to Contribute

There's a couple of ways you can help grow this initiative.

### Option 1: Opening a Pull Request

You can make any .toml file for a protocol under the `/data/protocols` directory or edit an existing one to help improve data around a protocol.

You can fork this repository and open a PR from the forked repo to this repo. 

#### Data Format

An example configuration file for the Lido protocol looks like this:

```toml
# Protocol Level Information
title = "lido"
website = "https://lido.fi/"

# Audits
# This is a list of links to associated audit reports and bug bounties. 
# These URLs do not necessarily have to be on GitHub, we use Way Back Machine and other archival tools to ensure that the links are always available.
[[audit]]
url = "https://github.com/lidofinance/audits/blob/main/Certora%20Lido%20V2%20Audit%20Report%2004-23.pdf"

[[audit]]
url = "https://github.com/lidofinance/audits/blob/main/ChainSecurity%20Code%20Assessment%20of%20the%20Lido%20Smart%20Contracts%20Report%2008-22.pdf"

[[audit]]
url = "https://github.com/lidofinance/audits/blob/main/ChainSecurity%20Lido%20Staking%20Router%20audit%20report%2002-23.pdf"
```

By specifying the data as evolving config files in git, we benefit from a long term, auditable database that is both human and machine readable.

## How to Give Attribution For Usage of the Electric Capital Crypto Audits 

To use the Electric Capital Crypto Audits Map, you will need an attribution.

Attribution needs to have 3 components:

1. Source: “Electric Capital Crypto Audits Mapping”
2. Link: https://github.com/electric-capital/crypto-audits
3. Logo: [Link to logo](https://drive.google.com/file/d/1DAX6wmcbtia7kaP5AaUWyg6t-ZEW9z22/view?usp=sharing)

Optional:
Everyone in the crypto ecosystem benefits from additions to this repository.
It is a help to everyone to include an ask to contribute next to your attribution.

Sample request language: "If you’re working in crypto security, submit your reports here to be counted."

<ins>Sample attribution</ins>

Data Source: [Electric Capital Crypto Audits Mapping](https://github.com/electric-capital/crypto-audits)

If you’re working in crypto security, submit your work [here](https://github.com/electric-capital/crypto-audits) to be counted and help make it easier for everyone to find your work.