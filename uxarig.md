代发 wailian999

);
来源：http://dali.zhijiandao.cn/Article/details/gt2heveewzg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vccrvjyb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqybtrd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hoomadbq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uscrncuq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wazkytgz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwkryue.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2oyosrhoc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fznvwlky.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2widiaige.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqeboob.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xeupkafh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgvsgfh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnsptds.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2appxmyzf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ojikbzmw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2euzwghnt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlvnoml.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhsuedc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnhvdze.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mvetuypr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rimuiefq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kkumlgdy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlmzkly.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2znvvykob.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaykgmv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tknfitdw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmtcdlr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwprguqo.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2syhfwddh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfkcabd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bogjglcl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sphyhrih.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyvjuyk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pbalnaod.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iokmpqac.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnqdbhh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjqqbgu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjxaqyp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwjippt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmcxivp.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nlehmevd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnmntwd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnsooit.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpvegkz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kszauogh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2viwztrtd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2srtuxuuf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuobuwz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrmloyo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfejtjg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ommzxosu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udgvrhag.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpbfseg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmboezk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwzkrao.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzxalcj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uunihufv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjitgbp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlcqjgj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdltsvy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsyeolu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2agclmblj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2iznabbyv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qwopsskq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2djgpjadp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2egrbiqni.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nmssxldo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2toeppght.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpoacei.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ilytxpje.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktblvwga.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrbvyiw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsrxrxl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jocsssgy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2niwezcay.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaidcnk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrduaej.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2egbgbdzn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dafrsbmi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uekqxoau.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrqlgvx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vecwkrtx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2evelznus.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fihqrvjt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2oketmlyl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbebqzh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnmwomk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxgexqt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmngehpj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gaunrzdo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeazqams.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2peshprhc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2spczaxwb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2edsnvyjr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuuxuof.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fntnvqcu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2adpnxbtx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2prxhcyfu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwweeyro.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcinrpi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2olismkdw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcauxvpe.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vbupgilu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvdracp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2loxmneay.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pitgjugi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2njflyask.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeaylmb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwwiydr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyrbelj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qxihlzfv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eavmkkfe.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uizovaue.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfqpxtq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2avzbhskb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbmutdt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgikpld.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnjtoyb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yznatjwj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2whrlodkb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zstyzhqi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzduscuv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlruyzv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnelkuf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoedfld.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjyiziq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqhnujk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pspgobio.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajebnfds.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhoomos.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqocyzc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ievfqdsc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2myidqzut.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhkbkub.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2canvgikl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvxorbj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvwcttk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lgooirui.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhbrwfy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ioewsfsb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlpretj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuuiqpv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gprcviru.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jskjbjpo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2upmmeamv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2khrsxgjn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpqxvqr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqtpgww.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hizhfdnb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaehylg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyyuhtk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvhxbwe.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kaobzwsp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ktixylzu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iolcpyfw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jxusyjhr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rqngqzgj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lokildnv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2azkadnsr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2abtjbcvi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyiekkh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfmmxqy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ateftbor.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mywnizis.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kosbdowb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaxpedy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wduxqzwy.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2atzytolu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzamewwc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdvcvha.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtofvub.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ilozdzzs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cykzxihf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2okqktxkx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdoauga.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qolaoiur.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wggriwub.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwxnljz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuzdbag.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjyrtfn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lengwndo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjriwdm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcvfldj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbeddrn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrzlwsw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkralji.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jrehpjig.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrcmgjj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqgkjuj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiwuqtt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txzrhvbu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sajutosm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovstuvng.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2smdmlkys.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hhijtpwi.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkxiwfy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wunacptv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjjgxyn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbkhccu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtjmcqb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cchsocfk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuitouaq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fjldfzzz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2znaigrtm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eguejtni.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxbqhzr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onkacsnp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vvniucqo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwdeaem.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdlqswe.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2niseswdp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkllgoq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2amctdukz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ylalmygf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ongybwek.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjuguah.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jetibcmz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2doylhwyo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpgwmbj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqqqemz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clcualwg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kwummgje.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyqzdfi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2erqfoscz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxchpbw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kywvrygq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsmcepi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jojfbrrd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnxiubb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcmhnin.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2czquwolz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlklkvr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqkvwia.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2joagjjdr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlvtftq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgxxllb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rncfhhol.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgbtiuw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2clmsdpzz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoqclxc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2sssqqths.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyguptfm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qckhbuit.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2buywyljr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnsykni.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvtejpz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvhwtiq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bolczimw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrtmysd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dukruaid.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnstfwx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrguprbr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2brujmzeo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvkvzop.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsfllhn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2emphdoll.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjxqoel.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2swethxqt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tcntulfh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtnjemx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcneeji.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxptsvoc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgmrjuq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bdendtml.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkxljuo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsivbnw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuagdcg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2znbzguss.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lppwzhpu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhdjwcf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2unxndazn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpgyesp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bhagszbz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oieuukxf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iecugdzw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqnsefj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvyyhtz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsqprqv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnpvudr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqvuerh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kcindiqf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efqlzpxw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rizqxzwe.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tyihafdk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2odxwmsek.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwncuvd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxvqiig.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmoyehz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2htmwzelr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqwettz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uerssedz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nypurkbs.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdjbuxd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxgzqaw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuuaist.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwakolm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqdwaol.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjwvkul.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfsoato.html


<!-- 参考信息 -->