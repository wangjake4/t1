代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2papzxofe.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lijimzpr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ccixthvp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeogkcb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjuskim.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2glvkqkdk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpflibtl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rclltktf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwenqij.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2miilyvzv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2chqctdmz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkjdsxu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzppijvu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmugolds.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeojzqsr.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sboedbqh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zngqitwg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeoytxu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjrzrqa.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfandtx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wakcyuci.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxcgdns.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvuyudt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpjltcp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhcgmdy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmygpctj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vjidhggr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sujuniil.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bupxiefg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pihxlugv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fjayvfmo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtldgpr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxdskme.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxjzipw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkcjmxw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jltibawu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2buyxhvzl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqlfkxs.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlyyqbo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itcvmmkj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxzxnbu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wghsypkz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgflohn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbrrtcf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyqhqog.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxjcdtk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmfuxea.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkhhirg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edermxku.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcgmfds.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2etviubgn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2onlplvoh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vviedrwd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gabksyrp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjelwgz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2izafgrin.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ozunpopu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckemcurx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcljkzn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzdezns.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xpngdkjr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2scsfmrvo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjgpqtz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnouggd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqimjhi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2galdcyje.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gctusuig.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqouthm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yastjmeq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mflqenxr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2toynrdim.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2numulquf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2guczfbzg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzuamnv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wwauweeb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zozpmomg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqdaknq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhtxlax.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kadtnwmz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcyeucz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2whjwzamu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2eplfadzf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlhtxqi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cksrcgjj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfpskpj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kncbsjgw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gssstmta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmagcwhm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdwkvgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otaaitye.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pljjdtdj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbckltb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rswznids.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jkloxylo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hajojabx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbnrprl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2azpcmeie.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvheitb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wywpmoer.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeflnry.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hddmygak.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbzxcyo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnmreux.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efyaxcpa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnwlwwz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2muyfqpbc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2spslfsut.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2djsgormi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2psyxptel.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mhezejzf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbmyafy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnkpiff.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlnotue.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfncgjl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyroyxw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kupovpef.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2aopdziuh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iclzrisw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmiwzqo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyviaso.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoawyvn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsevgaw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avgxpuss.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyeolgs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uuynymqo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pawlwooj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvawgcc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqrtsyo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdalyqfi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwlpirt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwrrapy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ozednibj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwizgqm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuxpaej.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kslqyzkj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nggfwhrj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2loiyphyp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2oolaihsz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmyofkx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvgohwr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2igtfrgag.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bymxoyax.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2roztealy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhagnwa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrztyotk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2niyvbxzm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2iddcbeqs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiwbhpd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrkehkt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vyinndaa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hazzznji.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnynkhxx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smhzctss.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xblpdebq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xycxelut.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkngdwl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgxizkb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2saniakiy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhkmahq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xilvjjam.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zmukpjix.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tdakjokn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mhykhxsx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqfrcyi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxphfazk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcyjpzv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fjddwtvl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwpibfp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2opqbgciq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lipbfhjc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qozldpgh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dncbumly.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dthysbya.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmdwlpa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwsrctm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjfuokf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tmliciwi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjwrylc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwonfyg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thveuktx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gktktzwg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pwditygy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zgohytvl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kjanmtxn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2miayujag.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwrbsjm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2azioxlfq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsylcrx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2capetxsd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcvnlfc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaciqxd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwcowur.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pqolfxwl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zuymwlav.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kgybpdeh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nudfmxob.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tlepxoub.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtivzhvp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rrydpppo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lryubhjy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mozplhqd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rczilhcg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwurbtw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2khbzviet.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2avirrmve.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2avoihalk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqdmchf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkyjcmo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqdrhwt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2quodxurk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhbwldl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dydzsovs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxtmwki.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjktctu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aenibjjl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzuxyhc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mscqopwu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugusprgw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2relgdtbg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yuamufsh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmizhbe.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjfbqra.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuzeitn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2orzlpgfq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrywnea.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2txptyjrn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhntqfk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwkzylo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhqhxxn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2okuuartk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjzyyls.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqmusdn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyzbhiw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rihhtdfr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vlztxtas.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mxorbsuh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwromfc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2adkdpxsi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mymndmwg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxhrlvn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pewiqadj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoqbyjx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxujfugp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mebmhysk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnfzsfr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjzaqis.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2epvqcpwh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2enecjosk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyaotlv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyjkcnz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqvjqwj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2osbbdziu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tifqmhoe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfjthnq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gghfvare.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phpyrpuf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdtjmjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzierbvk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtlevxv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2chvsolsl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujccgczf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvarooa.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsulsxae.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvkewzd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxvgdlr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fephhnel.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnwkbff.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2srnltzep.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2juftpguq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xuekkdtl.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiziopb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnuwdec.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2udizabdi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mhefjrqt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuprbaz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2txbwuwck.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvfflpp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlgmrav.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydstotzd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nshycuuf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlyeknn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2clvqqdyl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2evnovkmt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2voplaybr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiixfxf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2swjxzukh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqxjpbx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cydpuvli.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2avssmgbx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nvakrqic.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2drbyxujj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrywidc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sntcabqk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtalftr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaerifv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ceygjcnp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtxtrej.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjasmrj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkwmqct.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtorjag.html


<!-- 参考信息 -->