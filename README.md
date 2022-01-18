[![Build Status](https://travis-ci.org/Fundamentally-Uncentralizable-Cookies/Epicoin.svg)](https://travis-ci.org/Fundamentally-Uncentralizable-Cookies/Epicoin) [![Latest](http://github-release-version.herokuapp.com/github/Fundamentally-Uncentralizable-Cookies/Epicoin/release.svg?style=flat)](https://github.com/Fundamentally-Uncentralizable-Cookies/Epicoin/releases/latest)

[![Logo](LOGO.png)](https://ashwinsk01.github.io/epitacoin.github.io)
# [Epicoin](https://ashwinsk01.github.io/epitacoin.github.io)
Epita S2 Project. Epicoin is a blockchain where the proof of work is done by the solving of NP-Complete problems.

### Structure
Epicore is the core library of Epicoin, providing all components, their API, as well as methods for initialization, execution and termination. All in all, epicore is an active, asynchronous, self-managing library - it is a library with start/stop lifecycle, that runs asynchronously (from caller) on parallel thread(s), and self-manages (between lifecycle calls). Being a library, it has no entry point and caller must use its' lifecycle calls. It is located in `/Core`.

### Use Cases
NP-Complete problems are faced on a daily basis in both academia and industry. These problems occur in a wide range of areas such as asset management,storage optimization, or production of printed circuit boards...

Both of these actors would benefit from having a list of problems and their solutions as it would be quicker to explore the list than to solve the problem themselves. A layer of abstraction could even be added on top of Epicoin in order to further facilitate the reading process by having a server observe the Epicoin network and keep a sorted list of Epicoin’s solutions.

From a financial perspective, the value of Epicoin should be backed by the fact that these actors would benefit from keeping the EFOBE alive. Having a minimal threshold for its value, a better and optimized version of Epicoin(v3) could to a certain extend guarantee that its mining is profitable given that the offer does not exceed the demand too much. Fortunately, if there is more offer, the table grows bigger and interests more people. Thus, we have at least in theory a guarantee that a minimal number of miners would be present at any time on the Epicoin network.

`/Tests` contains various unit tests for all epicore components and utils.

Default baseline command line interface is provided in `/CLI`.

---
**[More information is available on the official website, epitacoin.ml](https://ashwinsk01.github.io/epitacoin.github.io)**
