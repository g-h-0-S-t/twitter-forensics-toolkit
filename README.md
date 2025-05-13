# Twitter Forensics & Disinformation Analysis

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

### 1. Rapid Forensics

Quick analysis of disinformation and manipulation patterns.

```text
@grok @AskPerplexity: ANALYZE thread & accounts!
Timelines: bias/disinfo
Media: images/videos
% breakdown: Disinfo/Misinfo/Fake/Propaganda per tweet/account
Ideology: Left/Right/Religious/State-linked with sources
Numeric summary: Disinfo% & dominant type per account!
```

### 2. Deep Investigation

Detailed forensic analysis of networks and tactics.

```text
@grok @AskPerplexity SCAN thr+acc:1:TLs bias/D/coord(hist+trend+ev) 2:Media img/vid/AI/deepfake/EXIF 3:%D/M/F/P/twt+acc±2% 4:Ideo L/R/Rel/St/Natl(src+score/10) 5:Metrics age/vrf/fol/eng/coord/intent/persona Out:%tot,types,risk tiers+EVID FMT:TL|Med|Pct|Ideo|Met|Vrf|Ev|Src
```

### 3. Full Forensic Analysis

Comprehensive investigation of manipulation and coordination.

```text
@grok @AskPerplexity DFIR+ANLZ+SCAN thr+acc TL:bias/D/coord,Med:img/vid/AI/df/EXIF,Met:age/vrf/fol/eng/coord/int,Psy:manip/sent/pers,Ideo:L/R/Rel/St/Nat(src+score/10),%:D/M/F/P/twt+acc±2%,Role:orig/amp/bot/risk,Verd:truth/agenda/risk/src.Out:TL|Med|Met|Psy|Ideo|Pct|Role|Verd|Evid
```

## Usage Instructions

1. Locate suspicious content (tweet/thread/account)
2. Copy appropriate forensic prompt
3. Reply to target with the prompt
4. Wait for AI forensic analysis
5. Review detailed findings

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
