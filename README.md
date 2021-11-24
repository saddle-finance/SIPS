# SIPs [![Discord](https://img.shields.io/discord/780508954916290610.svg?color=768AD4&label=discord&logo=https%3A%2F%2Fdiscordapp.com%2Fassets%2F8c9701b98ad4372b58f13fd9f65f966e.svg)](https://discordapp.com/channels/780508954916290610/) [![Telegram](https://img.shields.io/badge/chat-on%20Telegram-blue.svg)](https://t.me/saddle_finance) [![Twitter Follow](https://img.shields.io/twitter/follow/saddlefinance.svg?label=saddlefinance&style=social)](https://twitter.com/saddlefinance)

Saddle Improvement Proposals (SIPs) describe standards for the Saddle platform, including core protocol specifications, client APIs, and contract standards.
 
## Contributing

 1. Review [SIP-0](SIPS/sip-0.md).
 2. Fork the repository by clicking "Fork" in the top right.
 3. Add your SIP to your fork of the repository. There is a [template SIP here](sip-X.md).
 4. Submit a Pull Request to Saddle's [SIPs repository](https://github.com/saddle-finance/SIPS/).

Your first PR should be a first draft of the final SIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new SIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a new thread on [saddle.community](https://www.saddle.community/) where people can discuss the SIP as a whole.

If your SIP requires images, the image files should be included in a subdirectory of the `assets` folder for that SIP as follow: `assets/sip-X` (for sip **X**). When linking to an image in the SIP, use relative links such as `../assets/sip-X/image.png`.

When you believe your SIP is mature and ready to progress past the WIP phase, you should ask to have your issue added to the next governance call where it can be discussed for inclusion in a future platform upgrade. If the community agrees to include it, the SIP editors will update the state of your SIP to 'Approved'.

## SIP Statuses

* **WIP** - a SIP that is still being developed.
* **Proposed** - a SIP that is ready to be reviewed in a governance call.
* **Approved** - a SIP that has been accepted for implementation by the Saddle community.
* **Implemented** - a SIP that has been released to mainnet.
* **Rejected** - a SIP that has been rejected.
* **Withdrawn** - a SIP that has been withdrawn by the author(s).
* **Deferred** - a SIP that is pending another SIP/some other change that should be bundled with it together.
* **Moribund** - a SIP that was implemented but is now obsolete and requires no explicit replacement.

## Validation

SIPs must pass some validation tests.  The SIP repository ensures this by running tests using [html-proofer](https://rubygems.org/gems/html-proofer).

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
