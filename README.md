# Encoded_M7P
Custom addon weapon inspired by the MP7 Sub Machine gun and silencer attachment and full animation


copy and paste into ox_inventory/data/weapons.lua

		['WEAPON_M7P'] = {
			label = 'M7P SMG',
			weight = 1180,
			durability = 0.03,
			ammoname = 'ammo-9',
			description = 'Sister Ivan',
		},

this must be under components in weapons.lua

	['ace_m7p_silencer'] = {
		label = 'M7P Suppressor',
		type = 'barrel',
		weight = 280,
		description = "nil",
		client = {
			component = {`COMPONENT_AT_SUPP`},
			usetime = 2500
		}
	},
