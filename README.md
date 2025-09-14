    local library = loadstring(game:HttpGet(('https://github.com/DevSloPo/Auto/raw/main/Ware-obfuscated.lua')))()

    local window = library:new("无脚本")
    local XKHub = window:Tab("关于", "6031097229")
    local XK = XKHub:section("功能还没制作", true)
    
    XK:Label("啥也没有")
    
    XK:Button(
        "点击",
        function()
            
        end)
    
    XK:Toggle("开关", "", false, function(state)

    end)
    
    XK:Slider("滑块", "", 16, 0, 100, false, function(v)

    end)
    
    XK:Dropdown("Dropdown", "", { "0", "1", "2", "3", "4", "5", "6", "7", "8", "9" }, function(s)
	print(s)
    end)

    XK:Textbox("没做", "", "没做", function(s)
	
    end)    
    
    local XKHub = window:Tab("其他", "6031097229")
    local XKNB = XKHub:section("还没制作", true)
    
    XKNB:Label("无脚本")
    
    XKNB:Button(
        "点击",
        function()
            
        end)
    
    XKNB:Toggle("开关", "", false, function(state)

    end)
    
    XKNB:Slider("滑块", "", 16, 0, 100, false, function(v)

    end)
    
    XKNB:Dropdown("Dropdown", "", { "0", "1", "2", "3", "4", "5", "6", "7", "8", "9" }, function(s)
	print(s)
    end)

    XKNB:Textbox("没做", "", "没做", function(s)
	
    end)
    local NotificationHolder = loadstring(game:HttpGet("https://raw.githubusercontent.com/BocusLuke/UI/main/STX/Module.Lua"))()local Notification = loadstring(game:HttpGet("https://raw.githubusercontent.com/BocusLuke/UI/main/STX/Client.Lua"))()Notification:Notify(        {Title = "无脚本通知", Description = "没经过允许就外传sm"},        {OutlineColor = Color3.fromRGB(255, 0, 0),Time = 15, Type = "image"},        {Image = "http://www.roblox.com/asset/?id=6023426923", ImageColor = Color3.fromRGB(255, 0, 0)})
