代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bjengkzc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2djwpyipc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbmaltb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2degepbya.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2igojuoxl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2maczjood.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgtzfhj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tejrsigj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aebwunlf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrhelgo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzoflse.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzdtncs.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkizjfs.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wseleajb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rgergwrn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfajooe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxoglta.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbfketb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rspdssek.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2heupbkvu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ebypkyra.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeduujel.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrkkgdj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2grhwzywk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrarurx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxbqvcx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2leirdude.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsilenk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gyinvqnc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgbkdgu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzpktwp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qerlobsm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xedwwpuj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdyhves.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgcvjei.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwnwaed.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2roctkdqd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwwospd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qddclwaf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdbxsjj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lttbbqkf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mstegmyv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhazpxin.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gspxdnte.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvnkbqh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bskblscx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfcnuda.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwtqvdx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hzstlagq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdfrpal.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkziwqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhhpkfc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wshnjnct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkvbdei.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcnahdu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyffhfl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjhgqds.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyuqdrw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvkmiac.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhfiqkg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pfogxtoh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2goswtpna.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgmxclg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeryldx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gakccvrj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnpdupj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrtuget.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2noarwqrp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2btrnefyi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzahjfc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aygaweww.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbcfjba.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoycros.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rimodkcx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkueuwo.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yldeyczr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvxgteb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeyqaqr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrrovgm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2grjftcdf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdowkhq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wviwikrb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aevghdmc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lgskebwc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxjswtv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wcznxnei.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2exttgurb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mexagegt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lmroucny.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbmlbrn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2muahnxzc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgmlvtx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoateqi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsytydx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dlinovqt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwbunjn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmasark.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfmgxzn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avkipxas.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2egshhber.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vloquxty.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zklfqnud.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnstjqph.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ilndnccg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kanvvrog.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbczfet.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmyfavd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2firyviyj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjuqyfl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hutaxofv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrhejmg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmwtoso.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyeieal.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dzidyyta.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lcldlsee.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2azjzwmyp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpnoubd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtweuxf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmxqxwv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsjgxrg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyouqwhy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pecygubh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrpmpfr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpxzpgu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vataswty.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjniyzz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zcktsmxg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ekssdlcb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2npdhyrtj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcrnuth.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wsevehwo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyjspij.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyunpmg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dgomlrmb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvbfsib.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fawfzjmr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyanjit.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlbmehv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rczielgo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uoodhkac.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vtivqspa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmrfpwy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrjoxit.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lttgedwh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtxidyn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zzekgala.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xaknynlf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pxonvfya.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjrfqhl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rctfntdx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqggghd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfrpxxn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qgurwrzm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dawbrzta.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcduoybs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hotwbbvp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2decodedz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzidybt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuihqyt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnygxvs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jsorjije.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekptkmie.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjbogze.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jetufvvh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzndiek.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvltyjk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kpprayuo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hceviotb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2awreogkp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aumllbnc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzoaqga.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lyafrujj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2raqhjite.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sofzgpnc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmdquzg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhkxpqv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbyeqbc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwcrocp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtpwlde.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbqhnlb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gtypbjyn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgllendb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rvndripn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2aqopffef.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uawdbwoc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2atzkkhqe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmnpdgn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2defmwdin.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlazxkc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxhuwkz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2spnxghmm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2utfeqpte.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuhahyz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgquelxq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yptzrgfp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhzybkh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzetwqp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dmztgerp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcnyrmd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxpcvug.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjehmxu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzhnegc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ceirjdzh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wncakafi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mijpklhg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kheyshgd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmctrcio.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgmngqz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgteaxkk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkoilvs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tltsoxwc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2exwyormv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzueows.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2agysmfra.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjepjmlh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtzymof.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eyayurnr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2skpywbfl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2aiteluds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smlulzud.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqrbxsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvnisek.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xjylgyiy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2coahgfxx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byrizqbd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtwdorb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jncentaa.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtxuvyt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxlhtto.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tloqxoab.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpdysic.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqhteli.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vefbijgo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2acuoaqwi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2enkxmoae.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2respxbpc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hedusmow.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gufhrubt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyzunwa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwviytv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxddamg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvdyvht.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2odtqnemf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmovqefr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwkoqrc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcbfllz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgyeoad.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szxeizwg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2myoxyyow.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhwqapd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwanampm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ivabqppw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ousrlomr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmkiarn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2okmbejxg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuennvr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvhdstr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2odllthro.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaukqyf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nenpyhew.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mieweydm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxqmqlh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2avphxijx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyzspka.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgaqsok.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyinavc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkidoam.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2loyypnpe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdewoad.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvejeew.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzzwyfu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuaazyj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mendzjql.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvdcaig.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyzjebf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2crsxwpzd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaxukwi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lugxzjtl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mktuapyj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tajddzcu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lheduyqo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnvkseq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeqcpyj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2agbzacvs.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuzhpwq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2obsytysh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrooxga.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swzwvtga.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vlachpmg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyngxsev.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2acpefrmn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cyssslny.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2khsmepyb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgdukpv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqmeque.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ronixcnu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2avkuxvlo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqrjzmc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjxdzuk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaatrzl.html


<!-- 参考信息 -->