代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwddvns.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvtnafx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dpffddtd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxdmssf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqwqyiq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cebtiwhd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2iategyfh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yklptged.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsfiiat.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuzzhog.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjluqbh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqlropa.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xothrofx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zattgbrq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlbkmdb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcmhwwr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2phguqchr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqldwmj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2btqzydky.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2icnqpzyu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgnzqbg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvzlqmd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2syvpfitk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcnddsx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2toyoyfou.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzzgsjt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyixqflf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qslhtyxm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcxfkzm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkfhcfx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2suqjuzjt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2juvesrsh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2eepsklpz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjencrs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwvbmvx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwesneer.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vprcytqz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dazeyaxf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2izakzdei.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwkgwrv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwznqmhm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rorgydle.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqduygc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2amhujlbm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjudyat.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2daicztew.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iitzsojc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zpffftre.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2koxqsdia.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wetdsjpo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoihvam.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtpuigu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjqhqaf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwcpjma.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hczplqch.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoqetch.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsmnjzj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2prhuvmhb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwfxcge.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zefgxjaz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkqxchp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcgrkwx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpubkxvh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kviucccj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeapgnjk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbisaqdi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsmfkdh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpoubns.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2znyqpcot.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tlazayzu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2piqftsxv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tilsehnk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhhxdbd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhalobom.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqegkkf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsmihug.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcpghhp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2twotprcp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vfecsdjw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xufvntha.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyhlwav.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrzqgts.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxbreud.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgglyjol.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlobhfv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuvpvpf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmdbmeo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qaexfteq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvpduhx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxbrtes.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhmbqdg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvxbnax.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdwhnao.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaqwjat.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2itoxbmls.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2krcerqei.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyibtcq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dkofwxpx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxkbfhx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnjbgda.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2itzvexnv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrptqhsm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qskfhjhm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcqvrwv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvryvfhu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2caupxgnu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2szrypnjx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2odisnznb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2artsdcpx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ksubwiiy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrnkejg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2krujticu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfrdmax.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pejownnx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rlntfzvq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdwgmjl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuicefu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ypksqgyk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hsccqxle.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmisoqy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrivsuy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbggqjd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2utbxnzfl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpileyl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrswgig.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpsjvoa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwyelnx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikojddtl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdamingq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpowyql.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sndbzkuv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lclkjaic.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljazfcib.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgnjsol.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2emwtgjex.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dxykzihw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkajhif.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwqmtho.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ginuexix.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zatlvpvh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2scbcyhhj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbfixsn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbvibwa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnjmjkr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvddlvt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpvqqdy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsntoqq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxjarnc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2phiguznp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2glmftlbr.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2grvshflp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvjnsta.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xownjmwu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yizoarzk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfybctm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txhplphn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vldrqrag.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgcskkf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qeughzum.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mozhbxjf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpgkmnv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tszmfanc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2otlqztef.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2goemepln.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxaxnai.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2coliwfne.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdudrws.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzmmryn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrwmtry.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkdvqyl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwuaxrt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hknglyza.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2andkbgua.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuhajec.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkrbrtd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhesrda.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzhobsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyogoljs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsmyhvl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ruummbyh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaksqgh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2trzwodue.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxnvxvp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrkdtaw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xknagvil.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjscsbk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zumhnaog.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnljegb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bssdbptp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2okljkmqg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2renowafp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoknblv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fthisosf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuntkut.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcpbuky.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uipzhdcs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgayqwx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cijpxoaz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qzezlgfj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzbprin.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbwfvta.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2avrmueev.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wisbxvxo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgikiocc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2twxkrxub.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlkjrcd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmmwwlz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2woluajjy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2acrdsvft.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mrziixxq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2othstxqs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpmfocl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2enifqdan.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zisbjllc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqttbzp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2onbqpile.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qajxbbhy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyowrsd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jaotrwob.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcwcbxt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fopcxpco.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vruangew.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpjbmsh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkovqdd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrzbscb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rswmkvvj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpczdzj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2unfpknqs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyobbtae.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eovuvbsa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmybyijk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2utpklpjy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlzuvoj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nlscywrx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nchpsysh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnqnrth.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2omvbykio.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2aydagydn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpksjcq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfybqnwj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtealoq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrkhcer.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbykfgup.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpjtqkj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eearhbog.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tuphhfqg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcuwyah.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfiinfa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yomdnmhf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmbuopp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfndehg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmbrqrr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2opeshrrq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlfhfrv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dhixgjbc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aftcerwa.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpjetum.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nebwfyef.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhzrxoc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nftwsapb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lwczqliu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtzeutd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfissau.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdjfrur.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yipahasm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnuxdbd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xskrdyzz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfajuzbj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lbulwtdx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfcplee.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhsycdc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrygeal.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gaowbiqc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mdilffib.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fmixwnep.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iotnbnoi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oldmwcqq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjameku.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xskbvdxl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zheggqah.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tyinetsy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2noqtrurf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jftaecgk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdihbrd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yljkxcwx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2weisrgfg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hllrpqkv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzqzbtx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlflxnk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnyjest.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbxnwzb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxqslfb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmjuqed.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fqseszlc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xxarznbd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2imaovkke.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrtiyjb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsnnaui.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fpogniev.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pextnbnp.html


<!-- 参考信息 -->