代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmhqzed.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mewpucyv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsupecol.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2msyrvzqk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2aufvirty.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nerervmo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2agiiafkx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeszewy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrtoekz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwcyajp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwqtglq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wmheusre.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aeufhzec.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hdstdruj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vchswspr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2woqhwvtz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mstqvhdg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuinuhp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2pscyesuw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaizebm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfudsce.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbfsigk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkambuw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2csydnnbo.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrusmzkw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaqedpa.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoszkeg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2npbmpbbw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2koztkyfx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkyupnn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpxpxyl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvfucky.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpqagfw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ezikheih.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnnujof.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fsldhfqz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhkhjlb.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oijlzjmu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2socexlfk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkoovuw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkzhypg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbwqhue.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hovgkubt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyldcam.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xytwmfbf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfonfzrs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwvmmau.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eipuzgjg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2buymiltn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zhchvaht.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoscqle.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmcbcer.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmmljql.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vxecjhlf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tewxwgmh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzirrpq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cehgicjt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtjudvm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywctndxn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lhekbhkj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ackfheyx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhshltyu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hrifenrh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gzytungp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sumjecjd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jchslhap.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mopmtsum.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsyolcj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvdnbjw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgwrtwy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uigfydqq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbkkbni.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnapftq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qatasszs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqtnfim.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xtidqdzk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzretjb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqgovzl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdfkwyb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrvbkyk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2avmkosvx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzywmua.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjodwyi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fhezwhiu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mojjlkns.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdejxpg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2svoctmrh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrvmwtj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yekfudsy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcgfnqg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rjevmcqa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvmujua.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wpckjgby.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zithjtkm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2khafyzsy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2phoziket.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcdtmyl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqppffq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqotjtui.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqjxrxc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2scspkiet.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nvawjvwf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjcmrdf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jrypevyc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeniuoc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbrmikk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvfbiay.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkphvbd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2skypvfgv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhttcokg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiqbklu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjxcdiw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wijxloce.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbbncrz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2srlbgmgd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwjzcao.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rafiroht.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkdtqqg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2frkxxtto.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2assjmpks.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhwkmbf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zzevfyal.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2khfalnlg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfdthmi.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxjcsce.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaclbqo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqwaokl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnkxkts.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqpexgk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2yelrqgea.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qciaozca.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kchffllw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oibpeisl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rffgcooi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdqbuwj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2htfvmcli.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gowrsnuv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpypugq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hejuuikr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdgpydb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2weuxjxen.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlwilnt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zmictcce.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyuxljg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hogbpbyr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hyitkttd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lomfwzsx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tlphcepe.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2guggauyp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyblxed.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2quirivro.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrrpvwm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjlllee.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2igixuzmz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2evzcemzp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2whdihwqk.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpdtcnd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxpwwcx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bprmtrqm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwytkzb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pirczzof.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxdlhnh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoqisvt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rihtcsfl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2axpbnksw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2suhvnaoc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fapkgxce.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaqduas.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhgoqzl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyrlnye.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oipkzbnn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phvpcoiw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcshivu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jggxwqdg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2oruecwic.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdppatl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmthaww.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2caltkugn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfkybmz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcmxsto.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxovpowr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2temyqzgb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrbtwfx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkrdiul.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2obugcnvn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyzonwh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dytqlfjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2juwpstov.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2blwcoygz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snhzrond.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqguhxh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2feevrbfj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvurtib.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jerirfvu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzzwell.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyvcqrw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhpnjas.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2umkknvhn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvzfxhn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzytkpi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwyjhlr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaqsjdz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeumndsu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbcsiuw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hocrkxfm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrbdboi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsbhvrc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2auyzltjv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfrfkqq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xqybucou.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwfmjag.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2maiqmgav.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ydavvsbj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsrzehg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyrkxgi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lziiuicn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ggomvanr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjftrxfo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xirgqpeb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pifvnyyx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaadqng.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkidkil.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ilakbspl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2muoihoyj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wknqurnb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwuguuu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2glmwrsvz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2utpgsarl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfpqabf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nhedsnck.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rbumveey.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfvfdnh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdxzauo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2caywmyjf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aplohhem.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqkqtmv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dykkdhqi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmjhddj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mouakjpn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwdutug.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2spvkhslz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcxajpc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2budyjiyv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2corvumtk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfexoid.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvmleac.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvfdpnr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fkadszzv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2joatrdto.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vhflzkxf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsadcej.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pifsgrtk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxcclud.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nzegseyv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2azsltksz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbdhumn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuminof.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnuphng.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skueoqsp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzikvhs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wevzravr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jabdpacl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjehxax.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2acwtctju.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xakpzdbv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmwkqgg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkandbh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2obvzqynp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbxbpzw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hasxwsnn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxiafcg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2atrjfklq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaulppw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxmmlsm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2skhvomak.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eshvvtof.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnbyvra.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtbcdyw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqxmeib.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brvmueqr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2afvpjnzt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nixchyma.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjcquvq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nevlqnto.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqmdpzf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kymmwsxk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tlahsxoe.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2radxajzx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfgkxpz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2afstacxh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnobfmg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkfjckd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeimbxl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcichhv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mundogur.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2onwsecua.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2edcwyvxz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmvrkwk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxvhcia.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2znywwgbv.html


<!-- 参考信息 -->