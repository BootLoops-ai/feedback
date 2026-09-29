# BootLoops — comments, corrections and issues

This repository collects public feedback on **[bootloops.ai](https://bootloops.ai)**: the manuscripts, the web summaries, the tools registry and the downloadable scripts and data. It is also where you ask for a tool (build, port or link) and where you tell us about an application.

## How to file

Open an issue: **[New issue](../../issues/new/choose)** and pick a form.

- **Comment or correction on a paper or web page** — name the paper (PDF file name or title) or the page URL, quote the sentence, equation or figure, and say what you think is wrong or unclear. Page and equation numbers help.
- **Bug in a script, package or data file** — name the file (for example `files/phylo/phylo-evaluate.py` or the JaCK & Jill version), the command you ran, what you expected and what happened, with the full error text.
- **Suggestion** — a tool, a check, a comparison or a result you would like to see, or an integral/model you would like added.
- **Tool request (build, port or link a tool)** — pick the kind: *build a new tool* (describe the calculation, the input you have, the output you need, and a reference value if one exists), *port an existing tool* (name the package, its license, and which part you need driven from BootLoops or freed of a proprietary dependency), or *link my tool* (software you maintain that BootLoops should call or list: the repository, a one-paragraph description, and a test we can run).
- **Application** — you used BootLoops, or a method from one of its papers, on your own problem, or you have a problem you think fits: the field, the question, what was computed or should be, and whether the data are public, on request or private. Selected applications get a web summary on the site, with credit.

Issues are public. If you would rather write privately, use the addresses below.

## Email

- **science@bootloops.ai** — questions about the science, or new results obtained with BootLoops
- **bugs@bootloops.ai** — bug reports
- **tools@bootloops.ai** — tool requests (build, port or link), tool contributions and patches
- **matt@bootloops.ai** — questions for Matthew Schwartz

## What happens next

Corrections that check out are made in the manuscript or page and noted in the reply to the issue. Tool fixes are released under the same file names with a changelog line. Substantive contributions are credited on the site's [Contribute & contact](https://bootloops.ai/contact.html) record.

## Pull requests

The code is being released as BootLoops 1.0 under this organization in six repositories (`bootloops-dev` for the toolkit; `jackandjill-dev`; the engine forks `amflow-cpp-dev`, `kira-dev`, `blade-dev`; `skills-dev`), private now and opening with the release. Once they are public, pull requests go to the relevant repository; until then, send a patch by email or describe it in an issue here.
