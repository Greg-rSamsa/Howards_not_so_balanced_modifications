# Howards Not So Balanced Modifications
## Ascension Perks
Removed:
- Galactic Wonders AP

## Technology
Added:
- Tier 6 research
    - All megastructures added as Tier 6 research.
    - Tier 6 unlocks when an Empire has 2 Tier 5 techs.

Cost and draw weight
> `cost` = `28000`
> `weight` = `15`

Removed:
- Galactic Wonders AP needed for Megastructures

## Defines
**Lowered Galactic Community interaction times all over the board. Roughly lowered by 2,5x and rounded, increased costs.** (Values in days)
*GalCom voting cooldowns*
> `RESOLUTION_VOTE_TIMER` reduced from `1440` to `580`
> `RESOLUTION_VOTE_PREMATURE_TIMER` reduced from `720` to `290`
> `SENATE_RECESS_TIMER` reduced from `720` to `290`
> `CHANGE_VOTE_COOLDOWN` reduced from `120` to `30`

*GalCom resolutions interactions*
> `CATEGORY_VOTE_COOLDOWN` reduced from `2520` to `1010`
> `TYPE_VOTE_COOLDOWN` reduced from `5040` to `2020`
> `VETO_COOLDOWN` reduced from `1800` to `720`
> `EMERGENCY_MEASURES_COOLDOWN` reduced from `7200` to `2880`
> `DEFAULT_VETO_COST_MULT` reduced from `3` to `4`
> `COMMUNITY_FREEZE_RESOLUTION_MONTHS` reduced from `48` to `32`

*GalCom Council and Custodian elections*
> `COUNCIL_ELECTION_TIMER` reduced from `7200` to `4800`
> `CUSTODIAN_TERM_LIMIT_DAYS` reduced from `10800` to `5400`
> `CUSTODIAN_TERM_LIMIT_EXPIRATION_MESSAGE_DAYS` reduced from `1800` to `1250`

**Vassal contract cooldowns are reduced by 2.5x** (Values in months)
> `AGREEMENT_CHANGE_COOLDOWN_MONTHS` reduced from `60` to `24`

**Significantly reduces policy cooldowns**
> `POLICY_YEARS` reduced from `10` to `3`
> `SPECIES_POLICY_YEARS` reduced from `10` to `3`

**Reduced truce time by 2x**
> `TRUCE_YEARS` reduced from `10` to `5`

**Buffed research agreement bonus by 3x**
> `RESEARCH_AGREEMENT_SPEED_MULT` increased from `0.25` to `0.75`

**Increases likeness of AI to surrender with fleet power**
> `PEACE_DEFENDING_CLAIM_PLANET_FACTOR` increased from `-100` to `-80`
> `PEACE_RELATIVE_NAVY_STRENGTH_FACTOR` increased from `50` to `75`


**Disabled Dyson Gun for AI**

They spam the shit out of it and makes a horrible noise, it's not even that good