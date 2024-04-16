-- Fluxus New Made By @Truongdepzai✨ (OK)

local synversion = "Made By Truongdepzai✨"

-- this shit function makes my script fucked
--[[pcall(function()
    local HttpService = game:GetService("HttpService")
    local response = game:HttpGet("https://api.whatexploitsare.online/status")
    local data = HttpService:JSONDecode(response)

    for _, item in pairs(data) do
        if item.Synapse then
            synversion = item.Synapse.exploit_version
	end
    end
end)]]

-- Instances: 150 | Scripts: 8 | Modules: 4
local G2L = {};
-- StarterGui.SynapseX
G2L["1"] = Instance.new("ScreenGui", game:GetService("CoreGui"));
G2L["1"]["Name"] = [[SynapseX]];
G2L["1"]["ResetOnSpawn"] = false;

-- StarterGui.SynapseX.FloatingIcon
G2L["2"] = Instance.new("ImageButton", G2L["1"]);
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["2"]["Size"] = UDim2.new(0, 36, 0, 36);
G2L["2"]["Name"] = [[FloatingIcon]];
G2L["2"].Visible = false
G2L["2"]["Position"] = UDim2.new(0.7019911956787109, 0, 0.7092568278312683, 0);

-- StarterGui.SynapseX.FloatingIcon. 
G2L["3"] = Instance.new("ImageLabel", G2L["2"]);
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3"]["Image"] = [[http://www.roblox.com/asset/?id=17144388952]];
G2L["3"]["Size"] = UDim2.new(0, 23, 0, 26);
G2L["3"]["Name"] = [[ ]];
G2L["3"]["BackgroundTransparency"] = 1;
G2L["3"]["Position"] = UDim2.new(0.16640418767929077, 0, 0.13268542289733887, 0);

-- StarterGui.SynapseX.FloatingIcon.UICorner
G2L["4"] = Instance.new("UICorner", G2L["2"]);
G2L["4"]["CornerRadius"] = UDim.new(1, 8);

-- StarterGui.SynapseX.FloatingIcon.UIGradient
G2L["5"] = Instance.new("UIGradient", G2L["2"]);
G2L["5"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.720, Color3.fromRGB(0, 0, 0)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};

-- StarterGui.SynapseX.Main
G2L["6"] = Instance.new("Frame", G2L["1"]);
G2L["6"]["Active"] = true;
G2L["6"]["ZIndex"] = 4;
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(71, 71, 71);
G2L["6"]["BackgroundTransparency"] = 1;
G2L["6"]["Size"] = UDim2.new(0, 646, 0, 283);
G2L["6"]["Position"] = UDim2.new(0, 19, 0, 23);
G2L["6"]["Name"] = [[Main]];

-- StarterGui.SynapseX.Main.Icon
G2L["7"] = Instance.new("ImageLabel", G2L["6"]);
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["Image"] = [[http://www.roblox.com/asset/?id=17144388952]];
G2L["7"]["Size"] = UDim2.new(0, 23, 0, 26);
G2L["7"]["Name"] = [[Icon]];
G2L["7"]["BackgroundTransparency"] = 1;
G2L["7"]["Position"] = UDim2.new(0, 5, 0, 0);

-- StarterGui.SynapseX.Main.Background
G2L["8"] = Instance.new("ImageLabel", G2L["6"]);
G2L["8"]["ZIndex"] = 0;
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["ScaleType"] = Enum.ScaleType.Tile;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(52, 52, 52);
G2L["8"]["TileSize"] = UDim2.new(0, 25, 0, 25);
G2L["8"]["Size"] = UDim2.new(0, 647, 0, 283);
G2L["8"]["Name"] = [[Background]];

-- StarterGui.SynapseX.Main.Panel
G2L["9"] = Instance.new("Frame", G2L["6"]);
G2L["9"]["ZIndex"] = 0;
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["9"]["Size"] = UDim2.new(0, 647, 0, 27);
G2L["9"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["Name"] = [[Panel]];

-- StarterGui.SynapseX.Main.MainFunc
G2L["a"] = Instance.new("Frame", G2L["6"]);
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["BackgroundTransparency"] = 1;
G2L["a"]["Size"] = UDim2.new(0, 100, 0, 100);
G2L["a"]["Name"] = [[MainFunc]];

-- StarterGui.SynapseX.Main.MainFunc.Needs
G2L["b"] = Instance.new("Folder", G2L["a"]);
G2L["b"]["Name"] = [[Needs]];

-- StarterGui.SynapseX.Main.MainFunc.Needs.Tab
G2L["c"] = Instance.new("TextButton", G2L["b"]);
G2L["c"]["ZIndex"] = 0;
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(101, 101, 101);
G2L["c"]["TextSize"] = 14;
G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["Visible"] = false;
G2L["c"]["Size"] = UDim2.new(0, 56, 0, 16);
G2L["c"]["Name"] = [[Tab]];
G2L["c"]["Text"] = [[  Script 1]];
G2L["c"]["Position"] = UDim2.new(-0.0003878306597471237, 0, -0.011710520833730698, 0);
G2L["c"]["BackgroundTransparency"] = 0.10000000149011612;

-- StarterGui.SynapseX.Main.MainFunc.Needs.Tab.Remove
G2L["d"] = Instance.new("TextButton", G2L["c"]);
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(101, 101, 101);
G2L["d"]["TextSize"] = 15;
G2L["d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["Size"] = UDim2.new(0, 10, 0, 10);
G2L["d"]["Name"] = [[Remove]];
G2L["d"]["BorderColor3"] = Color3.fromRGB(28, 43, 54);
G2L["d"]["Text"] = [[x]];
G2L["d"]["Position"] = UDim2.new(0, 46, 0, 2);
G2L["d"]["BackgroundTransparency"] = 1;

-- StarterGui.SynapseX.Main.MainFunc.Needs.ScriptHubButton
G2L["e"] = Instance.new("TextButton", G2L["b"]);
G2L["e"]["ZIndex"] = 3;
G2L["e"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["e"]["TextSize"] = 14;
G2L["e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["Visible"] = false;
G2L["e"]["Size"] = UDim2.new(0, 96, 0, 15);
G2L["e"]["Name"] = [[ScriptHubButton]];
G2L["e"]["BorderColor3"] = Color3.fromRGB(61, 61, 61);
G2L["e"]["Text"] = [[test.lua]];
G2L["e"]["AutomaticSize"] = Enum.AutomaticSize.X;
G2L["e"]["Position"] = UDim2.new(0.039603959769010544, 0, 0, 0);

-- StarterGui.SynapseX.Main.MainFunc.Needs.Textbox
G2L["f"] = Instance.new("ScrollingFrame", G2L["b"]);
G2L["f"]["Active"] = true;
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["CanvasSize"] = UDim2.new(0, 0, 0, 0);
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(41, 41, 41);
G2L["f"]["AutomaticCanvasSize"] = Enum.AutomaticSize.XY;
G2L["f"]["Size"] = UDim2.new(0, 533, 0, 197);
G2L["f"]["Position"] = UDim2.new(0.05999999865889549, 0, 0.48061829805374146, 0);
G2L["f"]["Visible"] = false;
G2L["f"]["Name"] = [[Textbox]];

-- StarterGui.SynapseX.Main.MainFunc.Needs.Textbox.Frame
G2L["10"] = Instance.new("Frame", G2L["f"]);
G2L["10"]["Active"] = true;
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(41, 41, 41);
G2L["10"]["Size"] = UDim2.new(0, 533, 0, 200);
G2L["10"]["Selectable"] = true;
G2L["10"]["ClipsDescendants"] = true;
G2L["10"]["AutomaticSize"] = Enum.AutomaticSize.XY;
G2L["10"]["SelectionGroup"] = true;

-- StarterGui.SynapseX.Main.MainFunc.Needs.Textbox.Frame.Textbox
G2L["11"] = Instance.new("TextBox", G2L["10"]);
G2L["11"]["ZIndex"] = 4;
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["TextSize"] = 14;
G2L["11"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["11"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(41, 41, 41);
G2L["11"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["11"]["MultiLine"] = true;
G2L["11"]["Size"] = UDim2.new(0, 486, 0, 194);
G2L["11"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["Text"] = [[]];
G2L["11"]["Position"] = UDim2.new(0, 35, 0, 0);
G2L["11"]["AutomaticSize"] = Enum.AutomaticSize.XY;
G2L["11"]["Name"] = [[Textbox]];
G2L["11"]["ClearTextOnFocus"] = false;

-- StarterGui.SynapseX.Main.MainFunc.Needs.Textbox.Frame.Linebar
G2L["12"] = Instance.new("Frame", G2L["10"]);
G2L["12"]["ZIndex"] = 2;
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(36, 36, 36);
G2L["12"]["Size"] = UDim2.new(0, 32, 1, 0);
G2L["12"]["Name"] = [[Linebar]];

-- StarterGui.SynapseX.Main.MainFunc.Needs.Textbox.Frame.Linebar.LineText
G2L["13"] = Instance.new("TextLabel", G2L["12"]);
G2L["13"]["ZIndex"] = 5;
G2L["13"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["TextXAlignment"] = Enum.TextXAlignment.Right;
G2L["13"]["FontFace"] = Font.new([[rbxasset://fonts/families/Inconsolata.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["13"]["TextSize"] = 14;
G2L["13"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["Size"] = UDim2.new(0, 24, 0, 197);
G2L["13"]["Text"] = [[1]];
G2L["13"]["Name"] = [[LineText]];
G2L["13"]["BackgroundTransparency"] = 1;

-- StarterGui.SynapseX.Main.MainFunc.Needs.Textbox.Frame.Highlighted
G2L["14"] = Instance.new("Frame", G2L["10"]);
G2L["14"]["ZIndex"] = 5;
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(101, 101, 101);
G2L["14"]["BackgroundTransparency"] = 0.699999988079071;
G2L["14"]["Size"] = UDim2.new(1.0958691835403442, 0, 0, 13);
G2L["14"]["Position"] = UDim2.new(0, -44, 0, 0);
G2L["14"]["AutomaticSize"] = Enum.AutomaticSize.X;
G2L["14"]["Name"] = [[Highlighted]];

-- StarterGui.SynapseX.Main.MainFunc.Needs.Textbox.Frame.Highlighted.LineText
G2L["15"] = Instance.new("TextLabel", G2L["14"]);
G2L["15"]["ZIndex"] = 5;
G2L["15"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["TextXAlignment"] = Enum.TextXAlignment.Right;
G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["15"]["TextTransparency"] = 1;
G2L["15"]["TextSize"] = 14;
G2L["15"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["Size"] = UDim2.new(0, 24, 0, 197);
G2L["15"]["Text"] = [[1]];
G2L["15"]["Name"] = [[LineText]];
G2L["15"]["Visible"] = false;
G2L["15"]["BackgroundTransparency"] = 1;

-- StarterGui.SynapseX.Main.MainFunc.Textboxes
G2L["16"] = Instance.new("Folder", G2L["a"]);
G2L["16"]["Name"] = [[Textboxes]];

-- StarterGui.SynapseX.Main.MainFunc.ScriptHub
G2L["17"] = Instance.new("ScrollingFrame", G2L["a"]);
G2L["17"]["Active"] = true;
G2L["17"]["ZIndex"] = 2;
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["17"]["AutomaticCanvasSize"] = Enum.AutomaticSize.XY;
G2L["17"]["Size"] = UDim2.new(0, 101, 0, 215);
G2L["17"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["17"]["Position"] = UDim2.new(5.420000076293945, 0, 0.30000001192092896, 0);
G2L["17"]["Name"] = [[ScriptHub]];

-- StarterGui.SynapseX.Main.MainFunc.ScriptHub.UIListLayout
G2L["18"] = Instance.new("UIListLayout", G2L["17"]);
G2L["18"]["SortOrder"] = Enum.SortOrder.LayoutOrder;

-- StarterGui.SynapseX.Main.MainFunc.ScriptHub.UIPadding
G2L["19"] = Instance.new("UIPadding", G2L["17"]);
G2L["19"]["PaddingLeft"] = UDim.new(0.05000000074505806, 0);

-- StarterGui.SynapseX.Main.Maximize
G2L["1a"] = Instance.new("ImageButton", G2L["6"]);
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["1a"]["Size"] = UDim2.new(0, 15, 0, 15);
G2L["1a"]["Name"] = [[Maximize]];
G2L["1a"]["BorderColor3"] = Color3.fromRGB(99, 150, 182);
G2L["1a"]["Position"] = UDim2.new(0, 606, 0, 2);

-- StarterGui.SynapseX.Main.Maximize.NameText
G2L["1b"] = Instance.new("TextLabel", G2L["1a"]);
G2L["1b"]["TextWrapped"] = true;
G2L["1b"]["ZIndex"] = 2;
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(0, 55, 81);
G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1b"]["TextSize"] = 12;
G2L["1b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["Size"] = UDim2.new(0, 15, 0, 15);
G2L["1b"]["Active"] = true;
G2L["1b"]["Text"] = [[M]];
G2L["1b"]["Name"] = [[NameText]];
G2L["1b"]["BackgroundTransparency"] = 1;

-- StarterGui.SynapseX.Main.Maximize.ImageButton
G2L["1c"] = Instance.new("ImageButton", G2L["1a"]);
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(0, 55, 81);
G2L["1c"]["Size"] = UDim2.new(0, 15, 0, 15);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(99, 150, 182);
G2L["1c"]["Visible"] = false;
G2L["1c"]["BackgroundTransparency"] = 0.6000000238418579;

-- StarterGui.SynapseX.Main.Maximize.UICorner
G2L["1d"] = Instance.new("UICorner", G2L["1a"]);
G2L["1d"]["CornerRadius"] = UDim.new(0, 0);

-- StarterGui.SynapseX.Main.TitleSynapse
G2L["1e"] = Instance.new("TextLabel", G2L["6"]);
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1e"]["TextSize"] = 15;
G2L["1e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["Size"] = UDim2.new(0, 646, 0, 27);
G2L["1e"]["Text"] = "Fluxus New - "..synversion;
G2L["1e"]["Name"] = [[TitleSynapse]];
G2L["1e"]["BackgroundTransparency"] = 1;

-- StarterGui.SynapseX.Main.ScriptHub
G2L["1f"] = Instance.new("ImageButton", G2L["6"]);
G2L["1f"]["BorderSizePixel"] = 0;
G2L["1f"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["1f"]["Size"] = UDim2.new(0, 82, 0, 27);
G2L["1f"]["Name"] = [[ScriptHub]];
G2L["1f"]["BorderColor3"] = Color3.fromRGB(99, 150, 182);
G2L["1f"]["Position"] = UDim2.new(0, 560, 0, 250);

-- StarterGui.SynapseX.Main.ScriptHub.NameText
G2L["20"] = Instance.new("TextLabel", G2L["1f"]);
G2L["20"]["TextWrapped"] = true;
G2L["20"]["ZIndex"] = 2;
G2L["20"]["BorderSizePixel"] = 0;
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["20"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["20"]["TextSize"] = 14;
G2L["20"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["20"]["Size"] = UDim2.new(0, 82, 0, 27);
G2L["20"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["20"]["Text"] = [[Script Hub]];
G2L["20"]["Name"] = [[NameText]];
G2L["20"]["BackgroundTransparency"] = 1;

-- StarterGui.SynapseX.Main.ScriptHub.ImageButton
G2L["21"] = Instance.new("ImageButton", G2L["1f"]);
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(0, 55, 81);
G2L["21"]["Size"] = UDim2.new(0, 82, 0, 27);
G2L["21"]["BorderColor3"] = Color3.fromRGB(99, 150, 182);
G2L["21"]["Visible"] = false;
G2L["21"]["BackgroundTransparency"] = 0.6000000238418579;

-- StarterGui.SynapseX.Main.ScriptHub.UICorner
G2L["22"] = Instance.new("UICorner", G2L["1f"]);
G2L["22"]["CornerRadius"] = UDim.new(0, 0);

-- StarterGui.SynapseX.Main.Options
G2L["23"] = Instance.new("ImageButton", G2L["6"]);
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["23"]["Size"] = UDim2.new(0, 82, 0, 27);
G2L["23"]["Name"] = [[Options]];
G2L["23"]["BorderColor3"] = Color3.fromRGB(99, 150, 182);
G2L["23"]["Position"] = UDim2.new(0, 352, 0, 250);

-- StarterGui.SynapseX.Main.Options.NameText
G2L["24"] = Instance.new("TextLabel", G2L["23"]);
G2L["24"]["TextWrapped"] = true;
G2L["24"]["ZIndex"] = 2;
G2L["24"]["BorderSizePixel"] = 0;
G2L["24"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["24"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["24"]["TextSize"] = 14;
G2L["24"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["24"]["Size"] = UDim2.new(0, 82, 0, 27);
G2L["24"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["24"]["Text"] = [[Options]];
G2L["24"]["Name"] = [[NameText]];
G2L["24"]["BackgroundTransparency"] = 1;

-- StarterGui.SynapseX.Main.Options.ImageButton
G2L["25"] = Instance.new("ImageButton", G2L["23"]);
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(0, 55, 81);
G2L["25"]["Size"] = UDim2.new(0, 82, 0, 27);
G2L["25"]["BorderColor3"] = Color3.fromRGB(99, 150, 182);
G2L["25"]["Visible"] = false;
G2L["25"]["BackgroundTransparency"] = 0.6000000238418579;

-- StarterGui.SynapseX.Main.Options.UICorner
G2L["26"] = Instance.new("UICorner", G2L["23"]);
G2L["26"]["CornerRadius"] = UDim.new(0, 0);

-- StarterGui.SynapseX.Main.Minimize
G2L["27"] = Instance.new("ImageButton", G2L["6"]);
G2L["27"]["BorderSizePixel"] = 0;
G2L["27"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["27"]["Size"] = UDim2.new(0, 15, 0, 15);
G2L["27"]["Name"] = [[Minimize]];
G2L["27"]["BorderColor3"] = Color3.fromRGB(99, 150, 182);
G2L["27"]["Position"] = UDim2.new(0, 582, 0, 2);

-- StarterGui.SynapseX.Main.Minimize.NameText
G2L["28"] = Instance.new("TextLabel", G2L["27"]);
G2L["28"]["TextWrapped"] = true;
G2L["28"]["ZIndex"] = 2;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(0, 55, 81);
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["28"]["TextSize"] = 15;
G2L["28"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["28"]["Size"] = UDim2.new(0, 15, 0, 15);
G2L["28"]["Active"] = true;
G2L["28"]["Text"] = [[_]];
G2L["28"]["Name"] = [[NameText]];
G2L["28"]["BackgroundTransparency"] = 1;

-- StarterGui.SynapseX.Main.Minimize.ImageButton
G2L["29"] = Instance.new("ImageButton", G2L["27"]);
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(0, 55, 81);
G2L["29"]["Size"] = UDim2.new(0, 15, 0, 15);
G2L["29"]["BorderColor3"] = Color3.fromRGB(99, 150, 182);
G2L["29"]["Visible"] = false;
G2L["29"]["BackgroundTransparency"] = 0.6000000238418579;

-- StarterGui.SynapseX.Main.Minimize.UICorner
G2L["2a"] = Instance.new("UICorner", G2L["27"]);
G2L["2a"]["CornerRadius"] = UDim.new(0, 0);

-- StarterGui.SynapseX.Main.Execute
G2L["2b"] = Instance.new("ImageButton", G2L["6"]);
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["2b"]["Size"] = UDim2.new(0, 82, 0, 27);
G2L["2b"]["Name"] = [[Execute]];
G2L["2b"]["BorderColor3"] = Color3.fromRGB(99, 150, 182);
G2L["2b"]["Position"] = UDim2.new(0, 6, 0, 250);

-- StarterGui.SynapseX.Main.Execute.NameText
G2L["2c"] = Instance.new("TextLabel", G2L["2b"]);
G2L["2c"]["TextWrapped"] = true;
G2L["2c"]["ZIndex"] = 2;
G2L["2c"]["BorderSizePixel"] = 0;
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["2c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2c"]["TextSize"] = 14;
G2L["2c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["Size"] = UDim2.new(0, 82, 0, 27);
G2L["2c"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["Text"] = [[Execute]];
G2L["2c"]["Name"] = [[NameText]];
G2L["2c"]["BackgroundTransparency"] = 1;

-- StarterGui.SynapseX.Main.Execute.ImageButton
G2L["2d"] = Instance.new("ImageButton", G2L["2b"]);
G2L["2d"]["BackgroundColor3"] = Color3.fromRGB(0, 55, 81);
G2L["2d"]["Size"] = UDim2.new(0, 82, 0, 27);
G2L["2d"]["BorderColor3"] = Color3.fromRGB(99, 150, 182);
G2L["2d"]["Visible"] = false;
G2L["2d"]["BackgroundTransparency"] = 0.6000000238418579;

-- StarterGui.SynapseX.Main.Execute.UICorner
G2L["2e"] = Instance.new("UICorner", G2L["2b"]);
G2L["2e"]["CornerRadius"] = UDim.new(0, 0);

-- StarterGui.SynapseX.Main.SaveFile
G2L["2f"] = Instance.new("ImageButton", G2L["6"]);
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["2f"]["Size"] = UDim2.new(0, 82, 0, 27);
G2L["2f"]["Name"] = [[SaveFile]];
G2L["2f"]["BorderColor3"] = Color3.fromRGB(99, 150, 182);
G2L["2f"]["Position"] = UDim2.new(0, 266, 0, 250);

-- StarterGui.SynapseX.Main.SaveFile.NameText
G2L["30"] = Instance.new("TextLabel", G2L["2f"]);
G2L["30"]["TextWrapped"] = true;
G2L["30"]["ZIndex"] = 2;
G2L["30"]["BorderSizePixel"] = 0;
G2L["30"]["BackgroundColor3"] = Color3.fromRGB(61, 61, 61);
G2L["30"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["30"]["TextSize"] = 14;
G2L["30"]["Tex