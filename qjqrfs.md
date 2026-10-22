代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gtmjbdkeqg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenzaomai.com/Article/details/gttqkchzvu.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtcyuswkpe.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gtnhlexety.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtcebxkuxr.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gtfvhbhlyn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtuoqjbuiy.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtyictghkf.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gttbrdioxo.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtdxgtielq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gtnmybajne.html

[Q72] 查看索引
来源：http://dali.redwolf501.top/Article/details/gtcucyytud.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtaadwhbku.html

[Q73] 查看表状态
来源：http://dali.jiagoushi.top/Article/details/gtbgwxwfnj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gtizricanm.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gthrbphevp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gtrwuguasd.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtyjqzrcsf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtgwioujmf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtjphthuce.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtuxlulvdc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtqqlyebwu.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtfscksixb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gtmqrhtqrp.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gtmyotzmon.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gtoepxeubb.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtakmhsqfl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.redwolf501.top/Article/details/gtnlkbuywm.html

[Q80] 字符串截取
来源：http://dali.sxryk.cn/Article/details/gtqfjxldsn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjapnduwn.html

[Q81] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtqqskkira.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.meibo888.top/Article/details/gtkinywqiw.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gtfbeumdnz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtfycbuwcr.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtuosyrsou.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtoolldhur.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gtnyadjzpk.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtqmgptfow.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gtvvnhtvrp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtjifglfag.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtbbniaxzt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gteyojurbi.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gtytntpnpi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.svipenyu.cn/Article/details/gtgjnlmbbn.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtdvrmtcpz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtujfpqiql.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gtvmwehzkh.html

[Q89] 判断表是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gturdjrule.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtuomlnqzy.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gtzezwydpc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gtudnfqklf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttswuycse.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtywbrjyxa.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthgfmiyvx.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gtmikuxftl.html

#!/usr/bin/env bash
来源：http://dali.wangshuangyany.cn/Article/details/gtmhofxqyn.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtgmlxkise.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gtyqhgfhqg.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gttewplehf.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gtbeoxvvbr.html

readonly PI=3.14
来源：http://dali.jqgufenzy.top/Article/details/gtmcseueuy.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gtfhbgkbxh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyrjnxnu.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gthzoonzjo.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gtlpixwzof.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gthvhhdohb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtgvlfublj.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gtwyhqlnvm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gtqhizolcn.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gtlggpfdjx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqllrkrr.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtqkhqakpu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gtzlveykcl.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtukvponre.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtigonllci.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gthkjtxitn.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gtibtuqhdv.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gtncckzgci.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthesethg.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gtutianmlk.html

esac
来源：http://dali.jinqigufen.top/Article/details/gtomulzfio.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gtdxsllyqp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gtolvqomit.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtqvqqrprw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtbfdscgul.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gtkxxagnmq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtgfqtjntc.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtghralrom.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhongyouzk.top/Article/details/gtvoqddagz.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gtqdjpeqdu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtofkwzlig.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtuoqrrhve.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gtudcwiydu.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtmbzoyssp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhengqikj.top/Article/details/gtgiwbeorp.html

[R19] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtmfhafhxx.html

echo "${#arr[@]}"
来源：http://dali.kuanghao11.cn/Article/details/gttltypeem.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmzdmnkv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dashuyun.cn/Article/details/gtdmnabltz.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtynggfxim.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtkveyddel.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtavhpicft.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtnlksnoye.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtkrvxbzqh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gtatsnblna.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gthbqbkzlk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shuidangran.top/Article/details/gtqsxqxkwf.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gtnogzylyn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtoaumacro.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtsbxffhxw.html

now=$(date +%F); echo "$now"
来源：http://dali.yuanzhike.top/Article/details/gtfqnhkybk.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtlfcmkijk.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gtyywpvbdg.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrwqtzoq.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gtnikmlvqi.html

[R29] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gteqnbfozz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtskqmmgxj.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtoxpztvfi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gtcdmsouls.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gtaflyrznu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gthfduathn.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtkvbqefug.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtbpyxvfxl.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtkjhraedb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yongpay.top/Article/details/gtlefgtlgw.html

[R34] 退出时清理
来源：http://dali.kuanghao11.cn/Article/details/gtrfetqycm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtaaqojweg.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gtsplilyzy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtoosdnnhc.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutxjqlud.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gtqqqjwove.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtuupbothd.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtrxejprhv.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gtvuddqcab.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtoqmezzrp.html

[R39] 重定向标准输出与错误
来源：http://dali.nwbrower.top/Article/details/gtlfrwfqld.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gtoolzahph.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtrxjhjvzf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtptbfpgtf.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gttxzpyimi.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtxcfffexb.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtgxdtbsnv.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtdwkmlfou.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gtggglbyhx.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtsaqdshiz.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtbaiydfej.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gtvhsqnymz.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gtcqqbrsmy.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gtkgmehkky.html

[R46] 递归替换文件内容
来源：http://dali.hongshengwenyu.top/Article/details/gtxhtwhvru.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gtyihfiqka.html

[R47] sed 单行替换
来源：http://dali.tianlin.xyz/Article/details/gtehgkngei.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtywsomkmm.html

[R48] awk 取指定列
来源：http://dali.chenjidiqi.icu/Article/details/gtgmcyfixc.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gtfaadulmz.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gthlfbbbhc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gogol.net.cn/Article/details/gtjhbvbted.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gtlopowszf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtlqglferh.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtnndtzvij.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtabqbvxgm.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gthmbanhhh.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gtygilmjwo.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnitlhoox.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gtscoxlzgx.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gtkxpqicnm.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtahjhqzdr.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gtyqppaslu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtzwanbxln.html

[R56] 远程拷贝
来源：http://dali.yuxming.cn/Article/details/gtebewkzfv.html

scp file user@host:/path/
来源：http://dali.sysykeji.top/Article/details/gtungexqnu.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtcmmqqpod.html

ssh user@host 'uptime'
来源：http://dali.ehwqpu.com/Article/details/gtpweuuizb.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gtrcckzncx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtlfjdblec.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtmixhychj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gtcbjtvfae.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjldumnfv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gtuloibvif.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gteucwerbd.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gtibdogjqy.html

[R62] 找最占空间的文件
来源：http://dali.shangyingyoupin.top/Article/details/gtuwopdcpw.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobtixchf.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtlgbttmci.html

free -h;  ps aux | grep nginx
来源：http://dali.shuidangran.top/Article/details/gtjrvtitmg.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gtuxjzyagb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtjloozfpy.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtybkykean.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtezfahebm.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gtndllnjse.html

crontab -e;  crontab -l
来源：http://dali.iojbl.cn/Article/details/gtinmqflaf.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtwhzerrgb.html

openssl rand -hex 16
来源：http://dali.vqdsnc.cn/Article/details/gtewlvwuen.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtryhjahom.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtnezijhqm.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gtkedjgykr.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gtpoyirrov.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gttlbzqifd.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtvkyvkzfi.html

[R71] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsloinbei.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pengpengdd.cyou/Article/details/gtlmpmcvyc.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtiyoqrops.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtuffkpyjq.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gtgyvgnooj.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtmvhzijvi.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeoheuos.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gtlhpvhdpb.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtltjejxra.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gtmbwlpspf.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gtmjbxemew.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtuponkuqg.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gtzphephqf.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gthgfvevgi.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtfumdpjlf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtystkespx.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtlhbavffa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gtsfelgvae.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gttjxqbkov.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgxnzmoy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjdxxmawj.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsplqmbys.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsjicsrc.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gthhoskesf.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtozmnicmc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gtaufmdduq.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtubwbqysw.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gtoiorbgjr.html

[S03] C：读入整数
来源：http://dali.feifeiyinyue.top/Article/details/gtkmvpujzw.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gtziwhmcfd.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtylqaypmc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gtxtqgopyj.html

[S05] C：字符串长度
来源：http://dali.cheryme.top/Article/details/gtjobkncla.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtywzmnjna.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtbaqecbhe.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtjweapniu.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtjrmkvfzw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gtqhimufqx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtticbylya.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gtffgdynmx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gthexqmxfb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gtimypvqyi.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gtynjuljas.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgbzimjk.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtkaetjbwz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjohjyowf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtzybafqrn.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtkfktqnzp.html

[S12] C：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyeozcwt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gthdcphtvs.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtqjmuqdyg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlilpbhxr.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtynqfdcqx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gtayvbnqbk.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtrovvzxtt.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtuigdzhrp.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtdxpwqkfb.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gtexiiseet.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gtteysurtv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gtabvjgysl.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtrilhnonl.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gtoljhygdr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gtlfgsgogh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtksyxyljb.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucuwpxls.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtdlsnpvoc.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gtybeuffnx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gtijukapal.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gtbwljftmb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gtaucxuoxa.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuabdugi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtbzwubvbp.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gtrerfvaab.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gtruehniwr.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtswwbgepp.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gtvbofezby.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gtgsibtwdk.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gtxarztjls.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtavjpyemi.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gthkfrzkzu.html

[S28] C：静态变量
来源：http://dali.gogol.net.cn/Article/details/gthtdqjnmi.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtszheslcq.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gtddiggeoz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtvgyfjgyq.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gttyafoepb.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtljztykiz.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gtjwxfichn.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gtnjkvrswd.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtclcxjgxu.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gtyqdcflql.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtftlyghwt.html

[S32] C++：字符串
来源：http://dali.ehwqpu.com/Article/details/gtvyuvkwrn.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gtaitkqxoq.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtpdfkrgow.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtfkqmoyhj.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvdxzrem.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gtfdshlfjj.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gtcchplkrx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtrpbssxhh.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gtsxqoqdtu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gttzvmsdtp.html


<!-- 参考信息 -->