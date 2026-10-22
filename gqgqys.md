代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yspebubh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvydcow.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdxxaue.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwtrmbs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kppdiekq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hgldidwz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dobvalaw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyjbqls.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmknacd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2smsxgokw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2wckjrpqp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfnrtyq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fppdpnxd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fickcykq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdefhxp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzqskpa.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmfqwll.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hiinnfsu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkipaql.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xayndjia.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmajrfk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zaghdzxh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ibawafke.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ctafmwff.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2doxffehs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwyrqlg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyapcbh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjvmqmw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmuhnyc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ibffdzei.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbooyhy.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxpsnbp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrzitjr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pftdozut.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2whygrihd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fozqosvy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdrvevy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzwaawb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yizdzgtl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgindsv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opbiwxqy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dokehxcv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfprfxya.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbjgska.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwjhtfj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvhzzpu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2alhphmvk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xigbdyug.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2smgoriah.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yxumjrwi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2krycdnix.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vznpzzkj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbqijya.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzxmlmp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhyfuaz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2asmljmxg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnijoyn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbpctqu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbamwpt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2arvuqgnd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxkfrfq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyhnzgj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmbxvdy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuddaho.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxkjxxm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kotqwnqy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ichmcesn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjgerzs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxjtjwx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsahsxh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xchikqem.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoyqjad.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jagdjiog.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbbybiu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kworynjx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkghuzk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hbizktlz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjehsyhh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fvubdtlm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tumgygwc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2evwgtait.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfwajhe.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqwxrei.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2adimymwi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbjiwwa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnuidgw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgfufif.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2criaxzzp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cauqfypx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvywixd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpharxhu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbsgsgh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2euycwjll.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsymrya.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnepufn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnhfnxu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyyqbmq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwcnobi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxhslvt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsliovf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrtjfhu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzwkxmw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvayyvt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyenrgx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjijqhyu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkthzpux.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsucvth.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2apjllmbk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkoxomz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjvjvuv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbucicue.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2plchsicy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyzlhto.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yarfqobw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gmddvxfn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbhcsuc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2atevuoej.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyslaxaf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdysxms.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmtnhui.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjprpdp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxqhvxr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iotkldwj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzipdnld.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvnshkw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlyyyrd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfyboqg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxfotko.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2twnkcupm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2djmrfbid.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvbwltn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2odpuecml.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkfgynv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgpfseu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyozmxc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiysjob.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpopggm.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkaelmt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2etreekci.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfsrinc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzmkdfl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ullncjrb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ctncixke.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xunajrct.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2grcbmbds.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnbongz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmjqrwy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2iechdrux.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vuixzufa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyfihse.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hhehnaxk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2psrdarme.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrxaeup.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oggwifle.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnxbkkj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmwzsrx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qlejvocx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeswxfg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bxytokhx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmfligo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiyrbkc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbdxype.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rudoawxl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxdlnii.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uprgfbju.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ledgwxeo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lcirmkfx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2klynlhxq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhsdhqo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmqylwa.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2imlmqiep.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybppfhxs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjxvcfp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2snbeqfjm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvfzlfy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2twjnvtux.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2arqxoepi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrktgcj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgpbenp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdlamnz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qjapjexa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtwyhid.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2sipzppuv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqzlaji.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dimhsbmu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pkreofwz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbisibd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iugtlwjv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrhygpe.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgekqzai.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmevjqm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfizmdu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2prrwniyt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2snhpcbrf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njfpjwvr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnetlyd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2obfelwjf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjyahdk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgwvifv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eyavwqhl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzysrrh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzujzgs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaelvjn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rcntlbkj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tzezurxc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oresnukg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdhtykz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xazjtnel.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hagtxuvx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzscaqd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwghgur.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dycmunyp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwglbmv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpiruly.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvdoqek.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjmcsjf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtgvvch.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iprncfjs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrfzxey.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgpdtjj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2otnjknop.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpgcopo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkmlgfd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2grpphgfj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlcwbtm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlvrkip.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tugtoxdl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuwddok.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuykufqq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vomwjflx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwthusp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsfxklt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2obrwuhcz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dvylhfqj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjixgdbs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrxbdwf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbscvcmd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuktlzw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcupypb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqekodl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2orsjwjji.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oobfsuth.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ryodpdlq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrcdtlb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eztihbhs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kudqgydg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2phkvfdhu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rfabdzkt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmouoijs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcfoosc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzerzats.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nmndmlkk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnimufx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvytzzs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2etglempv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pymypplm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ardcnwdh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2owrdqmkf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxlsper.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfweczv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyenougx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2icmetzpf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bakyascd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ziehpijv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyctkop.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nzilinjg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsrxlpx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjnpqsp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfyvszd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ejageqmz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dispzqut.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcwjyjy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbhytld.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mtynrecf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eueafyfs.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2coqxkxjs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hqawujug.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2voeiycaj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfvzqun.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrgqgvt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmryqtn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gerxnddb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cefmjtnx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2exfaxwqp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjofiiu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtwqarc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2psrfsvzb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdgwkeb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnbbgbk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpljvhl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aczttakf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrhuhes.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmnirhj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbxsvvg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpjpvgq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2czwsaksy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdyepki.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmbxsvj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qyeopius.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rulcqetj.html


<!-- 参考信息 -->