# The Reverse-Engineering Framework: Master Cheat Sheet

The single lens to apply before writing anything else. Every region sheet, every written
practice answer, every "likely exam angle" is just this chain filled in for one place.
If you internalize this chain, you can construct a plausible, mark-scoring answer for a
region you have never specifically studied, because the exam is testing the reasoning
chain, not a list of memorized facts.

Grounded in the WSET Level 3 Sample Short Written Answer Paper (Oct 2017): see
`06_past_papers/` for the source questions this framework is built to answer.

## The chain

```
Latitude / Altitude / Proximity to water / Mountains
                    ↓
         Macroclimate type
   (cool–hot; maritime/continental/mediterranean)
                    ↓
      Diurnal range & rainfall pattern
                    ↓
   Ripening behaviour: sugar/acid balance,
   disease pressure, hang-time flexibility
                    ↓
      Soil: a MODIFIER, not the start
   (drainage, heat retention, vigour: fine-tunes
    what the climate already allows)
                    ↓
    Grape variety choice (which grapes suit
         this ripening profile)
                    ↓
  Viticulture / winemaking choices (irrigation?
  chaptalization? extended hang time? oak? MLF?)
                    ↓
         Final wine style
 (sweetness, body, aroma, structure, quality tier)
```

**Why soil comes fourth, not first:** soil cannot overcome a climate that is fundamentally
wrong for a variety. Gravel in a climate too cold for Cabernet Sauvignon still will not
ripen it. Soil decides *how well* a climate-appropriate variety performs: drainage,
vigour, heat retention at the margins: not whether it can grow there at all. Climate sets
the ceiling; soil adjusts within it. This is why altitude and climate "tell the biggest
story," and why they are always where you start.

## How to reverse-engineer an unfamiliar region on the exam

You will be asked about a region or a wine you have not specifically memorized. Do not
panic and search for a fact you don't have. Instead, run the chain forward, in order:

1. **What does the question tell me about location?** Latitude, distance from an ocean,
   nearby mountains, altitude, a named current. Even one of these is enough to start.
2. **What macroclimate type does that imply?** Land-locked and far from water suggests
   continental. Coastal suggests maritime. Warm latitude plus high altitude suggests a
   climate cooler than the latitude alone would predict.
3. **What does that climate type imply about ripening?** Wide diurnal range → sugar
   accumulates while acid is preserved. Narrow range and spread-out rainfall → higher
   vintage variation, rot risk at harvest. Dry autumns → safe extended hang time.
4. **Where does soil modify this?** Free-draining soil in a wet climate reduces rot risk
   and vigour. Water-retentive soil in a dry climate is an asset, not a liability. Heat-
   retaining soil (dark, stony) can push a marginal site over the ripening line.
5. **What grape and style follow logically?** Given the ripening profile, which grapes
   would actually succeed here, and what style: dry, off-dry, high-acid, full-bodied,
   built for ageing: is the climate/soil combination actually capable of producing?

Every step is a "so what": this is the same Golden Thread technique from
`07_training_video/script.md`, just aimed specifically at unfamiliar regions instead of
ones you've already studied.

## Worked example: using a real exam question, cold

**WSET sample paper, Question 3b:** *"The two regions stated below can grow Pinot Noir
successfully. For each region, identify TWO natural factors and explain how they moderate
the climate. Los Carneros / Central Otago."* (12 marks)

Neither region needs to be memorized in advance if you know the chain:

- **Los Carneros** sits at the north end of San Pablo Bay, next to the San Francisco Bay
  system. *Factor: proximity to the bay.* Cold water and the resulting fog moving inland
  cools the area well below what its latitude (relatively warm, Northern California) would
  otherwise suggest. *Factor: exposure to marine wind*, which also has a cooling and
  drying effect, reducing disease pressure. Chain complete: bay proximity → fog and wind →
  cooler mesoclimate than latitude predicts → suitable for a thin-skinned, early-budding,
  cool-climate-loving variety like Pinot Noir.
- **Central Otago** is at high latitude for the Southern Hemisphere (New Zealand's
  southernmost wine region) and at unusually high altitude for a New Zealand vineyard,
  inland rather than coastal. *Factor: altitude.* Cooler overall temperature and a wider
  diurnal range than coastal New Zealand sites. *Factor: continental, inland position* (rare
  for New Zealand): removed from the maritime moderation most NZ regions rely on, giving
  more settled, sunnier summers and a bigger day/night swing. Chain complete: altitude +
  inland position → wide diurnal range → sugar builds in sunny days while acid is
  preserved in cool nights → again suitable for Pinot Noir, by an entirely different
  mechanism than Los Carneros.

Notice: two regions, two completely different mechanisms (maritime cooling vs. altitude
and continentality), arriving at the same climatic outcome: moderate temperature, enough
diurnal range to hold acidity. That contrast **is the point of the question**. A Compare-
shaped answer here would explicitly say so: both regions moderate what would otherwise be
too warm a latitude for Pinot Noir, but they do it by opposite means.

## The label reverse-engineering skill

WSET sample paper, Question 2 shows two real labels: a basic Veneto Pinot Grigio IGT and
an Alsace Grand Cru *Vendange Tardive* Zind-Humbrecht Pinot Gris: and asks you to predict
sweetness, aroma, and quality **before tasting**, from the label alone. This is the same
chain, run against label evidence instead of a region name:

| Label evidence | What it tells you |
|---|---|
| Country/region named on label | Starting climate assumption (see the chain above) |
| Appellation tier (IGT vs Grand Cru, village vs Premier Cru, etc.) | Quality/price ceiling; stricter yield and site rules at higher tiers |
| Vintage/harvest descriptor (Vendange Tardive, Reserva, Late Harvest) | Signals extended hang time or higher ripeness: points toward more body, more sweetness, more concentration |
| Producer name, if you recognize it | Reputation-based quality signal: a secondary check, not a substitute for the above |
| Grape variety + region combination | Whether this is the variety's typical home style or an atypical one |

Applied to the real example: Veneto IGT Pinot Grigio → basic quality tier, cool-to-
moderate Italian climate, high-volume style → expect light body, neutral aroma, dry, early-
drinking, modest quality. Alsace Grand Cru Vendange Tardive Pinot Gris → top quality tier,
cool continental climate with a dry-autumn rain shadow (see `02_regions/france/alsace.md`),
late-harvest descriptor → expect off-dry to sweet, full body, concentrated aroma, high
quality, age-worthy. Every part of that prediction comes from the chain: none of it
requires having tasted either wine.

## Known gap: practical/service knowledge

Not every mark on the exam comes from the climate/soil/style chain. The sample paper also
asks purely practical questions: recommended storage conditions for long-term ageing,
how to open and decant a mature Vintage Port: that test service knowledge, not terroir
reasoning. This framework does not cover that category. It needs its own reference sheet;
flagged here so it isn't mistaken for something this chain already handles.

## Self-check

Before you write a region-specific answer, ask: did I start from climate/altitude, or did
I start from a memorized fact about soil or grape variety? If you started anywhere but the
top of the chain, you are pattern-matching from memory, not reasoning: which is exactly
the Level 2 habit that costs marks at Level 3 (see `07_training_video/script.md`, Segment
2).
