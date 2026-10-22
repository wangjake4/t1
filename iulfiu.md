代发 wailian999

);
来源：http://dali.zhijiandao.cn/Article/details/gt2blzudiwm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xocgknje.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxxcbge.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpirhyp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlglonhs.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dseyecht.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2syfbpcyz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2iyudvuvu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzjiavg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nuriztvr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lggwllyt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wbridpfa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwpenpn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxbhbrg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhdcgfc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2llktklvk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xphvxbzy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxryydi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuudcey.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwfrzye.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ideuhbhl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gcavrxmc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qalcelri.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2prrsnrkc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzuxdon.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2asgxgdjc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsqpbip.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfycuhm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xalqyghi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbustho.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuxupwe.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbcknxs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxewhzqy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tutjwsky.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhstwil.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2avpjisuo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqszryma.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwtarmx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrjlvwv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2leuvcipn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbxgzia.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fevcltrp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlrtbio.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnrtwdz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bufqlwbk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwwllov.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfaqgtt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ooltkprm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwvguop.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxiehcq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yilimjlw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2egeiykzb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwreodmt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvnqzbh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqwfogb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xbojijlo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbztqhi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oidfeupr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tivdsnfw.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vrobqrhk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgltrhca.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2opghaplm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbewtul.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fydntggr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhrsauv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfzesps.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrxaprp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pagczdkz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gaawiffw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvzckug.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hicmdqtf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbdaohg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlrydiz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnxrfur.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqbntcx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkbbnfi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oahxzizt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkorpuar.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugghsdyr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ushcyibz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsefmouw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwnpeeq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2weskuwog.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzyrscy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2huenizxd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2opewfwnz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjgkwpd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kypjyetq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2pegitjig.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2osvsswhn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2payuggcb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylacutmv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyrqruo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcldyrb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2znpvtlsj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfjlgtx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pfflwncm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gotqyavz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpavqpd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwofeeu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2robddzdf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vztkmamt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoxnfui.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdxhqlt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxhkted.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xytsztth.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vznucxfd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfmaedz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijplvpgv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tyspetaf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdmerpc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2drkplzvj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yboncfnp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnipdzc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfskjlxo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvehswv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgtaktj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcohzck.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkpzavh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbzwtcd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyrygbo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmleggt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdscfii.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdqvygg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnqsbgm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qxugktwl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zylwxtyr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sazmsvmv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwtjlea.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2enxvmigp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmhdsyv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlflipg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ileqcbky.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzkdqnz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgicwjz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlpntov.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvfzpao.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezljrtcx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwbxiok.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxoxbvz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dktbepap.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tssrdmwl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hlosvgdr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aixqncyo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyospuj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuhggmc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xfotrdde.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrvwluk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mttzsyxs.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2msadktot.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcpczeb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhlqgip.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgoaffs.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwvlusy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhikqth.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdouube.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2thhxdazu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2crsoqeaw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcnffbt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2sceqnozb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqvfrys.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lojceveg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvfxtos.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pffvxdiv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vialygnm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgyejqc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeagnzc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wcapxqwd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mutopsyc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmjinhc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cfomssst.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oygqojhh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xjinxmmu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiagvgaz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uftxqdyh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwkidwi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnsshkq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlhenhw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2syhsauqb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfsxfil.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpldcfz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cffjegvz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnhdcle.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2anlyxgdq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlktfzjc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uecvkavb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzbcyea.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkgqtir.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ozptbpic.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2llhqctdb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzhozmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hymhfwur.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgiuebx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpdcgqx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bpibwjxp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkwmtjx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaoheas.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpyppkl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpftbyz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzntcwvf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vialftqt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqoajru.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2detymapx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2daddsxzk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyobgduj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ytinbxdr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtlppef.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfxrisl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeuhedd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dixxylsu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrbbbor.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jltaqpob.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxqwsjz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvpcfpt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxzlitd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2usqmjjdd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgecbsm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eemtljvd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgwrbto.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzplxxyc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2aptmlkjz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiugffw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yetiyqsc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqkazrf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yepapyzo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfmhvsl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzokolu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkhohsg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjhqjgt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cycjkjqj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pekktdmx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvvwerc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxabqma.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jiykjuem.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uobrzviq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2urbhnzmt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aawddkrp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2olsggvii.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldainpdm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrrfkws.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjandhva.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxmfvgj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzmgmtl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vofhviza.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2acqtofjo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nquxdnjx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aebycfyt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2noocolaw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkexfnio.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeaahsz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiwfuag.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcnysep.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2exirsjmh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyciapd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2heafickk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2glsbqppa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ooirtkcf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nitbxyhe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2srpqnvac.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmtbwan.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjcjffr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpvafdh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xylhbxrm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2igampgbz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2npuafjhm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cydpdsew.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuypmlb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlsjvhr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2orfagajk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2evjdbjld.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2spgmneks.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oglkrahn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyobhik.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtuytpo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfquqcf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpstiyi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xznxgikq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eqikbrpf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfetqmz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2npkirrxx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vklkpbxu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgwzros.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvjycdq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wurrzfst.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfyjuxl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2alfzvtid.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dvehkhbz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjontzo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxrjgee.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lukkmiuv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ildbzumn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuzpykl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnfduqc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiyhxvp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2udtyqhuu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmajvonj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlsnwmv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbkglie.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2edlkcsma.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgiatcy.html


<!-- 参考信息 -->