---
{"dg-home":true,"dg-publish":true,"permalink":"/star-berry/analytics/ab-test-notes/firebase-ab-tests/","tags":"gardenEntry","dgPassFrontmatter":true}
---



```toc 
style: number min_depth: 1 max_depth: 6 
```


# Firebase AB tests


## List  

1. [Piggy Bank](#^afcd65)
2. [Added Inventory Slots](#^f5a60d)
3. [Generous + Energy refill](#^02ca38)
4. [Fast Refill PiggyBank](#^a304c2)
5. [Early Unlock Chilli Party](#^b5c488)
6. [Starter Pack Pricing](#^c03865)
7. [New Shop look](#^3b20ac)
8. [New Offer popup](#^5f5458)
9. [Daily Offer Refresh](#^2b3fd1)
10. [Weekly Deal Price Segmentation](#^2d92d6)
11. [Rewarded Video](#^d6b16a)







## Details

### <mark style="background: #BBFABBA6;">Piggy Bank</mark>    🆗  ▶️ 

^afcd65


| Name                                           | userProperty.key | Firabase AB Name | Start Time  | End Time |
| ---------------------------------------------- | ---------------- | ---------------- | ----------- | -------- |
| AppTurbine Initiative 3 - Event Unlock Android | firebase_exp_52  | abtest_52        | [12-Aug-2022](12-Aug-2022)          | -         |
| AppTurbine Initiative 3 - Event Unlock iOS     | firebase_exp_58  | abtest_58        | [12-Aug-2022](12-Aug-2022)            |  -        |

| Primary Goal     | Secondary Goals      |
| ---------------- | -------------------- |
| Purchase revenue | Retention (4–7 days) |
|                  | Retention (15+ days) |
|                  | Retention (2–3 days) |
|                  | piggybankopen        |
|                  | piggybankview        |

Variants:
1. ==Baseline==
2. ==Variant F==
3. ==Variant G==

Notes: 



### <mark style="background: #BBFABBA6;">Added Inventory Slots</mark>   🆗  ▶️ 

| Name                                                | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| --------------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| ## AppTurbine Initiative 2- Inventory Slots Android | firebase_exp_53  | abtest_53        | [05-Aug-2022](05-Aug-2022) | -        |  [08-Aug-2022](08-Aug-2022)       |
| ## AppTurbine Initiative 2- Inventory Slots iOS     | firebase_exp_57  | abtest_57        | [05-Aug-2022](05-Aug-2022) | -        |   [08-Aug-2022](08-Aug-2022)      |

| Primary Goal     | Secondary Goals      |
| ---------------- | -------------------- |
| Purchase revenue | Retention (4–7 days) |
|                  | Retention (15+ days) |
|                  | Retention (1 days) |
|                  | adview        |
|                  | buildingupgradepurchased |

Variants:
1. ==Baseline==
2. ==Added Inventory Slots= ^f5a60d

Notes: 

---
### <mark style="background: #FF5582A6;">Generous + Energy Refill </mark> 🚫 

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| AppTurbine Initiative 2- Econ Tests Android | firebase_exp_51  | abtest_51        | [05-Aug-2022](12-Aug-2022) | -        |     [08-Aug-2022](08-Aug-2022)   |
| AppTurbine Initiative 2- Econ Tests iOS     | firebase_exp_55  | abtest_55        | [05-Aug-2022](05-Aug-2022) | -        |    [08-Aug-2022](08-Aug-2022)     |

| Primary Goal     | Secondary Goals      |
| ---------------- | -------------------- |
| Purchase revenue | Retention (4–7 days) |
|                  | Retention (15+ days) |
|                  | Retention (1 days) |
|                  | adview        |

Variants:
1. ==Baseline==
2. ==Stingy Generators==
3. ==Generous Generators==
4. ==Generous + Energy Refill== ^02ca38

Notes: 


---

### <mark class="hltr-green">Fast refill PiggyBank</mark>  🆗  ▶️ 


| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| AppTurbine Initiative 3 - Fast PiggyBank Android | firebase_exp_63  | abtest_63        | [23-Aug-2022](23-Aug-2022) | -        |       |
| AppTurbine Initiative 3 - Fast PiggyBank iOS     | firebase_exp_64  | abtest_64        | [23-Aug-2022](23-Aug-2022) | -        |    |

| Primary Goal     | Secondary Goals      |
| ---------------- | -------------------- |
| Purchase revenue | Retention (4–7 days) |
|                  | Retention (15+ days) |
|                  | adview               |
|                  | piggybankview        |
|                  | piggybankopen                     |

Variants:
1. ==Baseline==
2. ==Fast Refill PiggyBank== ^a304c2

Notes: 
1. $ [03-Nov-2022](03-Nov-2022.md) We saw a statistically significant result in the total revenue. We can roll out the variant for all users.
2. 


---
 
### <mark style="background: #FF5582A6;">Early unlock ChilliParty</mark> 🚫 

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| AppTurbine Initiative 3 - Fast PiggyBank Android | firebase_exp_61  | abtest_61        | [23-Aug-2022](23-Aug-2022) | -        |       |
| AppTurbine Initiative 3 - Event Unlock iOS     | firebase_exp_62  | abtest_62        | [23-Aug-2022](23-Aug-2022) | -        |    |

| Primary Goal     | Secondary Goals      |
| ---------------- | -------------------- |
| Purchase revenue | Retention (4–7 days) |
|                  | Retention (15+ days) |
|                  | Retention (1 days)              |
|                  | adview        |
|                  | eventengagement                     |

Variants:
1. ==Baseline==
2. ==Early Unlock ChilliParty== ^b5c488

Notes: 

---
### <mark style="background: #FF5582A6;">AT3 - Rewarded Video</mark> 🚫 
^d6b16a

We are testing baseline against a version with weekly deal segmented by player highest IAP purchase

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| AppTurbine Initiative 3 - RV Android | firebase_exp_60  | abtest_60        |[22-Aug-2022](22-Aug-2022) | [11-Oct-2022](11-Oct-2022)        |     |
| AppTurbine Initiative 3 - RV iOS     | firebase_exp_59  | abtest_59        | [22-Aug-2022](22-Oct-2022) | [11-Oct-2022](11-Oct-2022)        |  |

| Primary Goal     | Secondary Goals      |
| ---------------- | -------------------- |
| Purchase revenue | Retention (4–7 days) |
|                  | Retention (1 days)   |
|                  | Retention (15+ days) |
|                  | adview               |
|                  | af_adviewcompleted                     |

Variants:
1. ==Baseline==
2. ==Chest 10==
3. ==Chest 20==

Notes: 

We do not have new users after [11-Oct-2022](11-Oct-2022.md) . We can check the results with existent users.
___
 ----
### <mark style="background: #BBFABBA6;">AT4 - Starter Pack Pricing</mark>  🆗  ▶️ 

| Name                                                | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| --------------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| AppTurbine Initiative 2- Inventory Slots Android | firebase_exp_53  | abtest_53        | [05-Aug-2022](05-Aug-2022) | -        |  [08-Aug-2022](08-Aug-2022)       |
| AppTurbine Initiative 2- Inventory Slots iOS     | firebase_exp_57  | abtest_57        | [05-Aug-2022](05-Aug-2022) | -        |   [08-Aug-2022](08-Aug-2022)      |

| Primary Goal     | Secondary Goals      |
| ---------------- | -------------------- |
| Purchase revenue | Retention (4–7 days) |
|                  | Retention (15+ days) |
|                  | Retention (1 days) |
|                  | adview        |
|                  | buildingupgradepurchased |

Variants:
1. ==Baseline==
2. ==Added Inventory Slots= ^f5a60d

Notes: 

---

^c03865

Testing different price point for the starter offer (mayor deal)

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| AT4 - Starter Pack Pricing (Android) | firebase_exp_73  | abtest_73        | [31-Aug-2022](31-Aug-2022) | -        |  [15-Sep-2022](15-Sep-2022)     |
| AT4 - Starter Pack Pricing (iOS)     | firebase_exp_66 | abtest_66        | [31-Aug-2022](31-Aug-2022) | -        |   [15-Sep-2022](15-Sep-2022) |

| Primary Goal     | Secondary Goals      |
| ---------------- | -------------------- |
| Purchase revenue | Retention (4–7 days) |
|                  | Retention (2-3 days) |
|                  | Retention (1 days)            |

Variants:
1. ==Baseline==
2. ==starter at 1.99 (new look)==
3. ==starter at 2.99==
4. ==starter at 4.99==
5. ==1.99 low devices, 4.99 high==
6. ==starter at 6.99==

Notes: 

---
### AT4 - New Shop (Store) Look
^3b20ac

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| AT4 - New Shop Look (Android) | firebase_exp_71  | abtest_71        | [15-Sep-2022](15-Sep-2022) | -        |       |
| AT4 - New Shop Look (iOS)     | firebase_exp_69  | abtest_69        | [15-Sep-2022](15-Sep-2022) | -        |    |

| Primary Goal     | Secondary Goals      |
| ---------------- | -------------------- |
| Purchase revenue | Retention (4–7 days) |
|                  | Retention (1 days) |
|                  | Retention (2-3 days               |
|                  | Crash-free users        |

Variants:
1. ==Baseline==
2. ==New Store Look== ^188f23

Notes: 

---
### AT4 - New Offer PopUp
^5f5458

We are testing the new offer popup layout (trifold and single) against the old design

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| AT4 - New Offer Popup (Android) | firebase_exp_74  | abtest_74        |[15-Sep-2022](15-Sep-2022) | -        |       |
| AT4 - New Offer Popup (iOS)     | firebase_exp_65  | abtest_65        | [15-Sep-2022](15-Sep-2022) | -        |    |

| Primary Goal     | Secondary Goals      |
| ---------------- | -------------------- |
| Purchase revenue | Retention (4–7 days) |
|                  | Retention (1 days) |
|                  | Retention (2-3 days)               |
|                  | Retention (8-14 days)        |
|                  | Retention (15+ days)                     |

Variants:
1. ==Baseline==
2. ==Variant A (New offer Popup)==

Notes: 

---
### <mark class="hltr-green">AT4 - Daily offer refresh</mark>  🆗  ▶️ 
^2b3fd1

Refresh the offers watching an Ad or with gems

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| AT4 - Daily offer refresh (Android)| firebase_exp_70  | abtest_70        |[15-Sep-2022](15-Sep-2022) |  [21-Nov-2022](21-Nov-2022)      |       |
| AT4 - Daily offer refresh (iOS)    | firebase_exp_68  | abtest_68        | [15-Sep-2022](15-Sep-2022) | [21-Nov-2022](21-Nov-2022)        |    |

| Primary Goal     | Secondary Goals      |
| ---------------- | -------------------- |
| Purchase revenue | Retention (4–7 days) |
|                  | Retention (1 days) |
|                  | Retention (2-3 days)               |
|                  | Crash-free users        |


Variants:
1. ==Baseline==
2. ==Refresh with RV and Gems==

Notes: 
1. We decided roll out the AT4-Daily Offer Refresh A/B test after the result of 18/11/2022 week. We can find the result here :
	1. https://docs.google.com/presentation/d/1U0Aw0l8oXlOHwp2NJmKd5awPdsam14LWkgM-Z3jBAew/edit?usp=sharing


![](assets/Firebase%20AB%20Tests/image-20221121180243604.png)


---
### <mark class="hltr-red">AT4 - Weekly deal price segmentation</mark> 🚫 
^2d92d6

We are testing baseline against a version with weekly deal segmented by player highest IAP purchase

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| AT4 - Weekly deal price segmentation (Android)| firebase_exp_72  | abtest_72        |[15-Sep-2022](15-Sep-2022) | -        | [19-Sep-2022](19-Sep-2022)      |
| AT4 - Weekly deal price segmentation (iOS)     | firebase_exp_67  | abtest_67        | [15-Sep-2022](15-Sep-2022) | -        |[19-Sep-2022](19-Sep-2022)    |

| Primary Goal     | Secondary Goals      |
| ---------------- | -------------------- |
| Purchase revenue | Retention (4–7 days) |
|                  | Retention (1 days) |
|                  | Retention (2-3 days)               |
|                  | Crash-free users        |

Variants:
1. ==Baseline==
2. ==Weekly offer segmented==

Notes: 

---

---
---

----
### SB1 - Daily City Reward - 21/10/2022


New city reward, watch RV for getting a bonus box

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| SB1 - Daily City Reward (andr)| firebase_exp_85  | abtest_85        |[21-Oct-2022](21-Oct-2022) | -        |       |
| SB1 - Daily City Reward (iOS)  | firebase_exp_77  | abtest_77        | [21-Oct-2022](21-Oct-2022) | -        |    |

| Primary Goal     | Secondary Goals       |
| ---------------- | --------------------- |
| Purchase revenue | Retention (1 days)    |
|                  | Retention (2-3 days)  |
|                  | Retention (4-7 days)  |
|                  | Retention (8-14 days) |
|                  | Retention (15+ days)                      |


Variants:
1. ==Baseline==
2. ==daily generous==
3. ==daily generous with confirm==

Notes: 
### SB1 - Offer PopUp  - 21/10/2022

Different individual and global cooldown for the auto offer popup

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| SB1 - Offer Popup (andr)| firebase_exp_86  | abtest_86        |[21-Oct-2022](21-Oct-2022) | -        |       |
| SB1 - Offer Popup (iOS)  | firebase_exp_75  | abtest_75        | [21-Oct-2022](21-Oct-2022) | -        |    |

| Primary Goal     | Secondary Goals       |
| ---------------- | --------------------- |
| Purchase revenue | Retention (4–7 days)  |
|                  | Retention (8-14 days) |
|                  | Crash free users      |
|                  | Estimated total revenue  |


Variants:
1. ==Baseline==
2. ==24h individual, 3h global==
3. ==8h individual, 1h global==

Notes: 


---
### <mark class="hltr-red">SB1 - Daily Energy Box RV</mark> 🚫 

Additionally to the free daily energy.

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| SB1 - Daily Energy Box RV (Andr)| firebase_exp_83  | abtest_83        |[13-Oct-2022](13-Oct-2022) | -        |       |
| SB1 - Daily Energy Box RV (iOS)    | firebase_exp_80  | abtest_80        | [13-Oct-2022](13-Oct-2022) | -        |    |

| Primary Goal     | Secondary Goals       |
| ---------------- | --------------------- |
| Purchase revenue | Retention (4–7 days)  |
|                  | Retention (1 days)    |
|                  | Retention (8-14 days) |
|                  | Crash-free users      |
|                  | Estimated ad revenue                      |

Variants:
1. ==Baseline==
2. ==Energy Box RV==

Notes: 

### SB1 - Label on Bubbles  - 20/10/2022

Bubbles will have a label with gems and ads

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| SB1 - Labels on Bubbles (Andr) | firebase_exp_87  | abtest_87        |[20-Oct-2022](20-Oct-2022) | -        |       |
| SB1 - Labels on Bubbles (iOS)    | firebase_exp_79  | abtest_79        | [20-Oct-2022](20-Oct-2022) | -        |    |

| Primary Goal     | Secondary Goals       |
| ---------------- | --------------------- |
| Purchase revenue | Retention (4–7 days)  |
|                  | Retention (1 days)    |
|                  | Retention (15+ days) |
|                  | Crash-free users      |
|                  | Retention (2-3 days)  |

Variants:
1. ==Baseline==
2. ==gem/ad label on bubble==

Notes: 

### SB1 - Bubble Spawn Rates and RV Gem Configs - 20/10/2022


Test against;
1. Higher spawn chances of mid- to high tier bubbles, 2
2. Higher gem value threshold to poke bubbles via RV

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| SB1 - Bubble Spawn Rates and RV Gem Configs (Andr)| firebase_exp_78  | abtest_78        |[20-Oct-2022](20-Oct-2022) | -        |       |
| SB1 - Bubble Spawn Rates and RV Gem Configs (iOS)   | firebase_exp_76  | abtest_76        | [20-Oct-2022](20-Oct-2022) | -        |    |

| Primary Goal     | Secondary Goals       |
| ---------------- | --------------------- |
| Purchase revenue | Retention (4–7 days)  |
|                  | Retention (1 days)    |
|                  | Crash free users |


Variants:
1. ==Baseline==
2. ==Higher Spawn Rates==
3. ==Higher Gem Value for RV==

Notes: 

### <mark class="hltr-red">SB1 - Golden Bubble  - 20/10/2022</mark>  🚫 

Golden bubble for high value RV or gems (All Users)

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| SB1 - Golden Bubble (andr) | firebase_exp_88  | abtest_88        |[20-Oct-2022](20-Oct-2022) | -        |       |
| SB1 - Golden Bubble (iOS)   | firebase_exp_84  | abtest_84        | [20-Oct-2022](20-Oct-2022) | -        |    |

| Primary Goal     | Secondary Goals       |
| ---------------- | --------------------- |
| Purchase revenue | Retention (4–7 days)  |
|                  | Retention (1 days)    |
|                  | Retention (8-14 days) |
|                  | Estimated ad revenue    |
|                  |  Estimated total revenue |

Variants:
1. ==Baseline==
2. ==RV and Gems==
3. ==Only RV==

Notes: 

---
---

----

---
### SB2 - More expensive energy - 02/11/2022  

Energy refill costs 1.5 time more

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| SB2 - More expensive energy (andr) | firebase_exp_94  | abtest_94        |[02-Nov-2022](02-Nov-2022) | -        |       |
| SB2 - More expensive energy (iOS)   | firebase_exp_93  | abtest_93        | [02-Nov-2022](02-Nov-2022) | -        |    |

| Primary Goal     | Secondary Goals       |
| ---------------- | --------------------- |
| Purchase revenue | Retention (4–7 days)  |
|                  | Retention (1 days)    |
|                  | Retention (15+ days) |
|                  | Adview    |


Variants:
1. ==Baseline==
2. ==Energy Refill 1.5x==


Notes: 

___

---

---
### SB3 - Golden Bubble v2 - 29/11/2022  

Golden bubble for high value RV or gems Version 2

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| SB3 - Golden Bubble v2 (droid)              | firebase_exp_98  | abtest_98        |[29-Nov-2022](29-Nov-2022)  | -            |          |
| SB3 - Golden Bubble v2 (iOS)                | firebase_exp_97  | abtest_97        | [29-Nov-2022](29-Nov-2022) | -            |          |

| Primary Goal     | Secondary Goals       |
| ---------------- | --------------------- |
| Purchase revenue | Retention (4–7 days)  |
|                  | Retention (1 days)    |
|                  | Retention (8-14 days) |
|                  | Estimated ad revenue  |
|                  | Estimated total revenue                    |


Variants:
1. ==Baseline==
2. ==Only Gems==
3. ==Only RV==


Notes: 

### SB3 - New Core Generator - 29/11/2022  

new balance for all core generators

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| SB3 - New Core Generator (droid)                            | firebase_exp_96  | abtest_96        |[29-Nov-2022](29-Nov-2022) | -        |       |
| SB3 - New Core Generator (iOS)   | firebase_exp_95  | abtest_95        | [29-Nov-2022](29-Nov-2022) | -        |    |

| Primary Goal     | Secondary Goals       |
| ---------------- | --------------------- |
| Estimated total revenue| Retention (4–7 days)  |
|                  | Retention (1 days)    |
|                  | Purchase revenue   |


Variants:
1. ==Baseline==
2. ==new generator balance==


Notes: 

---


### SB - Jelly No Vendor December 15 - 06/12/2022  

Variant will run without a Jelly Bowl Vendor.

| Name                                        | userProperty.key | Firabase AB Name | Start Time                 | End Time | Update |
| ------------------------------------------- | ---------------- | ---------------- | -------------------------- | -------- | ------ |
| SB - Jelly No Vendor December 15th (andr)   | firebase_exp_92  | abtest_92        |[06-Dec-2022](06-Dec-2022) | -        |       |
| SB - Jelly No Vendor December 15th (iOS)   | firebase_exp_91  | abtest_91        | [06-Dec-2022](06-Dec-2022) | -        |    |

| Primary Goal     | Secondary Goals       |
| ---------------- | --------------------- |
| Purchase revenue | Retention (4–7 days)  |
|                  | Retention (1 days)    |
|                  | Crash-free users   |


Variants:
1. ==Baseline==
2. ==No Vendor==


Notes: 