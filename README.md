# other-things

I own **some** of these, Not all of them are mine.

Cool UI Lib V3RM Thread: 
Cool UI Lib: 
```
loadstring(game:HttpGet('https://raw.githubusercontent.com/DisguisedFox94/other-things/main/cool-uilib.lua'))()
```
Create a UI: Lib.UI(Name)
Create a tab: UI:Tab(Name, Icon)
Create a container: Tab:Container(Name) 
Create a button: Container:Button(Name, Callback) [no return]
Create a toggle: Container:Toggle(Name, StartingState, Callback) [returns state]
Create a dropdown: Container:Dropdown(Name, List [contains strings], Callback) [returns selected string from table]
Create a label: Container:Label(Text) [no return]
Create a keybind: Container:Keybind(Name, Starting_Key, Blacklisted_Keys [contains strings], Callback) [returns key string form (example: "A")]
Create a textbox: Container:TextBox(Name, Callback) [returns text in textbox]
Create a slider: Container:Slider(Name, Min, Max, Start, Callback, Use_Decimals) [returns selected number]
Create a notification: Lib:Notification(Title, Info, Icon, Duration) [limit of 5 notifications being shown (can be edited in source)]
