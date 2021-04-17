## OASIS 🏁

Software systems for vending and exchange.

> Rather than slowly amass votes until some critical mass would allow state retreat (if the new statists did not change sides to protect their new vested interests), one could commit civil disobedience profitably,... having lower costs and (potentially) greater efficiency than one's statist competitors – if any.

The integration of MobileCoin in Signal represents the first time prototypical grandparents (or: "non-tech people") have ready access to exchange representations of value securely with a global population. Unfortunately, MobileCoin's minimalist design and absence of an integrated on-chain VM prevents the ready deployment of standard smart-contract solutions for escrow, or secure and integrate with existing third-party vending platforms.

As a result, individuals interested in vending via Mobilecoin chat-ops require the ability to define inventory, monitor transactions, host interactive agents, and cash out MOB for BTC, tokenized stablecoins, and anonymity oriented currencies.

On top of the dubiously unfortunate support for on-chain escrow, [Signal-CLI](https://github.com/AsamK/signal-cli) does not include the MobileCoin wallet abstractions implemented in [Signal-Android](https://github.com/signalapp/Signal-Android) - so there's no immediately available path forward for ie) deploying interactive online Signal+MOB agents as Docker containers or function-as-a-service artifacts.

This said, while existing software infrastructure doesn't meet the needs of vendomats, it seems as if a path forward exists, combining a hosted mobilecoind instance, [libsignal-protocol-javascript](https://github.com/signalapp/libsignal-protocol-javascript) and [Cloudflare Durable Objects](https://developers.cloudflare.com/workers/learning/using-durable-objects) to terminate E2E order and payment messages in a robust and secure manner, enabling the development and proliferation of high availability and high confidentiality automated agents with payment enablement and data transfer.

To explore, prototype, refine, and document viable solutions for Signal/MOB-based vending, we are recruiting donations in MOB and XMR to support the long-term rental of a dedicated OVH server with SGX support for hosting `mobilecoind` and prototype VMs, fund a few Cloudflare workers accounts, and incentivise developer time.
