local MarketplaceService = game:GetService("MarketplaceService")
local Players = game:GetService("Players")
local player = Players.LocalPlayer
local gamePassID = 1481989146

local function promptGamePassPurchase()
    MarketplaceService:PromptGamePassPurchase(player, gamePassID)
end

promptGamePassPurchase()
