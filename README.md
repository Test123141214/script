script_key = "HekfVKzkzAXhFbdNANNFCFSWECDrlbjg";

_G["HoHo Hub Auto Bounty V4"] = {
    ["Avatar"] = "rbxassetid://8598068647",
    ["Farm Method"] = "Normal", -- Normal or Gun (really Bad rn)
    ["Select Team"] = "Pirate", -- Pirate/Marine
    ["Discord Webhook"] = "",
    ["Bypass Teleport"] = false, -- not recommend cuz the bypass success rate is low
    ["Max Level Distance"] = 612, -- 612 is took from wiki but u can change it
    ["Don't attack friends"] = true,
    ["Don't attack player have cup"] = false,
    ["Distance Attack Y"] = 6, -- Shark Race = 0; Another >= 6
    ["Chat After Kill"] = {
        ["Active"] = false, -- if u don't want script chat just make it false
        ["List Chat"] = {""},
    },
    ["Yourself"] = {
        ["Invisible From Ken"] = true,
        ["No Stun"] = true,
    },
    ["SafeZone"] = {Enabled = true, ["Health Left (%)"] = 40, ["Wait Until Heal (%)"] = 60},
    ["Time Control"] = {
        ["Max Time Target Player"] = 150,
    },
    ["Abilities"] = {
        ["Auto Click"] = true,
        ["Melee"] = {
            Z = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            X = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.9},
            C = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
        },
        ["Sword"] = {
            Z = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            X = {Enabled = true, Hold = 0.5, WaitNextSkill = 0.6},
        },
        ["Gun"] = {
            Z = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            X = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
        },
        ["Fruit"] = {
            Z = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            X = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            C = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            V = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6}, -- don't forget to disable V if u r using zoan fruits
            F = {Enabled = false, Hold = 0.05, WaitNextSkill = 0.6},
        },
    },
}
_G.SupperFixLag = true -- eww potato device
_G["Auto Gacha & Store Fruit"] = true -- more fruits ^^
_G.UsePortalTeleport = true

_G.loadCustomId = "fac6dbd013c78163f8061ce11b2c1330"
loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI"))()
