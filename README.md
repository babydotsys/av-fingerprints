# av-fingerprints

This is a partial replication of results of the "[AVLeak:
Fingerprinting Antivirus Emulators Through Black-Box Testing](https://www.usenix.org/system/files/conference/woot16/woot16-paper-blackthorne_update.pdf)" paper that was presented at WOOT '16 and Black Hat USA 2016. Techniques from the paper are used to leak "fingerprints" from the x86 Windows emulators of various AV software. This can be used to develop and detect evasive malware.

Special thanks to Alexei Bulazel ([@0xAlexei](https://twitter.com/0xAlexei)) for his assistance.

|   | [8C777025](8C777025.md) | [949A2A6D](949A2A6D.md) | [A3150A5E](A3150A5E.md) | [B50C3DF2](B50C3DF2.md) |
|:--|:-----------------------:|:-----------------------:|:-----------------------:|:-----------------------:|
| **Environmental Artifacts** | [3](8C777025.md#environmental-artifacts) | [3](949A2A6D.md#environmental-artifacts) | [4](A3150A5E.md#environmental-artifacts) | [3](B50C3DF2.md#environmental-artifacts) |
| **OS API Inconsistency**    | 0 | [2](949A2A6D.md#os-api-inconsistency) | 0 | [1](B50C3DF2.md#os-api-inconsistency) |
| **Network Emulation**       | 0 | 0 | 0 | 0 |
| **Timing**                  | 0 | 0 | 0 | 0 |
| **Process Introspection**   | 0 | 0 | 0 | 0 |
| **CPU “Red Pills”**         | 0 | 0 | 0 | 0 |
