## Can do proofs:

[Agda](https://github.com/agda/agda) - a dependently typed programming language / interactive theorem prover. 
[Lean4](https://lean-lang.org/) -  - programming language and theorem prover
[Rocq](https://rocq-prover.org/) - interactive theorem prover and dependently-typed programming language

| Language                                     | lazy | dependant types | linear types | bootstrapped | general purpose | refinement types | type classes | effects |
|----------------------------------------------|------|-----------------|--------------|--------------|-----------------|------------------|--------------|---------|
| Agda                                         |      |       +          |              |              |                 |                  |              |         |
| Lean4                                         | -    | +               |              | +            | +               |                  |              |         |
| [Dafny](https://github.com/dafny-lang/dafny) |      |                 |              |              | +               |                  |              |         |
| !! [quint](https://quint-lang.org/)          |      |                 |              |              |                 |                  |              |         |
| Idris                                        |      |                 |              |              |                 |                  |              |         |
| Rocq                                          |      |                 |              |              | -               |                  |              |         |
| [Flix](https://flix.dev/)                    | -    | -               |              |              | +               |                  | +            | +       |
| F*                                        |      |                 |              |              | +               | +                |              |         |
| Kind                                         |      |                 |              |              |                 |                  |              |         |
| !!Alloy                                      |      |                 |              |              |                 |                  |              |         |
| !!TlaPlus                                    |      |                 |              |              |                 |                  |              |         |
| ??[Curry](https://curry-lang.org/)           |      |                 |              |              | +               |                  |              |         |
| ??[Mercury](https://mercurylang.org/)        |      |                 |              |              |                 |                  |              |         |
| [Isabelle](https://isabelle.in.tum.de/)      |      |                 |              |              |                 |                  |              |         | ?? Quint


### Internals

bootstrapped

### Runtime and compiled targets

| Language                                | wasm target | riskv target | x86 target | arm target | C | JS | JVM |
|-----------------------------------------|-------------|--------------|------------|------------|---|----|-----|
| Agda                                    |             |              |            |            |   |    |     |
| Lean                                    | +           |              | +          | +          |   |    |     |
| Dafny                                   |             |              |            |            |   | +  |     |
| !! [quint](https://quint-lang.org/)     |             |              |            |            |   |    |     |
| Idris                                   |             |              |            |            |   |    |     |
| Coq                                     |             |              |            |            |   |    |     |
| Flix                                    |             |              |            |            |   |    | +   |
| Fstar                                   |             |              |            |            |   |    |     |
| Kind                                    |             |              |            |            |   |    |     |
| !!Alloy                                 |             |              |            |            |   |    |     |
| !!TlaPlus                               |             |              |            |            |   |    |     |
| ??[Curry](https://curry-lang.org/)      |             |              |            |            |   |    |     |
| ??[Mercury](https://mercurylang.org/)   |             |              |            |            |   |    |     |
| [Isabelle](https://isabelle.in.tum.de/) |             |              |            |            |   |    |     |


### Stats

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=leanprover/lean4,dafny-lang/dafny,agda/agda,FStarLang/FStar,flix/flix,idris-lang/Idris2,HigherOrderCO/Kind,coq/coq&type=Date)](https://api.star-history.com/svg?repos=leanprover/lean4,dafny-lang/dafny,agda/agda,FStarLang/FStar,idris-lang/Idris2,HigherOrderCO/Kind,coq/coq&type=Date)

| Language | stars                                                                      | contributors                                                                        |   |   |   |   |
|----------|----------------------------------------------------------------------------|-------------------------------------------------------------------------------------|---|---|---|---|
| Agda     | ![GitHub Repo stars](https://img.shields.io/github/stars/agda/agda)        | ![GitHub contributors](https://img.shields.io/github/contributors/agda/agda)        |   |   |   |   |
| Lean     | ![GitHub Repo stars](https://img.shields.io/github/stars/leanprover/lean4) | ![GitHub contributors](https://img.shields.io/github/contributors/leanprover/lean4) |   |   |   |   |
| Dafny    | ![GitHub Repo stars](https://img.shields.io/github/stars/dafny-lang/dafny) | ![GitHub contributors](https://img.shields.io/github/contributors/dafny-lang/dafny) |   |   |   |   |
| Coq      | ![GitHub Repo stars](https://img.shields.io/github/stars/coq/coq)          | ![GitHub contributors](https://img.shields.io/github/contributors/coq/coq)          |   |   |   |   |
| Flix     | ![GitHub Repo stars](https://img.shields.io/github/stars/flix/flix)        | ![GitHub contributors](https://img.shields.io/github/contributors/flix/flix)        |   |   |   |   |
| Fstar    | ![GitHub Repo stars](https://img.shields.io/github/stars/FStarLang/FStar)  | ![GitHub contributors](https://img.shields.io/github/contributors/FStarLang/FStar)  |   |   |   |   |


## Out of scope


### Strong safe type systems which cannot do full proofs within language 

Languages like C/C++/Haskell/Ada/[Rust](https://github.com/newca12/awesome-rust-formalized-reasoning?tab=readme-ov-file#verification) 
has a lot of tooling to prove things about them, but that tooling is not part of langauge.
Haskell and Rust may get into if more unstable/extensiona/nightly/experimental features got into stable releases over time

### Prolog and its supersets

???

### Model checkers and specification languages 

??? Quint
??? TLA+

### Symbolic

??? Mathematica?

### Verifiaction tools and eDSLs

???

## Prominent projects

### Lean

Alfa fold


## Other lists

https://github.com/awesomo4000/awesome-provable?tab=readme-ov-file#languages
