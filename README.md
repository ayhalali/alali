
# How to get the saved wifi passwords in your computer:

## 
## ***First: how to show the networks that your computer connected to:***

1. Click on Windows icon and type Run, or you can press simultaneously on Windows button on your keyboard with R (Win + R)


2. The **Run** window will open. Type "cmd" and click enter.


3. When the Command Line opens, type the following command and click enter
```
netsh wlan show profile
```

4. As you can see above, there are two networks that my computer already connected to. You can choose any network and use it in the next step to get its saved password. 

## 
## ***Second: how to get the saved password for a selected network:***

- In the **Command Line**, type the following command with the network name instead of "*****"
```
netsh wlan show profile "*****" key = clear
```

-

-

[Help](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)
