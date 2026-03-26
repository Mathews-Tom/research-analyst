# Synthesis Framework Reference

Structures for combining multi-source evidence into actionable analysis.

## Report Structure

### Standard Research Report

```
1. Executive Summary (3-5 sentences)
   - Direct answer to core question
   - Key finding highlights
   - Confidence level and major caveats

2. Key Findings (numbered, with confidence ratings)
   - Finding statement
   - Confidence: HIGH / MEDIUM / LOW / CONTESTED
   - Supporting sources [citations]

3. Detailed Analysis (by sub-question)
   - Evidence from each source type
   - Cross-reference points
   - Contradictions and resolution

4. Comparison Matrix (if applicable)
   - Structured table with scored dimensions

5. Gaps and Limitations
   - Unanswered sub-questions
   - Source limitations
   - Methodology caveats

6. Recommendations
   - Grounded in findings (not opinion)
   - Linked to specific evidence

7. Sources
   - Complete citation list
```

## Confidence Rating System

| Rating | Criteria | Minimum Evidence |
|--------|----------|-----------------|
| HIGH | Independent corroboration from 3+ credible sources | 3 Tier 1-3 sources agreeing |
| MEDIUM | Supported by 1-2 credible sources | 1-2 Tier 1-3 sources, or 3+ Tier 4-5 |
| LOW | Single source or lower-tier evidence only | 1 source of any tier |
| CONTESTED | Sources actively disagree | 2+ sources with contradictory claims |

### Confidence Modifiers
- Recency of sources (+/- based on topic volatility)
- Methodology quality of supporting evidence
- Independence of sources (shared upstream = not independent)
- Consistency across source types (web + academic + practitioner = stronger)

## Synthesis Techniques

### Evidence Merging
1. Collect all findings from parallel research streams
2. Group by sub-question
3. For each sub-question:
   - List all claims with sources
   - Identify agreement clusters
   - Identify contradictions
   - Assign confidence rating
   - Write synthesis paragraph

### Contradiction Analysis Matrix

| Claim A | Source(s) | Claim B | Source(s) | Likely Explanation |
|---------|----------|---------|----------|-------------------|
| X is faster | Benchmark paper | Y is faster | Vendor blog | Different workloads, vendor bias |
| Method A preferred | 2022 survey | Method B preferred | 2025 blog | Ecosystem evolution |

### Pattern Identification
- Look for claims that appear across multiple source types
- Identify trends (e.g., adoption curves, technology shifts)
- Note outlier findings (true outliers vs. errors)
- Track the evolution of consensus over time

## Comparison Matrix Format

### Scoring Dimensions

| Dimension | Description | Scale |
|-----------|-------------|-------|
| Maturity | Production readiness, community size | 1-5 |
| Performance | Benchmarks, latency, throughput | 1-5 |
| Developer Experience | Documentation, API design, learning curve | 1-5 |
| Ecosystem | Integrations, plugins, tooling | 1-5 |
| Community | Contributors, issue response time, adoption | 1-5 |
| Cost | Licensing, infrastructure, operational | 1-5 |

### Matrix Template
```markdown
| Dimension | Option A | Option B | Option C | Notes |
|-----------|----------|----------|----------|-------|
| Maturity | 4 | 3 | 5 | C is oldest |
| Performance | 5 | 4 | 3 | A benchmarks best |
| DX | 3 | 5 | 4 | B has best docs |
| Ecosystem | 4 | 4 | 5 | C most integrations |
| Community | 3 | 4 | 5 | C largest community |
| **Total** | **19** | **20** | **22** | |
```

## Recommendation Formulation

### Rules
1. Every recommendation must cite specific findings
2. State the confidence level of the supporting evidence
3. Distinguish between "evidence supports" and "evidence suggests"
4. Include conditions under which the recommendation changes
5. Separate "do this" recommendations from "investigate further" recommendations

### Strength of Recommendation

| Evidence Strength | Recommendation Language |
|-------------------|----------------------|
| HIGH confidence, consistent | "The evidence strongly supports..." |
| MEDIUM confidence | "Based on available evidence..." |
| LOW confidence | "Preliminary evidence suggests..." |
| CONTESTED | "Evidence is mixed; [Claim A] if [context], [Claim B] if [context]" |

## Anti-Patterns

| Pattern | Problem | Correction |
|---------|---------|------------|
| Cherry-picking | Selecting only supporting evidence | Include contradictory findings |
| False consensus | Treating correlated sources as independent | Verify source independence |
| Scope creep | Answering questions not asked | Stay within defined sub-questions |
| Confidence inflation | Rating based on conviction, not evidence | Apply rating criteria strictly |
| Missing gaps | Not reporting what could not be found | Explicitly state unanswered questions |
