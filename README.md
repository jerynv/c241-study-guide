# C241 Test 1 Study Guide

I put this together while studying for the first C241 (Discrete Structures) test at IU, Fall 2026. My goal was to understand each idea well enough to explain it to someone else, not just memorize the rules. Sharing it in case it helps you too.

**[Read the PDF →](pdf/c241-test1-study-guide.pdf)**

## What it covers

Everything up to Test 1, and nothing past it:

1. **Sets**: membership vs. subset (the thing that trips everyone up), set-builder notation, the operations, power sets, and why ∅ and {∅} aren't the same.
2. **Logic**: truth tables, translating English into logic, satisfiable / tautology / contradiction / contingency, equivalence, quantifiers, and vacuous truth.
3. **Proofs**: the constrained proof style. The five definitions, the seven rules, how the shape of the goal tells you your next move, scope, contradiction, and counterexamples. This is where most points get lost, so it's the longest chapter.
4. **Relations and functions**: ordered pairs, Cartesian products, symmetry, and injective / onto / bijection.
5. **Graphs**: walks, trails, paths, cycles, connectivity, and rooted trees. Check with your TA whether these are on the test.
6. **Test day**: what to put on your one-page note sheet, and what to do when you get stuck.

Each chapter starts with the intuition in plain words, then the exact definitions in the notation the course uses, then pictures and worked examples, and ends with practice problems and full answers.

## A few honest notes

- **This is unofficial.** It's not from the course staff and it doesn't replace the lecture notes. If something here disagrees with the notes or your TA, go with them, and please let me know.
- **No homework answers.** Every example and practice problem is original. Nothing here comes from, or solves, an assigned homework or quiz.
- **The answers were double-checked** by brute force on small examples, but mistakes still happen. If you spot one, open an issue.

## Repo layout

```
pdf/   the compiled guide
tex/   the LaTeX source (one main file, one file per chapter, plus the style)
```

To build it yourself you need XeLaTeX with TikZ, plus the Times New Roman and STIX Two Math fonts. From inside `tex/`:

```sh
xelatex c241-test1-study-guide.tex
xelatex c241-test1-study-guide.tex
```

Good luck on the test.

Jeryn Vicari
