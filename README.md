# bluwhale_bot
年后大项目第一炮,上号!
种子轮700w 总融资超1亿的Web3 智能层Bluwhale 

注册RF:https://profile.bluwhale.com/login?referral=4325a44f-7c59-49c8-ac01-923270982185

## bluwhale_bot 2.0 项目教程

### config 配置目录说明
``token.txt``token一行一个
``proxy.txt``代理一行一个

### 怎么抓取token
chrome->F12 > 控制台
```bash
 const obj=JSON.parse(sessionStorage.getItem('firebaseUser'))
 console.log(obj.displayName+'***'+obj.auth.apiKey+'***'+obj.stsTokenManager.refreshToken+'***'+obj.stsTokenManager.accessToken)
```
![教程](https://github.com/user-attachments/assets/35207d2e-606e-4593-b58e-200ffb97f22e)


## 怎么运行 
```bash
#mac
cd 当前目录地址
chmod +x Bluwhale_Mac
./Bluwhale_Mac

#linux
cd 当前目录地址
chmod +x Bluwhale_Linux
./Bluwhale_Linux

#windows
#方法1:双击Bluwhale.exe
#方法2:日志方式运行 cmd到当前目录 然后.\Bluwhale.exe
```
