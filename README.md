

# Portland Has Skill

Resources for and by Portland Haskellers and other Functional Programming 
enthusiasts.

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md).

## Table of Contents

- [Events](#events)
  - [Upcoming Events](#upcoming-events)
  - [Past Events](#past-events)
- [Project Sharing](#project-sharing)
- [Links to Topics Discussed](#links-to-topics-discussed)
  - [FP for Interactive Web (and FRP)](#fp-for-interactive-web-and-frp)
  - [Types](#types)
    - [Cubical Types](#cubical-types)
    - [Dependently typed languages](#dependently-typed-languages)
    - [Type Checkers](#type-checkers)
  - [Paradigms](#paradigms)
    - [Rewrite Systems](#rewrite-systems)
    - [Incremental Computing](#incremental-computing)
    - [Distributed Processing in the Cloud](#distributed-processing-in-the-cloud)
    - [Stream Processing (in Haskell)](#stream-processing-in-haskell)
    - [Functional Reactive Programming](#functional-reactive-programming)
    - [High Level Programming for SIMD/GPU](#high-level-programming-for-simdgpu)
    - [Hardware Description](#hardware-description)
    - [Constant Memory, Low-Level Code](#constant-memory-low-level-code)
  - [Verification](#verification)
  - [Languages, etc.](#languages-etc)
  - [Nix and NixOS](#nix-and-nixos)
  - [AI](#ai)
  - [Robust Computing](#robust-computing)
  - [Text Editors](#text-editors)
  - [Database Tools](#database-tools)
  - [Web Tools](#web-tools)
  - [Learning Tools](#learning-tools)
  - [Real-World Haskell Use](#real-world-haskell-use)
  - [Misc](#misc)
- [Companies Using FP in Portland](#companies-using-fp-in-portland)
  - [Offices in the Portland Area](#offices-in-the-portland-area)
  - [Remote](#remote)

## Events

[Portland Has Skill Meetup](https://www.meetup.com/portland-has-skill/)

### Upcoming Events

- [Monads & Mojitos 4: September 19, 2024](https://www.meetup.com/portland-has-skill/events/302588288)
- [Monads & Mojitos 5: October 24, 2024](https://www.meetup.com/portland-has-skill/events/302588410)
- [Monads & Mojitos 6: November 21, 2024](https://www.meetup.com/portland-has-skill/events/302588453)
- [Monads & Mojitos 7: December 19, 2024](https://www.meetup.com/portland-has-skill/events/302588460)

### Past Events

- [Monads & Mojitos: Magic | 2024-08-22](https://www.meetup.com/portland-has-skill/events/302588198)
- [Monads & Mojitos: Coincidence | 2024-07-25](https://www.meetup.com/portland-has-skill/events/302105153/)
- [Monads & Mojitos: Inauguration | 2024-06-27](https://www.meetup.com/portland-has-skill/events/301628256/)

## Project Sharing

- [Tensort](https://github.com/kaBeech/tensort)

## Links to Topics Discussed

Sections with New Links from Most Recent Event:

- [Type Checkers](#type-checkers)
- [Robust Computing](#robust-computing)
- [Text Editors](#text-editors)
- [Learning Tools](#learning-tools)
- [Real-World Haskell Use](#real-world-haskell-use)

### FP for Interactive Web (and FRP):

- [Interactive logic (also demonstration of GHCJS)](http://incredible.pm/)

  - [See also](https://turingcomplete.game/)

- [Hyperbolic geometry version of sōkoban (also demonstration of purescript)](https://sokyokuban.com/)

### Types

#### [Cubical Types](https://arxiv.org/abs/1611.02108)

  - [Cubical Agda](/agda.readthedocs.io/en/v2.6.4.3-r1/language/cubical.html)

#### [Dependently typed languages](/en.m.wikipedia.org/w/index.php?title=Dependent_type)

  - [Coq](/en.wikipedia.org/wiki/Coq_(software))

  - [Lean4](/en.m.wikipedia.org/wiki/Lean_(proof_assistant))

  - [Idris2](/en.m.wikipedia.org/wiki/Idris_(programming_language))

  - [Agda](/en.m.wikipedia.org/w/index.php?title=Agda_(programming_language))

  - [Pie](https://mitpress.mit.edu/9780262536431/the-little-typer/) from *The Little Typer*

#### Type Checkers

  - [Sorbet](https://sorbet.org/)

  - [Dialyzer](https://www.erlang.org/doc/apps/dialyzer/dialyzer.html)

### Paradigms

#### Rewrite Systems

  - [egraphs good](https://github.com/egraphs-good/egg)

  - egglog [1](https://github.com/egraphs-good/egglog) and [2](https://arxiv.org/abs/2304.04332)

  - [egg as a lean tactic](https://github.com/marcusrossel/lean-egg)

#### Incremental Computing:

  - Umut Acar was mentioned by name. An example is [Umut A. Acar, Guy E. Blelloch, and Robert Harper. *Adaptive Functional Programming*](https://drive.google.com/file/d/1bAYubdbZ9VjO_y5-DoYXKSiuyid0sX4Z/view)

    - [Adaptive](https://hackage.haskell.org/package/Adaptive)

  - [Flare](https://github.com/sharkdp/purescript-flare)

  - [Typed Spreadsheet Library](https://github.com/Gabriella439/Haskell-Typed-Spreadsheet-Library)

  - [Differential Dataflow](https://github.com/TimelyDataflow/differential-dataflow)

#### Distributed Processing in the Cloud

  - [Flink](https://flink.apache.org/)

  - [Spark](https://spark.apache.org/)

  - [Ballista](https://arrow.apache.org/ballista/)

    - [Apache Arrow](https://arrow.apache.org/)

  - [Unison](https://www.unison.cloud/)

  - [Materialize](https://materialize.com/ (see also differential dataflow above))

#### Stream Processing (in Haskell)

- [conduit](https://hackage.haskell.org/package/conduit)

- [streaming](https://hackage.haskell.org/package/streaming)

- [streamly](https://hackage.haskell.org/package/streamly)


#### [Functional Reactive Programming](https://en.wikipedia.org/wiki/Functional_reactive_programming)

  - [Elm](https://en.wikipedia.org/wiki/Elm_(programming_language))

    - [Evan on why Elm didn't start with typeclasses (among other topics)](https://www.youtube.com/watch?v=oYk8CKH7OhE)

  - [Yampa](https://github.com/ivanperez-keera/Yampa)

#### High Level Programming for SIMD/GPU

  - [Bend](https://github.com/HigherOrderCO/bend)

  - [Futhark](https://github.com/diku-dk/futhark)

#### Hardware Description

  - haskell to verilog/vhdl with [Clash](https://github.com/clash-lang/clash-compiler)

#### Constant Memory, Low-Level Code

  - from haskell with [Copilot](https://github.com/Copilot-Language/copilot)

### Verification

- [Verifying a Rust implementation with Lean](https://github.com/cedar-policy/cedar)

- [TLA+](https://en.wikipedia.org/wiki/TLA%2B)

- [CompCert](https://compcert.org/compcert-C.html)

- [Alain (and students') formally verified network stack](https://www.youtube.com/watch?v=linRvpquOrg)

### Languages, etc.

- [Lean](https://en.wikipedia.org/wiki/Lean_(proof_assistant))

- [Idris](https://en.wikipedia.org/wiki/Idris_(programming_language))

- [Agda](https://en.wikipedia.org/wiki/Agda_(proof_assistant))

- [Coq](https://en.wikipedia.org/wiki/Coq_(software))
  - [Coq is getting renamed to 'The Rocq Prover'](https://coq.discourse.group/t/coq-community-survey-2022-results-part-iv-and-itp-paper-announcement/2001)

- [Oz](https://en.wikipedia.org/wiki/Oz_(programming_language))

- [Cedar](https://arxiv.org/abs/2403.04651)

- [Bend](https://higherorderco.com/)

- [Gleam](https://gleam.run/)

- [Isabelle](https://isabelle.in.tum.de/)

- [Roc](https://www.roc-lang.org/)

- Scheme
  - [The Little Schemer](https://mitpress.mit.edu/9780262560993/the-little-schemer/)

### Nix and NixOS

- [Nix and NixOS](https://nixos.org/)

- [Impermanence](https://github.com/nix-community/impermanence)

- [Vimjoyer's tutorials on youtube](https://www.youtube.com/playlist?list=PLko9chwSoP-15ZtZxu64k_CuTzXrFpxPE)

### AI

- [Bill Venners - AI Assisted Development | Scala Days 2023 Seattle](https://youtube.com/watch?v=2LENCCtP8Mo)

- [Oops! We Automated Bullshit.](https://www.cst.cam.ac.uk/blog/afb21/oops-we-automated-bullshit)
  - [Related](https://strikemag.org/bullshit-jobs/)

- [KAN: Kolmogorov-Arnold Networks](https://arxiv.org/abs/2404.19756)

### Robust Computing

- [Beyond Efficiency](https://www.cs.unm.edu/~ackley/be-201301131528.pdf)

  - [Beyond Efficiency by Dave Ackley](https://futureofcoding.org/episodes/070)

  - [Tensort](https://github.com/kaBeech/tensort)

### Text Editors

- [Kakoune](https://kakoune.org/)

- [Helix](https://github.com/helix-editor/helix)

- [Zed](https://zed.dev/)

### Database Tools

- [Beam](https://github.com/haskell-beam/beam)

### Web Tools

- [Servant](https://docs.servant.dev/en/stable/)

### Learning Tools

- [Haskellings](https://github.com/MondayMorningHaskell/haskellings)

### Real-World Haskell Use

- [Ivan Perez uses Haskell at NASA](https://haskell.foundation/podcast/43/)

- [Kyle's Reddit thread](https://www.reddit.com/r/haskell/comments/1av4g1g/what_do_you_use_haskell_for/)

### Misc

- [Concepts, Techniques, and Models of Computer Programming](https://en.wikipedia.org/wiki/Concepts,_Techniques,_and_Models_of_Computer_Programming)

- [Conal Elliott on "A Galilean revolution for computing" @ZuriHac2023](https://www.youtube.com/watch?v=k6rY5Mvx84E)

- Evan mentioned an essay by Dijkstra arguing that we should make machines with evaluation semantics closer to LISP

  - [lisp machine](https://en.wikipedia.org/wiki/Lisp_machine)

    - [reduceron](https://github.com/tommythorn/Reduceron)

## Companies Using FP in Portland

### Offices in the Portland Area

  - [Galois](https://galois.com/)

  - [Mercury](https://mercury.com/)

### Remote

  - [FP complete](https://www.fpcomplete.com/)

  - [Well-Typed](https://www.well-typed.com/)

  - [TripShot](https://www.tripshot.com/)

  - [SiriusXM](https://siriusxm.com/)

