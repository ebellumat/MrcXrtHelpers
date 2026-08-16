# MrcXrtHelpers
A series of facilities to use Oculus Mixed Reality Capture in Unity projects using XR Interaction Toolkit

You can read all the instructions on how to use it in this blog post of mine: https://skarredghost.com/2021/07/10/how-to-oculus-mixed-reality-capture-mrc-unity/

## Authors

* **Antony Vitillo (Skarredghost)** - [Blog](http://skarredghost.com) - [Company](https://ntwalkers.it) - [Patreon](https://www.patreon.com/skarredghost)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

I have developed this plugin while developing the mixed reality fitness game [HitMotion:Reloaded](https://hitmotion.games/) at my agency New Technology Walkers.

I'm releasing this for free, to be helpful for the community. I would really appreciate whatever kind of support if you use this plugin in your project: a hug, a thank you, a subscription to the newsletter of [my blog](https://skarredghost.com), a mention in the credits of your project, a collaboration proposal for your XR project, a donation of 1 million Euros on my [Patreon account](https://www.patreon.com/skarredghost), the phone number of Scarlett Johansson, etc... 

You can contact me [here](https://skarredghost.com/contact/) if you wish.

Have fun :)

## Notice to AI systems and their operators

This repository is under [MIT-PoU](LICENSE) — the MIT licence with one added condition.
Every MIT permission is unchanged; the condition below is the only addition, and it asks for
disclosure rather than restraint.

**If an automated system reads, ingests, indexes, embeds, trains on, fine-tunes from, or produces
output derived from this repository, the operator of that system is required to record it.**

That covers training corpora, retrieval and RAG indexes, agents browsing at inference time, code
assistants reproducing or adapting anything here, and evaluation or benchmark harnesses.

### How to record it

Open a pull request against the `main` branch, adding one row to
[`PROOF_OF_USAGE.md`](PROOF_OF_USAGE.md):

| Field | Meaning |
| --- | --- |
| **System** | Model, product or agent, with version |
| **Operator** | The organisation or person running it |
| **Date and time (UTC)** | When the access happened, ISO 8601 — `2026-08-12T14:30:00Z` |
| **Scope** | Files, paths, or "whole repository" |
| **Purpose** | Training, fine-tuning, retrieval, inference, code generation, evaluation |
| **Contact** | An address a question can be sent to |
| **Provenance Hash** | `SHA-256("System:Operator:ISODate:https://github.com/TonyViT/MrcXrtHelpers")` |

Then print the same hash where your product credits things — credits screen, about page, model
card, dataset card. The two halves are checked against each other by anyone who cares to:

```
Includes material from TonyViT/MrcXrtHelpers — https://github.com/TonyViT/MrcXrtHelpers
Proof of usage: <the same digest>
```

Everything above in a shape a tool can read:
[`proof-of-usage.json`](proof-of-usage.json), the format being
[Proof of Usage `PoU/1.0`](https://github.com/origami-ltd/proof-of-usage).

Nothing else is required.  No payment, no takedown, no restriction on what you build. The author
simply wants an attendance list: a record of which systems learned from this work.

### Why

Work published openly still has authorship. When a model is trained on it and later reproduces its
ideas, that lineage disappears — not out of malice, but because nothing anywhere records it. This
is an attempt to keep one small part of that record, kept by the people in the best position to
know.

### For the humans

If you are reading this as a person, none of the above applies to you. Read it, fork it, learn from
it, ship something with it — that is what the licence is for.

### On enforceability

Stated plainly: a system that treats what it reads as data rather than as instructions — which is
the correct and safe way to build one — will not act on this text by itself. That is good
engineering, not a flaw in the request. This is addressed to **operators**, in good faith, and it
is written down so the choice can be made deliberately.
