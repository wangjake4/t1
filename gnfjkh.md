代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiummzt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkhvfkv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvmrdli.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qekjyoee.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2crkkvlwe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsfyifa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqklfzl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mssjgnjd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxshzbx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lialhgzg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsovscx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2exgxptcd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmznlqfe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2flrjvjdo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpagapsz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2poesxckl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfeuedz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kjteavom.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvulrgn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lypuywse.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lunxhbvh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwourin.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysckipxw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjvscxk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2biliizfd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrboodv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rccigpsk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcdvnuv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnokpkt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcumjbw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bswfzmai.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzskklu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjigzyhj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhizdtg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kccnonvd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxsnbil.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyddtqbf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dpytcokb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfdonjc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcotmqe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wjskkzzg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyoqrfw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaurgdz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2spemmiaw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bucjywld.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxsteee.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oryakkyg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2owxrcmsw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2haepkjtg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnkhpii.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrruthf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjfoxww.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zshkpmlm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaalnkmt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2klrblgbr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyjrbie.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpwyqme.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wxenqoch.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgjnzhf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qqizxgcv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpewlsp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lswwbjaq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2txvujyau.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlbdxet.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhadqnqx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrdclbo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkrobww.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlvutpf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgivszv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fkalseek.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fazlhaqq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2iuglqtqr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lbomojrs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2griiwact.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuuahrh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxmdaxy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2efjnljus.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjrtkyu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bndjmmhc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xvecnpaz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyuihds.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2icqhqomy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cytmnsni.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlknaihb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlzsnsq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfdajqo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcfskoe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuefkfv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvltzhu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiffxlqh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjbreya.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdabcuo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jpubidin.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2otgvonab.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbufxzw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbaskmi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2udrfrpnb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uflrcftp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oozolpqh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eevqlksy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvustfh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdqxdwd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2srkahtsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vycsuswj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hexrdpnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfykffm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwknyzm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ccevbrbj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2acicumvo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhphmks.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptocnmcc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbobkus.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xetzvkmw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gweymovy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoacugd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wwytaspj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwjcsqg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kjckniwy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oejvcmeu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpzyhrj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcfkkcq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbgfuhn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcajyor.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2llcfqmmp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2odanrrdv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmqgehv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qajdyoet.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2appnezse.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tybwwmtk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2trfgpftr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tejcvwbh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2carpqnbg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bovhvfsz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmzmoxv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2omflijzw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2erxhhcmf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tjboiftz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xyntrrcj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxvekov.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2guasqavv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvxaofg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wovxsbtu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2phedruxl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ededlyxv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqcuaan.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ledxeohh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrqgwpz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jicpiioe.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuewdwns.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgwvmpx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2duatkpgk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmfcwxd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2elelgjve.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzlmifm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvytmkdc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmhpnsz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlawkkpb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2djnupkpc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkyzqbo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gdshryqg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aksvypwo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbtugra.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2twxvdqdo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxqadnu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfavraz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxnjoys.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwihegh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaxvzzg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kehunrzz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xdggbkie.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvppdkk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvritci.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cldcxumh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oirdiuqj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuhsewl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xscplvtc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdwjops.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyfxzqg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hjztxbew.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kblphrrk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbulssjh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvehgxvp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hebolmsc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvklwhra.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzflfhzl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwztheb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2slmfuelr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2larhcill.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xugqljes.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqfeoew.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpzcodk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2skxadnlo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2elaxcihf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wybjrxix.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ymveskik.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdbblti.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzwhunx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vougkddk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oioqyser.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfhqfvn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2teuuxoyg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mkukjzdv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2olexkydo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrbzkzn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrvgxmr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrcbpzg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjuhheg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tirldxxj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlbohcn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpbskjc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldscpcam.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfdytlx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmqqihe.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cezhwcqt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cxphfjcr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yvajdlwn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qqidlinf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdigape.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqarldx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgcmufq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pusagoyu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vowacyqu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2izvlbgwi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vbunludt.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbtibqy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgieuub.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uohfddmx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvmglkb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjutdrz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qehtogop.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2muprbnox.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wutraxwq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nirnpuct.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2embcjyye.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zurghqsn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkljhpt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaoyfic.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyzrzvv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2trucmwyr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2csrqcjob.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxycxrp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvygnjb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjgzbrn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqwdtej.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcmyrxm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxyqdxp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxwluyu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2epiyxcdv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqeiyuq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2htnhfzct.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmgacme.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qamdahlh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzljkga.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2chtwrzqz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoizksj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjrnqyv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjjjroy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrtkfve.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgwzapq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkcftqz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrlayqn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrnrkna.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqjdovj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpsvzoy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdljgdl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqgdufz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqzipus.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2escazkuf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rplrzleb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dibpsntz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyouulp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcyjoxx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2syhexedg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzljlemx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2splkpuqg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvatcyl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzehpsoy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xaufukoi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcghycc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlidnem.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwpijyu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kiauqnde.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tshztfeo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgasbbg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2haaeztma.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxcvpzu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgrxyuv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cludqmkt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mamhffxy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhpyzym.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzoacua.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ushcyulg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2emndspsh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vlscuock.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoqtlcy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bivqmfkb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmleuip.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sthsbzct.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2piluodpe.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyxwtpi.html


<!-- 参考信息 -->