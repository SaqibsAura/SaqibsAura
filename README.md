<div align="center">

# Sheikh Mohammed Saqib

**Founder of [iMpact AI](https://impacts-ai.com) · Building [ORION](https://impacts-ai.com/orion) · UAE**

I build AI agents that do real work on a computer, and the engineering that makes them safe to trust.

[**impacts-ai.com**](https://impacts-ai.com) · [**ORION**](https://impacts-ai.com/orion) · [**iMpacts-AI on GitHub**](https://github.com/iMpacts-AI)

</div>

---

### Highlights

- **Founder of [iMpact AI](https://impacts-ai.com)**, an AI technology company building practical, trustworthy agents.
- **Building [ORION](https://impacts-ai.com/orion)**: a permission-based AI agent that operates your computer for you.
- **UAE Hackathon 2026 by TDRA**: selected to present a live ORION prototype (Sharjah, 2–4 November 2026, Responsible AI / Smart Government track).
- **Shipped a public [ORION showcase](https://github.com/iMpacts-AI/ORION)** with a one-command installer for Windows, macOS, Linux and ChromeOS.
- **Run the [iMpacts-AI](https://github.com/iMpacts-AI) GitHub organisation.**

---

### ORION

> Most AI tells you *how* to do something. ORION does it, with your permission, and checks that it worked.

You say what you want in plain words, like *"yo, pull up youtube"* or *"make a pdf about the benefits of reading"*,
and ORION carries out the steps on your computer.

- **Terminal-first** app built with TypeScript, Node.js and Ink
- **Local models** through Ollama, so personal data doesn't have to leave the machine
- **Permission levels**: anything important waits for a human yes
- **Verification**: it checks the real result before it says "done", and tells you honestly when something failed

ORION is early and its source is private. The [project page](https://impacts-ai.com/orion) tracks exactly what works today.
I've written up how I built it, from the first prototype to today's architecture, in **[building-orion](https://github.com/SaqibsAura/building-orion)**.

---

### Open source

| Project | What it is |
| :--- | :--- |
| [orion-math](https://github.com/SaqibsAura/orion-math) | ORION's exact maths engine: plain-English questions in, exact answers out, no `eval`. Tested. |
| [leakcheck](https://github.com/SaqibsAura/leakcheck) | A zero-dependency secret scanner I run before every push. Tested. |
| [building-orion](https://github.com/SaqibsAura/building-orion) | How ORION went from a prototype to a CLI-first agent: architecture, decisions, honest status. |

---

### How I build

- **Doing beats explaining.** An agent should finish the task, not describe it.
- **Verify, don't assume.** What a model says is not evidence. If the result can't be checked, it isn't done.
- **People approve what matters.** Deleting, sending or paying waits for a human yes.
- **Code governs, models propose.** Permissions and safety live in plain, testable code.
- **Honest status.** I'd rather show what's unfinished than oversell it.

**Stack:** TypeScript · Node.js · Python · Ollama (local models) · React · Git

---

<div align="center">

**[impacts-ai.com](https://impacts-ai.com)** · **[impacts-ai.com/orion](https://impacts-ai.com/orion)** · **[github.com/iMpacts-AI](https://github.com/iMpacts-AI)**

</div>
