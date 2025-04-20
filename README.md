# CS2_Personal_Config
个人自用CS2 Config存档(到处偷的)  
* 仍然能使用跳投和前跳投的方法：将`movement`、`autoexec.cfg`、`listenserver.cfg`移动到cfg文件夹，加入启动项`+exec autoexec`  
* 个人启动项(freq刷新率 threads看大核数量)  
```
-allow_third_party_software -high -freq 240 -threads 6 +exec autoexec -nojoy -worldwide
```
***
## **autoexec.cfg**  
自动加载cfg  
* `Z` - w跳投  
* `C` - 跳投  
* `N` - 大跳  
* `V` - 全局静音  
* `MOUSE5` - 切换闪光弹   
* `r_show_build_info 0` - 不显示左下角时间  
  
  
## **prac.cfg**  
投掷物训练cfg  
* `ALT` - 飞天  
* `F4` - 重扔上一个投掷物  
* `L` - 清除烟雾  
* `J` - 跑图改刀，扔刀在地上，准星对着按J，再捡起来(507爪子/515蝴蝶)  
    500; //刺刀  
    503; //海豹短刀  
    505; //折叠刀  
    506; //穿肠刀  
    507; //爪子刀  
    508; //M9刺刀  
    509; //猎杀者匕首  
    512; //弯刀  
    514; //鲍伊猎刀  
    515; //蝴蝶刀  
    516; //暗影双匕  
    517; //系绳匕首  
    518; //求生匕首  
    519; //熊刀  
    520; //折刀  
    521; //流浪者匕首  
    522; //短剑  
    523; //锯齿爪刀  
    525; //骷髅匕首  
    526; //廓尔喀刀  

***
## **一些常用跑图指令**  
* bot_add                           (加1个BOT)  
* bot_stop 1                       (BOT不动不开枪)调成0是关闭  
* bot_place                      （把BOT放置在你鼠标指定的地方）  
* bot_crouch 1                   (让BOT蹲下)  
* bot_mimic 1                    (让BOT模仿你的动作)  
* bot_kick                        （踢掉所有BOT）  
  
* bind "F5" "toggle cl_draw_simulating_entities 0 1"  （按下F5跑图练穿点透视切换1）  
* bind "F6" "toggle r_drawworld 0 1"                        （按下F6跑图练穿点透视切换2）  
  
* getpos             （获取当前位置）  
* bind "F1" "setpos 132.355194 -1574.058105 51.871250;setang 6.677358 156.112930 0.000000"             （回到坐标位置）  
