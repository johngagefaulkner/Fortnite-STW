# Fortnite STW • Resources and References

Miscellaneous files all related or pertaining to **Fortnite: Save the World**.

---

## Item Shops

-   **Fortnite/BR/Item Shop:** https://fortnite.simplify.workers.dev/itemshop
-   **Fortnite/BR/Item Shop/Daily Items:** https://fortnite.simplify.workers.dev/itemshop/daily
-   **Fortnite/BR/Item Shop/Featured Items:** https://fortnite.simplify.workers.dev/itemshop/featured

---

## Save the World

### FortniteDB.com

> ![FortniteDB-Logo](https://b2.fortnitedb.com/file/peepoT/logo-small.svg)

- **User Profiles:**
    - [FortniteDB / Profiles / XiL Destruction](https://fortnitedb.com/profile/XiL%20Destruction)

### STW-Planner.com

> ![STWPlanner-Logo](https://stwplanner.azureedge.net/stwp-static/planner-logo.png)

-   **Mission Alerts:** https://stw-planner.com/mission-alerts
-   **DB / Heroes:** https://stw-planner.com/heroes
-   **DB / Schematics / Weapons:** https://stw-planner.com/schematics/weapons
-   **Profiles / Basaku:** https://stw-planner.com/profiles/Basaku
-   **Profiles / XiL Destruction:** https://stw-planner.com/profiles/XiL%20Destruction

---

### Fortnite EGS API URLs

-   **`GET` Save the World Mission Alerts:**
    -   **URL:** https://fngw-mcp-gc-livefn.ol.epicgames.com/fortnite/api/game/v2/world/info
    -   _**Note:**_ Try submitting either query params or headers to ensure I only receive `en-US` content (would dramatically lower file size.)
-   **`POST` Recycle Item(s) from Inventory:**
    -   **URL:** `https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountId}/client/{command}`
    -   [**Source**](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/DestroyWorldItems.md)
-   **`POST` Craft Item from Schematic:** `https://fortnite-public-service-prod11.ol.epicgames.com/fortnite/api/game/v2/profile/{accountId}/client/{command}`

---

### Target MCP Ops for App

-   **Tasks and Actions:**
    -   [**Re-roll Daily Quest**](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/FortRerollDailyQuest.md)
    -   [**Populate Pre-rolled Offers**](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/PopulatePrerolledOffers.md)
    -   [**Purchase or Upgrade Homebase Node**](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/PurchaseOrUpgradeHomebaseNode.md)
    -   [**Purchase Research STAT Upgrade**](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/PurchaseResearchStatUpgrade.md)
    -   [**QueryProfile**](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/QueryProfile.md)
    -   [**QueryPublicProfile**](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/QueryPublicProfile.md)
-   **Friend Codes:**
    -   [**Issue Friend Code**](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/IssueFriendCode.md)
-   **Hero Loadouts:**
    -   [Clear Hero Loadout](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/ClearHeroLoadout.md)
    -   [Assign Gadget to Loadout](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/AssignGadgetToLoadout.md)
    -   [Assign Hero to Loadout](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/AssignHeroToLoadout.md)
    -   [Assign Team Perk to Loadout](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/AssignTeamPerkToLoadout.md)
-   **Survivor Squads:**
    -   [Assign Suvivor to Squad](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/AssignWorkerToSquad.md)
    -   [Assign Survivors to Squads in Bulk](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/AssignWorkerToSquadBatch.md)
-   **Inventory Management:**
    -   [Craft Item from Schematic](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/CraftWorldItem.md)
    -   [Destroy Item from Backpack](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/DestroyWorldItems.md)
        -   _**NOTE:** Calling this function/method will **forcefully destroy** the items you specify and you **will not** receive materials back from the destroyed items. This is the **not** the same endpoint used to recycle items in-game_.
    -   [Recycle Item from Backpack](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/DisassembleWorldItems.md)
    -   [Change Perk on Schematic](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/RespecAlteration.md)
    -   [Set Active Hero Loadout](https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation/blob/9b5817e91f3d598cd14605d6cd7db8d4b4b072d7/Fortnite/MCP/operations/SetActiveHeroLoadout.md)
