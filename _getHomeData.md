```
POST https://api.m.jd.com/client.action?functionId=cakebaker_getHomeData HTTP/1.1
Host: api.m.jd.com
Connection: keep-alive
Content-Length: 71
Accept: application/json, text/plain, */*
Origin: https://bunearth.m.jd.com
User-Agent: <rm>
Content-Type: application/x-www-form-urlencoded
Referer: https://bunearth.m.jd.com/babelDiy/Zeus/3xAU77DgiPoDvHdbXUZb95a7u71X/index.html?babelChannel=fc1&lng=<rm>
Accept-Encoding: gzip, deflate, br
Accept-Language: zh-CN,en-US;q=0.9
Cookie: pt_pin=<rm>
X-Requested-With: com.jingdong.app.mall

functionId=cakebaker_getHomeData&body={}&client=wh5&clientVersion=1.0.0

HTTP/1.1 200
Date: Wed, 17 Jun 2020 14:44:38 GMT
Content-Type: application/json;charset=utf-8
Connection: keep-alive
Access-Control-Allow-Origin: https://bunearth.m.jd.com
Access-Control-Allow-Credentials: true
Access-Control-Expose-Headers: X-API-Request-Id
X-API-Request-Id: 186759315-10487-1592405078849
X-API-Wl-Message: 0
Server: jfe
Strict-Transport-Security: max-age=86400
Content-Length: 1114

{
    "code": 0,
    "data": {
        "bizCode": 0,
        "bizMsg": "success",
        "result": {
            "activityInfo": {
                "activityEndTime": 1592668799000,
                "activityStartTime": 1589903999000,
                "mainAwardStartTime": 1592481600000,
                "mainWaitLotteryStartTime": 1592467200000,
                "nowTime": 1592405078853
            },
            "cakeBakerInfo": {
                "jdCipher": 0,
                "raiseInfo": {
                    "brandFlag": true,
                    "buttonStatus": 1,
                    "curLevelStartScore": "50000",
                    "firstStatus": 0,
                    "fullFlag": false,
                    "levelImageList": [
                        "https://m.360buyimg.com/babel/jfs/t1/114279/5/5425/51866/5eb3ba28E1c5c832a/7aace47986cb9b69.png",
                        "https://m.360buyimg.com/babel/jfs/t1/126683/40/170/48025/5eb3ba4bEa6ebf71b/516e711051f021c7.png",
                        "https://m.360buyimg.com/babel/jfs/t1/111704/15/5433/48344/5eb3ba72E3ca66a23/c1088b13c7c92007.png",
                        "https://m.360buyimg.com/babel/jfs/t1/112233/26/5368/48056/5eb3ba93E7b1e1a84/28d50dc1bdda091c.png"
                    ],
                    "maxLevelScore": "156850",
                    "nextLevelScore": "52600",
                    "pkButtonStatus": 3,
                    "raiseButtonShow": 2,
                    "remainScore": "2537",
                    "scoreLevel": 30,
                    "signPopStatus": 0,
                    "totalScore": "52537",
                    "usedScore": "50000",
                    "wxPayStatus": 2
                },
                "secretp": "S14ZDoghEWErc9Z-5SbcLWv-pg",
                "shareMiniprogramSwitch": 0,
                "userType": 1
            }
        },
        "success": true
    },
    "msg": "调用成功"
}
```
