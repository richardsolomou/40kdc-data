# Pantheon of Woe contribution draft

[Proposed mechanics](proposals.json) covers four 40kdc placeholders. Each entry includes expected behavior, edge cases, and typed workbench annotations. Offsets identify spans in the private reference with the listed hash.

[Compiled JSON for review](compiled-preview.json) contains the three entries that pass the workbench's schema, integrity, description, and cruncher checks. The records are unsigned and pending human review.

- **Disharmonisation Cascade.** The 1 CP stratagem applies after a friendly Necrons Monster model is destroyed and before that same model's Deadly Demise roll. Only that model uses the 3+ threshold.
- **Phase Melding.** The 1 CP stratagem targets a friendly Necrons unit engaged with the Unravelling enemy selected to Fall Back in the opponent's Movement phase. Each model in that same enemy unit takes a Desperate Escape test if it Falls Back, with a −1 penalty if it is Battle-shocked.
- **Reletavistic Tether.** In your turn, the Transcendent C’tan can end an ingress or advance made through Transdimensional Displacement more than 6 inches horizontally from every enemy unit. If it ends that move within 8 inches of any enemy unit, it cannot declare a charge for the rest of that turn. The generated description gives the 6-inch limit and leaves horizontal measurement implicit.

**Mass Transmogrification** remains blocked. The existing designation predicate reads the current state. The rule requires checking whether the defeated enemy was Unravelling when the phase began. The other clauses are annotated in the workbench.

The workbench requires human approval of the annotations and the compiled result before writing the enrichment and any associated core restrictions. [40kdc authoring workflow](https://github.com/wn-mitch/40kdc-data/blob/main/SEMANTIC_AUTHORING.md)
