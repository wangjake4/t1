代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2twwtpjwt.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2adztfhee.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lormsgym.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqwthaa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeziqkm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgwceig.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysstiqcj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqvvhkn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2phiclgbu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gfauhclt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfqdpsj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fynjotdo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuaicck.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyofjmo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vwklgtke.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fltomihj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhcgznn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ldknsdet.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2smuqnzrd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ircoxiud.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhknkjv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnhxsiz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2prwehwmk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2naghxjui.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iifvxduv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2whkltcyi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjijicw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqtzfyq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2roqaukcc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2egjygxlg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdyovhs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cixahxgt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnefegg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yhedzvog.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pezfxwyv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2geznjfay.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fabvxzyj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgadzmz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2owlffyar.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyjgkdt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoszjeb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfstzfy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otwgzdbp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgokcwm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2flbnqbrx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tflpzduc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxuzezj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jijyndjt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fumatyjw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaptanr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zencrlxt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2erbnwcje.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skyxeecz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdnzqga.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozathiif.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2keltguas.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dirztjge.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zrejgpdx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ussejqcq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dmenhdit.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtvdokw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cntxyypg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2arnopmry.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvagktd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qlywvtgf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shglrurx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2izpxfvjh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhlmfsx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvskpok.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2huaghrtf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfgqcsb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2icpvktjr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2eudsijjz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaywnbs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzydwzs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjuhcfh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtevncjc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2owksrskr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lthoorpm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2umhfizvp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2irftcmap.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2taqkpada.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrjnfll.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jksflbje.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2sltwusgj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsdmvpg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jkknjpwj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vevkhnee.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpmlxzm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hypmatwr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aishbwff.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlaqomc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mgigdaqz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2muxqzcnb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2omqvvsgt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekujmhha.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pzorryvh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrowyhcw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2chpqjkgo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xumbmkwb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdtfdta.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2emkkzred.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzyotlw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdtltke.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cinkknzd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2invjrixw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cureykrk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tllejndq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ciharxwm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gajiwzvk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfftvetp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrmsvnl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2byeqgmuw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfpregp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfziktyy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmyznom.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edgmefbo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wbezzkqu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzedtbd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsvntvd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbqziyw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxlirff.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfopcvw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvenzlp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdvpzxa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eazpubob.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmehdax.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2khjsoirv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2npgpzbdq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbuqjyb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gizylszu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqfacaj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zevcdwcp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfpmsro.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxmqwcj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjnisal.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiycsda.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlojomg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oscuhbxh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gshfmxyc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdhekfd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tuulwkhy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sagmphoe.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwkkova.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atddhrwe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyrayvr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ulytgmlc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvzrnxh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbcjrfw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmuegrg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pcugbbpx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxfqlrw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2psvbeezp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uskcjvve.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2blesrwpy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ylomslmo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eytkuoek.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajliarlm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbeqyco.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfirkfn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cueilyfp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rigjjuao.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkytmfd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyiagsu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfbkyhz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcruyibb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvixlgv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kciaygvk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpxcerz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhophuop.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiizdof.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcusyxgj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nzztoofd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kagoagll.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaqkldo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bskrdyyh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lkttqyjc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnbjyci.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yclsrprg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlyyxzs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkddzrd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2eztetgwz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cavnetim.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeuelqv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2eroolzmf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2agerufrm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwfgmfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pamrlkit.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgsslzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qaezsksb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrrsucf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgdwhzr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gugssjvn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uctpadmx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2urzpllot.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtrzxri.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zomyiycj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhhykiu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2imlashla.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkbzlpw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlehtjjd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2semlclzf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuzgadj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbztbmxp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gliyhjeb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfeirup.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnohpxl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ymomnxhr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yfboaflb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbdladt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lktjfgyy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lizmmnwa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhpdahi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2igvjqttf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwtmmls.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxlfgxm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiaymww.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbeahkf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2weqtkzto.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qiutchml.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dnysrmzn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrgjaai.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtevmwe.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reqwcjfw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ynasulzj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2acszkkoc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dzromfea.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2oistyhiq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kethxbpy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmcgxok.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ovynbbfa.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mhretnnb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rssptjwq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xstjljva.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuvbbqp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkkexod.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lexefmvk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2omntoxpk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nilzqhnn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2getjasjb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsecbmu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bemuvynt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbncyljw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrpdvqg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sltalpth.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcseael.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kattiyob.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nllxojgi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cifozqwb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbjbmoj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ihigrvro.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiguecy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2prbknajy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lkptqhkl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2loannwme.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyjaeoo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyocgxqf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ktiziwct.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtyqwnf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsmxsfe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwytpeq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2liwjrjty.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dehoazos.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2txksqckk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lepjxufq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmclzcv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2iuudiqys.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lggifepo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bphzerwc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtjaphh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2whfhmukf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zxscyzwz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cogxgrjq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpcxcir.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgqntlj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjgzxmf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsrykjk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2olgixebp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiemqcv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uprwljuw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoatgeo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fgszbyna.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2loooztfp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgdxnmq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpwnkiq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqzecku.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkczgtn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mexljdgf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpbjqfq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lgolpekz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iutzisgo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cleexeja.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzzniuk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvcdvac.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xljaenww.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2szlgmksu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmdfoox.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rndigren.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzoptxb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xgawirbw.html


<!-- 参考信息 -->