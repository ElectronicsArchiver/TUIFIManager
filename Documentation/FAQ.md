
# FAQ
 
***How do I enable vim_mode ?***
> Set `tuifi_vim_mode` enviroment variable to `True`

***How do I map keys in vim_mode?***
> This ain't possible right now althought you could play around with the content of `toggle_vim_mode` function under `__init__.py`

***How do I set the default editor ?***
> Set `tuifi_default_editor` enviroment variable to `vim` or whatever you prefer

***How do I toggle hidden files/folders?***
> Edit `__main__.py` and specify `suffixes=['*','.*']` for hidden files. [THIS NEEDS TO BE FIXED]

***How do I change the default colors?***
> A bit complicated to explain here just make an issue and I will explain it there
