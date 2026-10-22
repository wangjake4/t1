代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmhjsdc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2soyhhdfu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfjqoiv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hllnfuwj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sutnkpfd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnhmmzj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dftuipmr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vejmqlwt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqzvjpf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcusnpct.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbfshhc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wersbcdd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xctpfonv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2roctwuvo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbmsfrf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnngdjq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebifgqru.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wilzrbft.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoktbvm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfcwmwv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhvbpxy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2phcpaslm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzpmblf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhwybsz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpdlnah.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqhqagi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdkgshc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aydynxir.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzakfnzj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwuvrqs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoozktb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kihckdmh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoevbwu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxdchmz.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zotlwcch.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sztvvrav.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvygexwu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nxopsvrc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdjmuoz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wexqezrb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnevhoei.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgotbxc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zefrcccf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwlansz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfwitio.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvzjjmx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxigfybq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2oewtfmdq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2edrwjdqc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oytfvxlb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2agrtsyot.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlfhupc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2oweuvzno.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfvvaae.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqybassp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sahjskaw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqzgbgb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpigtbx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rndmatbg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfuovyl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tynuvvnp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcssglk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqhvzzv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2orslvvfz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhmmobg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmtaogx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxyfanm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlnemsk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ookbqqod.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2twozyhyu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjmyasf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2izkcvghl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxfllzl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2odmmfkyu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gmntxpcp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2otgyedms.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbfuqpw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjljzxl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqvndkq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyumkrz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2aksvmcpz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbzupyx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpdadar.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2znbssxoc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sozlecgt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkcjbgr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2yshucvwz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ircodlhy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyvbxut.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2canccmlu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlforvg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hxymjixw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lujvcjcd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2htveamhr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2trsrdetc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2axbjdzjx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrcyfeg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbasrvj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtvqfgx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrexjbg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iwibaziu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dewykcut.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpzexjb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bglqyqwm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lvplvjcf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yorptozw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmzorpl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2snwwjbad.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtlgqpm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2drqypujt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2owubpwkj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hurshppo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkbuppx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlmsxue.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwmousf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sphxbhlb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvixlcx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2eesvrrai.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdqjnlv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrjrpnp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzjnlvf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmehecu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pubcvakz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzorrqq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mikgljgr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fddnkkay.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiryxzc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtdzxey.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2luvyxhwg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vysnclzc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2emqhuhai.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbdbjte.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cvufazeb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aovqmssn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2arvtabii.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvkvxqd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnzvajl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdcebgo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2thziujeu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2iapcwkad.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2twuekbty.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2txjwaqby.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzwgfyq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpcibbl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdpmheo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiluyyk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xsegtjsz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzxfkcf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndycoydk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbunfov.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcjrbfv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ytslajxi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2munukolz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2romyzvuw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzsdobi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqfdjju.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmjphyw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpneifa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2adbjzhqk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyqznmi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2juucbojm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gqorenbm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdchxsfk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsgseks.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiyyouy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkppzcf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmirrhd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuhzyls.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzgllct.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbxpmxw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxskhzh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2irykxlyc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2clsflmgw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwumxxxl.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qvewbymh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnplgbr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2euduhjbk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxasqtl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cltmmcmk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeowvrny.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcfhgaw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdcxhqy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2iylqzewr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zszisfde.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jldegkxr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqpfeew.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrspesdf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjmydzi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xagqlequ.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gyafrztg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mweqrmzh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcldbwt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbzspyo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zlatgvhp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2otxsmcft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnvapkq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaoxmdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwferyme.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2afvqtyug.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzxergk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2poeqhbmx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xsftxrlg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeddrxwx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzyjltv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdbqaft.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvhkmvi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaoxpuq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aolxxioc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vosrtwiz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qredgxch.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mswazkvh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcdpmpm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yybwokny.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qoainfxx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tonndvyt.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwnlpnv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2anfdasss.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfobqpy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oghietwu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2titqbhej.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mplfyizc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zznemwqf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2beucrmin.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzwllan.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hwffrruo.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vateuayd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaviarv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2quyivwsm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtervol.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2enjmrbxs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuxtvav.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbdjxth.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2foodooce.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xoksvwlu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2igjgovcm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kavvqnft.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eplfbgnv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmfmwwv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbmbvzg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hcphtvfl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2maiuwnnl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgacvtx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2npksttyj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdsqdxf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpjmykf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2biwikqvh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyrpfqi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2haqezyhu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpjwmsl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgozsdog.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2boqmmfyz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xphbxwra.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvdcwqk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2evxljhsk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2edpfxdiw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhopnue.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwerphh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2llpqxdhn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxuhbbo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iasydgrh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgrclte.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zbolxdka.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqdokoc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsbefdf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anmimbux.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeyqdcm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sntkxqll.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwessis.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xukskydp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oenknfge.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkljytw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ucncihor.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2asruqcva.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpmokcw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2idiekybg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fukhrhsw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhqmiry.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqdkruy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuchlgs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2neyuatjp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cevniafj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iibmmzwx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjztjoj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yaicrztr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwzcicv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlcslcl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zzguobed.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdnzbxr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2naseowyv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrpghnu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2swkdonno.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gwecobpv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzbuqta.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mpycboyf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2injrjxfz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjqrere.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfkwemh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eefboehi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqrscfr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuswovj.html


<!-- 参考信息 -->