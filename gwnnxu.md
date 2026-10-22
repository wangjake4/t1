代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zydaxsab.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2apktwfce.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gupomdwm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2urckimiv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbldybtd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uknnuvir.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qtixsuft.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrdwzpb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqvisrp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnqvujx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bretxbyp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrgqewt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbqqrhw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oltckdtv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyldxte.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bosuxtjn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xquagtmz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2djrhovxk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdrhzby.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdwmrpp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxlnkut.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wlidelhu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkscrrc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzzvkyw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrxiuet.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpiysxq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwkcasw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmzhuoh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2htejjlvg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzreyno.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgfcehg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xymsmisf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwappwl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufprbjet.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2aqherpws.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuobrjx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wymyoqqh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeivped.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2smwaqkcz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjrtxjm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjdlkii.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fersacvi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwpxpev.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2djibbgve.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cwebvcdl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2efcmuqqe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzpcedo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llttcjtc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dekitrot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bttzxqhg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2shtdqixd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dnllqmvr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2naksnske.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zelizcjc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcnaojw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qutyhdev.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmghivk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2azfbpiih.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbjsshj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvtynsl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgzuwos.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ougmlasg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avcnseri.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usfdqgns.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cudmqiap.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vttohltj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uiurlcln.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsiiwid.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dygqjkqm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2datgtkot.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqjnljw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbsveeu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvgrohk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmpqplk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2udcsyyvc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqmggea.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsryooz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cikpcygz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sthygzqq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fisconca.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnnjbot.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxxlckd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kesjvizq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxhzicm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhieero.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxhczmj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bttpowfa.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvleqwa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jenxjkhd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qskqldzh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pewtzbfe.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjkqzer.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2otekijva.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lotwgnbw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2puaudndh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oamuhwfs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2expgxiwp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iiprdnix.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzkqhbl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyqvxcb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmxkmcq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkmbvuq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owmvbjkn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrjimrg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnafwohb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrlkcsq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrlduqd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bwusprwl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsbqaku.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2foovtabo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mcybsbsh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhaavkq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ferrlopr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaaexod.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmabcka.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ismotvvg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfekxdwi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmtonuz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbplkja.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2btwrjctg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoyuswz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrmpnbj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oglecimm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2szjpmxcp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xogvcjwb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2glkkvvcf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuvxagq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bekdjqih.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mujplkmd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qsghkavu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcxiwsr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rapedjzp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpofzed.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pcatuydk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdbweic.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2evwcvdqm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vcobroej.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2whvkwizx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuqqrst.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xifxqpnt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2trmzamfi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nogeuizv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zpryakjy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyltwrm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tjebmpzr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2peqwxshy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2irzyqbtw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwsioqt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbitobvl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmmjzes.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkalczn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpmkmeh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhzmfuh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qimugana.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzxmibb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qmespvvp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwkwnum.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vevcueoj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkoxwir.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2shuunlyx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsbwlnp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkqpple.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzqnhpg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tojkutaq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvhrrce.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkjukdt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxtuxvl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyayifa.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2blewupfr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsvlard.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zedzgmoj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2htbgqxqc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oafvnkxg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmskkda.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmdfsia.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyblfmy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqxguos.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxvcoko.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zugkkpow.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwnlmjm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtgtnqb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2obhhwzoz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2asxfxfvh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pananfap.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nidppxfo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gmssykib.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zswcwsuk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2symirjib.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2orfpyydr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dksrpjbt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bkultqzn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tveczjip.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2szbblixe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtufiug.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fyilswgf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2limptemw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wegpnojs.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkbwcfy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obisxeyv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfbzbmg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdhgtwq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfsqiys.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wapyebqk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkncgcy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dffttzmx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpalpjf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzxjasw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrcbslj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbykxsd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2etaoecli.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2shifylin.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiymjhb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svblxbdr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwvpdjj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nllhrxoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whgaunvb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqazvtu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbnhxab.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2udsymqsl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qoesqtxi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrkcuqw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkjtsvd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvqhucv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdhhfep.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqaizjk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtkvmqd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2inekqwox.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2znuhgkcz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqpjcex.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzhanqx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2flqkirwk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqftwhm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwbvpoa.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxwoycb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2czcagwxw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnglepx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvmbsdb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jekjziqr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhgsyan.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqgqbhk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdujssh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxtqyok.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cezxmixw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cklbyrch.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2foqkhkzl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyjjdek.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2heoojjqu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzovdzn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qaesjbaf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgshytl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfsyyjr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2svfqetxy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2shhxeozg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xnthrnca.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzczwepl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfpovqx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2trqxmizh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eubyoulz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2newfqkxh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mpspmmez.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpugrgp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2htxgqfmj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdfduql.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qtexrbnb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqbmroy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgykqjyx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhzkyis.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vkznyjlt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrhfoox.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xhofpgbr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2elhmtbpv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiosnio.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgocwdw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvflaatf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsbrfza.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2utyisaek.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpohcga.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwsujgm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpabdpv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2igssgxwb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2avtjavtb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkseqqy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ykizwrhs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2adfbjnnc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdeskhx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrygvjm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoxfiel.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpchhti.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtbomga.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvsqccv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlzpnwc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnojxpeu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wxupngrh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfggsla.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zifxmtba.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxbtmpc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hubjshdc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbzxenm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ephyomcf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mkocbfio.html


<!-- 参考信息 -->