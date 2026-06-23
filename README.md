# JumpList Covert Channel

> A covert messaging technique embedded inside Windows JumpLists in a shared Active Directory workspace.

## ⚠️ Responsible disclosure note
This research is published for educational and defensive purposes.
The technique is documented so defenders can detect and remediate it.

## What this is
Windows JumpLists are files automatically maintained by the OS to track recently accessed
files and applications. In a shared workspace (shared drives, AD environment), these files
are accessible across the network — and can be weaponized as a covert communication channel.

**Key properties of this channel:**
- No custom malware or executables required
- Uses OS-native file management (low suspicion)
- Persists across sessions
- No traditional network communication signatures

**This technique has no prior public documentation** (verified before publishing).

## How it works
[Technical breakdown — include diagrams, code snippets, and step-by-step explanation]

## Detection (for defenders)
[Document what artifacts exist, what log events fire, what a defender would see]
- Relevant event IDs: [list them]
- Artifacts on disk: [list paths]
- SIEM query to detect: [include query]

## MITRE ATT&CK mapping
- Tactic: [e.g. Command and Control / Lateral Movement]
- Technique: [closest relevant T-code]

## Tools used
- Windows AD lab environment
- [Any specific tools used in research]

## Lab setup
[Describe the environment where this was developed and tested]

## References
[Any papers, OS documentation, or prior work you built on]
