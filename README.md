# Understanding the vaccine stance of Italian tweets

Social media is often used to express opinions and attitudes, and being "anonymous" it can be very useful source of data for understanding public opinion on a subject.
I worked on a project for research hospital OPBG (https://www.ospedalebambinogesu.it/) studying vaccine related tweets.
In July 2022 we published our findings
https://www.frontiersin.org/journals/public-health/articles/10.3389/fpubh.2022.948880/full#B29


With the recent advances in AI models, I thought to revist some of the data.

Claude.ai Opus4.6 produced a analysis and dashboard, blowing me away with the insights and accessibility of the findings.

The data was classified for stance by 3 medical professionals as voicing promotional, neutral or discouraging opinions towards vaccines.
Comments about the data from Calude.ai :

The three stances occupy very distinct rhetorical territories:
- Discouraging (639 posts, 36.8%) — The most emotionally intense category. These posts use fear-based persuasion: 11% mention adverse effects, 9.9% invoke children, 9.5% reference death. They ask the most questions (24.3%) and use the most exclamations (21.9%). Distinctive vocabulary includes "danni" (damages), "cavie" (guinea pigs), "iniettare" (inject), "imporre" (impose). Bill Gates conspiracy content clusters here at 3× the promotional rate.
- Neutral (541 posts, 31.1%) — Overwhelmingly news-driven. 45.5% mention COVID (nearly double the other categories), 71.7% include links — by far the highest. Distinctive words are factual: "test", "dosi" (doses), "sperimentazione" (trials), "milioni" (millions). These read as informational dispatches about vaccine development timelines.
- Promotional (558 posts, 32.1%) — A dual strategy emerges. On one hand, collective language ("siamo"/"we are", "speriamo"/"we hope", "mondo"/"world") frames vaccination as shared responsibility. On the other, 16.7% actively name and criticize the "NoVax" movement — making this a combative pro-vaccine stance, not just a gentle promotion.

For classification purposes: the dataset is well-balanced across classes. The strongest discriminating features would be emotional markers (questions + exclamations), theme keywords (adverse effects, children, death for discouraging; doses, testing for neutral; novax for promotional), and structural features (link density, post length).
