---
name: Add an acronym
about: Request a missing acronym to be added
title: 'New acronym '
labels: documentation
assignees: aheavey, brettviren, clairedavid

---

# Request of a new acronym

## Case 1: you know the definition
The glossary is to be updated in LaTeX format. It will be automatically converted in HTML.
The custom commands are:
- **terms that do *not* have acronyms**: `\newduneword` (3 arguments)
```
\newduneword{dword}{DUNE Word}{A term in the DUNE lexicon}
```
- **terms that do have acronyms**: `\newduneabbrev` (4 arguments) and `\newduneabbrevs` (5 arguments)
```
\newduneabbrev{lar}{LAr}{liquid argon}{Argon in its liquid phase}
\newduneabbrevs{cpa}{CPA}{cathode plane assembly}{cathode plane assemblies}{The component of the \gls{sp} detector module that provides the drift HV cathode}
```

Enter your requested acronym choosing the relevant template:
```

```
Paste reference/source link(s) below:


## Case 2: you do not know the definition
Please describe below in which context you encountered the acronym.
See [DUNE's wiki page](https://wiki.dunescience.org/) to list the relevant working groups. Thank you.
