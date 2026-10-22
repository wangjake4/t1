代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpgkzxf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyvlgxj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2htvzpgia.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ztktohmi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfjhito.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvsfiqc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2meujtivt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxctrfa.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdniftoh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2saasnpkf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvoxzvh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhtddze.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uonnnysb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2veuxgqls.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdzwyda.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jreegczc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xavrkkdl.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sisrluad.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbovqiv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpstxyn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzotqcw.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjcosqr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbinyhf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cvajdjuo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwncxkjd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvobtcn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snmrftau.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zpggwtpy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhazyuf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2janfqirs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeshhmsq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiznaxr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yokkypjd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2blweyfze.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2exdcyccg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzfdqxs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axuwmovx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lduhhbrl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmhnpvq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfejxsw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgddxwin.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbhzebd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fasqnlyr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnhmgmh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkeefjz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyfxfcb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nimumkkz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2obewebwd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lggytzte.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2npkbnuwx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaaboin.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwggplt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rafmikdl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nodklvcj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2efgtemdn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaecyuq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxobhdb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2quduvsgf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwzvcyj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgvffov.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkneggqw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeskgfn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2evjhulce.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghimaver.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbizaoh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rqheycal.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfffebr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjcyilh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwhngvn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxhfred.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaevcoz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhjkrpy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2izmjpivu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgokiod.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wmunaqtw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbygvfvz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxszmjm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qylmnjjh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnneelq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2azpxfffa.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yujadszf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwbsdfa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uchrmjmg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2trgbfmur.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujziwndr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzsfcms.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2unxygkrw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqgnkkf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtvqgfu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhacqrp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqdvakm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2njfzagmk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvdwzpc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2efepejsf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrbnoux.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsigeaqp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoxytbq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nroyrqxg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yupbdiav.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dozafqcv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edcyovew.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2camzycvo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2usobtxjd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwprity.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcstwtas.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vazrjzgj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nupjakvz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjcrlzg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmahnjh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2njurzxyo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzbgbxw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqmzswf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nofkyblv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sidvhwcv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2singpnfy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvjvioz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjcobos.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmoojcv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iukdlvwg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxbnbjv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2imvomoqx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaaefge.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpnfmpl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlhdeeo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2snhkqxaf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcajfpv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmbbjfe.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlokihd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aejwwkgx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyuipgn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kefnvige.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2unwnwoew.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdwidvk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2eadktfeq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmfjryy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrylrhb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrhgsro.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qcavtybn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcjyion.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ikacmspq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrvlanq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jthqnzsj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlmogxi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnziwfc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbdoqiq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmbwaud.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nfounoqe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbuoftj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gkufotie.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umrikxjp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcxolig.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsldkof.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdxzfll.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgcfygu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyrjszx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2slotcpry.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2umkaemgi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpidvyi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2aopqdqvo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pldguxxy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2axttergi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhxoequ.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2asnpbknc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlshdzyb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpvppmk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zyncuual.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iboydpqv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoawfty.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2prabizlp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmnpigm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbbfjan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdukkptn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2aavjtdbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vujrdhtk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fwltfmpu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2livalwzo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnxbhqv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2djuvaxwa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkymtck.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pavhfenw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnjusbg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbzczmf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdwrwcb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzxggcl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgfbwzw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzmxxhm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdosisvv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2frdjgkag.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzehnwf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mskdxdqg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cewvscot.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ntckadfq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcaekaz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gexkunde.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hhozrnto.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkhbrzk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ncynaxuj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjikybkc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjiyhti.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmgdazd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeujeyw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yoomjepd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eichalnt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwtlhzz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpqnmml.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lwifdeyh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cptyevpw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiuywht.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uygnnlts.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gljpkmyr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ximlbxad.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbpdzln.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gunrjzmj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxdpmkg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2blprkpof.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtxqfqj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gykqwkfq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2augcbmev.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pizzlymy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgcbnet.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxchwgp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhxvabv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlztztv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiawkiu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmveubmv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxcppms.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wswvctxw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2esxltgyp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqnzowp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiitauf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bndxmbdg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tplsbbxz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2srjtsymi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2omojinmh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2diwpspow.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alkaamdy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zptcelxx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpecfrv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhhsyyw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsnqgxd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiybkll.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2feunbzno.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaeaomj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2plhxkcvg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqwcblx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxfeeuw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rsktdhvb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2blkrdjte.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhepimzv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdnyvzl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2evnsbtqk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyovjrz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2okhgnfdg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqbupqw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ufztsoej.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ithwpkcf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hivxykia.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkbkalo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xqplknhs.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pgczqviz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2agzhfozf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vchovhqy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2juqvpeem.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdthferr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nabqyvop.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuqyakt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2onycnodc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jchnxnzj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfudpyf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkgcbbe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrbjbrv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2prkmgxjv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kccpocye.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qcduvjis.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ivigxwps.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsebbpjl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2adotdnsv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyyxtov.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgeknxd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yubmswyi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qntwheha.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2sovcmfan.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrjtrsz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cotiozng.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eshrrboc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scafditb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoviete.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qkezjago.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgikrwr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaucknx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2atjxgehl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxwhexf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhfixtm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhciyfkp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yoznriph.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nreyktqy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2eqazaxgc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aiesotyu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jvisnqny.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2glacjjse.html


<!-- 参考信息 -->