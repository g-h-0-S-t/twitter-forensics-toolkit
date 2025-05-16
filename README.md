# 𝕏 Forensics Toolkit

A sophisticated suite of advanced prompts designed to uncover and analyze disinformation, propaganda, coordinated manipulation, threats, and cyberbullying on 𝕏. Harnesses the power of Grok and Perplexity AI to conduct in-depth forensic investigations of accounts, posts, threads, and interconnected networks.

## Forensic Capabilities

- Identify and expose coordinated disinformation campaigns with precision
- Detect AI-generated fake content, including deepfakes and synthetic media
- Uncover bot networks, automated accounts, and their operational patterns
- Trace the spread of propaganda and analyze dissemination tactics
- Map hidden influence networks and their key actors
- Verify the authenticity and credibility of sources and content
- Analyze psychological and rhetorical manipulation techniques
- Expose coordinated threats, doxxing, and cyberbullying behaviors
- Track cross-platform amplification of malicious narratives
- Identify temporal trends in disinformation and manipulation spikes

## Analysis Prompts

### Prompt 1: Disinfo - Rapid Forensics

Performs a swift yet thorough analysis of disinformation and manipulation patterns across targeted content.

```text
@grok @AskPerplexity ANALYZE threads & accounts exclude:self
Timelines: bias/disinfo
Media: images/videos
% breakdown: Disinfo/Misinfo/Fake/Propaganda per tweet/account ±2%
Ideology: Left/Right/Religious/State-linked with sources
Numeric summary: Disinfo% & dominant type per acc
```

### Prompt 2: Disinfo - Deep Investigation

Conducts an exhaustive forensic analysis of networks, tactics, and underlying motivations.

```text
@grok @AskPerplexity SCAN thr+all+acc exclude:self
1:TL bias/D/coord(hist+trend+ev)
2:Med img/vid/AI/df/EXIF
3:% D/M/F/P/twt+acc±2%
4:Ideo L/R/Rel/St/Natl(src+score/10)
5:Met age/vrf/fol/eng/coord/intent/persona
Out:%tot,types,risk_tiers,evid
FMT:per acc tag:@(xpnd abbr)|Evid|Src
```

### Prompt 3: Threats & Cyberbullying - Deep Investigation

Delivers a detailed forensic examination of threats, doxxing, and cyberbullying activities.

```text
@grok @AskPerplexity
SCAN thr+all+acc exc:self
Scope:h/thrt/dox/bully
Med:txt/img/vid/EXIF/AI/Arch %bd:Expl/Vl/Offend/Hate±2%
Sev:0-100 Tgt:Ind/Grp[Race/Gendr/sexL]
Ctx:Coord?[Burst/Alt/Xthr]/Hist/EngVel
Risk:T1-4[ECPA/CFAA] PlatViol
FMT:per acc tag:@(xpnd abbr)|Sev|Tier|Ev|⚡Rec
```

## Usage Instructions

1. Identify suspicious content such as a tweet, thread, or account
2. Select and copy the appropriate forensic prompt from above
3. Reply to the target content with the chosen prompt
4. Await the AI-driven forensic analysis results
5. Review the comprehensive findings and evidence provided

> [!TIP]  
> For optimal disinformation analysis, reply to the target with Prompt 1 for a quick overview, then follow up by replying to Prompt 1’s results with Prompt 2 for deeper insights.

Instant forensic analysis with no setup or configuration required.

## Analysis Results

Each investigation provides actionable insights, including:

- Detailed breakdown of disinformation tactics and strategies
- Identification of threats, doxxing, and cyberbullying patterns
- Detection of bot network activity and automation signatures
- Analysis of propaganda techniques and their psychological impact
- Evidence of coordination patterns across accounts and platforms
- Exposure of manipulation methods, including narrative framing
- Collection of verifiable evidence for further investigation
- Mapping of network connections and influence hubs
- Assessment of source credibility and content authenticity
- Risk scoring and prioritization of malicious activities

## Designed For

- Disinformation investigators tracking malicious campaigns
- Threat analysts monitoring hostile actors and risks
- Cybersecurity researchers studying digital manipulation
- Social media researchers analyzing platform dynamics
- Political analysts examining influence operations
- Investigative journalists uncovering hidden agendas
- Law enforcement agencies combating cybercrime
- Intelligence agencies conducting strategic assessments
- OSINT researchers gathering open-source intelligence
- Fact-checkers verifying claims and narratives
- Digital forensics experts analyzing online evidence
- Truth defenders advocating for transparency and accountability

## License

MIT License

## Join the Fight

Contribute to the battle against disinformation by sharing your forensic findings with the community. Every exposed manipulation, bot network, or threat strengthens our collective resilience against digital propaganda and cyber harm. Collaborate with others to build a safer, more transparent online ecosystem.
