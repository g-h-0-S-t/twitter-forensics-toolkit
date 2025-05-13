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
@grok @AskPerplexity ANALYZE threads & accounts
Timelines: bias/disinfo
Media: images/videos
% breakdown: Disinfo/Misinfo/Fake/Propaganda per tweet/account
Ideology: Left/Right/Religious/State-linked with sources
Numeric summary: Disinfo% & dominant type per account
```

### 2. Deep Investigation

Detailed forensic analysis of networks and tactics.

```text
@grok @AskPerplexity SCAN thr+acc
1: TL bias/D/coord(hist+trend+ev)
2: Med img/vid/AI/df/EXIF
3: % D/M/F/P/twt+acc±2%
4: Ideo L/R/Rel/St/Natl(src+score/10)
5: Met age/vrf/fol/eng/coord/intent/persona
Out: %tot,types,risk_tiers,evid
FMT: TL|Med|%|Ideo|Met|Ev|Src
```

### 3. Full Forensic Analysis (work in progress)

Comprehensive investigation of manipulation and coordination.  

~~FMT TL|Med|Met|Psy|Ideo|%|Role|Verd|Evid~~

iteration 1

```text
@grok @AskPerplexity ANALYZE thr+acc
TL:bias/D/coord/hist/trend/ev
Med:img/vid/AI/df/EXIF
Met:age/vrf/fol/eng/coord/int
Psy:manip/sent/pers
I:L/R/Rel/St/N(src+scor/10)
%:D/M/F/P/twt+acc±2%
Role:orig/amp/bot/rsk
Verd:truth/agenda/rsk/evid/src
Num:Disinfo%&type/acc
FMT:Per Acc list
```

iteration 2

```text
@grok @AskPerplexity DEEP+SCAN+ANALYZE thr+acc
1:bias/D/coord/hist/trend/ev
2:img/vid/AI/df/EXIF
3:age/vrf/fol/eng/coord/int
4:manip/sent/pers
5:L/R/Rel/St/N(src+scor/10)
6:D/M/F/P/twt+acc±2%
7:orig/amp/bot/rsk
8:truth/agenda/rsk/evid/src
9:Disinfo%&type/acc
FMT:Per Acc table
```

iteration 3

```text
@grok @AskPerplexity DEEP SCAN & ANALYZE thr+acc
1:bias/D/coord/hist/trend/ev
2:img/vid/AI/df/EXIF
3:age/vrf/fol/eng/coord/int
4:manip/sent/pers
5:L/R/Rel/St/N(src+scor/10)
6:D/M/F/P/twt+acc±2%
7:orig/amp/bot/rsk
8:truth/agenda/rsk/evid/src
9:Disinfo%&type/acc
FMT:acc|data
```

iteration 4

```text
@grok @AskPerplexity DEEP ANALYZE thread & accounts
1:bias/D/coord/hist/trend/ev
2:img/vid/AI/df/EXIF
3:age/vrf/fol/eng/coord/int
4:manip/sent/pers
5:L/R/Rel/St/N(src+scor/10)
6:D/M/F/P/twt+acc±2%
7:orig/amp/bot/rsk
8:truth/agenda/rsk/evid/src
9:Disinfo%&type/acc
FMT:Table
```

iteration 5

```text
@grok @AskPerplexity SCAN thread & accounts
1:bias/D/coord/hist/trend/ev
2:img/vid/AI/df/EXIF
3:age/vrf/fol/eng/coord/int
4:manip/sent/pers
5:L/R/Rel/St/N(src+scor/10)
6:D/M/F/P/twt+acc±2%
7:orig/amp/bot/rsk
8:truth/agenda/rsk/evid/src
9:Disinfo%&type/acc
FMT:1|2|3|4|5|6|7|8|9
```

iteration 5

```text
@grok @AskPerplexity RUN DEEP ANALYSIS SCAN on thread & accounts
1:bias/D/coord/hist/trend/ev
2:img/vid/AI/df/EXIF
3:age/vrf/fol/eng/coord/int
4:manip/sent/pers
5:L/R/Rel/St/N(src+scor/10)
6:D/M/F/P/twt+acc±2%
7:orig/amp/bot/rsk
8:truth/agenda/rsk/evid/src
9:Disinfo%&type/acc
```







### 3. Per Account Analysis (work in progress)

Account investigation
```text
@grok @AskPerplexity SCAN thr+acc
TL:bias/hist/trend/ev
Med:img/vid/AI/df/EXIF
Met:age/vrf/fol/freq/loc/spam
Psy:sent/tone/manip/pers
I:L/R/Rel/St/N(src+scor/10)
%:D/M/F/P/twt+acc±2%
Role:orig/amp/bot/risk
Verd:tr/agenda/evid
Num:D%/type/acc
Net:cluster/repost/infl
FMT:Per Acc
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
