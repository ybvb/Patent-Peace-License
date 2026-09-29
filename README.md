# Patent Peace License

A permissive license that exists so that people who offer their work to the world are left in peace to do so, and so that a higher, mutually agreed standard of business and collaboration can be protected in a future of democratized and decentralized development, for everyone who develops, however they develop.

It asks one thing of everyone: that no patent be used against the shared work. It doesn't punish anyone who does; it dissolves the patent so used, and the way back stays open. The peace it protects belongs to no one and is held in common by everyone who upholds it.

Good-faith users get the freedoms of a permissive license: private repos, proprietary products, commercial use, no obligation to publish changes. Nothing in the patent sections affects anyone who never uses a patent against a protected work.

Current version: **1.0**, in [`PATENT-PEACE-LICENSE-1.0.txt`](PATENT-PEACE-LICENSE-1.0.txt)
SPDX identifier: `LicenseRef-Patent-Peace-1.0`

## How it works

The license is the text of the Apache License 2.0 with a preamble and four added sections.

| Section | What it does |
|---|---|
| **10. Patent Peace** | If anyone makes an unprovoked patent claim against a Protected Work (an *Attack*), then at that moment the patents they used, and every patent they hold, become licensed to everyone for Protected Works, so the attack dissolves. The person who attacked steps outside the peace: their rights under the license end, they stop distributing the work, they make their target whole for costs and damages, and on request they disclose their patents and patent transfers so the scope of the new license can be known. The way back is always open: withdraw the attack and make the target whole, and all rights return. Counterclaims stay allowed, and anyone with standing may act as a guardian for the person attacked, asserting their own patents against the attacker until the attacker takes the way back. Every person who builds on or uses a Protected Work can rely on all of this directly; no central owner or organization is needed. |
| **11. Excluded Rights and Separation** | The license never claims to grant rights it can't grant, such as a third party's earlier patent. If part of a work turns out to be covered by such a right, that part can be removed or replaced, and everything else stays fully licensed. Good-faith inclusion is not a breach. Attackers can't hide behind this: every patent they hold remains subject to Section 10. |
| **12. Offer of Adoption** | Before starting an intellectual-property dispute, a licensee first offers the other side to resolve it by adopting this license. The offer is an invitation only: it may never be coerced, declining carries no penalty, omitting it costs no rights, and the offer is made without prejudice. It rests on understanding, not enforcement. |
| **13. Successor Licenses** | Anyone may write a better license that succeeds this one. A successor qualifies if it is open and free, gives good-faith users at least the same freedoms, protects Protected Works at least as fully, and keeps this same path open. Anyone may then choose to use a work under a qualifying successor. No one can be forced to choose one, and no choice weakens the peace. |

### What this license cannot do

- **It binds only those who accepted it.** Someone who never used, modified, or distributed a work under this license is not bound by it. Against outsiders, the effective protection is prior art: publish your ideas early, in dated, detailed form, so nobody can later patent them.
- **It cannot cancel third-party patents.** Section 11 keeps the rest of a work usable and separable, but a valid patent held by an outsider still applies to the part it covers.
- **Its enforceability is untested.** No court has ruled on this license. It applies everywhere "to the maximum extent permitted by applicable law," and unenforceable parts are severed rather than voiding the whole.

## How to adopt it

1. Copy [`PATENT-PEACE-LICENSE-1.0.txt`](PATENT-PEACE-LICENSE-1.0.txt) into your repository as `LICENSE`.
2. **Optional:** add a `PATENT-PEACE-FIELD` file describing a field of technology. Every work in that field then becomes a Protected Work, including works that don't use your code, as far as attacks by licensees go. A field can later be widened, but narrowing or removing it never reduces protection for versions already released with it.
3. Add this header to each source file:

   ```
   Licensed under the Patent Peace License, Version 1.0 (the "License");
   you may not use this file except in compliance with the License.
   A copy of the License is included in the LICENSE file distributed
   with this work.

   SPDX-License-Identifier: LicenseRef-Patent-Peace-1.0
   ```

   A copyright line is optional. Copyright exists without one, and authors may stay anonymous or use a collective name such as "The Example Authors."

4. If you use the [REUSE](https://reuse.software) convention, place the text at `LICENSES/LicenseRef-Patent-Peace-1.0.txt`.

## Versions and successors

Each version is frozen once published; corrections become a new version with a new file. There is no "or any later version" clause, so no central author can change the terms of works already released.

Improvement happens instead through Section 13: anyone, anywhere, may write a successor. Whether it qualifies depends on what it does, not on who wrote it: it must give at least the same freedoms and at least the same protection, and keep the same path open for the next one. The license text is not licensed under itself; its text is free to use, adapt, and succeed (see [`LICENSE`](LICENSE)).

## Status

- Not approved by the Open Source Initiative (OSI), and not on the SPDX License List.
- Not reviewed by a lawyer. It is published as a design, not as legal advice. Anyone adopting it for significant work should have it reviewed by a lawyer experienced in open-source licensing and patents.
- Based on the Apache License 2.0 text, copyright The Apache Software Foundation. It is not the Apache License and is not endorsed by the Apache Software Foundation.

Also, I basically found this on the floor: it stands on the shoulders of the Apache License 2.0 and of the collective human work that trained and created AI models such as Claude Opus 5.5, which was used in drafting it.

Lastly, I credit David Hawkins' Power vs. Force framework, not for its controversial claims, but for the levels-of-consciousness lens used here, in collaboration with Claude and with my own mind and experiences, which together formed it.
