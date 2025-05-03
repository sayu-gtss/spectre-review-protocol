# Systematic Review Protocol

## Title
Spectre: Unmasking Speculative Execution Implications for Web Browsers and OS Kernels

## Review Type
Systematic Literature Review (Narrative Synthesis)

## Objective
This review aims to analyze and synthesize existing literature on Spectre-based vulnerabilities with a specific focus on their software-level impact in modern web browsers and operating system kernels. The study seeks to identify variant-specific exploit techniques, detection tools, mitigation strategies, and gaps in current research.

## Research Questions
1. What are the major Spectre variants that affect software systems such as browsers and kernels?
2. What tools have been developed to detect or exploit these variants?
3. What software-level mitigation techniques have been proposed or implemented?
4. What limitations and gaps exist in current research on Spectre-based software attacks?

## Databases and Sources
- Google Scholar  
- IEEE Xplore  
- Technical blogs and advisories (e.g., Project Zero, CISA, Indusface)  
- Reference lists from relevant papers

## Search Strategy
Search terms used included:  
- `"Spectre vulnerability" AND "software"`  
- `"Spectre variant" AND "browser"`  
- `"Spectre AND kernel exploit"`  
- `"speculative execution AND mitigation"`  
Filters:  
- Language: English  
- Years: 2018 to present

## Inclusion Criteria
- Peer-reviewed papers or credible technical sources  
- Focus on Spectre attacks at the **software level** (e.g., browser sandboxing, kernel memory leaks)  
- Describes tools, exploitation workflows, or mitigation strategies  
- Published from 2018 onward

## Exclusion Criteria
- Studies focusing solely on **hardware-level mitigations**  
- Theoretical models without implementation  
- Studies unrelated to Spectre (e.g., Meltdown-only)  
- Papers with insufficient technical clarity

## Study Screening and Selection
- Initial screening by reading titles and abstracts  
- Full-text review for relevance, clarity, and scope fit  
- Manual screening by one reviewer (coursework-based review)  
- PRISMA 2020 flowchart used to document inclusion/exclusion

## Data Extraction Strategy
From each included study, the following data were extracted:
- Spectre variant addressed
- Technical description of the exploit
- Tools or frameworks used
- Mitigation strategies discussed
- Publication year and source

## Synthesis Plan
Narrative synthesis grouped by:
- Spectre variant
- Affected software layers (browser vs. kernel)
  - Web Browser
  - *Variant 1*
  - *Variant 4*
  - OS Kernel
  - *Variant 2*
  - *Spectre BHB*
  - *Spectre RSB*
  - *Spectre SWAPGS*
  - *Retbleed*
- History, Technology, Tools and Mitigations
- Gaps in research

## Risk of Bias Assessment
No formal scoring tool used. However, bias was indirectly addressed by excluding studies with poor technical clarity, irrelevance to software-level security, or lack of data.

## Protocol Version
Version 1.0 – May 2025

## Maintainer
[Your Name], Sri Lanka Institute of Information Technology  
