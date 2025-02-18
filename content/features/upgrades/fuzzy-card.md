---
categories:
  - Upgrades
item_ids:
  - appliedenergistics2:fuzzy_card
title: Fuzzy Card
---

Used to add fuzzy behavior to <ItemLink
id="appliedenergistics2:item_formation_plane"/>, <ItemLink
id="appliedenergistics2:item_export_bus"/>, <ItemLink
id="appliedenergistics2:item_import_bus"/>, <ItemLink
id="appliedenergistics2:item_level_emitter"/>, <ItemLink
id="appliedenergistics2:item_storage_bus"/>, <ItemLink
id="appliedenergistics2:view_cell"/> and <ItemLink
id="appliedenergistics2:1k_item_storage_cell"/> as well as other non
spatial [storage cells](../me-network/storage-cells.md).

### Fuzzy Comparison Details

Below is an example of how Fuzzy Damage comparison mods work, left side is the
bus config, top is the compared item.

| 25%                     | 10% Damaged Pick | 30% Damaged Pick | 80% Damaged Pick | Full Repair Pick |
| ----------------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| Nearly Broken Pick Axe  | ✅               | \*\*\*\*         | \*\*\*\*         | \*\*\*\*         |
| Fully Repaired Pick Axe | \*\*\*\*         | ✅               | ✅               | ✅               |

| 50%                     | 10% Damaged Pick | 30% Damaged Pick | 80% Damaged Pick | Full Repair Pick |
| ----------------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| Nearly Broken Pick Axe  | ✅               | ✅               | \*\*\*\*         | \*\*\*\*         |
| Fully Repaired Pick Axe | \*\*\*\*         | \*\*\*\*         | ✅               | ✅               |

| 75%                     | 10% Damaged Pick | 30% Damaged Pick | 80% Damaged Pick | Full Repair Pick |
| ----------------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| Nearly Broken Pick Axe  | ✅               | ✅               | \*\*\*\*         | \*\*\*\*         |
| Fully Repaired Pick Axe | \*\*\*\*         |                  | ✅               | ✅               |

| 99%                     | 10% Damaged Pick | 30% Damaged Pick | 80% Damaged Pick | Full Repair Pick |
| ----------------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| Nearly Broken Pick Axe  | ✅               | ✅               | ✅               | \*\*\*\*         |
| Fully Repaired Pick Axe | \*\*\*\*         | \*\*\*\*         | \*\*\*\*         | ✅               |

| Ignore                  | 10% Damaged Pick | 30% Damaged Pick | 80% Damaged Pick | Full Repair Pick |
| ----------------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| Nearly Broken Pick Axe  | ✅               | ✅               | ✅               | **✅**           |
| Fully Repaired Pick Axe | **✅**           | **✅**           | **✅**           | ✅               |

<RecipeFor id="appliedenergistics2:fuzzy_card" />
