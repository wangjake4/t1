代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2kfylabho.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvfnwsy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2npevymbe.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2busntgrw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wytkxivf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoaprtc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhofctb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgcsqsw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2puvubbil.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtrhrzy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoysccs.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2plnmseiu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmnaqzj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpfgkrr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwelxwdb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjjhjpx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhnfonn.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2aksotzup.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxujfbz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2naysnusl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqfsnhv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2awckiadj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcxkrlg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuetzcv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yfespfqo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkpoiaw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2megyjsfq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqvutbh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoqsrzx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kmygnlbr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nacbzrbd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xckhaloh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwofifq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fddsxkpg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdslunx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2umqvucpg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyxtxfs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2egolluos.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwvrzwc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpxrujm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvceqfc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wruspjyo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vhymbnmu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2stxssgpw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzuzece.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uniukukz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsdulnf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqhikrp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2leeqolvg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvccukm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqixmtog.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwysuzb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxkjznc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ibczuamt.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwoirxe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vybkdsva.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2evkotzwd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgonkric.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zecdmyoa.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgehgxpy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsloriz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrnqipz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsoxxhs.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfixgazr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkuhkvs.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2arvozryq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyrthpq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qooymzgo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiuhiyq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzuirqt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2boxwprot.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2idoczcob.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wclsluph.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxogtjoi.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pflghuje.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuznvep.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mhacqcut.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcanksy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eaogyjkc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkeqigz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2alkywciz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcguqeeg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgtyksj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrppjwpt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2iplqbkeq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmedcgcd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqztjqr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsynnjc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuejfxf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gczhbjmm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuqzjtm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqrtfjc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsfmuwq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2enuagwwt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmcljar.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmoiozj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2opyenart.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rocugfue.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnoxgob.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2smkcbsxk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hxddzsmv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2oborchvs.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaqauql.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sncggcco.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2heoroosz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjranuk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdlppvw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2leukzrrx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xooookkv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmlnxub.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pogmtlny.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2snxrfpxh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtcrszz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2revowssi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2syuonbzh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jagiomcv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2haffmdxw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmchzmg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfmpxqb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzybwyk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjvjkmv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpnchku.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrfrcca.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aksdcjil.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2crltvyld.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsqkdrf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiatnkea.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pmimahtw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaydqihy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqyqkwc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrtwfrf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jpckesjg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kocnekfy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgzjlqy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsynygx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2clprcupr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwvqeyw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjbhcxy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvhqhez.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvctdgk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nugshtow.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtawcrv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xswvzmsn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2feqqflnw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqdaeom.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uicnjfqo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhaeyht.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2msvybarp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtchavx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lztusufq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vaojopha.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2phedihno.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hogjfgcc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zddnssln.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jknyzihh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fbysajof.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeojxdb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2algvbdrd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hpohwzop.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvsatzm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wszdntkg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkpchae.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbronuc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2poctwxhl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qvouqziz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvbhqor.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwgjmbo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnxjeyu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwssakf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2emlvzzyo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dysvahmo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hedjrbyf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rahrchli.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzrwpsn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwmpmdz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xwotuwkf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ymejvpaq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwjmouz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jukgqaux.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsirmqj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpeykmv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znbltfux.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwvtrwg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfcyluu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjdhvej.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzsybyq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfasehg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtwpvin.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wujfkhrn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvqcenr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcrthvo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgrdlpr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvbkldu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbjleur.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqbkjjw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmwkqhw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2meeqbfcj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kywbnlac.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlwdqqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzbzfdd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcmfiur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lacspwam.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2athfkfcv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwjbwrg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjupegv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfrypyx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uspbawpc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqwejmv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsttkmu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2whpofnok.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mupjxrlo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbnfcku.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlpvdex.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xnofjnla.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kihrntoy.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzdomwa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qcerstef.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhkmyys.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2krefaxlr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjvaeyh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ietwzzbi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lreeqmmy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wcubmxeh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtimuxs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xemctvds.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtjvddi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2whkfqfbg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlttpgr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bvszabhj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2odciobwl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2loqhsyti.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zirwjmdg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmlatdo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sdstrivb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2itqjggaz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2deknpzjl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2evujvogc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iepeusue.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zsigcaap.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2btzxgcpt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrwtyxb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwabyeq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fktkatfm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnhvzww.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgnlapf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvhuqqb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2khzfzinq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vawmkplj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2unyjqqyu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zacihhoj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcewwzdr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fmndpnbp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhgthsx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxdageh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmqwgsu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sidnuhtx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mprwkntm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zaczeivl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2odoghogb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnuvyto.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaynetd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdsyavg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjquaop.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpavkzeb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwswdrc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ekavxruh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2upqpmxcd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxpznau.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyrbazx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uagxkanf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sttcyxqc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xglgedqx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jilqlzyb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkufonf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2izrkzyog.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdawsty.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkumwry.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyjahrt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsvwvhz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gprilthq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzttrdns.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrjgrhj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pymiccwo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wkslsldj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfpodam.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cezhurgd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wwswefcs.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuamdao.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bvowawrt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xwykvrin.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vomsegqh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2euvjpngh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkjpinc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgvdngs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2izmtpcuy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmxsvux.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2undejlpo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dfymuglc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjyjhfx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pubvkpnn.html


<!-- 参考信息 -->