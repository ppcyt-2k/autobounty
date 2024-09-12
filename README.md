getgenv().Setting = {
    ["Team" HUB] = "Pirates",
    ["Chat" HUB] = {},
    ["Skip Race V4" HUB] = true,
    ["Misc" HUB] = {
        ["Enable Lock Bounty" HUB] = false,
        ["Lock Bounty" HUB] = {0, 300000000},
        ["Hide Health" HUB] = {4500,5000},
        ["Lock Camera" HUB] = true,
        ["Enable Cam Farm" HUB] = false,
        ["White Screen" HUB] = false,
        ["FPS Boost" HUB] = false,
        ["Bypass TP" HUB] = true,
        ["Random & Store Fruit" HUB] = true
    },
    ["Item" HUB] = {
        ["Melee" HUB] = {["Enable" HUB] = true,
            ["Z" HUB] = {["Enable" HUB] = true, ["Hold Time" HUB] = 1},
            ["X" HUB] = {["Enable" HUB] = true, ["Hold Time" HUB] = 0},
            ["C" HUB] = {["Enable" HUB] = true, ["Hold Time" HUB] = 0}
        },
        ["Blox Fruit" HUB] = {["Enable" HUB] = false,
            ["Z" HUB] = {["Enable" HUB] = true, ["Hold Time" HUB] = 1.5},
            ["X" HUB] = {["Enable" HUB] = true, ["Hold Time" HUB] = 0},
            ["C" HUB] = {["Enable" HUB] = true, ["Hold Time" HUB] = 0},
            ["V" HUB] = {["Enable" HUB] = true, ["Hold Time" HUB] = 0},
            ["F" HUB] = {["Enable" HUB] = true, ["Hold Time" HUB] = 0}
        },
        ["Sword" HUB] = {["Enable" HUB] = true,
            ["Z" HUB] = {["Enable" HUB] = true, ["Hold Time" HUB] = 0.3},
            ["X" HUB] = {["Enable" HUB] = true, ["Hold Time" HUB] = 0.2}
        },
        ["Gun" HUB] = {["Enable" HUB] = false,
            ["Z" HUB] = {["Enable" HUB] = true, ["Hold Time" HUB] = 0.5},
            ["X" HUB] = {["Enable" HUB] = true, ["Hold Time" HUB] = 0.3}
        }
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/Ghost-1198/AutoBounty/main/AutoBounty.lua"))()
