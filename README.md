local Scripts = {
    [994732206] = "https://pastefy.app/YGzmdl9d/raw",
}

local url = Scripts[game.GameId]
if url then
    loadstring(game:HttpGet(url))()
end
