Inbox
-----

- Foundations
  - The Plan
  - The Village
  - Ways Of Knowing
    - That tacit v explicit thing.
    - How we learn 'blue' versus how we learn 'two'.
    - Nothing I can write here could mean you could learn to drive a car, just by reading. Or ride a bike. Or write a poem. Or debug a computer program. I could write things to try, things that might help, but I can't write words that finish the job. It's not 'the battle of Hastings was in 1066', it's not '', it's not quiz fodder.
    - Not about repetition of something complex. Such recitations can build skills that help you learn, but the precise execution alone is not it.
  - Complexity & Predictability
    - The Preservation Game: Use Game of Life as a touchstone.
      - https://bl.ocks.org/lsbardel/c0edf5f88ca5af118599844b7d2dcdf8
    - Predictability, Focus on Digital Difference. Load/Save.
  - Evolution (Wardley etc.)
  - The Digital Difference:
    - Uncountable and countable sets
      - Describing reality versus language, packing infinities. 
      - That all digital limits this to finite sets.
    - Digital Media:
      - Understanding Digital Objects
      - Resist conceptualisation
      - Unsafe Device Removal
      - Format Patterns
        - Features v Versions
        - In-band v context
      - Why Magic Exists
      - Format Identification
        - POINT Format ID links bytes to the thing that groks it.
      - Talking about formats:
        - https://twitter.com/anjacks0n/status/1299291635302502400
        - http://anjackson.github.io/keeping-codes/practice/talking-about-formats
        - http://anjackson.github.io/keeping-codes/practice/defining-format
      - Significant Properties
        - I think the tendency to keep it all comes from trying to avoid deciding what’s worth knowing. 
        - For me, critical DP issue is dependency analysis. From ‘what software do i need to access this’ aka format identification, to ‘what external resources are required’ like non-embedded fonts.
        - http://anjackson.github.io/keeping-codes/practice/what-do-we-need
        - http://anjackson.github.io/keeping-codes/practice/what-do-we-need---characterisation
        - http://anjackson.github.io/keeping-codes/fundamentals/cantor-countability-and-sig-props.html
        - http://anjackson.github.io/keeping-codes/fundamentals/significant-properties-and-authentic-transformations
      - DPC post nicely shows the problem with abstracting representation information:
        - ? https://www.dpconline.org/blog/minding-the-gaps ?


...SOONER...  



- Context
  - Theory & Practice
  - Purpose
- Landscape
- Maps
  - Wardley Maps
  - Mapping Space & Time
  - ...?
- Patterns
  - Environments? is Authority part of this? Relationship between Producer, Creator & Archive. I think it is.
    - Authority - are these your records? Common Carrier or Information Source
  - Information Flows:
    - Combinations, with/without broader environment? 
    - Draw Your Own? 
  - Assessing Actions
  - Collaborations? Was _The Village_
- Blogs:
  - Reg workshop report.
  - Post on Edith's project, (built like I like "when blood sees blood of it's own".)
  - Post on the award, after getting/reading it, and when there's a web version.


...LATER...

- Patterns?
  - Contexts
    - Space-time diagrams
    - Implies access _via_ but this is not the norm!
    - Producer: partners or publishers?
    - Also native communities v wider communities, https://twitter.com/footage/status/1306488087657152517?s=21
    - Goals: 
      - Authority: Common Carrier or Information Source
        - Seems to link to Shannon.
      - Outcome or Process.
  - Systems Of Care:
    - Tactics:
      - Information Flows: Fork v Line
      - Workflows...
      - Monitor v Engage
      - Format v Adaptive Response
      - Once v Forever / Product v Process / Preservation
      - Non-linear editing, Undo, versus mutation
      - Failure-driven design
    - Repository Architecture Patterns:
      - Start with known, experienced risks, outline possible solutions that can be baked into the architectural design 
      - Policy versus structure
      - Pipeline versus sidecar preservation
      - POINT: If your not generating your DIP from your actual AIP you’re not doing OAIS.
      - Use digitised images as example. Look at risks of the sidecar approach. 
      - Note pipeline approach is the same parts in a different shape.
      - Note user-driven processing is common and better handles transient failure, extension to edge cases etc.
    - One repo consequences http://ruthtillman.com/repository-ouroboros/
    - Architectures
      - Library doesnt care about digital
      - Patterns
      - Ingest then transform over heavy pre-ingest processing
      - Bridge the gap between OAIS and practice, starting with the overall information architectures and different ways of delivering the OAIS functions.
      - ARCH: Files in the middle 
      - ARCH: Federation
      - ARCH: Fixity/inventory??? patterns! BagIt, DB, DAMS/ ??? blockchain.
      - ARCH: Also Just-in-time gives you more chances to get it right. Just-in-case is often only done once and it’s harder to pick up problems. https://twitter.com/euanc/status/1223656274203742208
    - Architectural patterns
      - Shearing Layers of the UK Web Archive
    - Conceptual Patterns
      - Digitisation dominance https://twitter.com/anjacks0n/status/1298284308315201542?s=21
      - Intellectual Entity 
      - Validation see https://www.bl.uk/britishlibrary/~/media/bl/global/digital%20preservation/non-print-lega-deposit-digital-preservation-review.pdf
      - Preservation Format
    - Procurement patterns
- Practices
  - Storage:
    - Goals versus requirements, why it's not trivial, IT partnership
    - Copy files is hard: Enumerate every failure mode I've seen.
      - See Tweet chain: https://twitter.com/hhockx/status/1300615432127361030
    - How fast can you hash?
    - Replicas Versus Checksumming
  - Access
    - http://anjackson.github.io/keeping-codes/practice/ukwa-sustainable-access
    - Kinds of Access?
    - Description:
      - Agile/GDS v library tension 
      - https://twitter.com/tropy/status/1214651133089714176?s=21: ‪Going a step further, I’d argue that the structure an archivist/curator needs to manage a collection isn’t necessarily the structure a researcher needs to find what they need.‬
    - http://anjackson.github.io/keeping-codes/practice/ukwa-mining-meaning
  - Web Archives:
    - Why WARC?
    - Working with Web Archives
  - Stories (minutae that provide examples)
    - A Mystery Format and a Bad Deed.
    - The Analogue Repository
    - JHOVE and Encrypted PDFs:
      - http://anjackson.github.io/keeping-codes/war-stories/characterising-pdfs
    - Archiving the Dynamic Web:
      - http://anjackson.github.io/keeping-codes/practice/archiving-the-dynamic-web.html
    - BBC Micro Data Recovery:
      - http://anjackson.github.io/keeping-codes/experiments/bbc-micro-data-recovery
      - http://anjackson.github.io/keeping-codes/experiments/images/bbc-master/
      - http://anjackson.github.io/keeping-codes/experiments/bbc-micro-data-recovery-appendicies
      - http://anjackson.github.io/keeping-codes/experiments/BBCUtils/src/uk/bl/dpt/bbc/DiskImageInterlacer.java
    - RISC OS Rescue
      - http://anjackson.github.io/keeping-codes/experiments/risc-os-rescue
    - Archiving Wikipedia During the SOPA Blackout
      - http://anjackson.github.io/keeping-codes/war-stories/wikipedia-sopa
    - War Stories:
      - http://anjackson.github.io/keeping-codes/war-stories/
    - Understanding web archiving (Interactive Fiction)
    - Remixing the PLANETS Testbed:
      - http://anjackson.github.io/keeping-codes/practice/remixing-the-planets-testbed
    - Reconstruction (personal history):
      - http://anjackson.github.io/keeping-codes/experiments/Reconstruction
    - Adopting Emulation:
      - http://anjackson.github.io/keeping-codes/experiments/dawn-of-emulation
      - POINT - Why does DP treat it as weird when it is totally mainstream? Products?
    - Using Web Archives To Improve Preservation Tools:
      - http://anjackson.github.io/keeping-codes/experiments/more-data-better-tools
    - Press Any Key (what happens)
      - http://anjackson.github.io/keeping-codes/fundamentals/press-any-key
    - Dissecting Domesday
      - http://anjackson.github.io/keeping-codes/war-stories/dissecting-domesday

- Ideas:
  - PREMIS in METS, PREMIS in WARC, PREMIS in text?
    - The model versus the encoding.
    - Document WARC usage.
    - Propose text/log form.
    - Layered PREMIS notes:
      - http://anjackson.github.io/keeping-codes/practice/accessible-digital-preservation




```{mermaid}
flowchart LR
  A[Jupyter Notebook] --> C
  B[MyST Markdown] --> C
  C(mystjs) --> D{AST}
  D <--> E[LaTeX]
  E --> F[PDF]
  D --> G[Word]
  D --> H[React]
  D --> I[HTML]
  D <--> J[JATS]
```

