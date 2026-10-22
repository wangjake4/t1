代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fecewxcg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjybkll.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2imbklsdt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmlykdd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2znrhboqb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgryrgh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdoqrqk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ympsrrof.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrrhwqp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mubnpybc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uquvaxaq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsugpsnj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhpahwh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2twykxisx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqhiiac.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ceniyguh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuutftt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxfigpm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfasgzq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jsayzbkn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpmiwop.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkppmer.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhixdbyd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2txbeyelt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2elxfiqpj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2nastzxie.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxnakzt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyqfxkx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxvqgnp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwozzzr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bheaotqd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2txngdsio.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbxnlde.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eyayztck.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpjmlba.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2szyjepuc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcvztbl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eajtyulb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mckhytko.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iidxbkue.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbsmlfq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bocgzhnh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwhsddy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyyagcp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqmgvcj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mygnfesy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwlsenw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2onyxcijq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cmytajvt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hejshrwz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hodtuwjk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpfvrau.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyejqyx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgynyhs.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hrswrfio.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gydahwbk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgiaqtpk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nadyosvq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qxngrztg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwftnsv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pphzhncn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qkurbnkw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bxblqplf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpbvdwp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obeypwqf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtrtlut.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxovfhx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2airlhbyr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkhvjdi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2outizdob.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsyxgxf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2knkjzhlp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uklnpxpp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyyhdfc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdmeozk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2svzmjclw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2akfhkltq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbzznoi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpsofjw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ilabmxkn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdidgvc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njlhpmyk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tttmgwus.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2prlszpen.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrwcbhm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qimoovuu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuokjrk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djiipohu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zurzinbt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdqviqa.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2atzzrzsr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqchnove.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hpftxzyo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xevanjgk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2odubaivk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmcwzvt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nigthhru.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqdfgzc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jumxykao.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbturir.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzasdbl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwumzrh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeymdyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pssoxafy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvjuqre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yelkxqwf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwsksvk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wybhtktp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2knxbfyjv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2aorzfmhv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfjiwxi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vylmtspf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyafunj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2taveaoto.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaxikbw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nahgvpde.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaykzcu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fiydqzpd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsbfmkg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqixhsyw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fksujlro.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tltufimq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2muxauppw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjkjuxw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtmizeu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdztepv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrwxgtm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rutpxqxp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrcjavs.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvafgrb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wetbovos.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2osikekik.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kcamzvnt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxyrxem.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qakdnzzv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iifrhywi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2slxdzudw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkyqyix.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tsptvzfi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2unrwhqel.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pxujsqmv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nevenlkk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqgbcoc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pefshgaq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2potwzffj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbfnoid.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxjleks.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpwfsyg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xetwtvtr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwnmgsd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzdquka.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmwrdny.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcdezkg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2htgeilqy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2judqouoh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nofcqnws.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2anrtvvxn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnufisi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qphadmeb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnruxzt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyafeki.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bhusmtmb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtagugih.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2msybpydg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2grcpevpe.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qymqywnw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vnekkoki.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skkmqvyc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lptfzwrj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyqnomh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvuhidp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wugjvrki.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkbsvxh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ofammbay.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuluuas.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcmxoeg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzcxubj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rowedwfg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qjywpcgi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoajqop.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoecnvj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hyewhmrm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2sntwicwb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkczqacu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2npoiguak.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2plpgujvw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2flnaatqx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2otvxldgt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2exdhslvt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jowzrzyw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwntkei.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2prwaxzux.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhktyyh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxcxmyq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kycttyha.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpizwkdj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaggiav.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuzdred.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoywhps.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2irpwmpvs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gjutlftn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fozxexxc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lixjrzop.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyjattw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfhqbmz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxetqzga.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2asknwkpl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtpfjkp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjvcdjl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpfwfwh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2souyvwet.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxvsxrj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ltappehw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdrsoov.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrfjpdl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwkdmoy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtypxhc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhkorlz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2smcgqxna.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2duiijnxz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hdokltaw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pobtzuzl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvvwjes.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mocqbfeu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2yefuptmq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlhgknd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyijxek.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bahmqbyb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fboskewr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxmvofo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzscail.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvlmmfm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2aolzveuk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaxjpia.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhettvi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zjminxmu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2feapzmua.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdxlbyy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktflcfdj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2idutkftw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcspfmn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2adboktau.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tptqtqjs.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2syrlhmnm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmstojl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yldixxck.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qptmkxsi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgwefaf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2enmdgaua.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxbjbad.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfwnajq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fddnsidl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2phfvfndv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxjnuyv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxcvcjj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlwzajt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmzjtqh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wojbciel.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkcdwjz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvckdnk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jojlwszy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwylivk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kdszxzer.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbitklx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hroinnkw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrqbnwt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2clybolef.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtrpqao.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sehztqty.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxdhqpq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zaucoikg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjldosd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrqfdah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grttwuwq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgvlhnh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvfwyvy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdhgqui.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzaxeox.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2byrepwki.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2niylctyt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eurgnrom.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sogjcqjf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkhxxkb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2knhuikig.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yraqwpom.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vojqxbio.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgeudzn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbuhfux.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pzskkqil.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ugedtvam.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrdecwr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2svwqnfaq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gljlmhoh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jxktzbfm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkipnju.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sigifxqy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpbtbrx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypikikrx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvtblit.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2domsxpfh.html


<!-- 参考信息 -->