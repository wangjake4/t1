代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdfddps.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gidxzndl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnxjksd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgndofo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxflrayf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2szvwinpw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixifnjvu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xypqfrbj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2iidajsfp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwomhwn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ospezkvt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyxvymw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zleyrxia.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsdbtss.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlwtnlt.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fljipezf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmyednn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yamlqpej.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kooamueo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kpttkoux.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epxvbmjh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2odxbrziv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjtjdae.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqxnfqk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixflalec.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyerthd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2twmsjfpq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxoolti.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wunesoqg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqignsp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdfddqh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmrymnd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2smibatkd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzpipwy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsgqlkb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmexxagi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lahwhmcb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsondkdb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkefvvt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkgtnor.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrqyuqk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2siyongwi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuwobfx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2anxuiucb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qogctjrs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdanesna.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2saajrbmg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gonvirvg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2yaguhgoz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmtpunm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrcbvjx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wcflyzoe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yllijwcl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2igkceuew.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zglvastb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpsxloo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtkzruc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnpevas.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xohvexrp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2doxzpdid.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rwznqdeu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfoktwy.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcuhqjx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsjkizt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fpewonsf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2guwvvegl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2blvbxsnx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmizbhx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2brvvhpvc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2endriamz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tlteslql.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrlaeer.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvruevzf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yohaeway.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtzuujb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyoyiuo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2spjichtk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2nymuzrjm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrlgjea.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsrftpu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkgwvwn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqoxzyx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiogesx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrdavmm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2miqaglup.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtfemrg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aleyxflg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lroehfht.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2airduwvj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eghzrkcj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgojdri.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2evpehtqg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhdacsk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aexquufy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iauewgnd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mroohkuc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pcupfgkc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmwfuyt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2frizbtom.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbejkubi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdycbtk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2txegtxes.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2miahtryp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxefdgki.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzwkmhi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yivrzkdp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lddpixra.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsacrok.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhurhwf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxuezja.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfnhmem.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzwdfge.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twzgcgcd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzlxbwe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2apfjwmup.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zvckfnet.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnescelj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ixievuts.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mteebymn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrnqtgf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkvyqka.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxnagvz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfifchci.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bokiknon.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kaihabtp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kccycoed.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2llnsmodn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2oegfsbcd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxogfzh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnqsbgu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2akhglhzd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2waslpkil.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2znznxeqp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkujizyr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2brllvera.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrtbgnx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zwblwxxo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyluiekq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aloauoyq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzgxsiy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2whmmrwbb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyocnuz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jirvells.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bizvekqy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmcfykn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwjeccx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2klreecse.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvttgxfp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mszaaknd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmyvpeg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xujcffel.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2azdusqnx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2znmvkidd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gqotwnmn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2czkbdgcz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmwdosm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bksakanv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkszlzp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2njegfyjo.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2knkbrrvo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrannkd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnzdqmb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jasxhvoz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbinmyh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjftysa.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejauvvxs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qimyrqkr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjjzjaq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpoxduj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtczyhz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjdflgd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pglhqndf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hrirnhub.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2quafnmlw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvazezd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgtncjf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbuwtie.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjaotrk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zzthpnuf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgbcgzd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaadsfe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvedgagt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaasbbz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpxxkdh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2evtwnbki.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbyonot.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqvsirj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2leeuksxv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bznbfatv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbvkokx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdiwmni.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyfgivy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zebdyxqg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjbjyfc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hffvupbv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfmejbj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjtpqlt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2emwcmsax.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eljyvsil.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfaibpa.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmongpb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpomazwp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjuofye.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwbthfo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrmhydv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkrmjvc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjtqbuh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdgunlo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsqpgwv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jcagumum.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2skbbacgn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhfhqfp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayavcbni.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nasnvvwt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxebdwqm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsftmqt.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kipzjwik.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2itxulhen.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtqvnjo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvpsaif.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpoovpe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bilowyez.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfeczwp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbimltsg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrurgdy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvyjwws.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyojsdl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsonydb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyiruhk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2smbwqmkf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ooofussp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fludviqr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2msflukwr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zincqquy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2iswmlbvz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kmklrued.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyroniup.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bcycpbyz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2slzqzipo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqwdgsf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ldudgmql.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2heqylyfy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zunagkvw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2erxudcgw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsyufgm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2oqohotpz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nuocdtce.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuwspfg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlnwwfo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2taontgbd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2veyubmoh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2puwtkydo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmtrohm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfrjazw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fiybkjqj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2odqottro.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2babsrurf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpvyxpy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rzokqskb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhjlqrs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtzcrcv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmotzvv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbggqyi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhcrefp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fwibukbx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdijmwo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlvablv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpdpatb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ovopfubv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcaodzf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2boittjtc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vthrpnhb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pnorbybz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xdixoere.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mvauloju.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjpntdi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcnyltk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ertrhwyg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lqndatku.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgftctb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuloafj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqsxjej.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhezcks.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jziwnozu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cajnzkxw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyncawgx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzkkyfn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2spcovhjn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ljogeold.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jmihepdu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2yacmuybg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fawrtdtw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gxogllna.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mftjpaqv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zwftnbib.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkohvme.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jkixofap.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2piqehzjo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2moxffiuc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kotjlbia.html


<!-- 参考信息 -->