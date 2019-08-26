
# How to get wifi passwords that are saved in your computer:


## ***First: how to show the networks that your computer connected to:***

1. Click on Windows icon and type *run*, or you can press simultaneously on Windows button on your keyboard with R (Win + R)

![Windows_run](https://user-images.githubusercontent.com/54427734/63726579-45aeb980-c823-11e9-93bc-77f567dcbf04.jpg)

2. The **Run** window will open. Type *cmd* and click enter.

![run](https://user-images.githubusercontent.com/54427734/63723753-e26d5900-c81b-11e9-98a6-d794d925e7ef.JPG)

3. When the Command Line opens, type the following command and click enter

```
netsh wlan show profile
```
![run_cmd](https://user-images.githubusercontent.com/54427734/63723751-e1d4c280-c81b-11e9-9954-a5cbe7f21b9c.JPG)

4. As you can see above, there are two networks that my computer already connected to. You can choose any network and use it in the next step to get its saved password. 


## ***Second: how to get the saved password for a selected network:***

- In the **Command Line**, type the following command with the network name instead of "*****"
```
netsh wlan show profile "*****" key = clear
```
- In my case, I am going to get the saved password for my Suddenlink SSID

![netsh wlan](https://user-images.githubusercontent.com/54427734/63726575-45162300-c823-11e9-8edd-0927721d22af.JPG)

- Once you type the command and click enter, you will get some information about the network. You can see the password beside key content

![security key](https://user-images.githubusercontent.com/54427734/63726906-3b40ef80-c824-11e9-8f79-a1015cde674e.JPG)



### Many internet service providers give you their router that is protected by a security key, which cannot be changed except by the provider, and it's hard to memorize it and usually get lost. By this way, you can show the password of your network in case you want to use it in another device.



Here is my Linked profile. 
[https://www.linkedin.com/in/ali-alali-a4067096/](https://www.linkedin.com/in/ali-alali-a4067096/)
