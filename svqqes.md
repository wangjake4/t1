代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gtydzignhy.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gtmjxivivk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenjidiqi.icu/Article/details/gtxhjjsvza.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtlpelhrro.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtbtwpljfu.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gtxkvvknmu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cheryme.top/Article/details/gtcnglqaex.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghxenvhx.html

SHOW INDEX FROM users;
来源：http://dali.tian-w.cn/Article/details/gtlvyuqrlt.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gtnjquyigi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jianghu66.top/Article/details/gtofuubhzy.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gteqtplyqk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtlsnnrmyv.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtymwlvbpc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxahjzlyj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ppjwa.cn/Article/details/gtelymgnkm.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gteqfwcsfa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gtxpmnopvd.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gthzlbmvkw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gtedgcldpx.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvdazysj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gtiidugvxv.html

[Q79] 字符串拼接
来源：http://dali.aizwys.cn/Article/details/gttnyqaqrz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxinkj.top/Article/details/gtldmwjilw.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gtnwrrrtdl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtdkqhbssp.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtihbfguvm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtuisukfom.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gtzgajlzgw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtafsggbcu.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtbaotmlcj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtjfyauarz.html

[Q84] 去除首尾空格
来源：http://dali.gzhubu.top/Article/details/gtrihnkwlw.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtfopgmdjt.html

[Q85] 数值取整
来源：http://dali.9152youxi.cn/Article/details/gtrfstlhqy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gtiivwfuhc.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gtzvhydrnu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gtmqfmtduc.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gthpdazzrm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pengpengdd.cyou/Article/details/gtrplfkfoc.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtxyubygrz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gtefejeafw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtafnxforw.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gtxqthxifb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtxzybpzye.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtlwrtynnv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtliksqiag.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgldxiflb.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtzovixsxs.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjgqopwav.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gtamvqejkc.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbnmbkvr.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gtpxfjmtxg.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtixoucdry.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtrdzshkix.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gthdxtabor.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gtinzxhiqk.html

[R04] 位置参数
来源：http://dali.yuxming.cn/Article/details/gtheffkzas.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zdqjudy.top/Article/details/gtrvkmnzpq.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gtmhgcpwms.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gteyrsmkxa.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gtngiplbva.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gthnakgwcl.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gtiqvsbfly.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtmmkkkije.html

[R08] 数值比较
来源：http://dali.gogol.net.cn/Article/details/gtnuxqhido.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gtmnsqbdpy.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtiigkjmui.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtjzkyqroi.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gtajipopny.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtncnpfmhq.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnjtelvl.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtzlbtiygy.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gtlxksqavc.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gtcnrcjyjk.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtexczqkwa.html

esac
来源：http://dali.havefunace.top/Article/details/gtwrutsaia.html

[R12] for 遍历文件
来源：http://dali.andypj.xyz/Article/details/gtexaxuied.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtfnfdmwcn.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtxedclnqe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqotyylvd.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gtmnxwmtaq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtyzdcxyqi.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtayhgosju.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtuvbsxsbi.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gtxhkzayky.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypuposes.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gtynliuefb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gthhatgrte.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtzojundke.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gtlgkuxyrj.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtxuhvmfiq.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gtzjlwfcib.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gtznbmoopa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gthdnsyseh.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtsmsvyfpc.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gteirwjedg.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtveuyomuk.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gtrzvpamig.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtklqfnihj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gtdccwcmqt.html

[R24] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtzzcbhexx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gtjequjqvo.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gtosbqjeqt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gtkbbcfgtp.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gtnfldurdn.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gtatggzhwm.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtljfjzlhs.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gtsiyzggfc.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtbufjeyak.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gtfqgzvbfb.html

[R29] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gthpedwzki.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtzuydfypr.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtiyrhzcbd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtdcggcpel.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gthlcmmtxp.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtcysnchdu.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gtiykzyyvu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtrztcxbwa.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gthtppkogh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gtbeuzfpme.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtnrrnlsou.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtawbygkfq.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtzhvxgmxs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhixingplan.top/Article/details/gtjgzmbabl.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gtttubzorh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gtgxidtbfh.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gtzjktotxi.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gtkupokrdx.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gtxbccdwrv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gtxioigfnq.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gtvckimtww.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gtggzjqrur.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gtijoowril.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gtnvogtpdw.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gtrnttphur.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapsdpujr.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gtqsmuhads.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gtzaovjxbe.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gtjtrivnzh.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtrnzdlfou.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gtqazmkjlg.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gtbzqnasgx.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gtynujocrn.html

find . -name "*.tmp" -delete
来源：http://dali.sweek.top/Article/details/gtzwaqmwwr.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtvuizipoc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtnmzyrnur.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gtgacilshy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtcktnvqqr.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtipyzkpqv.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtxbkzoqzo.html

[R49] awk 带条件
来源：http://dali.tianlin.xyz/Article/details/gtkqpfvvnk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pycfn.com/Article/details/gtxrndcpzt.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtvxvynylr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gttylmrrrx.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gtrtpfmanx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshaaapve.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtminyuaml.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefwepzeb.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gtpfskymzc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gtpdscltag.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gtwztrvlzk.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gtydhoulny.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gtsrbtzovq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gtqavlxevh.html

[R56] 远程拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtginykgiu.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkqhkdgu.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtgzvfbmyz.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gtdjisgdhn.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gticlyvckl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtjztfbpoo.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtvzcewvte.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gtyaprairp.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtvtdmzrmv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtsffxplgu.html

[R61] 磁盘占用
来源：http://dali.chenlongwang.top/Article/details/gtyufnnndd.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhcojuwe.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gtloonwnmi.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gtfysrhcmp.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gtsqeqhnpd.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtlicmqikj.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gtdrxddmca.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gtsuudslym.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtzgsngwmj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gtgnrbmkjq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtspgxcfom.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gtbaayugpz.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtweeqoxvd.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gtdtkeliao.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gtxfuqvker.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtkwphhsqp.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gtxppppaqk.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gtkropjwob.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtfiecqicz.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gtyhskntiu.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtdebqgcta.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlefftno.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpvsqdfo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtsajiqspe.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gtucwlgqof.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gttextvvev.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gtaaenwawp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlbipdrt.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gtogntqzlf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtlrqxqkno.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gtzlgqhbpx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtymuedrog.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gtzaepupqh.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gtzjsiuxvq.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtqowlwinw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gtcxvauukq.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gtvjhciiji.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gttwoppkhp.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gtaztuloxa.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gtxueozyzt.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkjscamyw.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gttnfitoay.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqkkvygsp.html

[S01] C：Hello World
来源：http://dali.sxryk.cn/Article/details/gtarzlfrfs.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gtookqvakw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtcpswfeyb.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gtinrjgbjd.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtwqvgsbsw.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gtdlleiuzo.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtoikhdyxh.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtgkbgxakt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gtsrygfftm.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtkpwsylkx.html

strlen(s)
来源：http://dali.nwbrower.top/Article/details/gtuozagmke.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gtpzxttlsq.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gtlzldiois.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtnfuvsjxh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gthgnevewy.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gtjujudsjf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorhosuvf.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gtrplxlsot.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gtpassylka.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtedbayfhf.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtgtzltwaq.html

[S11] C：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwtrltsk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gtrnqylrvu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtjxcxqhaq.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtuqanufoe.html

[S12] C：写文件
来源：http://dali.xuanzx.com/Article/details/gtzaplyljm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtaxcfuuvg.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gtcyeavsqx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258.top/Article/details/gttvmktsqh.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gtxijihkml.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtmnwlywgt.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtooqaxwpv.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gtjqgqgasn.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtkbmrvaoo.html

x |= (1 << 3);
来源：http://dali.iojbl.cn/Article/details/gtkvygvblk.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtpnynamsl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gtmrsndnwm.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtulvbraww.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtfhnhcnln.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxltqbkt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtqjcfobyd.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gtmubjvrdh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtojcommfu.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtqgcjhgik.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gtrzltsevg.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gteatxdqux.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzhbhbcc.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtxkqiqhce.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gtqenvfvox.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gtaoojvkjj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gtpuhrtmpb.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gthqgtumrn.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gtbcyjlxzt.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gtwwuiqusx.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gtggeucjen.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gtisrcltqs.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gthotbwuxv.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gtvmzenmpb.html

static int counter = 0;
来源：http://dali.shuidangran.top/Article/details/gttylpyxsz.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gttizbvuxr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gtfpjsoxeh.html

[S30] C：头文件保护
来源：http://dali.zhiwuduotai.top/Article/details/gtscpqnabq.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gttulmyiol.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gttcrdqlkd.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknthwoay.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtoyvmywvu.html

#include <iostream>
来源：http://dali.dianchejie.cn/Article/details/gtgbnpiuom.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtplndpnjm.html

[S32] C++：字符串
来源：http://dali.cheryme.top/Article/details/gtyfhbcubr.html

std::string s = "hi";  s += "!";
来源：http://dali.daria6918.cn/Article/details/gtsyxfrkjz.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwpbkuwa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtpneddfgc.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gtujoxbhag.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzeamziyq.html

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gtrcgkalcr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gthzpmhuge.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gtnkcqnwyi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gttshaabjx.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gttgeihbzb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtzjefcujd.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtmlompdno.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gtqmmoebja.html


<!-- 参考信息 -->