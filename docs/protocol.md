# Generative AI for Requirements Engineering: A Scoping Literature Review

## Summary  
This study explores how **Generative AI** is applied in **Requirements Engineering (RE)**, focusing on trends, challenges, and its role in optimizing the RE process. It assesses AI's impact on **elicitation, refinement, and validation** of requirements. Additionally, it identifies research gaps and methodological limitations in the field.

## Researchers & Roles  
- **Jomar Thomas Almonte** - *Doctor of Engineering (D.Eng) Candidate, Penn State University (Lead Investigator & Reviewer)*  
- **Dr. Nathalia Moraes do Nascimento** - *Assistant Professor, Penn State University (Methodology Reviewer & Advisor)*  

## Protocol Registration  
This protocol will be registered in **OSF Registries** (*https://osf.io/registries*) for transparency and future reference.

## Research Questions  
1. **How is Generative AI applied in Requirements Engineering?**  
   - RE subdomains (e.g., elicitation, validation) addressed  
   - Specific Generative AI methods/tools used  
   - Frequency and venues of relevant studies  
   - Key contributing authors, institutions, or regions  

2. **What are the benefits and challenges of using Generative AI in RE?**  
   - Recurring evaluation themes  
   - Outcome comparisons across RE tasks  

3. **What research gaps exist in integrating Generative AI with RE?**  
   - **Methodological Gaps** (e.g., lack of benchmarking, evaluation metrics)  
   - **Industrial Gaps** (e.g., challenges in real-world adoption)  
   - **Tooling & Automation Gaps** (e.g., lack of established frameworks)  

## Databases Searched  
- **Engineering Village** (Compendex, Scopus, Inspec)  
- **IEEE Xplore**  

## Search Strategy  
```plaintext
((((("Generative AI" OR "Large Language Models" OR "GPT" OR "GenAI" OR "LLMs")  AND ("Requirements Engineering" OR "software requirements" OR "requirements elicitation"  OR "requirements refinement" OR "requirements validation"))) WN ALL)) AND (({ca} OR {ja}) WN DT)) AND (({english} WN LA) AND ((2024 OR 2023) WN YR))) AND ({requirements engineering} WN CV))
```

### Search Strategy Notes  
- The search focuses on **Generative AI in RE** while avoiding broader software engineering topics.  
- It retrieves **only journal and conference papers** (`{ca}` and `{ja}`) in **English** (2023-2024).  
- **Controlled vocabulary (`WN CV`)** ensures subject relevance.  

**Engineering Village (Compendex) yielded 95 results.**  

## Inclusion/Exclusion Criteria  

| **Category**         | **Inclusion**                                          | **Exclusion**                                    |
|----------------------|-------------------------------------------------------|-------------------------------------------------|
| **Databases**       | Engineering Village, IEEE Xplore                      | Not indexed in selected databases              |
| **Document Types**  | Journal articles, conference papers                    | Editorials, blogs, non-peer-reviewed works     |
| **Years**           | 2023-2024                                              | Pre-2023                                       |
| **Language**        | English                                                | Non-English                                    |
| **Topic Focus**     | Generative AI in RE                                    | General AI topics unrelated to RE             |

## Review Process  
### Abstract Review  
- Independently review **100 articles** for inclusion/exclusion.  
- Calculate **interrater reliability**.  
- Discuss discrepancies and refine criteria.  
- Screen **remaining abstracts individually**.  

### Full-Text Review  
- Confirm **inclusion criteria** through full-text assessment.  
- Proceed with **data extraction** for qualifying articles.  

## Data Extraction Plan  
Extracted information includes:  
- **Title, authors, publication year, and venue**  
- **RE subdomains addressed**  
- **Generative AI tools/methodologies used**  
- **Evaluation metrics and methods**  
- **Benefits, challenges, and research gaps**  

Guidelines for data extraction will be collaboratively **established and refined** throughout the review.

## Quality Assessment (Optional for Scoping Reviews)  
Although **quality assessment** is not mandatory for scoping reviews, we will **document study limitations** (e.g., lack of empirical validation).  
We will consider **Kitchenham's criteria** for evaluating software engineering studies:  
- **Study design**  
- **Sampling method**  
- **Empirical evaluation rigor**  
- **Reproducibility of results**  

## Subgroup Analysis  
Focus areas:  
- **Trends by RE subdomain** (*e.g., elicitation vs. validation*)  
- **AI methods/tools applied**  
- **Publication trends** (*journals vs. conferences*)  
- **Institutional and geographic patterns**  

## References  
- Kitchenham, B., et al. (2009). *Systematic literature reviews in software engineering - A systematic literature review*. *Information and Software Technology, 51*(1), 7-15.  
- M. Phillips et al., "Systematic Reviews in the Engineering Literature: A Scoping Review," in *IEEE Access*, vol. 12, pp. 62648-62663, 2024, doi: 10.1109/ACCESS.2024.3394755.  
