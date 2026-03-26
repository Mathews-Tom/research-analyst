# Source Evaluation Reference

Criteria for assessing source credibility, detecting bias, and weighting evidence.

## Credibility Assessment Framework

### CRAAP Test (adapted)

| Criterion | Questions to Ask | Weight |
|-----------|-----------------|--------|
| **Currency** | When published? Updated? Relevant time period? | High for tech topics |
| **Relevance** | Directly addresses the question? Appropriate depth? | Critical |
| **Authority** | Author credentials? Publisher reputation? Peer-reviewed? | High |
| **Accuracy** | Evidence-backed? Verifiable claims? Methodology disclosed? | Critical |
| **Purpose** | Inform, persuade, or sell? Funding disclosed? | High |

### Quick Credibility Scoring

| Signal | Score Modifier |
|--------|---------------|
| Peer-reviewed journal | +3 |
| Known expert author | +2 |
| Methodology described | +2 |
| Data/evidence provided | +2 |
| Independent (no vendor affiliation) | +1 |
| Recent (< 2 years) | +1 |
| Vendor-authored | -2 |
| No author attribution | -2 |
| No date | -1 |
| Marketing language | -3 |
| Conflicts of interest undisclosed | -2 |

## Bias Detection

### Common Bias Types

| Bias | Description | Detection Signal |
|------|-------------|-----------------|
| Vendor bias | Source promotes their own product | Published by product company, comparisons always favor their solution |
| Survivorship bias | Only successful cases reported | No failure cases mentioned, sample selection unclear |
| Selection bias | Non-representative sample | Small sample, convenience sampling, no control group |
| Recency bias | Overweighting recent events | "Everything has changed" narratives without historical context |
| Confirmation bias | Seeking supporting evidence only | No counterarguments addressed, cherry-picked data |
| Authority bias | Accepting claims due to source prestige | Assertions without evidence from well-known figures |
| Anchoring bias | First number encountered dominates | Statistics presented without methodology or comparison |

### Vendor Content Evaluation Rules
1. Never treat vendor benchmarks as independent evidence
2. Check if comparison methodology is disclosed
3. Verify claims against independent benchmarks
4. Note vendor affiliation explicitly in citations
5. Weight vendor content at Tier 7 unless independently verified

## Source Type Characteristics

### Academic Papers

| Strength | Weakness |
|----------|----------|
| Rigorous methodology | Publication lag (6-18 months) |
| Peer review quality gate | May not reflect real-world conditions |
| Reproducibility standards | Narrow scope by design |
| Citation networks for tracing | Accessibility barriers (paywalls) |

### Preprints (arXiv, SSRN)
- Not peer-reviewed — methodology may have flaws
- More current than published papers
- Treat as Tier 2 with methodology caveat
- Check if a peer-reviewed version was later published

### Blog Posts / Practitioner Reports

| Trustworthy Signals | Suspicious Signals |
|--------------------|--------------------|
| Shows raw data | Claims without evidence |
| Describes methodology | "In my experience" without specifics |
| Acknowledges limitations | Superlatives ("best", "revolutionary") |
| Links to reproducible code | No date or author |
| Author has track record | Affiliate links, sponsored content |

### Conference Talks
- Practitioner insights not yet in papers
- Speaker reputation and conference tier matter
- Verify claims against written sources when possible
- Recording date is the relevant date, not upload date

## Recency Requirements

| Topic Category | Maximum Source Age | Rationale |
|---------------|-------------------|-----------|
| AI/ML techniques | 12 months | Rapid advancement |
| Cloud services/pricing | 6 months | Frequent changes |
| Security vulnerabilities | 3 months | Active threat landscape |
| Programming languages | 24 months | Slower evolution |
| Software architecture | 36 months | Principles more stable |
| Foundational CS | No limit | Timeless concepts |

## Citation Format

### Required Fields
- Author(s) or organization
- Title
- Publication date
- URL (with access date for web sources)
- Source type indicator (paper, blog, docs, talk)

### Example
```
[1] J. Smith, "Building Reliable Distributed Systems,"
    ACM Conference 2025. https://doi.org/10.1145/...
    [Paper, accessed 2025-03-15]
```
