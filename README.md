# MX - Slot

-- Version: V3.1.6

Looks like my old guy from guy help to fix this MOD under Engine layer! All reported bug fixed !

V3.1.6: Fixed a related bug which may stuck when pick up heavy item during riding caused by above unofficial update patch. If you still have such issue, `ThePlayer.sg:GoToState("idle")` may help you out.

---

The goal of this MOD is to provide an extra slot ability to the game DS/DST from a more deep phase inside the Klei Engine system. Compared to other similar mods, it(MX_Slot) has a more clean and efficient solution to handle the challenges on the equipment system under the current various and gorgeous mods developing environment. In fact, it supports backpack slot from a new prospect that it keeps `EQUIPSLOTS.BODY` for backpack, whereas creates a new slot for other body related equipments such as Armor, Suit, etc. So that, in this mod, we will have no need to worry about backpack related features anymore;

Currently, version 3.0.1 has been released and can work perfectly with almost all third-party charactor mods and has no doubt will become the most popular and powerful slot-mod in near future; it can achive this mainly thanks to my deep traceback to the Klei's Engine, and modify one of the root system function which existed in both DS/DST; it means the **MX_Slot** can soon finish the last stage and be prepared to be applied in both DS/DST with bug-free experience when cooperated with other charactor mods; But due to the my limited time and energe, I still here to encourage guys who currently using this mod but has issues with third-party mods can contact the author of these `issued mods` to leave comments here to make the **MX_Slot**, in return, I will annouce those mod's legality in MX_Engine and keep supporting those mods with no features left;

### Native features including

- 1.Build from inventory.
- 2.Seed Pack-It (RWYS).
- 3.Keeping backpack opened after resurrection and keep your hat still if drop disabled.
- 4.Items in backpack will automatic add to the Queue.

### Modified features including

- 1. Correct exchange equipments with sewing_man but keep backpack (For Klei's mercy, the team added `SwapEquipment` instead of direct `for loop`).
- 2. Correct stage acting as it should be.
- 3. Correct right click actions behaviors related to `REPAIR.fn`, `COMPARE_WEIGHABLE.fn` and `USE_HEAVY_OBSTACLE.fn`.
- 4. Compat with third-party charactor's Armor, Backpacks and items;
- 5. Completely fixed bugs caused by `ACTIONS.PICKUP.fn` and related hook `inventory.GetEquippedItem`;
- 6. More compat mod added to list;

| Num | Mod Name | Steam Portal |
| --- | --- | --- |
| 001 | Uncompromising | [spoiler][https://steamcommunity.com/sharedfiles/filedetails/?id=2039181790](https://steamcommunity.com/sharedfiles/filedetails/?id=2039181790)[/spoiler] |
| 002 | Legion | [spoiler][https://steamcommunity.com/sharedfiles/filedetails/?id=1392778117](https://steamcommunity.com/sharedfiles/filedetails/?id=1392778117)[/spoiler] |
| 003 | Medal | [spoiler][https://steamcommunity.com/sharedfiles/filedetails/?id=1909182187](https://steamcommunity.com/sharedfiles/filedetails/?id=1909182187)[/spoiler] |
| 004 | Musha | [spoiler][https://steamcommunity.com/sharedfiles/filedetails/?id=439115156](https://steamcommunity.com/sharedfiles/filedetails/?id=439115156)[/spoiler] |
| 005 | ElementReaction | [spoiler][https://steamcommunity.com/sharedfiles/filedetails/?id=2578151314](https://steamcommunity.com/sharedfiles/filedetails/?id=2578151314)[/spoiler] |
| 006 | Architect | [spoiler][https://steamcommunity.com/sharedfiles/filedetails/?id=2428854303](https://steamcommunity.com/sharedfiles/filedetails/?id=2428854303)[/spoiler] |
| 007 | Insight | [spoiler][https://steamcommunity.com/sharedfiles/filedetails/?id=2189004162](https://steamcommunity.com/sharedfiles/filedetails/?id=2189004162)[/spoiler] |
| 008 | 伊蕾娜 | [spoiler][https://steamcommunity.com/sharedfiles/filedetails/?id=2640834455](https://steamcommunity.com/sharedfiles/filedetails/?id=2640834455)[/spoiler] |
| 009 | 小穹 | [spoiler][https://steamcommunity.com/sharedfiles/filedetails/?id=1638724235](https://steamcommunity.com/sharedfiles/filedetails/?id=1638724235)[/spoiler] |
| 010 | 强化护甲 | [spoiler][https://steamcommunity.com/sharedfiles/filedetails/?id=2780209976](https://steamcommunity.com/sharedfiles/filedetails/?id=2780209976)[/spoiler] |

### Updates:

...

14. V3.0.7; Add an extra SG layer for `BACKPACK` slot related equipments; - Dec, 4th, 2022

15. V3.0.8; Add an extra SG layer for `Amulet` slot related equipments; - Dec, 5th, 2022

16. V3.1.1; Enhanced the compatibility when interacted with other mods, now support for `|Uncompromising|`; - Dec, 6th, 2022

17. V3.1.2; Fix running animation compatibility when interacted with `HEAVY` items，specially for @RiCK; - Dec, 6th, 2022

18. V3.1.3.2; Enhanced AnimateState related compatibility, temp fix the none-cave game mod; - Dec, 9th, 2022

19. V3.1.3.4; Fixed `HEAVY` animation toggle and usage related bugs, more compat with all mods on, thx to @defAK36; - Dec, 11st, 2022

20. V3.1.4; Renamed v3.1.3.4, format the code to keep clean and added thanks list; - Dec, 13rd, 2022

21. V3.1.5; Thanks for `Klei` providing hotfix for Engine's bug to make this mod works still on none-cave mod; - Dec, 14th, 2022

22. V3.1.6; Fix a bug due to `Klei`'s unannounced update on Dec, 14th, 2022, it caused PICKUP issue during ridinng; - Dec, 15th, 2022

23. V3.1.7; Fully fixed the `AnimState` cover issues, accidental crash should never happen again; - Dec, 17th, 2022
