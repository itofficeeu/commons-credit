# commons-credit

A Post-Money Ledger
How Communities Can Keep Trading When the Grid Goes Dark

When every payment rail—from bank APIs to mobile wallets—assumes a live internet and a functioning central bank, what happens if they all blink out? It’s a scenario that once lived only in dystopian fiction, yet resilience planners, homesteaders, and eco-villages now model it seriously.

One promising fallback is a decentralised, offline-first time-credit ledger: people log the hours they spend helping each other, those hours become spendable credit, and the records live on every participant’s phone rather than in one data centre.
Below is a sketch of how such a system could work, the twists we’ve added to make it community-ready, and an open invitation to turn the sketch into a lifeline.
1 The Simple Core

    Double-entry hour accounting – Every “2 h carpentry” post debits the giver and credits the receiver, so balances across the whole network always net to zero.

    Local keys, local data – Each phone keeps its owner’s signed transaction log; devices gossip updates whenever they meet over Bluetooth, Wi-Fi Direct, or satellite texting.

    Offline first, online when available – If the wider net returns, the same data-sync layer can ride conventional bandwidth unmodified.

2 Taxes Without Bureaucrats

Real villages need roads, a root cellar, maybe even a shared solar array. We graft a built-in VAT-style slice onto every transaction:

Giver logs 2 h  →
  1.80 h to receiver
  0.15 h to “State” fund
  0.05 h to “Community” fund

Those fractions accumulate in dedicated treasury accounts and can later be “spent” as labour on collective projects—without spreadsheets or cash.
3 Going Beyond One Village

Each settlement (≈ 300–600 people) runs its own ledger, but treasuries can open trust-lines to neighbours:

    AliceVille ↔ BobTown agree on a 500 h credit limit.

    Cross-village trades route through the two treasuries, applying each side’s tax rate automatically.

    Exchange rates can float: 1 h of grain labour may equal 1.2 h of carpentry labour if demand shifts.

4 People as Natural Gateways

Nothing stops a single person holding balances in several villages:

    Relocation – Move to a new eco-village? Open a second account while your first balance continues ticking.

    Travel – Regular travellers’ phones become human-mesh “banks,” clearing small debts between settlements long before councils schedule bulk settlements.

These multi-home members boost liquidity, share skills, and spread economic shocks across the network instead of letting them fester locally.
5 Why This Matters To…
Community	Benefit
Preppers & homesteaders	Store food and fuel—now store cooperative credit.
Amenities & eco-villages	Replace brittle SaaS barter apps with tooling you can audit, fork, and patch.
Remote settlements	Where cash supply chains already fail, a phone-to-phone ledger keeps value fluid.
Municipal resilience planners	Acts as a bottom-up continuity layer that still respects tax collection once the state reconnects.
6 What’s Still Needed

    A reference implementation (Holochain, local-first CRDT, or an L2 smart contract—let’s test them all).

    UX that feels like Venmo, not a command line.

    Cryptographic “selective disclosure” so users can prove balances without publishing every favour.

    Governance templates: credit limits, dispute resolution, code-change voting.

7 An Open Invitation

No single founder should—or could—own a survival tool like this. We need cryptographers, food-system wonks, UI designers, village planners, and plain-spoken testers who can run a beta on patchy 3 G.

Next step → If this sparks your curiosity, open an issue, share a use-case, or link code you’ve already written. Once interest clusters, we’ll spin up weekly chats so anyone can push the idea forward.

Let’s make sure that even if the money tap turns off, cooperation doesn’t.

Licence suggestion: We recommend AGPL v3 so every hosted deployment stays open for security review and community improvement.
Working repo name: lifeboat-ledger (or pick your favourite from the README discussion).

#ResilienceEngineering #MutualCredit #TimeBank #Decentralization #CommunityEconomics #OpenSource
