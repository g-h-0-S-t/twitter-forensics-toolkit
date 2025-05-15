# 𝕏 Forensics Toolkit

Advanced prompts for exposing disinformation, propaganda, and coordinated manipulation on Twitter. Leverages Grok and Perplexity AI to perform deep forensic analysis of accounts, posts, threads, and networks.

## Forensic Capabilities

- Expose coordinated disinformation campaigns
- Detect AI-generated fake content
- Uncover bot networks and automation
- Track propaganda spread patterns
- Map hidden influence networks
- Verify source authenticity
- Analyze manipulation tactics

## Analysis Prompts

### Prompt 1: Rapid Forensics

Quick analysis of disinformation and manipulation patterns.

```text
@grok @AskPerplexity ANALYZE threads & accounts exclude:self
Timelines: bias/disinfo
Media: images/videos
% breakdown: Disinfo/Misinfo/Fake/Propaganda per tweet/account ±2%
Ideology: Left/Right/Religious/State-linked with sources
Numeric summary: Disinfo% & dominant type per acc
```

### Prompt 2: Deep Investigation

Detailed forensic analysis of networks and tactics.

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

## Usage Instructions

1. Locate suspicious content (tweet/thread/account)
2. Copy appropriate forensic prompt
3. Reply to target with the prompt
4. Wait for AI forensic analysis
5. Review detailed findings

> [!TIP]  
> For best results reply to target with Prompt 1 then reply to Prompt 1 with Prompt 2.

Instant forensic analysis - no setup required.

## Analysis Results

Each investigation reveals:

- Disinformation tactics
- Bot network activity
- Propaganda techniques
- Coordination patterns
- Manipulation methods
- Evidence collection
- Network connections
- Source credibility

## Designed For

- Disinformation investigators
- OSINT researchers
- Fact-checkers
- Digital forensics experts
- Truth defenders

## License

MIT License

## Join the Fight

Help combat disinformation by sharing your forensic findings. Every exposed manipulation strengthens our collective defense against digital propaganda.
