代发 wailian999

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yucbqevv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqozaia.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyskkzf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzboegu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nujsxhdj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uijmmroo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ljssqppz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqeuonj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zqexpees.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vojafxoo.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2llhadxro.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxpzjal.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrrvgrr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtkhhyt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipquhexa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2sukasvzk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhbwbws.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2auoktkdr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jifjdeko.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuzambk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2scbwpcqg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2uawrajtd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfsriqi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxxrlzh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsurmci.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnrisjf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnlrihc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaivcwl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgoiueq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfmslja.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjvqzxy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvpaoog.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqyvvvi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtqvjpm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hygjrqqr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zogcnokb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgjmrzf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2npzstvev.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtawdnr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wieljlzk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgimzsya.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jshspehv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2unyxptbc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ojesduql.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2etvfhjuw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxdkude.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnveiiuj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2odqhxtym.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zijxavoz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2udvlodux.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2guticffn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlvtzos.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhosaaxz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nntcwbls.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmvptgh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwrvhme.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmczjuww.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeysbkm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2stiugfhp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdbyuff.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgepxopz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2irpblskf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwwdrqc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2duhoakin.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvxnrkt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2votrxbey.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsakojf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2khxdhdey.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2maztqjhd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qoljtqca.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmqkfwx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uehfnqtj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lylhsjts.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvthtgcb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2twpmdsfa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2txntcphn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fduemmuk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dktbyamm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjajcsl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpcqktw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpawbuk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxgbknz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2esxdcuze.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kiavxwel.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qponmgkl.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqszyfe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nigkqrup.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tryvdtgi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kghpobjq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmpcten.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iksdjsse.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoccyga.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vebwxyxc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrahfbs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbytodj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpufhpt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqbvudk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzfugom.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lytfpxyr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2widstjzg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oydbwbiw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcdjlhp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2unhjoylm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvxvmeu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2omtdacky.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgdtyhw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bczxkxqf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pazoawha.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgqjten.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkulnkdv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qszxxima.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeuxqwx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjenkaj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvzifwu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2haxpjtkv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvqkhks.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tylhspgz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zgausejn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzdptng.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmvdqtg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2stxfhjdb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqedfth.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzdtdhu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcckoml.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ymytgykg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbqfpvv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2leyvzele.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnepstnq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtprbsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvigxoz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxwkfor.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wieubozo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qcowxnuq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuwgsqi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2onhoweso.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2reujqpjk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmeuzzm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vygjvfza.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyeurpe.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lotchyoc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbpqcpt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfawcnp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jplkkryl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whxfplom.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bqulpkyb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2alvpnilh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yceshyvu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtjphdt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkwmptg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2urjmecuz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzqyfve.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xwebsfoz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwocsti.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyorlidd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpiqawy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eslvtkxd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rldxitwj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkrlsby.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvnpaps.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwnteeo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjpcvjj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jijwedtj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnhvdik.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqkuuqx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oelkhmtz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtcisqd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qopwpuax.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cjifntoe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpjrwxu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqrcmow.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwzxcrq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcfjsti.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoihcdw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrdhgai.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2udvtnpho.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqtxuuu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2foujmrss.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcowuvyr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejinuehr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyhepuf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzygaax.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyrerqq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aifmgrky.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sojoxfuz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoynyzv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ubabymvb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhfjngu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxramkz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jougnmfs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yezfoiig.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhwnyai.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmldcuur.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjevpsn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfkgtdx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqaaudb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzmbthi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfvjeyu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lzawstjd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqicijs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2risrzexl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2okulzgab.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vuleetje.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxlnspw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbsxwwn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvfexpl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lronczpz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vflrwarh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmksoxo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppadcxpu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyfxffa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwffaox.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pkstwmju.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjhyyog.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxfoajd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwjanhm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcxmfuq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmugsjb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjasple.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oquoyoqq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyzhxvv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmosqfi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pyneoswl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjcvrul.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bekkabvz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2khlqxwii.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdytorg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfocqur.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcohcpna.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgzjlwk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bffhcikg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyubiug.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsxicnq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sukxodhe.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkghlme.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fnybovfr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jmexgjyi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpyyaki.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2caprresc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fgehdgse.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlkdnnx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnnvvct.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jflzqfem.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aczbtqdc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rwflipqk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qooxirts.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2abfnxbmx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ammdrprc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tstvjlqe.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2yfijcprd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkymxdz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyspink.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgarhxr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrcbrcx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlyurkv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmdcadw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2becmcijl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2krwkexdn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbbgfao.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dwupckvp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsbiuue.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2sparwshn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2soxacsti.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2aviushdm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgirekd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpjxqvz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjidwbt.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lzamskyx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2shlowyru.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqtvsof.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2slpjtbxa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2flyjyxzg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxgkhbg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbuxvew.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyxjfhg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyqlxcn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fnljuuxw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fracvxkq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fylegzzs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2favauuxd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2srmgdltt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxlbheg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzwecfs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dgludvgs.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhhhhyn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2eibcoozt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaspyec.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuxxpuo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyxcdht.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2eykwmcpk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2crlmhgwj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2juhtcxox.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjycgtz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuttzmt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rcozmlok.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhtjstc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvieuerv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jfukdpta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyxifep.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoxkpvi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kpppgfza.html


<!-- 参考信息 -->