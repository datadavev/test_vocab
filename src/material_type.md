---
comment: | 
  WARNING: This file is generated. Any edits will be lost!
title: "iSamples Materials Vocabulary"
date: "2024-01-03T12:54:23.336880+00:00"
subtitle: |
  High level vocabulary to specify the kind of material that constitutes a physical sample
execute:
  echo: false
---

Vocabularies and extensions: 

- `iSamples Materials Vocabulary ` [`https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`](https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary)

**History:**

2022-01-05 SMR version 0.9, change base uri to https://w3id.org/isample/vocabulary/material/0.9/ for testing with ESIP COR and w3id uri resolution <br /> 2022-03-11 SMR change definitions from rdfs:comment to skos:definition. Minor fixes to some definitions.  Add skos matches to URIs from other vocabularies; 2023-11-05 version 1.0, in preparation for release. 


**Concept Hierarchy:**

  - [Material](#material)
    - [Any anthropogenic material](#any-anthropogenic-material)
      - [Anthropogenic metal material](#anthropogenic-metal-material)
      - [Anthropogenic material](#anthropogenic-material)
    - [Any ice](#any-ice)
      - [Frozen water](#frozen-water)
    - [Biogenic non-organic material](#biogenic-non-organic-material)
    - [Dispersed media](#dispersed-media)
    - [Natural Solid Material](#natural-solid-material)
      - [Mineral](#mineral)
      - [Mixed soil sediment or rock](#mixed-soil-sediment-or-rock)
      - [Particulate](#particulate)
      - [Rock or sediment](#rock-or-sediment)
        - [Rock](#rock)
        - [Sediment](#sediment)
      - [Soil](#soil)
    - [Fluid material](#fluid-material)
      - [Gaseous material](#gaseous-material)
      - [Liquid water](#liquid-water)
      - [Non-aqueous liquid material](#non-aqueous-liquid-material)
    - [Organic material](#organic-material)


## Material
[]{#material}

The concept `Material` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/material` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

This is the top concept of the vocabulary.


Immediately narrower concepts:

[`Any anthropogenic material`](#any-anthropogenic-material), [`Any ice`](#any-ice), [`Biogenic non-organic material`](#biogenic-non-organic-material), [`Dispersed media`](#dispersed-media), [`Natural Solid Material`](#natural-solid-material), [`Fluid material`](#fluid-material), [`Organic material`](#organic-material)

**Definition:**

Top Concept in iSamples Material Category scheme


## Any anthropogenic material
[]{#any-anthropogenic-material}

The concept `Any anthropogenic material` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/anyanthropogenicmaterial` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Any anthropogenic material`](#any-anthropogenic-material)


Immediately narrower concepts:

[`Anthropogenic metal material`](#anthropogenic-metal-material), [`Anthropogenic material`](#anthropogenic-material)

**Definition:**

Material produced by human activity.


## Anthropogenic metal material
[]{#anthropogenic-metal-material}

The concept `Anthropogenic metal material` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/anthropogenicmetal` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Any anthropogenic material`](#any-anthropogenic-material)` -> `[`Anthropogenic metal material`](#anthropogenic-metal-material)



**Definition:**

Specimen is dominantly composed of metal that has been produced or used by humans; subclass of anthropogenic material. Samples of naturally occuring metallic material (e.g. native copper, gold nuggets) should be considered mineral material. Metallic material is material that when polished or fractured, shows a lustrous appearance, and conducts electricity and heat relatively well. Metals are typically malleable (they can be hammered into thin sheets) or ductile (can be drawn into wires). The boundaries between metals, nonmetals, and metalloids fluctuate slightly due to a lack of universally accepted definitions of the categories involved. (https://en.wikipedia.org/wiki/Metal). c.f. http://purl.obolibrary.org/obo/ENVO_01001069


## Anthropogenic material
[]{#anthropogenic-material}

The concept `Anthropogenic material` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/otheranthropogenicmaterial` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Any anthropogenic material`](#any-anthropogenic-material)` -> `[`Anthropogenic material`](#anthropogenic-material)



**Definition:**

Non-metallic material produced by human activity. Organic products of agricultural activity are both anthropogenic and organic. Include lab preparations like XRF pellet and rock powders. Examples: ceramics, concrete, slag, (anthropogenic) glass, mine tailing, plaster, waste.


## Any ice
[]{#any-ice}

The concept `Any ice` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/anyice` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Any ice`](#any-ice)


Immediately narrower concepts:

[`Frozen water`](#frozen-water)

**Definition:**

a solid material that is normally a liquid or gas at Standard Temperature and Pressre (STP) that is in a solid state under the observed temperature and pressure conditions.


## Frozen water
[]{#frozen-water}

The concept `Frozen water` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/waterice` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Any ice`](#any-ice)` -> `[`Frozen water`](#frozen-water)



**Definition:**

Water that is in a solid state.

**Alternate labels:**

`Water ice`


## Biogenic non-organic material
[]{#biogenic-non-organic-material}

The concept `Biogenic non-organic material` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/biogenicnonorganicmaterial` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Biogenic non-organic material`](#biogenic-non-organic-material)



**Definition:**

Material produced by an organism but not composed of 'very large molecules of biological origin.' E.g. bone, tooth, shell, coral skeleton,


## Dispersed media
[]{#dispersed-media}

The concept `Dispersed media` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/dispersedmedia` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Dispersed media`](#dispersed-media)



**Definition:**

A material contains discrete elements of one medium that are dispersed in a continuous fluid medium.  The dispersed component can be a gas, a liquid or a solid (based on https://en.wikipedia.org/wiki/Dispersed_media). Does not include mixtures of granular material like soil, sediment, particulate, or solids that would be considered a rock.


## Natural Solid Material
[]{#natural-solid-material}

The concept `Natural Solid Material` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/earthmaterial` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Natural Solid Material`](#natural-solid-material)


Immediately narrower concepts:

[`Mineral`](#mineral), [`Mixed soil sediment or rock`](#mixed-soil-sediment-or-rock), [`Particulate`](#particulate), [`Rock or sediment`](#rock-or-sediment), [`Soil`](#soil)

**Definition:**

Undifferentiated soil, sediment, rock, or natural particulates. Typically (nessarily?) a granular aggregate that might include any of the previous constiturents. Use for Earth Material aggregates of uncertain origin


## Mineral
[]{#mineral}

The concept `Mineral` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/mineral` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Natural Solid Material`](#natural-solid-material)` -> `[`Mineral`](#mineral)



**Definition:**

Material consists of a single mineral or mineraloid phase. .  'A mineral is an element or chemical compound that is normally crystalline and that has been formed as a result of geological processes.' (Nickel, Ernest H. (1995), The definition of a mineral, The Canadian Mineralogist. 33 (3): 689–90). Include mineraloids. ... A material primarily composed of some substance that is naturally occurring, solid and stable at room temperature, representable by a chemical formula, usually abiogenic, and that has an ordered atomic structure. (http://purl.obolibrary.org/obo/ENVO_01000256). Comment: the identity of a mineral species is defined by a crystal structure and a chemical composition that might include various specific elemental substitutions in that structure. Mineraloid: A naturally occurring mineral-like substance that does not demonstrate crystallinity. Mineraloids possess chemical compositions that vary beyond the generally accepted ranges for specific minerals. Examples: obsidian, Opal. (https://en.wikipedia.org/wiki/Mineraloid)


## Mixed soil sediment or rock
[]{#mixed-soil-sediment-or-rock}

The concept `Mixed soil sediment or rock` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/mixedsoilsedimentrock` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Natural Solid Material`](#natural-solid-material)` -> `[`Mixed soil sediment or rock`](#mixed-soil-sediment-or-rock)



**Definition:**

Material is mixed aggregation of fragments of undifferentiated soil, sediment or rock origin. e.g. cuttings from some boreholes (rock fragments and caved soil or sediment).


## Particulate
[]{#particulate}

The concept `Particulate` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/particulate` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Natural Solid Material`](#natural-solid-material)` -> `[`Particulate`](#particulate)



**Definition:**

Material consists of microscopic particulate material derived by precipitation, filtering, or settling from suspension in a fluid, e.g. filtrate from water, deposition from atmosphere, astro material particles. Might include mineral, organic, or biological material. ENVO definition (ENVO_01000060) has "composed of microscopic portions of solid or liquid material suspended in another environmental material.", refine here to define as the solid particles, distinct from a material in which they are suspended. A material that includes solid or liquid particles suspended in another material would be a dispersed_media in this scheme, not defined in ENVO. Human manufactured particulates (e.g. rock powder) should be categorized as 'anthropogenic material' as well as 'Particulate'


## Rock or sediment
[]{#rock-or-sediment}

The concept `Rock or sediment` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/rockorsediment` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Natural Solid Material`](#natural-solid-material)` -> `[`Rock or sediment`](#rock-or-sediment)


Immediately narrower concepts:

[`Rock`](#rock), [`Sediment`](#sediment)

**Definition:**

Material is rock or sediment.  E.g. for samples from subsurface cores that are not well described, from drill holes that likely penetrate sediment near the surface an might be sampling rock at greater depth.

**Notes:**

Use for sample like dredge hauls and ROV scoops that mix rock and sediment from a water body bottom.

Use for samples described as rock>sedimentary AND sediment, where it is unclear whether the sample is a consolidated 'rock' object, or loose disaggregated material in a bag.


## Rock
[]{#rock}

The concept `Rock` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/rock` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Natural Solid Material`](#natural-solid-material)` -> `[`Rock or sediment`](#rock-or-sediment)` -> `[`Rock`](#rock)



**Definition:**

Consolidated aggregate of particles (grains) of rock, mineral (including native elements), mineraloid, or solid organic material. Includes mineral aggregates such as granite, shale, marble; natural glass such as obsidian; organic material formed by geologic processes such a coal;  extraterrestrial material in meteorites; and  crushed rock fragments like drill cuttings from rock.  (based on http://resource.geosciml.org/classifier/cgi/lithology/rock, same as http://purl.obolibrary.org/obo/ENVO_00001995)


## Sediment
[]{#sediment}

The concept `Sediment` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/sediment` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Natural Solid Material`](#natural-solid-material)` -> `[`Rock or sediment`](#rock-or-sediment)` -> `[`Sediment`](#sediment)



**Definition:**

Solid granular material transported by wind, water, or gravity, not modified by interaction with biosphere or atmosphere (to differentiate from soil). Particles derived by erosion of pre-existing rock, from shell or other body parts from organisms, precipitated chemically in the surficial environment, or generated by explosive volcanic activity. (http://resource.geosciml.org/classifier/cgi/lithology/sediment). Sediment is not consolidated, i.e. Particulate constituents of a compound material do not adhere to each other strongly enough that the aggregate can be considered a solid material in its own right. Similar to http://purl.obolibrary.org/obo/ENVO_00002007

**Notes:**

Note that this category includes chemical sediments that might preciptate to form a solid mass, e.g. preciptitates forming vents at submarine hot springs, or gypsum and halite deposites formed by evaporation in hypersaline lakes. (http://resource.geosciml.org/classifier/cgi/consolidationdegree/consolidated).

Tephra is subclass of sediment because it is generally not lithified, in which case it would be considered Rock.


## Soil
[]{#soil}

The concept `Soil` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/soil` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Natural Solid Material`](#natural-solid-material)` -> `[`Soil`](#soil)



**Definition:**

Mixed granular mineral and organic matter modified by interaction between earth material, biosphere, and atmosphere, consisting mostly of varying proportions of sand, silt, and clay, organic material such as humus, gases, liquids, and a broad range of resident micro- and macroorganisms. (https://en.wikipedia.org/wiki/Soil) Soil consists of horizons near the Earth's surface that, in contrast to the underlying parent material, have been altered by the interactions of climate, relief, and living organisms over time. (http://www.nrcs.usda.gov/wps/portal/nrcs/detail/soils/edu/?cid=nrcs142p2_054280) (http://purl.obolibrary.org/obo/ENVO_00001998)


## Fluid material
[]{#fluid-material}

The concept `Fluid material` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/fluid` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Fluid material`](#fluid-material)


Immediately narrower concepts:

[`Gaseous material`](#gaseous-material), [`Liquid water`](#liquid-water), [`Non-aqueous liquid material`](#non-aqueous-liquid-material)

**Definition:**

a substance that continually deforms (flows) under an applied shear stress, or external force. Fluids are a phase of matter and include liquids, gases and plasmas. They are substances with zero shear modulus, or, in simpler terms, substances that cannot resist any shear force applied to them. (https://en.wikipedia.org/wiki/Fluid)


## Gaseous material
[]{#gaseous-material}

The concept `Gaseous material` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/gas` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Fluid material`](#fluid-material)` -> `[`Gaseous material`](#gaseous-material)



**Definition:**

Material composed of one or more chemical entities that has neither independent shape nor volume but tends to expand indefinitely (http://purl.obolibrary.org/obo/ENVO_01000797). Infer that the sample is curated in some kind of container.


## Liquid water
[]{#liquid-water}

The concept `Liquid water` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/liquidwater` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Fluid material`](#fluid-material)` -> `[`Liquid water`](#liquid-water)



**Definition:**

A material primarily composed of dihydrogen oxide in its liquid form; infer that the sample is curated in some kind of container.


## Non-aqueous liquid material
[]{#non-aqueous-liquid-material}

The concept `Non-aqueous liquid material` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/nonaqueousliquid` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Fluid material`](#fluid-material)` -> `[`Non-aqueous liquid material`](#non-aqueous-liquid-material)



**Definition:**

Liquid composed dominantly of material other than water. Includes liquids that do not fit in any other category. E.g. alcohol, petroleum.


## Organic material
[]{#organic-material}

The concept `Organic material` <br/> 
with URI `https://w3id.org/isample/vocabulary/material/1.0/organicmaterial` <br/> 
is defined in vocabulary `https://w3id.org/isample/vocabulary/material/1.0/materialsvocabulary`

Path from the top concept: <br/>
[`Material`](#material)` -> `[`Organic material`](#organic-material)



**Definition:**

Environmental material derived from living organisms and composed primarily of one or more very large molecules of biological origin. Examples: body (animal or plant), body part, fecal matter, seeds, wood, tissue, biological fluids, biological waste, algal material, biofilm, necromass, plankton. source: http://purl.obolibrary.org/obo/ENVO_01000155


