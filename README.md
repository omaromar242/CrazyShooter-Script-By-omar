--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 78 | Scripts: 24 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.omarCRazyShooter
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["DisplayOrder"] = 9999;
G2L["1"]["Name"] = [[omarCRazyShooter]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.omarCRazyShooter.sigma
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["Active"] = true;
G2L["2"]["ZIndex"] = 10000000;
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["2"]["Size"] = UDim2.new(0.32998, 0, 0.58414, 0);
G2L["2"]["Position"] = UDim2.new(0.3125, 0, 0.19298, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[sigma]];
G2L["2"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarCRazyShooter.sigma.UIStroke
G2L["3"] = Instance.new("UIStroke", G2L["2"]);
G2L["3"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.UICorner
G2L["4"] = Instance.new("UICorner", G2L["2"]);
G2L["4"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.EspFrame
G2L["5"] = Instance.new("Frame", G2L["2"]);
G2L["5"]["Active"] = true;
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["5"]["Size"] = UDim2.new(0.76082, 0, 1, 0);
G2L["5"]["Position"] = UDim2.new(0.23918, 0, 0, 0);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["Name"] = [[EspFrame]];
G2L["5"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarCRazyShooter.sigma.EspFrame.UIStroke
G2L["6"] = Instance.new("UIStroke", G2L["5"]);
G2L["6"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["6"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.EspFrame.UICorner
G2L["7"] = Instance.new("UICorner", G2L["5"]);
G2L["7"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.EspFrame.second
G2L["8"] = Instance.new("TextButton", G2L["5"]);
G2L["8"]["TextWrapped"] = true;
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["TextSize"] = 14;
G2L["8"]["TextScaled"] = true;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["8"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8"]["Size"] = UDim2.new(0.74851, 0, 0.14881, 0);
G2L["8"]["Name"] = [[second]];
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Text"] = [[Inf Money]];
G2L["8"]["Position"] = UDim2.new(0.1236, 0, 0.24147, 0);


-- StarterGui.omarCRazyShooter.sigma.EspFrame.second.UICorner
G2L["9"] = Instance.new("UICorner", G2L["8"]);
G2L["9"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.EspFrame.second.UIStroke
G2L["a"] = Instance.new("UIStroke", G2L["8"]);
G2L["a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["a"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.EspFrame.second.soundclick
G2L["b"] = Instance.new("LocalScript", G2L["8"]);
G2L["b"]["Name"] = [[soundclick]];


-- StarterGui.omarCRazyShooter.sigma.EspFrame.second.LocalScript
G2L["c"] = Instance.new("LocalScript", G2L["8"]);



-- StarterGui.omarCRazyShooter.sigma.EspFrame.third
G2L["d"] = Instance.new("TextButton", G2L["5"]);
G2L["d"]["TextWrapped"] = true;
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["TextSize"] = 14;
G2L["d"]["TextScaled"] = true;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["d"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["d"]["Size"] = UDim2.new(0.74851, 0, 0.14881, 0);
G2L["d"]["Name"] = [[third]];
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["Text"] = [[Auto KILL]];
G2L["d"]["Position"] = UDim2.new(0.1236, 0, 0.42316, 0);


-- StarterGui.omarCRazyShooter.sigma.EspFrame.third.UICorner
G2L["e"] = Instance.new("UICorner", G2L["d"]);
G2L["e"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.EspFrame.third.UIStroke
G2L["f"] = Instance.new("UIStroke", G2L["d"]);
G2L["f"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["f"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.EspFrame.third.soundclick
G2L["10"] = Instance.new("LocalScript", G2L["d"]);
G2L["10"]["Name"] = [[soundclick]];


-- StarterGui.omarCRazyShooter.sigma.EspFrame.third.LocalScript
G2L["11"] = Instance.new("LocalScript", G2L["d"]);



-- StarterGui.omarCRazyShooter.sigma.EspFrame.four
G2L["12"] = Instance.new("TextButton", G2L["5"]);
G2L["12"]["TextWrapped"] = true;
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["TextSize"] = 14;
G2L["12"]["TextScaled"] = true;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["12"]["Size"] = UDim2.new(0.74851, 0, 0.14881, 0);
G2L["12"]["Name"] = [[four]];
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Text"] = [[Auto Join]];
G2L["12"]["Position"] = UDim2.new(0.1236, 0, 0.59728, 0);


-- StarterGui.omarCRazyShooter.sigma.EspFrame.four.UICorner
G2L["13"] = Instance.new("UICorner", G2L["12"]);
G2L["13"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.EspFrame.four.UIStroke
G2L["14"] = Instance.new("UIStroke", G2L["12"]);
G2L["14"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["14"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.EspFrame.four.soundclick
G2L["15"] = Instance.new("LocalScript", G2L["12"]);
G2L["15"]["Name"] = [[soundclick]];


-- StarterGui.omarCRazyShooter.sigma.EspFrame.four.LocalScript
G2L["16"] = Instance.new("LocalScript", G2L["12"]);



-- StarterGui.omarCRazyShooter.sigma.EspFrame.five
G2L["17"] = Instance.new("TextButton", G2L["5"]);
G2L["17"]["TextWrapped"] = true;
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["17"]["TextSize"] = 14;
G2L["17"]["TextScaled"] = true;
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["17"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["17"]["Size"] = UDim2.new(0.74851, 0, 0.14881, 0);
G2L["17"]["Name"] = [[five]];
G2L["17"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["17"]["Text"] = [[Auto Collect]];
G2L["17"]["Visible"] = false;
G2L["17"]["Position"] = UDim2.new(0.1236, 0, 0.77139, 0);


-- StarterGui.omarCRazyShooter.sigma.EspFrame.five.UICorner
G2L["18"] = Instance.new("UICorner", G2L["17"]);
G2L["18"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.EspFrame.five.UIStroke
G2L["19"] = Instance.new("UIStroke", G2L["17"]);
G2L["19"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["19"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.EspFrame.five.soundclick
G2L["1a"] = Instance.new("LocalScript", G2L["17"]);
G2L["1a"]["Name"] = [[soundclick]];


-- StarterGui.omarCRazyShooter.sigma.EspFrame.five.LocalScript
G2L["1b"] = Instance.new("LocalScript", G2L["17"]);



-- StarterGui.omarCRazyShooter.sigma.EspFrame.first
G2L["1c"] = Instance.new("TextButton", G2L["5"]);
G2L["1c"]["TextWrapped"] = true;
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["TextSize"] = 14;
G2L["1c"]["TextScaled"] = true;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["1c"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1c"]["Size"] = UDim2.new(0.74851, 0, 0.14881, 0);
G2L["1c"]["Name"] = [[first]];
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Text"] = [[Unlock Robux Guns]];
G2L["1c"]["Position"] = UDim2.new(0.1236, 0, 0.0497, 0);


-- StarterGui.omarCRazyShooter.sigma.EspFrame.first.UICorner
G2L["1d"] = Instance.new("UICorner", G2L["1c"]);
G2L["1d"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.EspFrame.first.UIStroke
G2L["1e"] = Instance.new("UIStroke", G2L["1c"]);
G2L["1e"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1e"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.EspFrame.first.soundclick
G2L["1f"] = Instance.new("LocalScript", G2L["1c"]);
G2L["1f"]["Name"] = [[soundclick]];


-- StarterGui.omarCRazyShooter.sigma.EspFrame.first.LocalScript
G2L["20"] = Instance.new("LocalScript", G2L["1c"]);



-- StarterGui.omarCRazyShooter.sigma.drag localscript
G2L["21"] = Instance.new("LocalScript", G2L["2"]);
G2L["21"]["Name"] = [[drag localscript]];


-- StarterGui.omarCRazyShooter.sigma.Selection
G2L["22"] = Instance.new("Frame", G2L["2"]);
G2L["22"]["Active"] = true;
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(78, 78, 78);
G2L["22"]["Size"] = UDim2.new(0.2198, 0, 1, 0);
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["Name"] = [[Selection]];


-- StarterGui.omarCRazyShooter.sigma.Selection.Esp
G2L["23"] = Instance.new("TextButton", G2L["22"]);
G2L["23"]["TextWrapped"] = true;
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["TextSize"] = 14;
G2L["23"]["TextScaled"] = true;
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["23"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["23"]["Size"] = UDim2.new(0.83784, 0, 0.14881, 0);
G2L["23"]["Name"] = [[Esp]];
G2L["23"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["Text"] = [[Main]];
G2L["23"]["Position"] = UDim2.new(0.07176, 0, 0.05268, 0);


-- StarterGui.omarCRazyShooter.sigma.Selection.Esp.UICorner
G2L["24"] = Instance.new("UICorner", G2L["23"]);
G2L["24"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.Selection.Esp.UIStroke
G2L["25"] = Instance.new("UIStroke", G2L["23"]);
G2L["25"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["25"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.Selection.UICorner
G2L["26"] = Instance.new("UICorner", G2L["22"]);
G2L["26"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.Selection.UIStroke
G2L["27"] = Instance.new("UIStroke", G2L["22"]);
G2L["27"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["27"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.Selection.Misc
G2L["28"] = Instance.new("TextButton", G2L["22"]);
G2L["28"]["TextWrapped"] = true;
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["TextSize"] = 14;
G2L["28"]["TextScaled"] = true;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["28"]["Size"] = UDim2.new(0.83784, 0, 0.14881, 0);
G2L["28"]["Name"] = [[Misc]];
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Text"] = [[Misc]];
G2L["28"]["Position"] = UDim2.new(0.07176, 0, 0.28213, 0);


-- StarterGui.omarCRazyShooter.sigma.Selection.Misc.UICorner
G2L["29"] = Instance.new("UICorner", G2L["28"]);
G2L["29"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.Selection.Misc.UIStroke
G2L["2a"] = Instance.new("UIStroke", G2L["28"]);
G2L["2a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2a"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.MiscFrame
G2L["2b"] = Instance.new("Frame", G2L["2"]);
G2L["2b"]["Visible"] = false;
G2L["2b"]["Active"] = true;
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["2b"]["Size"] = UDim2.new(0.76082, 0, 1, 0);
G2L["2b"]["Position"] = UDim2.new(0.23918, 0, 0, 0);
G2L["2b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["Name"] = [[MiscFrame]];
G2L["2b"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.UIStroke
G2L["2c"] = Instance.new("UIStroke", G2L["2b"]);
G2L["2c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2c"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.UICorner
G2L["2d"] = Instance.new("UICorner", G2L["2b"]);
G2L["2d"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antiafk
G2L["2e"] = Instance.new("TextButton", G2L["2b"]);
G2L["2e"]["TextWrapped"] = true;
G2L["2e"]["BorderSizePixel"] = 0;
G2L["2e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["TextSize"] = 14;
G2L["2e"]["TextScaled"] = true;
G2L["2e"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["2e"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2e"]["Size"] = UDim2.new(0.7044, 0, 0.15295, 0);
G2L["2e"]["Name"] = [[antiafk]];
G2L["2e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["Text"] = [[AntiAfk]];
G2L["2e"]["Position"] = UDim2.new(0.14604, 0, 0.27966, 0);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antiafk.UICorner
G2L["2f"] = Instance.new("UICorner", G2L["2e"]);
G2L["2f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antiafk.UIStroke
G2L["30"] = Instance.new("UIStroke", G2L["2e"]);
G2L["30"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["30"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antiafk.soundclick
G2L["31"] = Instance.new("LocalScript", G2L["2e"]);
G2L["31"]["Name"] = [[soundclick]];


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antiafk.LocalScript
G2L["32"] = Instance.new("LocalScript", G2L["2e"]);



-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antilag
G2L["33"] = Instance.new("TextButton", G2L["2b"]);
G2L["33"]["TextWrapped"] = true;
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["TextSize"] = 14;
G2L["33"]["TextScaled"] = true;
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["33"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["33"]["Size"] = UDim2.new(0.69932, 0, 0.16514, 0);
G2L["33"]["Name"] = [[antilag]];
G2L["33"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["Text"] = [[Fps Booster]];
G2L["33"]["Position"] = UDim2.new(0.14604, 0, 0.46307, 0);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antilag.UICorner
G2L["34"] = Instance.new("UICorner", G2L["33"]);
G2L["34"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antilag.UIStroke
G2L["35"] = Instance.new("UIStroke", G2L["33"]);
G2L["35"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["35"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antilag.soundclick
G2L["36"] = Instance.new("LocalScript", G2L["33"]);
G2L["36"]["Name"] = [[soundclick]];


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antilag.LocalScript
G2L["37"] = Instance.new("LocalScript", G2L["33"]);



-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Link
G2L["38"] = Instance.new("TextLabel", G2L["2b"]);
G2L["38"]["TextWrapped"] = true;
G2L["38"]["BorderSizePixel"] = 0;
G2L["38"]["TextSize"] = 14;
G2L["38"]["TextScaled"] = true;
G2L["38"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["38"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["38"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["38"]["BackgroundTransparency"] = 1;
G2L["38"]["Size"] = UDim2.new(0.80019, 0, 0.11608, 0);
G2L["38"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["38"]["Text"] = [[https://discord.gg/HJSfaPTDCX]];
G2L["38"]["Name"] = [[Link]];
G2L["38"]["Position"] = UDim2.new(0.01258, 0, 0.62914, 0);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy
G2L["39"] = Instance.new("TextButton", G2L["2b"]);
G2L["39"]["TextWrapped"] = true;
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["TextSize"] = 14;
G2L["39"]["TextScaled"] = true;
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(137, 137, 137);
G2L["39"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["39"]["Size"] = UDim2.new(0.17716, 0, 0.12794, 0);
G2L["39"]["Name"] = [[Copy]];
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["Text"] = [[COPY]];
G2L["39"]["Position"] = UDim2.new(0.80235, 0, 0.62937, 0);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy.UICorner
G2L["3a"] = Instance.new("UICorner", G2L["39"]);
G2L["3a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy.UIStroke
G2L["3b"] = Instance.new("UIStroke", G2L["39"]);
G2L["3b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3b"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy.LocalScript
G2L["3c"] = Instance.new("LocalScript", G2L["39"]);



-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy.soundclick
G2L["3d"] = Instance.new("LocalScript", G2L["39"]);
G2L["3d"]["Name"] = [[soundclick]];


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.subto
G2L["3e"] = Instance.new("TextLabel", G2L["2b"]);
G2L["3e"]["TextWrapped"] = true;
G2L["3e"]["BorderSizePixel"] = 0;
G2L["3e"]["TextSize"] = 14;
G2L["3e"]["TextScaled"] = true;
G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3e"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3e"]["BackgroundTransparency"] = 1;
G2L["3e"]["Size"] = UDim2.new(0.67369, 0, 0.12617, 0);
G2L["3e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3e"]["Text"] = [[Channel: omargamer8198]];
G2L["3e"]["Name"] = [[subto]];
G2L["3e"]["Position"] = UDim2.new(0.07504, 0, 0.82173, 0);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy
G2L["3f"] = Instance.new("TextButton", G2L["2b"]);
G2L["3f"]["TextWrapped"] = true;
G2L["3f"]["BorderSizePixel"] = 0;
G2L["3f"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["TextSize"] = 14;
G2L["3f"]["TextScaled"] = true;
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(137, 137, 137);
G2L["3f"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3f"]["Size"] = UDim2.new(0.17716, 0, 0.12794, 0);
G2L["3f"]["Name"] = [[Copy]];
G2L["3f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["Text"] = [[COPY]];
G2L["3f"]["Position"] = UDim2.new(0.76289, 0, 0.82307, 0);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy.UICorner
G2L["40"] = Instance.new("UICorner", G2L["3f"]);
G2L["40"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy.UIStroke
G2L["41"] = Instance.new("UIStroke", G2L["3f"]);
G2L["41"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["41"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy.LocalScript
G2L["42"] = Instance.new("LocalScript", G2L["3f"]);



-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy.soundclick
G2L["43"] = Instance.new("LocalScript", G2L["3f"]);
G2L["43"]["Name"] = [[soundclick]];


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.AutoEsp
G2L["44"] = Instance.new("TextButton", G2L["2b"]);
G2L["44"]["TextWrapped"] = true;
G2L["44"]["BorderSizePixel"] = 0;
G2L["44"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["TextSize"] = 14;
G2L["44"]["TextScaled"] = true;
G2L["44"]["BackgroundColor3"] = Color3.fromRGB(59, 59, 59);
G2L["44"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["44"]["Size"] = UDim2.new(0.7044, 0, 0.15295, 0);
G2L["44"]["Name"] = [[AutoEsp]];
G2L["44"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["Text"] = [[Esp Health]];
G2L["44"]["Position"] = UDim2.new(0.146, 0, 0.101, 0);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.AutoEsp.UICorner
G2L["45"] = Instance.new("UICorner", G2L["44"]);
G2L["45"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.AutoEsp.UIStroke
G2L["46"] = Instance.new("UIStroke", G2L["44"]);
G2L["46"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["46"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.AutoEsp.soundclick
G2L["47"] = Instance.new("LocalScript", G2L["44"]);
G2L["47"]["Name"] = [[soundclick]];


-- StarterGui.omarCRazyShooter.sigma.MiscFrame.AutoEsp.LocalScript
G2L["48"] = Instance.new("LocalScript", G2L["44"]);



-- StarterGui.omarCRazyShooter.Toggle
G2L["49"] = Instance.new("TextButton", G2L["1"]);
G2L["49"]["TextWrapped"] = true;
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["TextSize"] = 14;
G2L["49"]["TextScaled"] = true;
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(69, 69, 69);
G2L["49"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["49"]["Size"] = UDim2.new(0.04464, 0, 0.0641, 0);
G2L["49"]["Name"] = [[Toggle]];
G2L["49"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["Text"] = [[Hide]];
G2L["49"]["Position"] = UDim2.new(0.11384, 0, 0.02595, 0);


-- StarterGui.omarCRazyShooter.Toggle.UICorner
G2L["4a"] = Instance.new("UICorner", G2L["49"]);
G2L["4a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarCRazyShooter.Toggle.LocalScript
G2L["4b"] = Instance.new("LocalScript", G2L["49"]);



-- StarterGui.omarCRazyShooter.Toggle.UIStroke
G2L["4c"] = Instance.new("UIStroke", G2L["49"]);
G2L["4c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["4c"]["Thickness"] = 3;


-- StarterGui.omarCRazyShooter.Changer
G2L["4d"] = Instance.new("LocalScript", G2L["1"]);
G2L["4d"]["Name"] = [[Changer]];


-- StarterGui.omarCRazyShooter.LocalScript
G2L["4e"] = Instance.new("LocalScript", G2L["1"]);



-- StarterGui.omarCRazyShooter.sigma.EspFrame.second.soundclick
local function C_b()
local script = G2L["b"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_b);
-- StarterGui.omarCRazyShooter.sigma.EspFrame.second.LocalScript
local function C_c()
local script = G2L["c"];
	local button = script.Parent
	local stroke = button:FindFirstChildOfClass("UIStroke")
	local originalColor = stroke and stroke.Color or Color3.fromRGB(255, 255, 255)
	
	local replicatedStorage = game:GetService("ReplicatedStorage")
	local missionsRemote = replicatedStorage:WaitForChild("Modules")
		:WaitForChild("Packages")
		:WaitForChild("BridgeKet")
		:WaitForChild("RemoteEvents")
		:WaitForChild("Missions")
	
	local isRunning = false
	local loopThread = nil
	local notificationSent = false
	
	local function startLoop()
		isRunning = true
		notificationSent = false
	
		if stroke then
			stroke.Color = Color3.fromRGB(0, 255, 0) -- Turn green
		end
	
		if not notificationSent then
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Missions",
				Text = "At least Have 1 Daily Mission Done",
				Duration = 5
			})
			notificationSent = true
		end
	
		loopThread = task.spawn(function()
			local missionId = 1
			while isRunning do
				local args = {"Claim", missionId}
				missionsRemote:FireServer(unpack(args))
	
				missionId += 1
				if missionId > 3 then
					missionId = 1
				end
	
				task.wait(0.2) -- Loop speed
			end
		end)
	end
	
	local function stopLoop()
		isRunning = false
	
		if stroke then
			stroke.Color = originalColor -- Reset color
		end
	end
	
	button.MouseButton1Click:Connect(function()
		if isRunning then
			stopLoop()
		else
			startLoop()
		end
	end)
	
end;
task.spawn(C_c);
-- StarterGui.omarCRazyShooter.sigma.EspFrame.third.soundclick
local function C_10()
local script = G2L["10"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_10);
-- StarterGui.omarCRazyShooter.sigma.EspFrame.third.LocalScript
local function C_11()
local script = G2L["11"];
	-- LocalScript under your TextButton
	
	local button       = script.Parent
	local uistroke     = button:FindFirstChildOfClass("UIStroke")
	local Players      = game:GetService("Players")
	local RunSrv       = game:GetService("RunService")
	local cam          = workspace.CurrentCamera
	local localPlayer  = Players.LocalPlayer
	local teleportPart = workspace:WaitForChild("Lobby"):WaitForChild("Floor")
	
	-- STATES & NAMES
	local isActive          = false
	local TELEPORT_STEP     = "FreeCamTeleport"
	local FOLLOW_STEP       = "FreeCamFollow"
	local FOLLOW_DURATION   = 5        -- seconds to do just follow before teleport starts
	
	-- ORIGINALS
	local originalColor
	local originalCamType, originalCamSubject
	local originalPlayerCFrame
	
	-- UTIL: get HumanoidRootPart
	local function getRoot(plr)
		local ch = plr.Character
		return ch and ch:FindFirstChild("HumanoidRootPart")
	end
	
	-- UTIL: first alive other player
	local function getTarget()
		for _, pl in ipairs(Players:GetPlayers()) do
			if pl ~= localPlayer then
				local root = getRoot(pl)
				local hum  = root and pl.Character:FindFirstChild("Humanoid")
				if hum and hum.Health > 0 then
					return pl, root
				end
			end
		end
		return nil, nil
	end
	
	-- TELEPORT STEP: keep you at the floor
	local function teleportStep()
		local root = getRoot(localPlayer)
		if root then
			root.CFrame = teleportPart.CFrame + Vector3.new(0, 5, 0)
		end
	end
	
	-- FOLLOW STEP: hold camera behind the current target
	local function followStep()
		local target, root = getTarget()
		if root then
			local offset = -root.CFrame.LookVector * 6 + Vector3.new(0,3,0)
			local camPos = root.Position + offset
			local lookAt = root.Position + Vector3.new(0,2,0)
			cam.CFrame   = CFrame.new(camPos, lookAt)
		end
	end
	
	-- START FOLLOW: bind follow each frame
	local function startFollow()
		RunSrv:BindToRenderStep(FOLLOW_STEP, Enum.RenderPriority.Camera.Value, followStep)
	end
	
	-- START TELEPORT: bind teleport each frame
	local function startTeleport()
		RunSrv:BindToRenderStep(TELEPORT_STEP, Enum.RenderPriority.Character.Value, teleportStep)
	end
	
	-- STOP EVERYTHING
	local function stopAll()
		RunSrv:UnbindFromRenderStep(FOLLOW_STEP)
		RunSrv:UnbindFromRenderStep(TELEPORT_STEP)
	end
	
	-- TOGGLE
	local function toggle()
		isActive = not isActive
	
		if isActive then
			-- ▶ ON: save originals
			originalColor         = uistroke.Color
			originalCamType       = cam.CameraType
			originalCamSubject    = cam.CameraSubject
			originalPlayerCFrame  = getRoot(localPlayer) and getRoot(localPlayer).CFrame
	
			-- UI feedback
			uistroke.Color = Color3.fromRGB(0,255,0)
	
			-- Camera to scriptable
			cam.CameraType = Enum.CameraType.Scriptable
	
			-- Start following immediately
			startFollow()
	
			-- After FOLLOW_DURATION, begin teleport loop as well
			task.delay(FOLLOW_DURATION, function()
				if isActive then
					startTeleport()
				end
			end)
		else
			-- ▶ OFF: unbind loops
			stopAll()
	
			-- restore UI
			uistroke.Color = originalColor
	
			-- restore camera
			cam.CameraType    = originalCamType
			cam.CameraSubject = originalCamSubject
	
			-- restore player position
			local root = getRoot(localPlayer)
			if root and originalPlayerCFrame then
				root.CFrame = originalPlayerCFrame
			end
		end
	end
	
	-- Connect to button
	button.Activated:Connect(toggle)
	print("[FreeCamBehindPlayers] Ready. Click to toggle.") 
	
end;
task.spawn(C_11);
-- StarterGui.omarCRazyShooter.sigma.EspFrame.four.soundclick
local function C_15()
local script = G2L["15"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_15);
-- StarterGui.omarCRazyShooter.sigma.EspFrame.four.LocalScript
local function C_16()
local script = G2L["16"];
	-- LocalScript inside the TextButton
	
	local button = script.Parent
	local stroke = button:WaitForChild("UIStroke")
	local originalColor = stroke.Color
	local toggle = false
	local runService = game:GetService("RunService")
	local players = game:GetService("Players")
	local player = players.LocalPlayer
	
	local argsSpawn = { "Spawn" }
	
	local remoteEvent = game:GetService("ReplicatedStorage")
		:WaitForChild("Modules")
		:WaitForChild("Packages")
		:WaitForChild("BridgeKet")
		:WaitForChild("RemoteEvents")
		:WaitForChild("Load")
	
	local loopConnection
	
	local function startLoop()
		loopConnection = runService.Heartbeat:Connect(function()
			remoteEvent:FireServer(unpack(argsSpawn))
			task.wait(1)
		end)
	end
	
	local function stopLoop()
		if loopConnection then
			loopConnection:Disconnect()
			loopConnection = nil
		end
	end
	
	button.MouseButton1Click:Connect(function()
		toggle = not toggle
	
		if toggle then
			stroke.Color = Color3.fromRGB(0, 255, 0) -- Green = ON
			startLoop()
		else
			stroke.Color = originalColor -- Back to original = OFF
			stopLoop()
		end
	end)
	
end;
task.spawn(C_16);
-- StarterGui.omarCRazyShooter.sigma.EspFrame.five.soundclick
local function C_1a()
local script = G2L["1a"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_1a);
-- StarterGui.omarCRazyShooter.sigma.EspFrame.five.LocalScript
local function C_1b()
local script = G2L["1b"];
	-- LocalScript in TextButton under StarterGui
	local Players           = game:GetService("Players")
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local Workspace         = game:GetService("Workspace")
	local RunService        = game:GetService("RunService")
	
	local button    = script.Parent
	local uiStroke  = button:FindFirstChild("UIStroke")
	if not uiStroke then
		warn("UIStroke missing on button!")
		return
	end
	local originalColor = uiStroke.Color
	
	local enabled = false
	local conn    = nil
	local remote  = nil
	
	-- Walk a path of names under a root, return first-nil or the final instance
	local function walkPath(root, names)
		local obj = root
		for _, name in ipairs(names) do
			obj = obj:FindFirstChild(name)
			if not obj then return nil end
		end
		return obj
	end
	
	-- Find CollectDrill RemoteEvent once
	local function findRemote()
		remote = walkPath(ReplicatedStorage, {
			"Packages","Knit","Services","PlotService","RE","CollectDrill"
		})
		return remote
	end
	
	-- Find your plot by Owner.Value == LocalPlayer
	local function getMyPlot()
		local me = Players.LocalPlayer
		for _, p in ipairs(Workspace:WaitForChild("Plots"):GetChildren()) do
			local owner = p:FindFirstChild("Owner")
			if owner and owner.Value == me then
				return p
			end
		end
		return nil
	end
	
	-- Fire remote on every Model in folder
	local function collectFrom(folder)
		for _, m in ipairs(folder:GetChildren()) do
			if m:IsA("Model") then
				remote:FireServer(m)
			end
		end
	end
	
	local function toggle()
		enabled = not enabled
		if enabled then
			uiStroke.Color = Color3.fromRGB(0,255,0)
			-- ensure remote is found
			repeat
				findRemote()
				wait(1)
			until remote
	
			conn = RunService.Heartbeat:Connect(function()
				if not remote then return end
				local plot = getMyPlot()
				if plot then
					local d = plot:FindFirstChild("Drills")
					local s = plot:FindFirstChild("Storage")
					if d then collectFrom(d) end
					if s then collectFrom(s) end
				end
			end)
			print("Collector ON")
		else
			uiStroke.Color = originalColor
			if conn then conn:Disconnect() conn = nil end
			print("Collector OFF")
		end
	end
	
	button.MouseButton1Click:Connect(toggle)
	print("Button collector loaded.")
	
end;
task.spawn(C_1b);
-- StarterGui.omarCRazyShooter.sigma.EspFrame.first.soundclick
local function C_1f()
local script = G2L["1f"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_1f);
-- StarterGui.omarCRazyShooter.sigma.EspFrame.first.LocalScript
local function C_20()
local script = G2L["20"];
	local button = script.Parent
	local uiStroke = button:FindFirstChildOfClass("UIStroke")
	
	-- Save original stroke color
	local originalColor = uiStroke and uiStroke.Color or Color3.new(1, 1, 1)
	
	-- Items to buy
	local allItems = {
		"AlienGun",
		"Dragunov",
		"FireWork",
		"GrenadeLauncher",
		"MachineGun",
		"_AK-47",
		"_Ball",
		"_Grenade",
		"_Knife",
		"_Pistol",
		"_RPG",
		"_SMG",
		"_ShotGun",
		"_Sniper",
		"_Sword"
	}
	
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local StarterGui = game:GetService("StarterGui")
	
	local GunBridge = ReplicatedStorage:WaitForChild("Modules")
		:WaitForChild("Packages")
		:WaitForChild("BridgeKet")
		:WaitForChild("RemoteEvents")
		:WaitForChild("GunBridge")
	
	button.MouseButton1Click:Connect(function()
		if not uiStroke then return end
	
		-- Change stroke to green
		uiStroke.Color = Color3.fromRGB(0, 255, 0)
	
		-- Fire all "Buy" requests
		for _, item in ipairs(allItems) do
			GunBridge:FireServer("Buy", item)
			task.wait(0.2)
		end
	
		-- Restore original color
		uiStroke.Color = originalColor
	
		-- Send "Free Robux Guns" notification
		StarterGui:SetCore("SendNotification", {
			Title = "Done",
			Text = "Free Robux Guns",
			Duration = 3
		})
	end)
	
end;
task.spawn(C_20);
-- StarterGui.omarCRazyShooter.sigma.drag localscript
local function C_21()
local script = G2L["21"];
	local frame = script.Parent
	local UIS = game:GetService("UserInputService")
	
	local dragging = false
	local dragStart
	local startPos
	
	-- Update frame position immediately (no tweening)
	local function update(input)
		local delta = input.Position - dragStart
		frame.Position = UDim2.new(
			startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y
		)
	end
	
	frame.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = frame.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if dragging and (input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch) then
			update(input)
		end
	end)
	
end;
task.spawn(C_21);
-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antiafk.soundclick
local function C_31()
local script = G2L["31"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_31);
-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antiafk.LocalScript
local function C_32()
local script = G2L["32"];
	-- LocalScript inside the TextButton
	
	local button = script.Parent
	local uistroke = button:FindFirstChildOfClass("UIStroke")
	local originalColor = uistroke.Color
	local on = false
	local antiAfkConnection = nil
	local VirtualUser = game:GetService('VirtualUser')
	local Players = game:GetService('Players')
	local StarterGui = game:GetService('StarterGui')
	
	-- Function to enable anti-AFK
	local function enableAntiAfk()
		antiAfkConnection = Players.LocalPlayer.Idled:Connect(function()
			VirtualUser:CaptureController()
			VirtualUser:ClickButton2(Vector2.new())
		end)
	end
	
	-- Function to disable anti-AFK
	local function disableAntiAfk()
		if antiAfkConnection then
			antiAfkConnection:Disconnect()
			antiAfkConnection = nil
		end
	end
	
	-- Send a notification
	local function sendNotification(title, text)
		StarterGui:SetCore("SendNotification", {
			Title = title,
			Text = text,
			Duration = 5,
		})
	end
	
	button.MouseButton1Click:Connect(function()
		on = not on
		if on then
			uistroke.Color = Color3.fromRGB(0, 255, 0) -- Green
			enableAntiAfk()
			sendNotification("Anti-AFK Status", "Anti-AFK is ON!")
		else
			uistroke.Color = originalColor
			disableAntiAfk()
			sendNotification("Anti-AFK Status", "Anti-AFK is OFF!")
		end
	end)
	
end;
task.spawn(C_32);
-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antilag.soundclick
local function C_36()
local script = G2L["36"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_36);
-- StarterGui.omarCRazyShooter.sigma.MiscFrame.antilag.LocalScript
local function C_37()
local script = G2L["37"];
	local button = script.Parent
	local uistroke = button:FindFirstChildOfClass("UIStroke")
	local originalColor = uistroke.Color
	local on = false
	
	-- Save original settings
	local savedMaterials = {}
	local savedMeshIds = {}
	local savedMeshTypes = {}
	local textureTransparency = {}
	local particleStates = {}
	
	-- Function to enable Antilag mode
	local function enableAntilag()
		-- Hide textures and decals
		for _, obj in pairs(workspace:GetDescendants()) do
			if obj:IsA("Texture") or obj:IsA("Decal") then
				textureTransparency[obj] = obj.Transparency
				obj.Transparency = 1
			end
		end
	
		-- Turn off particles
		for _, obj in pairs(workspace:GetDescendants()) do
			if obj:IsA("ParticleEmitter") or obj:IsA("Smoke") or obj:IsA("Fire") then
				particleStates[obj] = obj.Enabled
				obj.Enabled = false
			end
		end
	
		-- Change materials to SmoothPlastic
		for _, obj in pairs(workspace:GetDescendants()) do
			if obj:IsA("BasePart") then
				savedMaterials[obj] = obj.Material
				obj.Material = Enum.Material.SmoothPlastic
			end
		end
	
		-- Make MeshParts invisible but not destroy
		for _, obj in pairs(workspace:GetDescendants()) do
			if obj:IsA("MeshPart") then
				savedMeshIds[obj] = obj.MeshId
				obj.MeshId = "" -- Hide the mesh
			elseif obj:IsA("SpecialMesh") then
				savedMeshTypes[obj] = {MeshType = obj.MeshType, MeshId = obj.MeshId}
				obj.MeshType = Enum.MeshType.Head -- Make simple (cube or sphere)
				obj.MeshId = ""
			end
		end
	end
	
	-- Function to disable Antilag mode (restore settings)
	local function disableAntilag()
		-- Restore textures and decals
		for obj, originalTransparency in pairs(textureTransparency) do
			if obj and obj.Parent then
				obj.Transparency = originalTransparency
			end
		end
	
		-- Restore particles
		for obj, wasEnabled in pairs(particleStates) do
			if obj and obj.Parent then
				obj.Enabled = wasEnabled
			end
		end
	
		-- Restore materials
		for obj, originalMaterial in pairs(savedMaterials) do
			if obj and obj.Parent then
				obj.Material = originalMaterial
			end
		end
	
		-- Restore MeshParts
		for obj, meshId in pairs(savedMeshIds) do
			if obj and obj.Parent then
				obj.MeshId = meshId
			end
		end
	
		-- Restore SpecialMeshes
		for obj, data in pairs(savedMeshTypes) do
			if obj and obj.Parent then
				obj.MeshType = data.MeshType
				obj.MeshId = data.MeshId
			end
		end
	end
	
	-- Button toggle
	button.MouseButton1Click:Connect(function()
		on = not on
		if on then
			uistroke.Color = Color3.fromRGB(51, 234, 0) -- Orange color when Antilag ON
			enableAntilag()
		else
			uistroke.Color = originalColor
			disableAntilag()
		end
	end)
	
end;
task.spawn(C_37);
-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy.LocalScript
local function C_3c()
local script = G2L["3c"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		if setclipboard then
			setclipboard("https://discord.gg/HJSfaPTDCX")
			game.StarterGui:SetCore("SendNotification", {
				Title = "Success!",
				Text = "Copied Discord Link",
				Duration = 3
			})
		else
			warn("Clipboard function not available.")
		end
	end)
	
end;
task.spawn(C_3c);
-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy.soundclick
local function C_3d()
local script = G2L["3d"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_3d);
-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy.LocalScript
local function C_42()
local script = G2L["42"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		if setclipboard then
			setclipboard("omargamer8198")
			game.StarterGui:SetCore("SendNotification", {
				Title = "Success!",
				Text = "Copied Youtube Link",
				Duration = 3
			})
		else
			warn("Clipboard function not available.")
		end
	end)
	
end;
task.spawn(C_42);
-- StarterGui.omarCRazyShooter.sigma.MiscFrame.Copy.soundclick
local function C_43()
local script = G2L["43"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_43);
-- StarterGui.omarCRazyShooter.sigma.MiscFrame.AutoEsp.soundclick
local function C_47()
local script = G2L["47"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_47);
-- StarterGui.omarCRazyShooter.sigma.MiscFrame.AutoEsp.LocalScript
local function C_48()
local script = G2L["48"];
	--!strict
	local button    = script.Parent :: TextButton
	local parentFrm = button.Parent    :: Frame
	local inputBox  = parentFrm:WaitForChild("after")   :: TextBox
	
	-- Ensure a UIStroke on the button
	local stroke = button:FindFirstChildWhichIsA("UIStroke")
	if not stroke then
		stroke = Instance.new("UIStroke")
		stroke.Thickness = 2
		stroke.Parent = button
	end
	local originalColor = stroke.Color
	
	-- RemoteEvent
	local oreServiceRE = game:GetService("ReplicatedStorage")
		:WaitForChild("Packages")
		:WaitForChild("Knit")
		:WaitForChild("Services")
		:WaitForChild("OreService")
		:WaitForChild("RE")
		:WaitForChild("LockItem") :: RemoteEvent
	
	-- Notification helper
	local StarterGui = game:GetService("StarterGui")
	local function notify(msg: string)
		StarterGui:SetCore("SendNotification", {
			Title    = "Invalid Input",
			Text     = msg,
			Duration = 3,
		})
	end
	
	-- State
	local isOn = false
	local loopTask
	
	-- Parse “k” suffix to number
	local function parseThreshold(str: string): number?
		str = str:lower():gsub("%s+", "")
		if str:match("k$") then
			local n = tonumber(str:sub(1, -2))
			if n then return n * 1000 end
		end
		return tonumber(str)
	end
	
	-- Validate input on focus lost
	inputBox.FocusLost:Connect(function(enterPressed)
		local raw = inputBox.Text
		local num = parseThreshold(raw) or 0
		if num < 1000 then
			inputBox.Text = ""
			notify("You can’t put any values under 1k.")
		end
	end)
	
	-- The scanning loop
	local function startLoop(minChance: number)
		loopTask = task.spawn(function()
			local Players = game:GetService("Players")
			local seen = {} :: {[Instance]: boolean}
			while isOn do
				local backpack = Players.LocalPlayer:WaitForChild("Backpack")
				for _, tool in ipairs(backpack:GetChildren()) do
					if tool:IsA("Tool") then
						local chance = tool:GetAttribute("Chance")
						local locked = tool:GetAttribute("Locked")
						if typeof(chance) == "number"
							and chance >= minChance
							and not locked
							and not seen[tool] then
	
							seen[tool] = true
							oreServiceRE:FireServer(tool)
						end
					end
				end
				task.wait(1)
			end
		end)
	end
	
	-- Button click toggles ON/OFF
	button.MouseButton1Click:Connect(function()
		if not isOn then
			-- OFF → ON
			isOn = true
			stroke.Color     = Color3.fromRGB(0,255,0)
			inputBox.Visible = true
	
			-- Read threshold (default to 1000 if empty/invalid)
			local num = parseThreshold(inputBox.Text) or 1000
			if num < 1000 then num = 1000 end
	
			startLoop(num)
		else
			-- ON → OFF
			isOn = false
			if loopTask then
				task.cancel(loopTask)
				loopTask = nil
			end
	
			stroke.Color     = originalColor
			inputBox.Visible = false
		end
	end)
	
	-- INITIAL STATE: hidden textbox
	inputBox.Visible = false
	
end;
task.spawn(C_48);
-- StarterGui.omarCRazyShooter.Toggle.LocalScript
local function C_4b()
local script = G2L["4b"];
	local button = script.Parent -- The TextButton inside the Bubble Gum GUI
	local bubbleGumGui = game.Players.LocalPlayer.PlayerGui:WaitForChild("omarCRazyShooter") -- Reference to the Bubble Gum GUI
	local frame = bubbleGumGui:WaitForChild("sigma") -- The Frame named 'All' inside the Bubble Gum GUI
	
	button.MouseButton1Click:Connect(function()
		if frame.Visible then
			frame.Visible = false
			button.Text = "Show"
		else
			frame.Visible = true
			button.Text = "Hide"
		end
	end)
	
end;
task.spawn(C_4b);
-- StarterGui.omarCRazyShooter.Changer
local function C_4d()
local script = G2L["4d"];
	-- LocalScript: UISelectionController (Esp & Misc Only)
	print("[UISelectionController] Script initializing...")
	
	-- Find the parent ScreenGui
	local screenGui = script:FindFirstAncestorWhichIsA("ScreenGui")
	if not screenGui then
		warn("[UISelectionController] ERROR: Not inside a ScreenGui!")
		return
	end
	print("[UISelectionController] Found ScreenGui: " .. screenGui.Name)
	
	-- Grab Sigma and Selection
	local sigma = screenGui:FindFirstChild("sigma")
	if not sigma then
		warn("[UISelectionController] ERROR: Sigma frame not found under ScreenGui")
		return
	end
	print("[UISelectionController] Found Sigma: " .. sigma.Name)
	
	local selection = sigma:FindFirstChild("Selection")
	if not selection then
		warn("[UISelectionController] ERROR: Selection frame not found under Sigma")
		return
	end
	print("[UISelectionController] Found Selection: " .. selection.Name)
	
	-- Define active tabs only: Esp and Misc
	local tabs = {
		Esp  = {buttonName = "Esp",  frameName = "EspFrame"},
		Misc = {buttonName = "Misc", frameName = "MiscFrame"},
	}
	
	-- Prepare storage
	local activeKey
	local defaultStrokes = {}
	
	-- Initialize each tab
	for key, def in pairs(tabs) do
		local btn = selection:FindFirstChild(def.buttonName)
		if not btn or not btn:IsA("TextButton") then
			warn(string.format("[UISelectionController] ERROR: %s button '%s' not found or not a TextButton", key, def.buttonName))
		else
			print(string.format("[UISelectionController] Found button '%s' for %s", def.buttonName, key))
		end
	
		local frm = sigma:FindFirstChild(def.frameName)
		if not frm or not frm:IsA("Frame") then
			warn(string.format("[UISelectionController] ERROR: %s frame '%s' not found or not a Frame", key, def.frameName))
		else
			print(string.format("[UISelectionController] Found frame '%s' for %s", def.frameName, key))
		end
	
		local stroke = btn:FindFirstChildOfClass("UIStroke") or Instance.new("UIStroke", btn)
		defaultStrokes[key] = stroke.Color
	
		if frm then frm.Visible = false end
	
		def.button = btn
		def.frame  = frm
		def.stroke = stroke
	end
	
	-- Tab switch function
	local function switchTo(key)
		print("[UISelectionController] switchTo called for " .. key)
		if activeKey and tabs[activeKey].stroke then
			tabs[activeKey].stroke.Color = defaultStrokes[activeKey]
			if tabs[activeKey].frame then tabs[activeKey].frame.Visible = false end
			print("[UISelectionController] Hiding frame for " .. activeKey)
		end
	
		local current = tabs[key]
		if not current then
			warn("[UISelectionController] ERROR: No tab definition for key " .. key)
			return
		end
		current.stroke.Color = Color3.new(1, 0, 0)
		if current.frame then current.frame.Visible = true end
		print("[UISelectionController] Showing frame for " .. key)
		activeKey = key
	end
	
	-- Connect tab buttons
	for key, def in pairs(tabs) do
		if def.button then
			def.button.Activated:Connect(function()
				print("[UISelectionController] Button " .. def.buttonName .. " activated")
				switchTo(key)
			end)
			print("[UISelectionController] Connected Activated for " .. def.buttonName)
		end
	end
	
	-- Auto-open Esp tab
	switchTo("Esp")
	
end;
task.spawn(C_4d);
-- StarterGui.omarCRazyShooter.LocalScript
local function C_4e()
local script = G2L["4e"];
	local Players = game:GetService("Players")
	local StarterGui = game:GetService("StarterGui")
	local UserInputService = game:GetService("UserInputService")
	local RunService = game:GetService("RunService")
	local player = Players.LocalPlayer
	local camera = workspace.CurrentCamera
	
	-- Function to send notifications
	local function sendNotif(title, text, duration)
		pcall(function()
			StarterGui:SetCore("SendNotification", {
				Title = title,
				Text = text,
				Duration = duration,
				Button1 = "OK"
			})
		end)
	end
	
	-- Show credit message to all players
	sendNotif("📢 CREDITS", "✅ Made by omar_gamer", 5)
	
	-- Only for PC players
	if UserInputService.KeyboardEnabled and not UserInputService.TouchEnabled then
		sendNotif("🔓 MOUSE CONTROL", "📌 PRESS [ B ] TO UNLOCK YOUR MOUSE\n📌 PRESS AGAIN TO LOCK IT BACK", math.huge)
	
		local mouseUnlocked = false
	
		local function applyMouseState()
			if mouseUnlocked then
				UserInputService.MouseBehavior = Enum.MouseBehavior.Default
				UserInputService.MouseIconEnabled = true
				camera.CameraType = Enum.CameraType.Custom
			else
				UserInputService.MouseBehavior = Enum.MouseBehavior.LockCenter
				UserInputService.MouseIconEnabled = false
				camera.CameraType = Enum.CameraType.Custom
			end
		end
	
		UserInputService.InputBegan:Connect(function(input, gameProcessed)
			if gameProcessed then return end
			if input.KeyCode == Enum.KeyCode.B then
				mouseUnlocked = not mouseUnlocked
				applyMouseState()
			end
		end)
	
		-- Keep forcing third-person and correct mouse state
		RunService.Heartbeat:Connect(function()
			if camera.CameraType ~= Enum.CameraType.Custom then
				camera.CameraType = Enum.CameraType.Custom
			end
			if mouseUnlocked and UserInputService.MouseBehavior ~= Enum.MouseBehavior.Default then
				applyMouseState()
			end
		end)
	end
	
end;
task.spawn(C_4e);

return G2L["1"], require;
