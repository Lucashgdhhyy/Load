local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Waffles Hub| Discord Comming Soon", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
  local Window = OrionLib:MakeWindow({
		Name = "Creditos",
		HidePremium = false,
		SaveConfig = true,
		ConfigFolder = "OrionTest",
        IntroText = "Key Waffles"       
}) --This Will Load The Script Hub

OrionLib:MakeNotification({
	Name = "Carregando",
	Content = "Waffles Hub Carregado",
	Image = "rbxassetid://4483345998",
	Time = 5
})

Tab:AddParagraph("Waffles Hub","The Best Script Hub:D")
Tab:AddParagraph("Creator","Waffles_Exility")
Tab:AddParagraph("Beta Testers","Tubaro Script,Exilitys,so cool")

local Tab = Window:MakeTab({
	Name = "Exec e Logs",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("Versão","Esta em Alpha com acesso antecipado")
Tab:AddParagraph("Executores Suportados","Vega X,Arcerus Neon,Codex e Delta.Se nao tiver um que nao esteja na lista favor,fale no discord se funcionar")
Tab:AddParagraph("Status","Funcionando")
Tab:AddParagraph("Proxima update, 25 de abril","")
Tab:AddParagraph("Oque veio na V0.3","King Legacy, Tradução a portugues blade ball ")

local Tab = Window:MakeTab({
	Name = "Blox Fruit",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Redz Hub",
	Callback = function()
      		print("button pressed")         
loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
  	end    
})


Tab:AddButton({
	Name = "Domadic Hub",
	Callback = function()
      		print("button pressed")      loadstring(game:HttpGet("https://raw.githubusercontent.com/Domadicoof/Domadicoof/main/Domadichub/NottoGay/Start.ranscript"))()        
  	end    
})

Tab:AddButton({
	Name = "Naja Hub",
	Callback = function()
      		print("button pressed")              loadstring(game:HttpGet("https://raw.githubusercontent.com/NaJaxHub/M/main/%3F.lua"))() 
  	end    
})

Tab:AddButton({
	Name = "Khang Hub",
	Callback = function()
      		print("button pressed")        loadstring(game:HttpGet("https://raw.githubusercontent.com/Nguyenchikhangg/YTB_Khang_Mod_Game/main/Khang_Mod_Game_Version_1.2.txt"))()                       
      		end    
})

Tab:AddButton({
	Name = "Strawberry Hub",
	Callback = function()
      		print("button pressed")         loadstring(game:HttpGet("https://raw.githubusercontent.com/CheemsNhuChiAl/Sotringhuhu/main/StrawberryHup"))() 
      		end    
})

local Tab = Window:MakeTab({
	Name = "King Legacy",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Domadic Hub",
	Callback = function()
      		print("button pressed")      loadstring(game:HttpGet("https://raw.githubusercontent.com/Domadicoof/Domadicoof/main/Domadichub/NottoGay/Start.ranscript"))()        
  	end    
})

local Tab = Window:MakeTab({
	Name = "Blade Ball",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Darkrai Hub",
	Callback = function()
      		print("button pressed")                     loadstring(game:HttpGet("https://raw.githubusercontent.com/poolist/Foolds/main/Bladd"))() 
  	end     
})

Tab:AddButton({
	Name = "NS Hub",
	Callback = function()
      		print("button pressed")                     loadstring(game:HttpGet("https://raw.githubusercontent.com/HenSeu87PofghYT/Blade-Ball2/main/Nameless%20Scripts"))() 
  	end    
})

Tab:AddButton({
	Name = "Bedol Hub",
	Callback = function()
      		print("button pressed")                       _G.UI_Size = 200 -- config ui size
loadstring(game:HttpGet("https://raw.githubusercontent.com/3345-c-a-t-s-u-s/-beta-/main/AutoParry.lua"))() 
  	end    
})

Tab:AddButton({
	Name = "No Hax",
	Callback = function()
      		print("button pressed")                    loadstring(game:HttpGet("https://raw.githubusercontent.com/r4mpage4/NoHaxV3/main/BladeBallNoHax%20V3"))(); 
  	end    
})
