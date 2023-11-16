## 介绍请转至以下链接查看：
https://github.com/rxrw/daily_morning  (Has been disabled)


# 'Cause the formal blog has been closed, I just wanna introduce it roughly

1. In the "Settings", you'd better click the button "Secrets", then "Actions", click the button "New repository secret" in the upper right corner
![image](https://user-images.githubusercontent.com/55289804/199138872-05e44f31-917b-4c87-87e3-3ff586771b36.png)

2. Add these params:
 
    1). app_id: the appid of WeChat Test Number.
  
    2). app_secret: the appsecret of WeChat Test Number.

    3). template_id: the test number's id.  

    4). user_id: Who wanna receive the message alert, must scan the QR firstly. (The four params' url is: [微信测试平台](https://mp.weixin.qq.com/debug/cgi-bin/sandbox?t=sandbox/index))

   ![image](https://github.com/Rory-luo/girlfriend_info_clock/assets/55289804/ada746c9-df14-48bb-9fc6-aef0f285f373)
![image](https://github.com/Rory-luo/girlfriend_info_clock/assets/55289804/1f9852e3-db34-4028-b1f0-997944cf012b)


    5). birthday: the owner's birthday of host  (e.g. xx-xx) 
  
    6). city: the owner's location city of host (e.g. 北京) You'd better input Chinese
  
    7). city_location_dict: the latitude and longitude's dictionary of the city (e.g. {'北京': {'lat': 39.9042， 'lon': 116.4074}, '雄安': {'lat': 38.6, 'lon': 116}})
  
    8). period: the owner's period date of host (e.g. 19) (e.g. 02).
  
    9). start_date: the date that you both meet and together (e.g. 20xx-xx-xx). 
   
    10). uv_key: the key of openuv, the url is [OpenUV](https://www.openuv.io/dashboard)

4. Then, click the "Actions" and run it
