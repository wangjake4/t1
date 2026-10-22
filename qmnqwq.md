代发 wailian999

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hirtdzcl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkmyxhr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2obspldwx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtjwygz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmyygvv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxtgnss.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsbayim.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2soeympbf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2inuxyisg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnejlhc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkmyjey.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eykiupcs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbnytfc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeggpxf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2brbkspfs.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbhxssz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2recmsqgs.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jyypixtf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ojksfxms.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqemqfj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnemcjy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfilued.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ylenifop.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2emliyqnr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2buyenosa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqbgsnf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfmzibt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvmvwyq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmnebcr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyyjtix.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjidzupa.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pbncmpiu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxctoco.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zvirhuyn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlldwem.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mgldyuaw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpabgwd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujryasfx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbszogs.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2baykapfd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgpbkof.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbtltlz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcarqhip.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2smdrdrjt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2acaszjnw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pxptfeuy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnfigcl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqsbemk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxagksl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzksqfwg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhvtxuz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdmbafv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdhcmnq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdpboxm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmizwnga.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jprwozmx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nghwsclm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aabfczup.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqzzkkq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2atayboiq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfniswud.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tiodtkjb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2trtmksnm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuosnxb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dlivojwq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2umikeooi.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdqchtw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuzbdck.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gpysstoa.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiffgbv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaiayxr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxjfbve.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2citrfmrg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhuhdup.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kzibqtpa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2axvzpwoc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmqpbgk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2penobxhn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2czppiltt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtijcoe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eutnhidp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2khsutrmn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2uowpohot.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kiusktpb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzmoado.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2giwqayto.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eopcbqiy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiqsfax.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tobvbvci.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnicmtli.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mktosabi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2uupjisqt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pctflhme.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2baqsauta.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ktknwtqp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2agrspirg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcbkfew.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbetcwzi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aqekfayd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcukrxg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqbqobz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijikgszm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2demuhxxh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgvqwjz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiudzag.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lrorexuk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cnybxdzp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyhmpys.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnpuzun.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkxgbgj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hezrnxrj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wzucmsgr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2thmmayaw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmmyaqj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnfxdti.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2muexyanu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnuoijc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2syyxlbjd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcldyvi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtapjtc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoljzwa.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2awfhnuuj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcdximz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2eddebdat.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkvmhdk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iitagafh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbdipwz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsdtwhz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcctzqx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxskmtf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyscxdn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iifzswyz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2paiotnus.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqwijne.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgfdaol.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzszobqx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lccqurky.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tffhfxdh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2adzrrtve.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcxisyd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ztslscfk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqhfymx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2glwbvxyi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsnhbde.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhprjotm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jaykhxlz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2myabtczp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkongzr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yztwpkor.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2urjntyhw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qnltofiv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2idklqwms.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeykxlcg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcmelzq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dguvagzb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dhflbptv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnhckqs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuilrsa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhurjup.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jephieiv.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vznovptg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwrntlc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnndued.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qabjgttf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2slkplqtt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybocapbt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrkixxo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lrutuvmo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uakmgpep.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sebeswkn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnplgoux.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blodfxho.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2enscntdf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqylufnr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjysxuqa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oukamzdq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyumpsw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omicslzo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqsdubz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2goyfwzpe.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpdtbpw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpugtrk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzidzdkv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyrercg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sedeyokl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uuokhbxt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fngutxou.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrsdgyy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfvmygp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jamyqtsb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsfertj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lafulxzp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jerbqapk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcdtqqq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xumyvvbb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyzuhtg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrbdryi.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbxxrsv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbitdeh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijauvcxv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgqffub.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oacpgijs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtonbfuz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfekuwv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlokkij.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gygduzxt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tutptmmi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkdsztw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2esmruniq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lncvvptg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kasiwbkq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zbimkvgh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlpnlhb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnsxrzb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ituqsttk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mhblgqcw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnvivin.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkbjmnq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtbvecw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxpbxdx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaqiyty.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqvvjjx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bmruvslg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgigjro.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxmhojf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2swtnwvij.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2drfpicof.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thyakipg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2urkogvgx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tynrskjs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2suugebzm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbqomqs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkciefnr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2abrgyndo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwzcphg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqrdytq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mujbzhlz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyqznmz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvfcdsc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bgakbnxt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiaciuj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgvwzpu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfboqsa.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxwfrka.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhhjawp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sfexbibx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqceoip.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrydbmy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiblqwm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2copyqugi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pczzhoty.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qamliuhe.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsyhpex.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2eotrxskf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2sreqgmci.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2luebzupi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlpppjf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dgirnmkq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2htudrufw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2glozusvm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrmdobq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cvstyxkj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bffqaxqq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyzhqrj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbomezi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpqznrv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2muhyxhnx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjaqnbg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrflgsd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvwumkk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtdpeog.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeawwdo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkebfzuu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2oooxewlj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpwsndm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wseredhq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvagdth.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnkoxoc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pbesdpyw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2icuuoqfu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjcfqdu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuiyfuk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnzevwt.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyadbyfp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2owejziri.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhzoeyz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nahhkxug.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzcdrbw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuueoxz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qxszwnyh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiyorec.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdyscho.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcnokdw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lframlwf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aemboevu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwpexoa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ngacwjhl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eljnqztr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjutryac.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pombtnyu.html


<!-- 参考信息 -->