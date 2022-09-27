# Atlas-LUA
***Natives***

We support most of the natives here: https://docs.fivem.net/natives/
Not CFX Namespace


***Functions***

```
rage.joaat(string name)
> return hash
```

- **players**
```
get_player_selected.player_id()

get_player_selected.net_game_player()

get_player_selected.CPed()

returns selected player from player list
```



- **scrips**
```
util.find_script_thread(rage::joaat_t hash)
> returns script thread
```



- **netword manager**
```
util.get_network_player_mgr()

util.get_network_player_mgr.player_limit()

util.get_network_player_mgr.get_name(int id)

util.get_network_player_mgr.get_player_info(int id)
```



- **Globals**
```
SCRIPT.SET_GLOBAL_INT(string index, int i)

SCRIPT.SET_GLOBAL_FLOAT(string index, float f)

SCRIPT.GET_GLOBAL_INT(string index, int i)

SCRIPT.GET_GLOBAL_FLOAT(string index, float f)
```



- **Menu**
```
g_running() 
> Menu Running bool, if set to false menu unloads

Unload()

exit()

Notification(string title, string message)

g_gui.rect(float posx, float posy, float sizew, float sizeh, int r, int g, int b, int a)

g_gui.text(string text, float posx, float posy, float sizew, float sizeh, bool center)

g_gui.is_open()

Log.Info(string log)

Log.Error(string log)

script.yield();

os.Sleep(time)

GetAsyncKeyState(int key)

GetTickCount()

GetTickCount64()
```


- **MISC**
```
SET_SPAWN_BYPASS() 
> Make sure you restore after object is spawned

RESTORE_SPAWN_BYPASS()
> These natives already have model spawn bypass: 
    CREATE_PED | CREATE_OBJECT_NO_OFFSET | CREATE_OBJECT | CREATE_VEHICLE
```
