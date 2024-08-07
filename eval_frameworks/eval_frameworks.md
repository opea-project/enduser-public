# Evaluation Frameworks for Use Case Discussion
## Purpose
Our goal with these use case evaluation frameworks is to help end users provide both high-level context and enough detail that OPEA engineers can transform the use cases into useful features of OPEA that the end users desire. 

## Big Box and Arrow Diagram Analysis
The "big-box and arrow" approach intentionally over simplifies the architectural diagram allowing the use case developer to provide context and details for each of the key components under analysis. 

<img src="Box_n_arrow.png" alt="Box and arrow diagram showing external influences, traditional systems, a vector DB and an LLM" style="width: 50%;" />

| Category | Description | Examples |
|----------|----------|----------|
| External Influences | Porter's 5 forces + regulatory bodies | FINRA for finance, HIPPA for healthcare. As we think about other things like supplier power, it could be contractual requirements, etc. |
| Traditional Systems | CRM, HR Systems, ERP, industry-specific processes and software  | see below for more - this is where the use cases get interesting |
| Vector DB | Less about the choice of vector DB and more about the features needed, how to interface with it, and the representation of the data as it flows from the traditional systems to the vector DB (in preparation for RAG) | see examples below |
| Supporting Infrastructure | On-Prem/Cloud/Hybrid and what are your specific needs as you wire up your traditional systems with RAG/GenAI | need a few here |


### Example Use Cases


## Failed Project Analysis
With this type of analysis, the end user provides information about previous attempts to incorporate AI (either GenAI or traditional) to their enterprise. They discuss the successes and (importantly) the failures of those efforts and what they would need in a successful system. Some helpful components of failure analysis include: 
- Software (what was available at the time, what was tried, what was developed)
- Data (representation, flow, ingest, storage)
- Algorithms
- Talent
- Infrastructure
- APIs
