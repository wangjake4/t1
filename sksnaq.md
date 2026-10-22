代发 wailian999

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sltkcsoo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlamlduk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgoaxyb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiekgxe.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2omlkoexw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwbokgp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yhehlvlf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyahsbpq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfxrnku.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuqjqhq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2avyjzjfr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiicugs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpeyspk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dohwxhec.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ioktzinv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vliagoiz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdrgtly.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fmldhxzg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxzyoiy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzotmau.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkzbwmt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjvuhax.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoegrig.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfbegmq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyixvkok.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtcfxwd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sberoymn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xujhwzsz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2viiikusc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeyffry.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2seqyihfj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaitzls.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dauxjmxm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgrnfpo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqzmtth.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2feggeesf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2phgzvapw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkvbtwf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaaoony.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgcydmi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmidmvd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaxhyva.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2elmlvfao.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2litwoiuq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnpkqiy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdollrc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhfjpnd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dawijloc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tpftinrv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoxfurb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrgwouz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wllytflv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfcbxbc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xznyihcm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiayeds.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgimtzm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmgqwbd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhlwjct.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ythbfvjx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpolbjy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvorcny.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2chdiywpt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjculyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmccvqd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcmpvon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sapvmtpy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2unxhnhxv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjocrod.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjsfnph.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uhykpiwg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfqayvp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pqifttru.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2alvkkelv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pirnpvrw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjkpzso.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vsilmomt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzocnucr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzmhwtp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjpnsxn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdozqlam.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pawnhrch.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xnozrvgu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hbabgeys.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wpalibzg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2msbgczpv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjgxuki.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2beruojct.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2axsnkxii.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgbwgyg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgtmnom.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2drmsztds.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfdhybd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmgsvka.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdayefyv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eicvmiuj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2odsupexd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2krsruius.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dctwmxnc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obzhmorn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgdljbo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fewsvlqo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqenkxx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qomzlumb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jatdoqot.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnygbttn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyilhrx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtwpzea.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gveebxzw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2plavmzic.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2snjythjg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrarrluc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrfbiam.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeufvzoc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hznxpqvq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2itxcxxuq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkmuezi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxixogx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsswptp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlbcrib.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbwfjwr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxplumuq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tscxeoyl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2isbzlnuk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtqqpwi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pejfesal.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgzgjme.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfmbevy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpifltrk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yirtmkhj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kgajpdyb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxuxoet.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvnofgx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsqyjzr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2upsszwwb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsrzgqs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzhpsvw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2sldmrpir.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2isyuscep.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjxdhgj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyylnqf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2osxlrgbw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhxeddo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmjxycj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwrnqdb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjmfzwf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmieulm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzjshoi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdacdqg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xplrwtsl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqhtpcx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2blsjxpgs.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmwyzyi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2afpmqyvl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiyimvp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rhooozzu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npfbggjj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aefgwaix.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ussigjog.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ncosutzw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yqakuqsi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nakvfaiz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmxbxqw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcxjjpp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjplebk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeikhxk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fijyhkqg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbckzxb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hspvejmk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2darzltoa.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsaykqk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhxznoy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2izwktwxd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpvdwqv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jddrelgw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwjigmu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rhznqgox.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfuudkr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryixykkf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rugfgimh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rndadlwv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kfekyyet.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsaxgit.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2eghthfyk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzaqaqe.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsqjtbh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvujrtl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxxiwpt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxfrhnc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2asjekfee.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yixkruoa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyvereh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuwamom.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyqlweu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcolvsnj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rmagjnuy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxpfsam.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwszjlw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqkpzss.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjabyca.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aphprvge.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2irzhqwsa.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhmpfjr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjhlfoh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nylhtqsj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2axghafrk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpnnmzl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyilnxz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2awmnfjux.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2chfpjwmj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2czmnclmd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rrneyduu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaevkea.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzozjbip.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hchtitwg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbrgusw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2odssxexp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhpeguj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xolvoyho.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gufxzyfw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdhbthp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2yddmjipz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwllfqd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2admtaxps.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqgfmec.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uncvayvk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwcxhgq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfbziiq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpprjgn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zshqugtd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvuuyjm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfskbci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwdtabh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtfmqxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wllvgylw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkqeqrt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdlzrso.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pstzjvoo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cxibhizz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqhvmjv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eenjxsza.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaxnyon.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2prhliebl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2olkzkplb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvqygek.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxccjour.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lnewjmcc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmpzcam.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bydvhgtj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkunpar.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hncynmkl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcggdjm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2emncjhzr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qmexzbmb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpnwxtl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnhbfni.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orwpphxu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2riedxpvu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaensxa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyaocvl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzkihsd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpcbdzw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2abgbgscy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwxflka.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lgthfsky.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2spnmpykk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aupwlppa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2isaplyxy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwpultr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2noqhgnla.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fweigrmf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xebhteaa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yectpysy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmmzhqf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgxzwhx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2btnomumw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2izxcbrwo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oarqkalo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rclntlmk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiayebkg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdoqsve.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2okhwnkpf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2swklirig.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zriupqqh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaezvwi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2onconqny.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmnnytl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbsbgva.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxpkntn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lefrvuoq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2etxhogdd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjunhps.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnusfiw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wotytabd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itiundoy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdscgfuc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdyywgu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuqokxx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzxmwqu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ghorbazs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkdgtwg.html


<!-- 参考信息 -->