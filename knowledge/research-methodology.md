# Research Methodology Reference

Structured approaches for multi-source investigation and evidence gathering.

## Question Decomposition

### PICO Framework (adapted for technical research)
- **P**opulation: What system, technology, or domain?
- **I**ntervention: What approach, tool, or change?
- **C**omparison: Against what alternatives?
- **O**utcome: What metrics or results matter?

### Decomposition Steps
1. Identify the core question (single sentence)
2. Extract implicit assumptions
3. Break into 3-7 sub-questions that independently contribute to the answer
4. Classify each sub-question by source type (web, academic, practitioner, competitive)
5. Identify dependencies between sub-questions

## Source Type Selection

| Question Type | Primary Sources | Secondary Sources |
|--------------|----------------|-------------------|
| State of the art | Academic papers, conference proceedings | Blog posts, GitHub trends |
| Tool comparison | Documentation, benchmarks, practitioner blogs | Conference talks, GitHub stars/issues |
| Market landscape | Industry reports, company blogs | News articles, social media |
| Best practices | Documentation, style guides, RFCs | Conference talks, community forums |
| Emerging tech | Preprints, blog posts, conference talks | Early adopter case studies |
| Historical context | Academic surveys, retrospectives | Wikipedia, archived documentation |

## Search Strategy

### Query Construction
- Start broad, narrow iteratively
- Use domain-specific terminology (not layperson language)
- Include year constraints for recency-sensitive topics
- Combine concepts with boolean operators for precision

### Iteration Pattern
```
Round 1: Broad survey (5-10 sources) → identify key terms and players
Round 2: Targeted search using discovered terminology → deeper sources
Round 3: Fill gaps identified in cross-referencing → specific questions
```

### Source Quantity Targets

| Research Depth | Web Sources | Academic | Video/Talks | Total |
|---------------|-------------|----------|-------------|-------|
| Quick survey | 5-8 | 0-3 | 0-2 | 8-13 |
| Standard | 8-15 | 3-8 | 2-5 | 15-28 |
| Deep dive | 15-25 | 8-15 | 5-10 | 30-50 |

## Evidence Hierarchy

| Tier | Source Type | Weight |
|------|-----------|--------|
| 1 | Peer-reviewed research, controlled experiments | Highest |
| 2 | Pre-prints with methodology, official benchmarks | High |
| 3 | Practitioner case studies with data | Medium-High |
| 4 | Expert blog posts, conference talks | Medium |
| 5 | Documentation, tutorials | Medium |
| 6 | Community forums, social media | Low |
| 7 | Marketing materials, vendor whitepapers | Lowest |

## Triangulation

### Corroboration Rules
- A claim supported by 3+ independent Tier 1-3 sources = HIGH confidence
- A claim supported by 1-2 Tier 1-3 sources = MEDIUM confidence
- A claim supported only by Tier 4-7 sources = LOW confidence
- A claim contradicted by a higher-tier source = CONTESTED

### Contradiction Resolution
1. Check publication dates (newer may supersede)
2. Compare methodologies (different methods may explain different results)
3. Check for shared upstream sources (apparent independence may be illusory)
4. Check for funding/vendor bias
5. If unresolvable, report both positions with context

## Gap Analysis Categories

| Gap Type | Description | Report Action |
|----------|-------------|---------------|
| Data gap | No source addresses this sub-question | Flag as unanswered |
| Recency gap | Available data is outdated | Note age, caveat conclusions |
| Methodology gap | No rigorous study, only anecdotes | Lower confidence rating |
| Perspective gap | Only one stakeholder type represented | Note bias risk |
| Scale gap | Evidence only from small/large contexts | Note applicability limits |
