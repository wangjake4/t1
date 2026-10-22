代发 wailian999

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrcefuh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtwxbch.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbzrgyl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoipsbk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeopmllq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uluzqmib.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkannip.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ioalikby.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2yosoqlnj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgnlxfl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiknafdk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vunukadj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrquudq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcsoqbf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrqlhjl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhwtzmu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tslrpgst.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xtorhecy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsmvyoi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyhksnb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ohojonoc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srzsozqw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzwehqv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kspxpfdm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxauccq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdclpjqn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2slcqbizs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2napftnvu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2oltorpuu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnzgvgi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgsicbc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbpnhyy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sweaeewe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkcojqh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2phkgraun.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbcmlmz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpajtyxp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuenzyw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otkqgapu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpnqcdg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tybqnkrf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnfcbya.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmttwjhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuhhdlc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcudfme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhuzyfy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2svzuqpkf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmeccpu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxyhwgc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjidvcp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjyxymg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrvkdxy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qebjvygi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2emuwxxto.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsxctdf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjndhqxh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xucnojer.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vusrrprr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmrctxf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyeslzl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xghwikyc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2edhohcro.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dooszifp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jertmehn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jsystebp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhpktgi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fjougrxa.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cymabzhs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwxavss.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqdipya.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vokzltqa.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyldrvxq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfvqipz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnmbnmp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbzfqdk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jniqyssg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dqncfngd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jowhpnew.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoeidix.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfiqxty.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjnumqa.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvatfoy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2boqptdvw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzajvkbv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuizjvwe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nwirowcd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2veebgwvk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvxnjcu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsemuatj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdlzhbq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lntqzllc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hyopplfa.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lncaxrdp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfkknap.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdigtrip.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrbmusv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2twuzzusk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mhagtisn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pggocjik.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gschcpow.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrydqby.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xplhfhyh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2neyjmlsz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmkvksw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjvqijm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgjarno.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pncgrnfr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jggbdwac.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmqamyt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lchhzbmj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgbhjzd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tiernbcs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jddnobyx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rzplcsxm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmahpphk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmiintp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2romxefzd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhyzvhg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtdedkg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqyzoft.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvfeguh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kaombrct.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtvlfju.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2emxbwoek.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2byxtimuo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qriykvpk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lvelqgsf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtntjdy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jobsmgcg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgkjrcc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfjntax.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpmjtot.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2byrgcotj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qatidgkk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snwsfgci.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmemgerm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qepbtdku.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xafqfxdr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zohfrocn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xajjcads.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qmalprxf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhfcahk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hebuodvd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbxxepc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjoprga.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrebwxi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhogyxbj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzamxzb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhpzqlx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2khesjhdi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2stteelft.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fudxmhaz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhfiqtl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkreioka.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2csevlxjh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbivijc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bedmnoic.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkqgggs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xceimwbz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2eulxhktr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwvlwsh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfwylkz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ywydefww.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlujrgx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuspdas.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkyzdbu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqawplq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwlpncm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lqldxttn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rsukdjij.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nmickfvj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxaguwk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2biywiuuj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qengrewh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdrcdpk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwyofjr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcvqozv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zoinauyq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wozplnte.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vitekgls.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmdqdkg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hzucjmni.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2woerabcf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkckkfsl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cgorqyua.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ifumgzvq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvynfkpq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2uinzqfhb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzcbfdo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuikqgr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nwczextt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkcisrl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcyuvbu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzwgwvj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2shkdncov.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rndihmxw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhvoriy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvmxamx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbtipeb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwxqnkv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmzvpxq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2slrjqvrr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cyirdniu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hyriyiiy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmrugru.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyyrlcc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fnesthra.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqsqlxs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcmhwel.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgamsyr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqrplhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hamyikas.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbngtmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mayywqgs.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2suqrpjhx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhhxpzm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eggzyihg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cfatxvtb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkjwetv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2knjjksjm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjtwahi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bchkjjjk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgvlxab.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrswjjt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfkheyf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fvugmybj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2laidxfmm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rhizwxie.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmzdzgn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoghzxg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2thljkfqw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vtufruyk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wbplvhff.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2crdmvvte.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2efpcqnqy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwocnkle.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2azgodeoe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2biroxuzd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrmamyo.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yauxpsha.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sitmcqks.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mahqpqxd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mulaxxas.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yydynmts.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtmgodx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kjljlkke.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbvhhrp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2entfnuvy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rydcpdbc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjoitvw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlwdgqn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqduvqs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tufzdbar.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2giftznfn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjvwcck.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxxrfxf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzewtxi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nitbinjw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2niaubwwb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjklpyl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nobpxbgd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqqbqty.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2akupvmni.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfpkcgp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cizqrqlq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lalgammm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2okhvgjyv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jebpjgaf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2baqstkyz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ruabgjfy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wamrbrql.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wwojlham.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcktsgh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phmaecwu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcottynm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ycleivtq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uknscksm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvyljyz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtsgvlo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oomqmahi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2agmmygce.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjslboin.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxtxrbg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eycgegui.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwxbqmt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rooqrvyj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fraqljtu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkztjrnn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fpznwbpw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uasupnrg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2iycgenpw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iudifxfx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vmabgslc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pegoqgeb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdnychq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpdhetf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcdmjqu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2shnlpudu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgjpmhp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2icsvdnav.html


<!-- 参考信息 -->