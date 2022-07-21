# 5GIP 1: Genesis Rewards

* Author(s): [Max Gold](https://github.com/maxgold91)
* Start Date: 2022-07-21
* Category: Technical, Economic
* Original HIP PR: 
* Tracking Issue: 

## Summary and Motivation

As the Mobile subDAO transitions from the genesis period to the stub period defined in HIP-53, there is ambiguity as to what will happen to remaining MOBILE from the original 50B premine.  As of now that MOBILE sits in a wallet controlled by Helium Foundation with the plan to emit 100M MOBILE on a pro-rata basis to all radio owners.  This emission schedule and the value placed on each radio is wholly determined by the a centralized body.  The motivation of this 5GIP is to encourage decentralization in the 5G subDAO.

## Stakeholders

All 5G Hotspot owners are affected by this proposal. Specifically, those that purchased and deployed gateways and radio before there were any rewards for doing so.

### Detailed Explanation

This HIP will codify the emission schedule of the 50B MOBILE premine after the genesis period has ended.  The 5G community expects the Helium Foundation to transfer the keys of the wallet holding the premined MOBILE to the Mobile subDAO Operations Fund as soon as one is set up and able to take over the emissions of the premined MOBILE.  The MOBILE subDAO Operations Fund will then continue to emit 100M MOBILE per day solely to radios that pass QoS metrics, are registered with the SAS, and assserted in a whitelisted hex as per the guidelines stated in HIP-53.  It is important to note this is per day using "clocks not blocks" with a catch-up period of 7 days in the event that slow block times.  Assuming MOBILE rewards go live on July 26, 2022 it is proposed that the emissions have 2 "halvening" events, the first coinciding with the first MOBILE havlening on August 1, 2023 and the second occruing on February 1, 2024.  This schedule will exhaust all MOBILE in the premine fund by August 1, 2024. 

| Month |	Start |	Emitted |	End|
| - |	- |	- |	- |
|Jul-22 |	0	|500,000,000	|500,000,000
|Aug-22	|500,000,000	|3,000,000,000|	3,500,000,000|
|Sep-22|	3,500,000,000|	3,000,000,000|	6,500,000,000|
|Oct-22	|6,500,000,000	|3,000,000,000	|9,500,000,000|
|Nov-22	|9,500,000,000	|3,000,000,000	|12,500,000,000|
|Dec-22	|12,500,000,000	|3,000,000,000|	15,500,000,000|
|Jan-23	|15,500,000,000	|3,000,000,000|	18,500,000,000|
|Feb-23	|18,500,000,000	|3,000,000,000|	21,500,000,000|
|Mar-23	|21,500,000,000	|3,000,000,000|	24,500,000,000|
|Apr-23	|24,500,000,000	|3,000,000,000|	27,500,000,000|
|May-23	|27,500,000,000	|3,000,000,000|	30,500,000,000|
|Jun-23	|30,500,000,000	|3,000,000,000|	33,500,000,000|
|Jul-23	|33,500,000,000	|3,000,000,000|	36,500,000,000|
|Aug-23	|36,500,000,000	|1,500,000,000|	38,000,000,000|
|Sep-23	|38,000,000,000	|1,500,000,000|	39,500,000,000|
|Oct-23	|39,500,000,000	|1,500,000,000|	41,000,000,000|
|Nov-23	|41,000,000,000	|1,500,000,000|	42,500,000,000|
|Dec-23	|42,500,000,000	|1,500,000,000|	44,000,000,000|
|Jan-24	|44,000,000,000	|1,500,000,000|	45,500,000,000|
|Feb-24	|45,500,000,000	|750,000,000|	46,250,000,000|
|Mar-24	|46,250,000,000	|750,000,000|	47,000,000,000|
|Apr-24	|47,000,000,000	|750,000,000|	47,750,000,000|
|May-24	|47,750,000,000	|750,000,000|	48,500,000,000|
|Jun-24	|48,500,000,000	|750,000,000|	49,250,000,000|
|Jul-24	|49,250,000,000	|750,000,000|	50,000,000,000|


## Open Questions

* How will voting for this occur before veMOBILE goes live?
* Should the premine emissions continue to be UBI or should they be added to 5G proof of coverage?
* Can a "One MOBILE One Vote" system be put into place temporarily?



