代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzriuzn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fealwyct.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wnipoxsw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjhmfgr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qogbxtwe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgajiwj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoysudk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbcqrrp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mquqhjme.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2llvxmyep.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyopzpqh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvwsimr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yajkhxbg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2epxhwgzv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mveaepwg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zclocayj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqboiulr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ickgqmwk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdqysot.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2shdbtkdd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdcmxoi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zzabnoxs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpvtmjk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqoyxwz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlolhosv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sowqofbx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2txzctavh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rderiveh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2doyawfbr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vudkmull.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sidbfcke.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ertkzgbu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wavwjbwv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjlrjez.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2okzztmsm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtckowt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iysqwyyt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzzxmhg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqojanxx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yofrbkxy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xifqwuac.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xnetxmdx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2olokuemm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2plwwvkhn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbftxfks.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bfadrtnv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2azrbbnsk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhcbimx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fnszueiu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsufjvj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mskjcprh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2njrjhkyt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mamyqnnx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gevbwesv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrtsicn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfkxfow.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gukrcktz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppanqdoh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlrzayx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2argcnyca.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvefdhez.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwufrrku.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhiuzoi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gyybjdlo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtnhzqz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlncxaiz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2flxnmzcj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rrarxfjb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mamezdma.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2oknbvwmk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvbnmwy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdiewdr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2skmujgms.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtsiegy.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrxgmxh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pstxunik.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zysfiwop.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qibytrdw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gorwlbrj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xghastvy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzvzmuk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiembiv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnimbre.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2onxpzgod.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nqloblbu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2svliejjy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwytcaok.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tedicdsx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2edpdigsg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zrthkoal.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjvvotx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsfbwos.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoawvedu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtctegu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjjjlxz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qjafmeos.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmovvxn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uiolwqco.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxxbkti.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqawaezl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vswstfpk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2buvejuor.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoplwvk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxnearj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlbhidh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zaseopyo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnbsxmp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dernfkck.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrkaahn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2shknxudx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwqnqhz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxooallp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxwouiq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pytgqomb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhsyfev.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jknlpqbd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaffdzq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wegnusgi.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oogsfnyl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ignjpyge.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzvzpsj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yknebueh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqvjnbb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqosczjm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2etivfgid.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvaopuu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sormqwgj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmtifmk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvmcfms.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fwotndll.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xayzsowm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzzrqnx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdieauhr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbbeoxw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ozybgrvv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoybnuf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frpsgjkf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2abzihctf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kftmezvg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2beloddfo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2prexvmwf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjjdjlj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqbgxjg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyzmaef.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbyhekk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhcshqo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwvvaad.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2yqowuovo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gimoiifl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2luiwhjbn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgacerxt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnbivja.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lyujoaiy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxrjbkk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgmzgqx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqwjdps.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgbppis.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpschptf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mljtkewb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmcwnhn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qczphruy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqapvxw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zrozzvwx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2erhgwaio.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yugmzwvx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzhirkj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2epafqlzq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2oacvypkf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2juxmrabd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2egtndkro.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdyffif.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgxiith.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zfezwslk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tysumeey.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmhuujv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wabtjquu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2akytdjpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atsycnks.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2umgjkvip.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2alogcvcl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvpbcqg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tpghearw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoockslq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pktexigo.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsieran.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzbjutn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtomuvg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvidxgw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pztqtkck.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dccdaizt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbrptii.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqrnlrx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuvbnkm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpjrwts.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2odmdgunm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnmgrbg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxjlirh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfxhpvh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfxmkas.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zgckaqtc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwzecrx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuqtgpg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtcqhwq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2juubievk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cqocykge.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2judubmld.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ilibwzrz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzivvdr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkbvjbm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2aieiwpbb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgnppgt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awkvwfxd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmacjiw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfclllm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yqegalqv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjjxktq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfziqkv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpnwadl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fajjepbj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eolocxbi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhdjslv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxgcqiy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzsfgbp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2udwfwnfp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgghmioc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsmoyxy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjlmwas.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eryszgqw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwfmzqe.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyhamez.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcostknr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ikppjuew.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyxpbwd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2awkkckqn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2udbcgxii.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2epfysjit.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nycfxunc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rkikcupw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxhjnrr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2btvfvdgp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2phrhntte.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bnycgucb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2phxibzen.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkwrltx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmclqzzi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrmbspn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxubeudf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bctpdpmm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxjerrk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ptipusah.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ockonoac.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dnotmlwn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmxmiew.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhhtdzk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnazveo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxsxjln.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjrwkmj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rifkqdhw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wuklgxnw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rtogfkrx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2quvjgpsl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkimfkw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ezijabfv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lcntqdli.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkjybsv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gljlfgnt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrzzgfy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akcsftsg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hsohylwt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xmerjhxb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqxahhi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkignxs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qddfjtvc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2egzoiyqx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2crdvryvh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoquebv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdleiub.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlhumja.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2himjewqn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzniypnj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhtflrt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pitbdynz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpjseeh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ggprohpx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzrzqrl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2drhorkmr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2knpszscw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2olrpdbxo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwhgjij.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btyvwjwp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhlzhqy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lptrizig.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2byvjltib.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiapbzs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaotebk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wobkfccp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2uejvhtdf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sotslebs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ticqfrch.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uahntzmg.html


<!-- 参考信息 -->