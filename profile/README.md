<!-- research-legitbiz/.github → profile/README.md -->

```
 _            _ _   _      _
| | ___  __ _(_) |_| |__  (_)____
| |/ _ \/ _` | | __| '_ \ | |_  /
| |  __/ (_| | | |_| |_) || |/ /
|_|\___|\__, |_|\__|_.__(_)_/___|   --research
        |___/
```

```console
anon@legitbiz:~$ cat /etc/motd
research. that's legitimate.
```

**legit{biz} --research** is a small computer-security R&D collective. We read the
advisories, break the thing in a lab, and write down what we learned: proof-of-concepts
for *already-disclosed* vulnerabilities, bug bounty writeups, privacy/OPSEC tooling, and
the occasional philosophy paper on what all of this means.

---

### `$ ls ~/research`

| dir | what lives there |
|---|---|
| `pocs/` | Working proof-of-concepts for publicly disclosed CVEs, built to understand the bug, not to weaponize it |
| `writeups/` | Bug bounty reports and vuln breakdowns, published after the fix and with permission |
| `tools/` | Open-source utilities for privacy, OPSEC, and OSINT self-audits |
| `papers/` | Longer-form essays on security, technology, and theory |

### `$ ls ~/repos`

| repo | description |
|---|---|
| [`unredact.tools`](https://github.com/research-legitbiz/unredact.tools) | Local-first OPSEC for files. Scans images, PDFs, Office docs, and media for GPS, serials, usernames, hidden text, and failed redactions, then writes a clean copy. |
| [`doxxx`](https://github.com/research-legitbiz/doxxx) | Email and username footprint scanner for auditing your *own* exposure, based on upstream [`kaifcodec/user-scanner`](https://github.com/kaifcodec). |
| [`hydra_onion`](https://github.com/research-legitbiz/hydra_onion) | THC-Hydra over Tor. Lab tooling that goes with our Hydra tutorials and upstream contributions. |

Other tools from members: [`govint`](https://github.com/NPCmillionaire/govint) ·
[`openpacer`](https://github.com/NPCmillionaire/openpacer) ·
[`foiatool`](https://github.com/NPCmillionaire/foiatool) ·
[`cryptopastebin`](https://github.com/NPCmillionaire/cryptopastebin) ·
[`bettercaptui`](https://github.com/NPCmillionaire/bettercaptui)

### `$ ./vuln-breakdown --now-playing`

**Vuln Breakdown** is our faceless video series. It covers newly disclosed vulnerabilities
end to end: what broke, why it broke, a terminal-first PoC walkthrough, and how to patch
it. It's written for mid-to-advanced security and CS folks, so there's no hand-holding.

### `$ whoami`

```
NPCmillionaire   tools, PoCs, writeups          github.com/NPCmillionaire
bodegaCat        philosophy & theory            (pen name)
you?             see CONTRIBUTING below
```

### `$ cat CONTRIBUTING`

- We publish only **disclosed** vulns (a CVE has been assigned, a patch is out, or the vendor has signed off).
- Bounty writeups follow the program's disclosure policy. If the program says no, we don't publish.
- Every PoC targets a lab you own. Nothing in this org is for use against systems you aren't authorized to test.
- Want to contribute a writeup, a tool, or a paper? Email us and send a link to your work.

### `$ cat SECURITY`

Found a bug in one of **our** tools? Please report it privately to
**research@legitbiz.xyz** and don't open a public issue. We'll reply, fix it, and credit you.

### `$ cat /contact`

```
web     https://research.legitbiz.xyz
main    https://legitbiz.xyz
mail    research@legitbiz.xyz
```

<sub>Nothing here is financial or legal advice. Tools are provided as-is for education and
authorized testing.</sub>
