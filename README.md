2021年3月10日更新
=
>JDC-v2.0
>>JDC-v2.0通过多个结合两个主机返回的信息，直接获取最佳的返回值，可以更好地整合结果。监控路由器运行状态，建立数据分析表<br>
>>项目过程：<br>
>>>①基本完善JDC中代码结构,代码完善程度90<br>
>>>②host= router-app-api.jdcloud.com/正常抓取，headers不会过期，host=gw.smart.jd.com的headers中有个参数叫做authorization，其认证方式大概几天一换，就很烦，导致监控路由器网速等信息不能正常返回<br>
>>>③目前在等京东云无线宝app的逆向<br>

>JDC-v1.0
>>JDC-v1.0通过主机router-app-api.jdcloud.com/正常抓取数据
>>项目过程：<br>
>>>①代码完成度100<br>
>>>②能长期的，正常的返回数据,但是仅仅只能返回每日收益，历史总收益，当前未兑换。不能对路由器的运行信息进行监控<br>
>>>③JDC-v1.0配合qq机器人运行结果展示:<br>
>>><img width="248" alt="JDC-v1.0配合qq机器人运行结果展示" src="https://user-images.githubusercontent.com/61647893/110599044-7237e580-81bd-11eb-918f-3e989acb3d0d.png">
