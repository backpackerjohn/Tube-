# Source Log and Evidence Ledger

**Access date for this build:** 2026-07-12 unless another date is shown.

Reliability scale:

- **A — primary/official:** government, platform policy, manufacturer warranty, API response.
- **B — strong secondary:** Reuters or similarly rigorous reporting that identifies underlying data providers.
- **C — specialist commercial research:** useful proprietary data with disclosed limits or incentives.
- **D — directional only:** connected-tool metrics that cannot be reproduced from a public URL.

The package uses source IDs in brackets. A claim described as an **inference** is a conclusion drawn from one or more sources rather than something a source states directly.

## Official and primary web sources

### S01 — IRS: Used Clean Vehicle Credit
- URL: https://www.irs.gov/credits-deductions/used-clean-vehicle-credit
- Title: *Used Clean Vehicle Credit*
- Accessed: 2026-07-12
- Evidence supported: The Previously-Owned Clean Vehicle Credit is not available for vehicles acquired after September 30, 2025; historical $25,000 price cap and maximum $4,000 credit; page last reviewed July 10, 2026.
- Reliability: **A** — current IRS guidance.

### S02 — U.S. Department of Energy: EV consumer fit
- URL: https://afdc.energy.gov/vehicles/electric-consumers
- Title: *Electric Vehicles for Consumers*
- Accessed: 2026-07-12
- Evidence supported: Buyers should evaluate daily mileage, home/work charging, compatible public charging, longer trips, climate, terrain and loads; many current EVs travel 200–300 miles per charge.
- Reliability: **A** — DOE Alternative Fuels Data Center.

### S03 — FuelEconomy.gov: all-electric vehicles
- URL: https://www.fueleconomy.gov/feg/evtech.shtml
- Title: *All-Electric Vehicles*
- Accessed: 2026-07-12
- Evidence supported: EV efficiency, range and recharge tradeoffs; DOE-cited design-life estimate of 12–15 years in moderate climates and 8–12 years in severe climates; replacement can be costly.
- Reliability: **A** — DOE/EPA site. The design-life statement is a general estimate, not a guarantee for a specific vehicle.

### S04 — NHTSA recall lookup
- URL: https://www.nhtsa.gov/recalls
- Title: *Check for Recalls*
- Accessed: 2026-07-12
- Evidence supported: VIN search can identify certain unrepaired safety recalls; limitations include repaired recalls, some newly announced recalls and recalls older than 15 years.
- Reliability: **A** — official U.S. vehicle-safety authority.

### S05 — YouTube monetization policy
- URL: https://support.google.com/youtube/answer/1311392?hl=en
- Title: *YouTube channel monetization policies*
- Accessed: 2026-07-12
- Evidence supported: Monetized content must be original and authentic; mass-produced or repetitive content, minimal-value slideshows and copied content are ineligible; reused material may qualify only when meaningfully transformed with substantive commentary or editing.
- Reliability: **A** — YouTube’s current policy page, including the July 15, 2025 terminology update.

### S06 — Tesla vehicle warranty
- URL: https://www.tesla.com/support/vehicle-warranty
- Title: *Vehicle Warranty*
- Accessed: 2026-07-12
- Evidence supported: Current Model 3/Model Y battery and drive-unit warranty variants; minimum 70% capacity retention; remaining original battery warranty transfers with a pre-owned vehicle; Tesla says the authoritative warranty is the one supplied with the specific vehicle.
- Reliability: **A** — manufacturer source. Current terms must not be assumed to apply retroactively to every model year.

## Market and specialist research

### S07 — Reuters: U.S. used-EV market
- URL: https://www.reuters.com/business/autos-transportation/falling-prices-steer-us-buyers-toward-used-electric-vehicles-2026-03-11/
- Title: *Falling prices steer US buyers toward used electric vehicles*
- Published: 2026-03-11
- Accessed: 2026-07-12
- Evidence supported: January 2026 used-EV sales of 31,503, up about 21% year over year (Cox Automotive); 2025 sales of 378,140, up roughly 35% (CarEdge); used-EV price premium narrowed to $1,376 in January from $2,591 in December; Model 3 and Model Y were among widely available and sought-after used EVs.
- Reliability: **B** — Reuters reporting with named underlying data providers. The underlying proprietary datasets were not independently downloaded.

### S08 — IEA Global EV Outlook 2025
- URL: https://www.iea.org/reports/global-ev-outlook-2025/trends-in-electric-car-affordability
- Title: *Trends in electric car affordability — Global EV Outlook 2025*
- Published: 2025
- Accessed: 2026-07-12
- Evidence supported: EVs can have lower lifetime total cost due to fuel and maintenance savings; global average battery-pack price fell more than 25% in 2024; U.S. battery-price decline contributed to lower average electric-SUV purchase prices; U.S. new-EV affordability remained constrained.
- Reliability: **A/B** — intergovernmental analysis using S&P Global Mobility, BNEF and EV Volumes.

### S09 — Recurrent battery replacement research
- URL: https://www.recurrentauto.com/research/how-long-do-ev-batteries-last
- Title: *New Data: How Long Do Electric Car Batteries Last?*
- Published: 2025-11-11
- Accessed: 2026-07-12
- Evidence supported: Analysis of a 30,000-plus-vehicle community; outside major recalls, under 4% had a battery replacement across all years; stated replacement rates were about 8.5% for first-generation EVs, 2% for second-generation examples and 0.3% for 2022-and-newer EVs; range availability is not the same as battery degradation; data limitations are explicitly disclosed.
- Reliability: **C** — specialist commercial dataset with methodology and limitations. Not representative of all EVs and not suitable for guaranteeing an individual car.

## YouTube Data API evidence — recent viewing validation

All metrics below were returned by the YouTube Data API connection on 2026-07-12. URLs are direct video pages. Counts are snapshots and will change.

### Used-EV buyer-intelligence sample

#### Y01
- URL: https://www.youtube.com/watch?v=2bQ0Ug8MMVw
- Title: *Buying a Used Tesla? Here’s What You Need to Know*
- Published: 2025-01-08
- API snapshot: 469,001 views; 6,863 likes; 505 comments; 10:19.
- Supports: recent, commercially oriented used-Tesla guidance can attract substantial long-form viewing.
- Reliability: **A** for the API metadata; the video’s own claims were not adopted as facts.

#### Y02
- URL: https://www.youtube.com/watch?v=dvyEM0OmfS4
- Title: *Is it worth buying an older Tesla in 2025? (Don’t Make This Mistake!)*
- Published: 2025-04-22
- API snapshot: 418,342 views; 6,705 likes; 521 comments; 13:11.
- Reliability: **A** for metadata.

#### Y03
- URL: https://www.youtube.com/watch?v=tjAJt2YZRx4
- Title: *Why is EV Resale Value Dropping So Fast Worldwide? Golden opportunity to buy a used EV?*
- Published: 2025-07-09
- API snapshot: 390,595 views; 9,076 likes; 863 comments; 13:19.
- Reliability: **A** for metadata.

#### Y04
- URL: https://www.youtube.com/watch?v=LHtmrg-i70Q
- Title: *Would I Do it Again? 6 Months With a Used Porsche Taycan 4S*
- Published: 2025-10-07
- API snapshot: 371,730 views; 6,781 likes; 722 comments; 15:28.
- Reliability: **A** for metadata.

#### Y05
- URL: https://www.youtube.com/watch?v=JQXW9a2AUXU
- Title: *Is Buying A Used Electric Vehicle Worth It? | Hyundai IONIQ 5 Purchase*
- Published: 2025-01-22
- API snapshot: 257,224 views; 3,226 likes; 372 comments; 11:21.
- Reliability: **A** for metadata.

### Wi-Fi troubleshooting sample
- W01: https://www.youtube.com/watch?v=nj8RO74JdSw — 1,308,722 views.
- W02: https://www.youtube.com/watch?v=tz3OrU3UNpY — 736,332 views.
- W03: https://www.youtube.com/watch?v=kCuA3EWLvIw — 595,923 views.
- W04: https://www.youtube.com/watch?v=SiAZuRTe0V4 — 457,148 views.
- W05: https://www.youtube.com/watch?v=SeVECJCWrdI — 441,929 views.
- Use: candidate demand comparison only. Reliability **A** for API metadata.

### Rail-planning sample
- R01: https://www.youtube.com/watch?v=Jz64bL8tU_s — 611,938 views.
- R02: https://www.youtube.com/watch?v=uJbKonD9j7M — 263,821 views.
- R03: https://www.youtube.com/watch?v=k1loQUuYaE8 — 226,936 views.
- R04: https://www.youtube.com/watch?v=OsKelxcQUNo — 176,536 views.
- Use: candidate demand comparison only. Reliability **A** for API metadata.

### Appliance-repair sample
- A01: https://www.youtube.com/watch?v=2qg2jGeQVjI — 2,899,657 views.
- A02: https://www.youtube.com/watch?v=FLKKzTIPJ0w — 2,652,452 views.
- A03: https://www.youtube.com/watch?v=nv5VbdPtqdk — 1,389,487 views.
- A04: https://www.youtube.com/watch?v=wOaZxLLl8Lo — 860,872 views.
- A05: https://www.youtube.com/watch?v=SK12HXBgFAI — 683,566 views.
- Use: validates demand but also shows that custom repair demonstrations are central. Reliability **A** for metadata.

### Megaproject sample
- M01: https://www.youtube.com/watch?v=h3DCdWyb0cc — 3,239,746 views.
- M02: https://www.youtube.com/watch?v=J-fxqsjaav0 — 1,626,370 views (adjacent historical-explainer result).
- M03: https://www.youtube.com/watch?v=TT1WO8zWk7o — 1,097,218 views.
- M04: https://www.youtube.com/watch?v=iN27GcrkXVo — 907,224 views.
- M05: https://www.youtube.com/watch?v=nQmFpa3yxxg — 862,398 views.
- Use: candidate demand and competition/production benchmark. Reliability **A** for metadata.

### Airport-navigation sample
- P01: https://www.youtube.com/watch?v=me_zrNbq--E — 1,183,458 views.
- P02: https://www.youtube.com/watch?v=apAq188bHII — 501,748 views.
- P03: https://www.youtube.com/watch?v=-wzRtaqIsLs — 244,001 views.
- P04: https://www.youtube.com/watch?v=n3tw0ST-8Og — 242,774 views.
- P05: https://www.youtube.com/watch?v=vhlXdk1mgR0 — 148,027 views.
- Use: candidate demand comparison. Reliability **A** for metadata.

### HVAC/home-energy sample
- H01: https://www.youtube.com/watch?v=K15qIMH8qDs — 792,593 views.
- H02: https://www.youtube.com/watch?v=xn03N3b0-lE — 604,492 views.
- H03: https://www.youtube.com/watch?v=jjX5B8Txc7E — 320,706 views.
- H04: https://www.youtube.com/watch?v=cJDRqWwlKug — 245,498 views.
- Use: candidate demand comparison and safety/filming burden. Reliability **A** for metadata.

### Used-device sample
- T01: https://www.youtube.com/watch?v=IkIh-_cg6iA — 887,418 views.
- T02: https://www.youtube.com/watch?v=FBDKCP-clf0 — 849,726 views.
- T03: https://www.youtube.com/watch?v=MNovjY0mLIY — 566,242 views.
- T04: https://www.youtube.com/watch?v=lGcy4vTxn80 — 353,177 views.
- T05: https://www.youtube.com/watch?v=le6UjODjiRY — 250,018 views.
- Use: candidate demand comparison; search drift toward phones and non-U.S. audiences is noted. Reliability **A** for metadata.

### Subscription/dark-pattern sample
- D01: https://www.youtube.com/watch?v=7JfovrVIV0I — 966 views.
- D02: https://www.youtube.com/watch?v=TaPokwdsLM4 — 310 views.
- D03: https://www.youtube.com/watch?v=dnrh6WJw9_I — 283 views.
- D04: https://www.youtube.com/watch?v=UHKf_0_w3-w — 200 views.
- D05: https://www.youtube.com/watch?v=J5bSMQBjaO4 — 153 views.
- Use: evidence that apparent keyword demand did not translate into strong recent English long-form viewing in this sample. Reliability **A** for metadata.

## vidIQ connected evidence

These metrics came from the authenticated vidIQ connection. vidIQ did not return a public, query-specific URL, so they are **directional evidence rather than independently URL-verifiable facts**. This limitation is retained instead of pretending the metrics are public. Generic service URL: https://vidiq.com/

### V01 — Used EV / battery-health cluster
- Query snapshots included:
  - “tesla battery health check”: estimated monthly search 4,305; competition 13; overall 67.35.
  - “used tesla buying guide”: 3,408; competition 21.5; overall 63.04.
  - “ev buying guide”: 5,061; competition 17.5; overall 66.18.
  - “buying used ev”: 4,779; competition 22.2; overall 64.07.
  - “ev battery degradation”: 3,718; competition 24; overall 62.38.
- Reliability: **D** — useful for relative prioritization, not a promise of traffic.

### V02 — Scam/fraud cluster
- “scam prevention”: 4,052; competition 18; overall 65.11.
- “online scam”: 17,553; competition 46; overall 59.61.
- “romance scam”: 37,469; competition 56; overall 58.56.
- Reliability: **D**.

### V03 — Wi-Fi cluster
- “wifi option not showing in windows 10”: 12,528; competition 12.9; overall 71.54.
- “network troubleshooting”: 5,409; competition 28.9; overall 61.88.
- Reliability: **D**.

### V04 — Rail cluster
- “sleeper train”: 30,555; competition 70; overall 52.17.
- “amtrak roomette”: 8,596; competition 29.5; overall 63.44.
- “train travel”: 27,742; competition 49.5; overall 60.00.
- Reliability: **D**.

### V05 — Appliance cluster
- “appliance repair”: 17,591; competition 35; overall 64.02.
- “home repair”: 31,837; competition 40; overall 64.33.
- Reliability: **D**.

### V06 — Megaproject cluster
- “megaprojects”: 220,422; competition 66; overall 61.46.
- “construction”: 398,313; competition 47; overall 71.36.
- Reliability: **D**.

### V07 — Airport cluster
- “airport transfer”: 4,219; competition 24.2; overall 62.79.
- “travel tips”: 154,825; competition 53.7; overall 65.0.
- Reliability: **D**.

### V08 — HVAC cluster
- “heat pump troubleshooting”: 4,690; competition 20.1; overall 64.84.
- “hvac basics”: 4,997; competition 25.9; overall 62.77.
- “hvac course”: 14,566; competition 17.4; overall 70.33.
- Reliability: **D**.

### V09 — Used-device cluster
- “second hand laptop”: 15,718; competition 29.4; overall 65.83.
- “laptop battery health check”: 39,423; competition 39; overall 65.56.
- Reliability: **D**.

### V10 — Subscription/dark-pattern cluster
- “subscription trap”: 28,503; competition 29.9; overall 67.94.
- “cancel subscriptions”: 5,241; competition 20.4; overall 65.15.
- “dark patterns”: 17,305; competition 41.8; overall 61.24.
- Reliability: **D**.

## vidIQ channel-pattern evidence

Channel metrics are connector snapshots and can change. Direct channel URLs provide identity; numerical snapshots remain **D** because the public page was not separately scraped.

- https://www.youtube.com/@japanesemotors — 24.4K subscribers, 2.76M views, 32 videos, approximately 86K average views in the connected snapshot; faceless automotive buying/maintenance format.
- https://www.youtube.com/@everythinghyundai80 — 4.53K subscribers, 659K views, 68 videos; connected snapshot showed 20.8% 30-day subscriber growth.
- https://www.youtube.com/@everythinglexus — 9.82K subscribers, 1.08M views, 48 videos; approximately 22.4K average views.
- https://www.youtube.com/@autogearshift2 — 30.2K subscribers, 3.43M views, 479 videos; connected snapshot showed strong one-year growth.
- https://www.youtube.com/@carlandtv — 64.1K subscribers, 9.29M views, 948 videos.
- https://www.youtube.com/@garycevrepairs — 10.1K subscribers, 1.1M views, 176 videos.
- https://www.youtube.com/@scamhut — 70.6K subscribers, 170.3M views, 76 videos; Shorts-heavy breakout that also illustrates reused-clip risk for the scam niche.
- https://www.youtube.com/@omtherails — 47K subscribers, 9.73M views, 154 videos; successful faceless rail channel, but its trip-report premise requires original journey footage.

## Evidence-handling rules used in this package

1. Current policy, tax, safety and warranty claims default to official sources.
2. Market numbers are dated on screen and in descriptions.
3. Connector metrics are never described as guaranteed search volume or guaranteed earnings.
4. A dashboard range estimate is never treated as a direct state-of-health reading. [S09]
5. A recall lookup is treated as a safety screen, not a complete service-history report. [S04]
6. Model-year warranty claims must be verified against the VIN-specific or vehicle-supplied warranty before publication. [S06]
7. Any future price ranking must save a dated listing sample and state geography, trim, mileage and fees.