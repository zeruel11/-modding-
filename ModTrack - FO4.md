[1]: https://www.nexusmods.com/fallout4/mods/26108
[2]: https://www.nexusmods.com/fallout4/mods/28192
[3]: https://www.nexusmods.com/fallout4/mods/2249?
[4]: https://www.nexusmods.com/fallout4/mods/32277
[5]: https://www.nexusmods.com/fallout4/mods/35598

# MasterList Mod Ideas

1. [Archimedes-II Finder][5][^CEFF2D7D].
2. Make killmoves easier and frequent perform[^8F4C28EF].
3. Holster and Sheaths + _VIS-G_ _personalEdit_ _VisibleWeapon_[^126B11E2].
4. Make craftable ammo for New Calibers using [New Calibers Reload (RELOAD_RELOAD.esp)][4] as a base[^A0120CD7].
5. CROSS_2077 + CROSS_HandMaiden + Fortaleza + Shino_VaultPack + CROSS_IEX [_UniquePC_][1] + _armorConversion_[^43F8030E]

[^CEFF2D7D]: Make easier to switch between different firing modes. Try console:`player.cf CROSS_sol_GunMenuScript`
[^8F4C28EF]: Apply changes to killmoves using mods [Sync Kill Animations a.k.a Killmoves for all Humanoid races](https://www.nexusmods.com/fallout4/mods/15408), [Bashing killmoves enabled](https://www.nexusmods.com/fallout4/mods/13370), and [Better killmove frequency](https://www.nexusmods.com/fallout4/mods/12673).
[^126B11E2]: Modify weapon model to also use holster models and add material keywords to said models. Also added VIS-G tagging.
Last edited record:
Last edited model:
[^A0120CD7]: Edit craftable ammunition to use AWKCR workbenches.
[^43F8030E]: Changing 1st person body to use Unique PC synth arm:
    - [x] CROSS 2077
    - [x] CROSS TheKite_HandMaiden
    - [ ] Fortaleza Armor
    - [x] Shino Vault Pack
    - [ ] ~~CROSS Institute Ex~~ (unneeded)

## myCompatibilityPatch

Shino_VaultPack + _AWKCR_ + _VIS-G_[^4652CD7D]
[CROSS_Archimedes-II][5] + _AWKCR_ + _VIS-G_[^4D7311B0]
CROSS_HandMaiden + CROSS_TechMask + CROSS_2077 + CROSS_CoA _AE_+_VIS-G_[^BCD6EDE2]
Darker Night + WestTek Tactical[^BEBDE78F]
New Calibers + _VIS-G_ (and maybe VIS-G Legendary)[^378F4450]
Smokable Cigars (Hardcore Patch) + _VIS-G_[^3ECF7B48]
Fortaleza Armor (+_AE_) + _VIS-G_[^C538C2B1]
More Smarter Companions Mod + [Creative Perks][2][^18EE74EF]
MAID Assaultron + Humanoid Assaultrons[^22E1BF3C]
~~CROSS_Blades + _VIS-G_~~ [^8C461351] `~~I am probably gonna uninstall this, the sword doesn't work as I had hoped and the throwing knives are rather hard to use since they have no projectiles. Also found better alternatives for swords.~~Yep uninstalled`
_VIS-G_ various mod setting holotapes & aids[^91E0ADE0]
Widow Shotgun + _AWKCR_ + _VIS-G_ + New Calibers[^1C9C6C03]
SimSettlement + _AWKCR_ + _AE_ + _VIS-G_ hugePatch[^36EB201B]
More Where That Came From + Reverb and Ambiance Overhaul[^F3DDBBD1]
[Creative Perks][2] + [WIPAG][3] + additional _VIS-G_ tags[^466223E4]

[^466223E4]: Changed Nuclear Physicist perks (NuclearPhysicist01-03) to use creative perks values but removed Fusion Core drain in favor of WIPAG's power armor modification system. Also changed companion perk FULL to VIS-G tags.
[^F3DDBBD1]: Changed radio station sound mapping to follow Reverb and Ambiance Overhaul.
[^4652CD7D]: Moved COBJ to AWKCR workbenches and uses VIS-G sorting. Manual armor KWDA edit needed, needs doing:
    - [x] Vault Closed
    - [x] Vault Top Open
    - [x] Vault Half-Open
    - [x] Vault Open
    - [x] Vault Open Sexy
[^4D7311B0]: Moved COBJ weapon and ammo craft to respective AWKCR workbench. Also changed ammo (solar core) and mods to use VIS-G tags. Added AWKCR KWDA to main weapon.
[^BCD6EDE2]: Added AE keywords and VIS-G name sorting.
[^BEBDE78F]: Modified WestTek Tactical night vision to resemble betternightvision.esp from Darker Night.
[^378F4450]: Combined New Calibers KEYW and OMOD with VIS-G FULL.
[^3ECF7B48]: Current patch removed the effects of hardcore mode, needs overwrite on ingestibles.
[^C538C2B1]: Added VIS-G tags to armors. Also need to convert to Fusion Body.
Rebuild 2077, HandMaiden, and Shino Vault Pack bodyslide files with full ZeX body to avoid glitches.
[^18EE74EF]: Modifies some NPC data to better match UF4P and used Eli's Courser outfit. Also changes some companion perk bonus with More Smarter Companion.
[^22E1BF3C]: Combined workbench edits. ~~Also added head laser enchantments to MAID head.~~No longer needed due to [MAID Assaultron Head Laser Ability](https://www.nexusmods.com/fallout4/mods/37613).
[^8C461351]: Give back CROSS naming and balance to VIS-G sorting: (FULL is unneeded if using INRD dn_CommonMelee)
    - [x] Plasma Katana... [4da Katana] _WeaponMeleeClass_Katana [KYWD:08000F09]
    - [x] Plasma Throwing Knife... (Grenade) _WeaponType_Thrown [KYWD:08000959]
    - [x] Plasma Throwing Knife (Unpowered)... (Grenade) _WeaponType_Thrown [KYWD:08000959]
    - [x] Laser Sword... [4d Sword]
    - [ ] Crucible Blade...a
[^91E0ADE0]: Change holotapes/ingestibles FULL to use VIS-G sorting names.
[^1C9C6C03]: Added AWKCR KWDA keywords and VIS-G sorting:
    - _WeaponCaliber_12_Gauge [KYWD:0800087A]
    - _WeaponGunClass_Shotgun [KYWD:08000BE4]
    - ma_OrnamentalWeapons [KYWD:08001B6B]
    - ma_12gShotgun [KYWD:0B04E114]
APPR:
    - ap_Weapon_Condition "Condition" [KYWD:08000F13]
    - ap_Gun_Caliber "Caliber" [KYWD:080008AE]
Also added New Calibers caliber mods OBTE:
    - modcol_12gShotgun_Ammo_All [OMOD:0B00A7ED]
[^36EB201B]: Changed a lot of names to follow new VIS-G sorting. Overrides taken from [Sim Settlements VIS-G Patch v1.0-33383-2-4-1539543979](https://www.nexusmods.com/fallout4/mods/33383) and [Kinggath VISGified-37935-1-00-1552394872](https://www.nexusmods.com/fallout4/mods/37935) respectively. Last EDID record is: 

## bashedPatch (tags)
