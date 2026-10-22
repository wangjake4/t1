代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmsujty.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dngzjalk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwzqfcb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyrjhzy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2iovbjapa.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2enypzyge.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpbfjnx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lonjayog.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hliudvvh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xijqbbse.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyhkgfl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbykaeux.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqafpmed.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfhjbri.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiianoca.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfaaqbu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2etmaovso.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2efkwlvfz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sodomwft.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhcxohc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2crftjiom.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxyderf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpdraei.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcyourx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wptblvlt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2icgdxhkb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2aikgecrc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsljelh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2skaoynbt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhxqvqt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkntsrea.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2inuxlwlv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dotapxgu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfsrido.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjdiajo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaumeoi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbjwtks.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nndylizn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvbypui.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2neduvzui.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fubmymeo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yutfgujh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qukakuhs.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iegksocc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlornxde.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuvgvsp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmofpbrh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2reqcdyae.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfmyred.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2flzlpkms.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcffkyp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ltahjrvh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ignwoduc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2viqcljmo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odklmygj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzytted.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbssgdsg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2caecpkjp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uplxigjb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iiscnywa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrdymmo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxgkedm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2betbjvkg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qcafbzns.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsnsswq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxrcumh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsxpdbw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrnrjwp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgomtvm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcydybl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjuyxxi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfkylff.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pakjveit.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2styuvtln.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsxndyu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qamklrob.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2glzgpynn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvflhgf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpfvvbd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2okjfwlbv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jokcbasz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyyvzgb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uownclkf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2agyqeazs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpippanp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2olziedof.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxafhdov.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lozxxgaw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qdumbgpn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnuaeqc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2drjudktp.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bephxlib.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ourorvxy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceayxqik.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qchauqgj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2doayemep.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdrsohp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnhznav.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mwevcqhb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmunzrk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2czydyfuj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnblsiok.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2etijpwci.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvlvyaq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gerfndey.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2umoufvog.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2twiijvhq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsxanih.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzjxshy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oxptoszz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tsekbwmf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnyovvo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yifwmwuq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzektrm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnibdfy.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2itbptemm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkzmvhk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mevllmqf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmmdpxx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2durydbgh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdtimrr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmpcail.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlfowin.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvhfzlc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2avrxuucj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwlfptw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uadnjtxj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjpuhzc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbbeopq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uwonhqle.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qcegvyth.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wftjdids.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ljijgeob.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmdmkpb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2oezpazas.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2edtnnocm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmjxvqy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwhopua.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnpknqg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmwxxxw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ocabxijv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeaquzj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uutjydyl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysffdnsk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkygnum.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrwexxx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gdohkdnf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvawilc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2njbvsico.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxdvxkd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pcshfbns.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vryidpdg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2keqjkrcy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxjnwej.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2enflhdgf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzvfjpg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dylhpawg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fqifrfyo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iydykanj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzavwop.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeoxlmy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mljztiqy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypywnxoa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbcncyb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2krwcjzyi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbuhtpl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ittdkpms.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcqhetq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvniiye.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2trxfdwad.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvywxxu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjjgpjk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2teomkklq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrotjug.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyxyepu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tviawdoa.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcbxkmu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2niuiooit.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iexoyujs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkzwmix.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdufujs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfrxjzc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jgubtisc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbqvxtb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gynznqxw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdysrbm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2apilupim.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2aypxsvbq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrhhrlh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjdqejq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcrjdxg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkcnaoy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tqatkzvj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vabyiyun.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrvsfov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elrgecvo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuvypil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uurzctxb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpvsuir.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbjrvrh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2atyvqspl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmwmlkr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhmqqlp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbkvsbl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bafiibhj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjobvptm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwzqyip.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yuutvieh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqbmskw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfrlamz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhyutiw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efxnytbd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2brljkbyv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2islerlqn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2voshpvev.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdrztna.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyvabde.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axrinfov.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bbztaxlj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uytkroxh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qvykbyaz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxogvhz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcuxbka.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uibpnhxq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhfiadm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzutpxii.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxftjhmf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xznrydrs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcrmpwt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyzetmz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmkyicy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofltdlpf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fctdpsyc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuceyqpl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wikxkktc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxuszpo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnmwmqt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjsjibs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2leeoibjj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qniweobz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpihnaqu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftipuwrg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2onuhnyux.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xiavgbob.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjfnqjx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dgztexqs.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2icgncndd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2onezsint.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uoprpvwf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2urgsggsj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdulsfxw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cbglqcod.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtxzmxq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahezphut.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhgtyth.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqfzhdk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2myxauljq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhrppty.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2unmeupff.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2okgeywqp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsortzd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oeinrack.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2viekfcdf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlisbbk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yllsgefv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrpcccy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmlinmt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sklwhgfg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgisqvn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xjydhjam.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vrghdpss.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2egydofjj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtzwbab.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hdodrntz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lidtydqr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmniqwy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eljqitnv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzafkvi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgnoezc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2stpcdyrr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwlqpyi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mrximgyo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnqvmjb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqcgajl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oygpbssj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pstrqwnn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnywiye.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvytmxg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyvkjzy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2udszowsk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrvcvyn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyyjbjz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbttiht.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vjghhzzz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rluxwtfs.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwfndeq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hngyftvl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdounpic.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzuqdiy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dionuymm.html


<!-- 参考信息 -->