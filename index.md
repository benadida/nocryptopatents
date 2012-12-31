The End of Crypto Patents
===
Ben Adida - December 31st, 2012

Overview
--

Cryptographers have long noticed a large and growing gap between the latest research developments and what is used in practice. The reasons for this growing gap are many. One of them -- the systematic patenting of new crypto algorithms and methods -- is, in my opinion, insufficiently highlighted. Before we can truly consider the replacement of a major cryptographic building block -- RSA --, we must consider addressing this problem.

Crypto is Essential
--

Cryptographic algorithms are most useful in use cases that require interoperaiblity between systems, e.g. one party encrypts or signs, another party, using different software, decrypts or verifies. This is increasingly true with the ever-increasing dominance of the Web with multiple browser vendors -- including some fully open-source. Because cryptography mediates communication, it is typically only useful when it becomes part of a standard, formal or ad-hoc. Thus, new cryptographic algorithms are only interesting if they can play a part in these standards. In other words, cryptography is either essential or useful only to small niches.

Crypto is systematically patented
--

Since the advent of RSA, crypto algorithms have, for the most part, been patented. This makes crypto implementation work either particuarly onerous or particularly risky. In the case of open-source software, which comprises a large portion of the Web and contributes disproportionately to its generativity, patented algorithms are rarely usable.

If new crypto is patented, developers will use old crypto
--

The software industry is starting to understand that the cost of software patents to innovation far exceed any incentive they might provide. In the case of crypto patents, the situation is far worse: if new algorithms are patented, web developers will simply use older ones. We already have evidence that standards bodies and developers are falling far behind the state-of-the-art in cryptanalysis, using algorithms that are known to be broken. Continuing the patenting of crypto at a time when we begin to question the strength of the most broadly used crypto algorithm could make this situation far worse.

Proposal: open crypto
--

As an industry, we should follow the example set by http://www.openpatents.org/, a mutual non-aggression pact that freely licenses crypto patents to anyone, as long as they do not ever use a crypto patent aggressively. Crypto algorithms should be free for all to analyze, improve, and implement in any setting. Only then will we be able to move developers away from older algorithms and onto new, more secure ones.
