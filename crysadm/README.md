# 如有任何疑问及Bug欢迎加入L.k群讨论
# @爱转角遇到了谁 大力更新,请尊重作者
# 更新日期：2016-03-31

# 为了您的云监工安全,请立马修改config.py[SECRET_KEY] Key！请不要使用默认的
本次为累计型补丁包更新，直接覆盖即可
底版:2016-3-31

更新日记：2016-4-11 （本次改动文件:crysadm_helper.py,web_common.py,dashboard.html）   
修复监控中心速度换算判断    
修复数据中心数据有效判断    
修复Install 账号日记错误    
修复本周收益不正常问题    

修复日记：2016-4-2 （本次改动文件:admin.py,crysadm_helper.py,excavator.py,user.py）
修复运行日记显示登陆时不刷新问题
修复部分用户登陆失败出现502错误
注意：需重新登陆

更新日记：2016-4-3 （本次改动文件:admin.py,admin_user.html,user.py）
添加用户管理登陆时间显示
添加用户管理登陆状态显示

更新日记：2016-4-5 （本次改动文件:api.py,admin.py,crysadm_helper.py,user.py,profile.html,user_management.html）
添加秘银复仇接口
添加秘银复仇函数
添加秘银复仇按钮

更新日记：2016-4-10 （本次改动文件:account.py,api.py,crysadm_helper.py,login.py,accounts.html）
删除无用接口
添加双重登陆接口
更新部分接口参数
添加迅雷账号全部启用函数
添加迅雷账号全部停用函数
添加迅雷账号全部启用按钮
添加迅雷账号全部停用按钮

By:爱转角遇到了谁
更新日期：2016-4-10
api.py更新日记:
更新用户提现接口
更新MINE信息接口
新增免费宝箱接口
新增放弃宝箱接口
新增进攻查询接口
新增秘银进攻接口
新增幸运转盘接口

crysadm_helper.py更新日记:
删除老式矿机变量
更换自动任务函数
新增自动用户提现函数
新增自动免费宝箱函数
新增自动秘银进攻函数
新增自动幸运转盘函数
更换自动收取水晶函数
更换自动用户提现函数
新增自动日记记录函数
新增正则转换数据函数
新增数据重组处理函数

excavator.py更新日记:
添加设备升级函数
添加设备定位函数
添加出厂设置函数
添加设备管理函数
添加单个账号提现
添加单个账号进攻
添加单个账号转盘
添加所有账号提现
添加所有账号进攻
添加所以账号转盘
添加日记记录函数
添加正则转换函数

admin.py更新日记:
添加自动用户提现变量
添加自动开免费宝箱变量
添加自动秘银进攻变量
添加自动幸运转盘变量
更改生成邀请码:30
更改生成公开邀请码:15
更改最高迅雷账号上限:100

ueer.py更新日记:
添加收取水晶触发变量
添加自动用户提现变量
添加用户提现触发变量
添加自动开免费宝箱变量
添加自动秘银进攻变量
添加自动幸运转盘变量
添加全能运行日记函数
添加清空运行日记函数
更改注册后迅雷账号上限:20

web_common.py更新日记:
更换类型返回信息
删除老式矿机变量
添加两种收益显示

register.html更新日记:
添加注册成功提示框

excavator.html更新日记:
修正所有按钮显示
删除老式矿机信息
删除雇佣矿机信息
添加秘银数量信息
添加今日收益信息
添加水晶产量信息
添加秘银产量信息
添加秘银存量信息
添加设备升级按钮
添加设备定位按钮
添加出厂设置按钮
添加设备管理按钮
更换设备显示类型
添加设备固件版本显示
添加设备端口映射显示
添加单个账号进攻按钮
添加单个账号转盘按钮
添加所有账号进攻按钮
添加所以账号转盘按钮

excavator_info.html更新日记:
新增设备管理页面

log.html更新日记:
新增运行日记页面

base.html更新日记:
新增运行日记选项

profile.html更新日记:
添加切换收益开关
添加收取触发开关
添加自动提现开关
添加提现触发开关
添加免费宝箱开关
添加秘银进攻开关
添加幸运转盘开关

user_management.html更新日记:
添加切换收益开关
添加收取触发开关
添加自动提现开关
添加提现触发开关
添加免费宝箱开关
添加秘银进攻开关
添加幸运转盘开关

运行环境 python3.3+ , redis
crysadm 启动web服务
config 配置redis server
crysadm_helper 启动后台服务

安装后访问 /install 生成管理员账号
config.py.example 改名为config.py 使用
