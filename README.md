# other-things

I own **some** of these, Not all of them are mine.

Cool UI Lib V3RM Thread: https://v3rmillion.net/showthread.php?tid=1151036
Cool UI Lib: ![image](https://user-images.githubusercontent.com/77709966/147716823-c4363cce-9de7-4cda-9f59-33734429b426.png)

Loadstring:
```
loadstring(game:HttpGet('https://raw.githubusercontent.com/DisguisedFox94/other-things/main/cool-uilib.lua'))()
```
Instructions:
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
```
