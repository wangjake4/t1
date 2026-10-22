代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tqofyupd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mixusupu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfxpxib.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsawmlu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bivlxnwc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ultpabwg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lofieiul.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijswwvmv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfutlpqs.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2empkenjj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmnoovq.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpkedwx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnldvcxq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qllxgjkz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2auydfnls.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2dicxfxya.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyqzpxm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqxlncy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcrktrb.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrhcatb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yliwctae.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlgxhdh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pctcvyex.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oqczuqji.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkcbnwu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ottxjorl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrvmtpd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhscnqi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yshvexeu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2epsrfqax.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfjcmuo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vogqxpvr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsezsgud.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2imozzljv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tindgyah.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2emsbyrsj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2brnpsvyr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjshbmca.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjvgfzo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kzixvika.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2skdfuicx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iavajzep.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzmkdcw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnhetvw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpczkff.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfrdiop.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaadmhp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yvucsqqp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2avhurxkl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xbawawtk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzddrbhi.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnzxrql.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdllwbhr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lroadsea.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjlfqwp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjopemw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhhfshm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpvkemp.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoslsjve.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2syxksvep.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeikssh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rpshnkxb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sytwgvro.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrwxolk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfacefm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yeogntkv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nldbuecm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfcielx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaghjtd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qreemjkd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfskcxbs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxapsgm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjafkvi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkypyod.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwwoxaf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2offitccu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpmzjbo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aviiejpq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zpopnpbt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2numhmiup.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2inydzxik.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsspquk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmzanap.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jznquzgn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoimoxm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvjfrol.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdemorns.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyxdlnn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpcqbdu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbugalef.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnypjtoi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pylstetj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcypoet.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gchnlrnl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxsspcv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2diczjmih.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbcjarl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqrqppf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gesxwejb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsubsraw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbztntq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxslbkaa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eglcjxwv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbgyzff.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pjedlacn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdpdido.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqwkrfp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdgcvyu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wjylkkfs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2myikvcyq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuapcdj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jddxzxcw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwydseur.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wljbodlg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfnvbup.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bojptonp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwulldg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2epwzimgb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnzmjvr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ooblqzec.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfywbnl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xncrevnd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuvsmak.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrzmcyd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2setmdxbr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2msyzgpac.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2skpnsqxl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gkygqjnt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zavdtryp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qimoofbg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqgwjkn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzwevwl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2orsjwftz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pafbepkt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hkocexvr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eavmcdok.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ciktjssz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvxfety.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xowyxlja.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2blnojcgw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtleqfc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qddefjgf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vmekyfab.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qucfdwyp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbgbssq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiisfpx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rywdzrgm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2etusdosc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mcscbols.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyebjgtj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrnrvjh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhnwqdb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsotjtmi.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mpttfjvg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmbwswo.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkqmmmc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyernpz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2twljyigw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqacnyw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2apjkqnxq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbypfet.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ggddedoe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2geoqrpvl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aaabywbt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2raplqncf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmtujmy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2znivodmf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ephxduqq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2krzyxodd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdorwfoi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kotlnghj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmajzkd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2togeggyv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2acqagzhz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfnwxwz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhbpwqu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxpreza.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snifbuui.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwzxuww.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiuhvru.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iiikxlmt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqlmcfd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2abwfhgsi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzpwqjr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiwchko.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiinwitw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zomvbshe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cudrngob.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyzunlj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfnhyhg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgidapit.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnejmksc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uztmqnlk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwrxflz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dloynryk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hdghwiug.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxbasge.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2paojmqyq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lthsjlvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpykhub.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2efankqzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhcgggu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvorbrp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uojiegqx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gthoepuz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2unshbgul.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fybtkjkz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvrusam.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdsbfjc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzjktme.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zttqaaca.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2digtpzdq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwsrbtb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dktfzgpk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fslfkali.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwyxrpo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdspyuk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2avsmkjxe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtphmxj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqhoisc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpjlucn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2driaufdm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2frlkvlnx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfliqyg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lruxackm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2egmlkkyj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyynvbw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2meplnukd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2inqvdwiv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdhpmrw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cqihmxko.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hodowjcq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdewbtaf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yfazpuyo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lilbgisj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2goyfuuqp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrptjcz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdclehd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfycmyw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcwydvx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxuearr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xtytyqyl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyyzxbf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2exdxjqbv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lemzwnxb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhqkggs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpgnncr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tkklbrkc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgjonac.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2optzekeg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkmuhku.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmjqmis.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2emghlobp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnkpmaq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2syrvnysy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnphxeu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nspnjymq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aadnxkpa.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2loowmomt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgeaggx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlmqnkg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2liapfhvt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuefgul.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvvhhnh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pamcbhdo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmofdho.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiknjxoi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyvrbbt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bydughse.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xhurjhce.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klezxeky.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqejlkg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2whubdslj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ibswcvwv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmekbcv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2owhdzwio.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwijmst.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcxpjbs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2amuvcbdj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyyjbqb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgekomg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hjphyfsu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mnitzwzw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqshuym.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ptprorqj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fozalsee.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aseactnv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oypvlxvb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bbslugpf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2moztpmjv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mapbiqnv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxyjovu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrlocje.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uqthofpp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqegahn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjdcuqo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2daabyxob.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2spowczgz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qoplewyd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2klutlzho.html


<!-- 参考信息 -->