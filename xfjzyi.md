代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyrurlr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wrivqlwf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjhsqdx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vypgmlsn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpfltuh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xkreeqeh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hykcsigq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsezsnp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wlulerqw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2oncseptr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrixfwa.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xhffupna.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmoniiq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdhiodf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhlfaeg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xnijtiye.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cspdnsah.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkkjlnm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2khwnnngu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfznkhc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gngwhlme.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qislfosu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwviiexa.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdxivlk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmixiuu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrcyzse.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2yowthtpp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjzkimq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwicjmwn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsfxlnv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsnxupn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzlicfi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lljxhuef.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxohegc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vobhedva.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ulckgfma.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyyyoio.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwddtow.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxrlsyz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaputsg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmmjpea.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziubgzam.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmtdrvp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fteessha.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdhvwhg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqmemuo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nskwrohp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvbkbif.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gecvflvl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2spityped.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfypdrw.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuzsthw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfougqr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmjktpn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2canmpuqh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwhykdr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2taivlmqi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlojvmwp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2grynbzqd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ckprcbzy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkwshoh.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2noxvzawx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmphpqc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2olmirsrt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaklagj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nplkkqzk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yyolmlbb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmxsjss.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpxvzih.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pydhfqnv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvbbxrr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2knnepubc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2btwyfxwy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2snodsfng.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxcmhhh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoowjze.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lylmuepz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2phfizqag.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwoqfne.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyfejmw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cblamhfu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rulklhap.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gsubhaok.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqobfbhy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2evlrbsak.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyefxbct.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuplbrf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrrlzmz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zanqibam.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgrvdvb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmlhtga.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzrpeti.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rrblrffe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdganmo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvmaumk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjgkuol.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2svlcrkfg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cquzomgv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nehlpvdu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpzfmww.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziryygjk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhxnrgb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjokwmsc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vpedttqk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2btnwiubm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkmivcj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mztfgoxs.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2noepsfvk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyekqez.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpsbpby.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iubjxqjc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dxffwegx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yytudxkv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sybopguz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdifkbjw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjndpng.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkejbkqt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2svrqrhxv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2sygiswlh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjbifxg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxrhyzl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyksdgc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmsohuf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdwijmo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlkaatc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xrluutuo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpyusvc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnorvih.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2anifyghw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptayxgng.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdqdltq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbizdtyr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeitqyl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkrikcf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mpziavab.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2truitwlp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmahfpmm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsgzaln.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2scoemnez.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbinuvt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgdpbdh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuifygy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2eimlvxob.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lbesrepr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvjpzdj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjzdhau.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yebjlfuy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcmmjqb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2noykimjr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcfzqjm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rezpdeth.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dixlxbuw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mwocyfpg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcgkqpl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkqlswv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbjpaix.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2glybpssn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrdvtlm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqfagpl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfurmbc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wmknqtar.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqepmcs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoslwlh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2winosiaz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fvelhbtf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekizhezq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2inrukhej.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaebtnim.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxskrvo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gveditgl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvozfzs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yinmvyov.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tamkgygq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyrskpy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2isworytp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjhdipf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmdjakx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxpecer.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2altxojjy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xyobdhhr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqplkox.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wytdmawr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2azbgwplu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjrexqb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2somvrbhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdqdglq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjedajv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aufysbqm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmbxgsw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2exikyojp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrgjlzy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efjpuajy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2thkcbebf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcmrnea.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2krdlyjda.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqguzho.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsjmlij.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2crhaizdg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgberqs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jovhrriq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlwgxxd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pucqedla.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfuhbkm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hkftiwxt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fhugrmua.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axtsymmb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kumygziz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2onzfmjpe.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnveebz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzbnvjh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzentyc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyklspqo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tszdnccs.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgiujdyh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnmrapl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zykavlar.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zplhzhve.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lydoeqhd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yoczhtlg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2haywqzcm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2igfceybg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcusmne.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnthlqf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mxylovlk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdlsmhh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2odndmgfg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xcokdhtz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbnkert.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2txwebzxc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtskqouc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmpxqms.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xahwkhmt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmyamlw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jejconsz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fntlruxn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmpgovu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxnuhbp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzattae.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsxslmu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2artvmump.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrkshau.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qufzfnwh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfaawnx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoknicm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxcfrke.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2acyjstie.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2llgfymqq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mysgozwj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzfinme.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2asadjhuk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkzqevm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwhexzj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfokcuy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xytjbzwx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogncocwu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbmflhw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2sbupayuy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaympzn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaloaod.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2googfbmw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtwnjgy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpneroy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqifnqz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmdjvsm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxtcyye.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kooavtgx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2unqsdljx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hojneunb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2arehwhvq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jndsxnvi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pxveyiko.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rszdmtky.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uuogmtwi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjrxlts.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmmflgx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2euvtgidj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ypecohmj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2arhktbha.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdiugxw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgdzyjz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hubeprbk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkglzaa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhbvsxt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rawlrrms.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhimyex.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2devhllxq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkwjyag.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwmtxhn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hducclky.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oadblmej.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvztgtm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcwfkgc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgxdsxo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsowfesr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsazawq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2logsqaqf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aldrlwvl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqflbok.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjfojhs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tyipzzbz.html


<!-- 参考信息 -->