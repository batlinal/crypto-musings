# Crypto 2.0 Musings - DApp Centralisation

For the last few months I have been grappling with a gut feeling that somehow Ethereum’s smart contract based distributed application (DApp) model has a different dynamic to that of hardwired protocols like Bitcoin or Ripple. This week that feeling has crystalized into a semi coherent thought.

Hardwired protocols do not have a separation of concern between the protocol and business logic. Same set of protocol designers, software developers and miners control how the emergent distributed autonomous organisation (DAO) functions.

It’s different for DApps - there is a clear separation of concern between the protocol and business logic encapsulated in the smart contract. Dynamics of how a DApp based protocol evolves can be similar to Bitcoin, yet very different for DApps themselves – they can have a clearly attributed owner e.g. person or organisation that wrote the smart contract, or uploaded it, or charges an ether fee for it’s use.

This presents an unexpected, to me at least, risk of centralisation. Sure, the protocol may be distributed and hence the operation of the DApp is also distributed, but if many other DApps use a unilaterally controlled shared smart contract, then at least at the logical level you get back to a centralised model, which in some cases you may wish to avoid.

This is not necessarily an issue if managed well. Highly shared smart contracts could be recognised as key infrastructure components and be formally owned and managed by some form of open software foundation (OSF), be that Ethereum Foundation or some other body. Key here is that there should be no confusion about who owns the smart contract and what obligations they have.

Alternatively, you could write mirrored smart contracts to mitigate centralisation risk e.g. lets say two parties need to track bi-lateral obligations, each would deploy their own instance of the smart contract, and each instance would track nostro and vostro views of obligations. Technically this is less efficient as you are double tracking data, but it does offer a simpler ownership model.

That said, there is no reason why smart contacts cannot be privately owned even if highly shared, as long as they provide unique value and users fully understand associated risks. Assuming that the contract owner fixes fees in code, price hike risk is mitigated in the on-chain world compared to traditional intermediation business.

Once you start charging fees for use of your DApps, you have to be clear what you are charging for. Are you charging for the license to deploy an own instance of a smart contract and use of the DApp wallet – a bit like buying an app from an App Store, or for a service provided by an already deployed smart contract?

Arguably, since it is really the miners that provide the service of actually executing and validating the transactions, it’s hard to justify charging a service fee for smart contracts, unless there are many value add off-chain services bundled together with the DApp.

Based on that assessment, we may end up with a DApp Store model where folks purchase a licence to deploy an instance of a well written, standards compliant, tested and proven DApp onto a blockchain. This however implies that the DApp creator does not provide operational guarantees, so who does?

There are parallels today e.g. iOS developers rely on Apple to provide the device, the OS and the App Store, and both rely on the broadband and mobile internet service providers (ISPs) to provide connectivity, but none of them guarantee entire front to back service to the app user.

Conclusion therefore is that a new type of entity is required – a blockchain service provider (BSP). Essentially this is today’s Bitcoin or Ethereum miner/validator equivalent, but one that provides guarantees and maintains full nodes that can be used by lightweight end user wallets. The BSP is likely to be running on a Blockchain as a Service (BaaS) cloud compute platform e.g. Microsoft’s Azure platform is already supporting multiple blockchains.

Such a construct is required to have clear legal responsibility for the entire supply chain i.e. an end user must formally accept the terms and conditions of the DApp wallet, the DApp smart contract and the BSP.

> a blockchain business is a trusted business

Multiple interconnected BSPs will be required to provide adequate level of trust, which will be higher than one provided by a centralised service, since no single participant is able to alter any part of the system unilaterally. In other words, a blockchain business is a trusted business. You then will need to decide if you need the enhanced trust or not for your specific use case.
