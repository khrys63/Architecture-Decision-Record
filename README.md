# Architecture Decision Record 

An architectural decision record (ADR) is a document that describe an important decision with its context and consequences.

Lightweight Architecture Decision Records was rated in ADOPT part of the Technology Radar by Thoughworks in november 2017.

## What is ADR ?

An architectural decision record (ADR) is a document that describe an important decision with its context and consequences.

An architectural decision is a design choice realized in a product to respect a requierement.

A Requirement is a constrain element that affect a product with measurable effect.

The decision log groups all ADRs for a particular product.

This project will help you in this practice with somme guideline to log all of yours architecture decision and with a template of ADR.

## How to start decision log

Nothing more simple, just create a directory at the root of your project.

Then for each decision, it will be enough to create a file, to inform the decision in then and to commit it.

## Naming convention

We will use a simple naming convention.

The naming convention :
```
Prefix with the date AAAAMMJJ.
Short name of the decision.
Use Markdown extension.
```

Examples :
```
20180102_Choose_js_framework.md
20180210_Choose_graph_database.md
20180601_Replace_js_framework.md
```

## Content

An Architecture Decision must respect this follwing practices :
- Dated. When the decision was taken.
- Rationnal. Explain why the decision was taken.
- Immuable. The content should not be altered. 
- Unique. Only one decision by record.

The context should be explain. Explain why decision was taken :
- Business priority.
- Organisation.
- Skills.

The consequences must be measurables :
- Right approach. The decision is pertinent and will be stable in time.
- Wrong approach under constraint. Explain what will be arrived and what is under survey.

An Architecture Decision can remplace an older :
- Identify replaced ADR and log it in the new.


## Sources

- [ThoughtWorks - Lightweight Architecture Decision Records](https://www.thoughtworks.com/radar/techniques/lightweight-architecture-decision-records)
- [joelparkerhenderson/architecture_decision_record](https://github.com/joelparkerhenderson/architecture_decision_record)