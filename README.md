## OASIS 🏁

Software systems for vending and exchange.

> Rather than slowly amass votes until some critical mass would allow state retreat (if the new statists did not change sides to protect their new vested interests), one could commit civil disobedience profitably,... having lower costs and (potentially) greater efficiency than one's statist competitors – if any.

The integration of MobileCoin in Signal represents the first time prototypical grandparents (or: "non-tech people") have ready access to exchange representations of value securely with a global population. Unfortunately, MobileCoin's minimalist design and absence of an integrated on-chain VM prevents the ready deployment of standard smart-contract solutions for escrow, or secure and integrate with existing third-party vending platforms.

As a result, individuals interested in vending via Mobilecoin chat-ops require the ability to define inventory, monitor transactions, host interactive agents, and cash out MOB for BTC, tokenized stablecoins, and anonymity oriented currencies.

On top of the dubiously unfortunate support for on-chain escrow, [Signal-CLI](https://github.com/AsamK/signal-cli) does not include the MobileCoin wallet abstractions implemented in [Signal-Android](https://github.com/signalapp/Signal-Android) - so there's no immediately available path forward for ie) deploying interactive online Signal+MOB agents as Docker containers or function-as-a-service artifacts.

This said, while existing software infrastructure doesn't meet the needs of vendomats, it seems as if a path forward exists, combining a hosted mobilecoind instance, [libsignal-protocol-javascript](https://github.com/signalapp/libsignal-protocol-javascript) and [Cloudflare Durable Objects](https://developers.cloudflare.com/workers/learning/using-durable-objects) to terminate E2E order and payment messages in a robust and secure manner, enabling the development and proliferation of high availability and high confidentiality automated agents with payment enablement and data transfer.

To explore, prototype, refine, and document viable solutions for Signal/MOB-based vending, we are recruiting donations in MOB and XMR to support the long-term rental of a dedicated OVH server with SGX support for hosting `mobilecoind` and prototype VMs, fund a few Cloudflare workers accounts, and incentivise developer time.


### Preliminary Goals and funding stages

 * ☑️ MET - €0 - discourse and discuss; identify and recruit small selection of high trust developers to enable and support initial designs
 * ☑️ DONE - €50 - proof of concept and derisking; identify prerequisite APIs and building blocks, proof fallback integration plans via android virt embed
 * ⬜ NEXT - €5000 - two people-weeks of full time integration and infrastructure work, beta launch of info/code-vending chatbot
 * ⬜ SRSLY - €50000 - one year of hosted servers funded and enablement software maintained, six person-months of integration and documentation work, public launch of DIY chatbot vending project, beta launch of hosted enablement
 * ⬜ ORLLY - €500000 - three person-years of integration and documentation work, verifiable autonomous escrow agent designed and funded, five-year LTS deployment playbook for enablement services, public bug bounty fund, grants for sponsoring vending teams for rhyzomatic growth, and surprise ecosystem enablement features (NFC h\*rdware wall\*t!?)
 * ⬜ NXTLVL - €5mm - Everything above, but done extremely right. Ten person-years of integration work including short-term horizontal team growth, sponsored coding bootcamp(s) for new devs, GB incorporation, Defcon29/Defcon30 party, guerrila marketing (airdr\*p?), advertising campaigns, and customer service agents.
