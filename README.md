<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0f2027,50:203a43,100:2c5364&text=Karthikeyan%20Sadayamuthu&fontColor=ffffff&fontSize=48&fontAlignY=38&desc=Principal%20engineer%20%C2%B7%20agentic%20AI%20%C2%B7%20security%20and%20compliance%20engineering&descAlignY=58&descSize=17&animation=fadeIn" width="100%" alt="Karthikeyan Sadayamuthu" />

<a href="https://github.com/sadayamuthu"><img src="https://readme-typing-svg.demolab.com/?lines=Principal+Software+Engineer+%40+Autodesk;Agentic+AI+platforms+for+regulated+environments;FedRAMP+Moderate+%C2%B7+AWS+GovCloud+%C2%B7+NIST+800-53;Creator+of+OpenGPL+and+OpenAstra;mergelock+%C2%B7+unasked+%C2%B7+anySQL+%C2%B7+ControlGate;Traveler+%C2%B7+Author+%C2%B7+Car+freak+%C2%B7+Hiker&font=Fira+Code&size=20&duration=3200&pause=800&color=2C5364&center=true&vCenter=true&width=720&height=48" alt="typing banner" /></a>

<a href="http://sadayamuthu.com"><img src="https://img.shields.io/badge/Website-sadayamuthu.com-2c5364?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
<a href="https://www.linkedin.com/in/sadayamuthu"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://openastra.org"><img src="https://img.shields.io/badge/OpenAstra-openastra.org-203a43?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="OpenAstra" /></a>
<a href="https://github.com/sadayamuthu"><img src="https://img.shields.io/github/followers/sadayamuthu?style=for-the-badge&logo=github&logoColor=white&color=181717" alt="GitHub followers" /></a>

<img src="https://img.shields.io/badge/experience-16%2B%20years-2ea043?style=flat-square" alt="16+ years" />
<img src="https://img.shields.io/badge/FedRAMP-Moderate%20%C2%B7%20GovCloud-8957e5?style=flat-square" alt="FedRAMP Moderate and GovCloud" />
<img src="https://img.shields.io/badge/certifications-5-b45309?style=flat-square" alt="5 certifications" />
<img src="https://img.shields.io/github/stars/sadayamuthu?affiliations=OWNER&style=flat-square&color=1f6feb&label=stars" alt="total stars" />
<img src="https://komarev.com/ghpvc/?username=sadayamuthu&style=flat-square&color=2c5364&label=profile+views" alt="profile views" />

</div>

I'm a principal engineer with 16+ years building secure, large-scale software platforms, now focused on agentic AI for commercial and regulated environments.

In open source I build in two areas: guardrails for AI coding agents, and machine-readable security compliance. On the agent side that means catching what parallel agents break and what they change without being asked. On the compliance side it means turning NIST SP 800-53 and FedRAMP into data and pre-commit checks that developers can actually run.

Principal Software Engineer at Autodesk. Ashburn, VA.

---

## AI coding agents

<div align="center">

<a href="https://github.com/sadayamuthu/mergelock"><img src="https://github-stats-extended.vercel.app/api/pin/?username=sadayamuthu&repo=mergelock&theme=transparent&hide_border=true&description_lines_count=3" alt="mergelock" /></a>
<a href="https://github.com/sadayamuthu/unasked"><img src="https://github-stats-extended.vercel.app/api/pin/?username=sadayamuthu&repo=unasked&theme=transparent&hide_border=true&description_lines_count=3" alt="unasked" /></a>

</div>

- [**mergelock**](https://github.com/sadayamuthu/mergelock): catches the merge conflicts git can't see between parallel AI agent branches, like a changed signature against a new caller or a deleted symbol that's still in use. TS/JS/Python, tree-sitter based. CLI and MCP server, installable from [homebrew-tap](https://github.com/sadayamuthu/homebrew-tap).
- [**unasked**](https://github.com/sadayamuthu/unasked): shows what your coding agent changed that you never asked for. It scores every hunk against your prompts and the agent's transcript, then reverts just those hunks, with undo. Works with Claude Code and Codex, runs locally, no network.

## AI observability and policy

<div align="center">

<a href="https://github.com/sadayamuthu/anySQL"><img src="https://github-stats-extended.vercel.app/api/pin/?username=sadayamuthu&repo=anySQL&theme=transparent&hide_border=true&description_lines_count=3" alt="anySQL" /></a>
<a href="https://github.com/sadayamuthu/opengpl"><img src="https://github-stats-extended.vercel.app/api/pin/?username=sadayamuthu&repo=opengpl&theme=transparent&hide_border=true&description_lines_count=3" alt="OpenGPL" /></a>

</div>

- [**anySQL**](https://github.com/sadayamuthu/anySQL) ([anysql.org](https://anysql.org)): a SQL analytics engine for AI systems. Query LLM responses, agent traces and RAG pipelines with standard SQL, in-memory on DuckDB and persisted to SQLite, with zero configuration.
- [**OpenGPL**](https://github.com/sadayamuthu/opengpl) ([opengpl.org](https://opengpl.org)): Open Generative Policy Language, a declarative policy language for AI behavioral constraints. It has a schema spec, a parser, and compliance mappings to NIST AI RMF, FedRAMP and ISO 42001, and ships with an SDK, a CLI and a Docker sidecar for runtime policy enforcement in AI pipelines.

## Security compliance: OpenAstra

[OpenAstra](https://openastra.org) brings NIST-grade security compliance into the developer workflow.

<div align="center">

<a href="https://github.com/sadayamuthu/controlgate"><img src="https://github-stats-extended.vercel.app/api/pin/?username=sadayamuthu&repo=controlgate&theme=transparent&hide_border=true&description_lines_count=3" alt="controlgate" /></a>
<a href="https://github.com/sadayamuthu/ocbc"><img src="https://github-stats-extended.vercel.app/api/pin/?username=sadayamuthu&repo=ocbc&theme=transparent&hide_border=true&description_lines_count=3" alt="OCBC" /></a>

</div>

- [**ControlGate**](https://github.com/sadayamuthu/controlgate): an automated NIST 800-53 Rev. 5 compliance gate. Scans code changes across 8 security domains at pre-commit and PR time, with block/warn verdicts and remediation guidance. Validated against [controlgate-test-suite](https://github.com/sadayamuthu/controlgate-test-suite), a set of deliberately vulnerable projects.
- [**OCBC**](https://github.com/sadayamuthu/ocbc): Open Controls Baseline Catalog, a machine-readable NIST SP 800-53 Rev. 5 + FedRAMP catalog. Updated daily, zero install, cloud-agnostic.
- [**nist-cloud-security-baseline**](https://github.com/sadayamuthu/nist-cloud-security-baseline): maps NIST SP 800-53 Rev. 5 controls to FedRAMP baselines via OSCAL, published as enriched JSON.
- [**OEBC**](https://github.com/sadayamuthu/oebc): Open Exposure Baseline Catalog.

---

## Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=python,java,go,ts,js,aws,azure,terraform,docker,git,linux,bash&perline=12" alt="Python, Java, Go, TypeScript, JavaScript, AWS, Azure, Terraform, Docker, Git, Linux, Bash" />

</div>

AI and agents: multi-agent orchestration, MCP (FastMCP), LangChain, OpenAI, Claude, RAG, LLM guardrails, LangSmith, Opik. Security and compliance: FedRAMP Moderate, AWS GovCloud, NIST SP 800-53 Rev. 5, NIST AI RMF, ISO 42001, OSCAL, Zero Trust, GDPR/CCPA. Cloud: AWS (Lambda, EventBridge, SQS, S3, CloudWatch), Azure Identity / MSAL, Terraform. Data: Snowflake, Airflow, dbt, Fivetran, Neo4j, DuckDB.

---

## Experience

- **Principal Software Engineer, Autodesk** (2022–present)
- **Senior Software Development Engineer, Comcast** (2016–2022)
- **Senior Java Developer, The Home Depot** (2013–2016)
- **Earlier:** Tata Consultancy Services, BNY Mellon, Sybrant Technologies (2009–2013)

## Certifications

- Trusted AI Safety Expert (TAISE), Cloud Security Alliance
- Certificate of Competence in Zero Trust (CCZT), Cloud Security Alliance
- Microsoft Azure Security Engineer Associate
- Microsoft Cybersecurity Analyst
- Neo4j Certified Professional

## Education

- **B.E. Information Technology**, Annamalai University, 2008.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:2c5364,50:203a43,100:0f2027&section=footer" width="100%" alt="" />

</div>
