# Poynter's _Index of Unreliable News Websites_ (excluding _satire_)
Domain block list based on Poynter's [_An Index of Unreliable News Websites_](http://www.poynter.org/ifcn/unreliable-news-index/) Internet Fact Checking Network article from 30 April 2019 and taken down after legal threats from some of those sites 2 days later. The original list is their property and was downloaded thanks to the Wayback Machine.

It's intended for use with the [Pi-Hole](https://pi-hole.net/) or other DNS-based website filtering, and uses standard /etc/hosts file format, e.g.:
```
0.0.0.0 www.example.com
0.0.0.0 www.example.net
```

The Poynter list allows domains to have multiple tags, as follows (paraphrased):
* **bias**: Extreme bias. Propaganda, opinions distorted as facts, etc.
* **conspiracy**: Well-known promoters of conspiracy theories.
* **clickbait**: Generally credible but use exaggerated, misleading, or questionable headlines, etc.
* **fake**: Fake, hoax, or presented in a biased and tawdry fashion. This 'real' content serves as cover for the fake.
* **satire**: Not necessarily intended to mislead (e.g. _The Onion_ and), using humour, irony, etc, to comment on current events.
* **unreliable**: Have posted deceptive, extremely misleading, hate, junk science, rumours and gossip, repressive state controlled, etc, content.

This block list uses the original list, but with the domains containing the 'satire' tag removed. These are the sites I have no interest in seeing or inadvertently clicking.

I'm not planning on maintaining this list unless IFCN/Poynter make changes and/or put it back up again.
