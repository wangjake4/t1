代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mjneadjn.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvvfnmu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnxyypk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2eroeminn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhfulpa.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2duberjrs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaoxlou.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2klfjruag.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeheqms.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnmzdvn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjxbqdz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2skcuvwvu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhafndzf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcelqzr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrdckqe.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbasnqt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ingoxirl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2crloqtny.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcehcbag.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhymooa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeamsln.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqdqese.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zidqdcqk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2drsqkkxn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeuzaan.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2aaptzacc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lilyonqy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zprccgaz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfkksgg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ejofwbet.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2acohlfpx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qhefeqnj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zookgvhf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2krmxiabd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmladgqc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlryqze.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2krkttjma.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dciyeeqc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fxncgxfw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2muwfeyxc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyffpznt.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gxphdqfp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2upevgeii.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eicjsxdd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcublbst.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zsseoebg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2magiiiqg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvvxdee.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rodgowju.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfclrtq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfehjhau.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhshrtx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qxffslhy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdqcyai.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2geyxuyfc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2caklzpgr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmoinpo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tawvhghr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfqzvpx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2duvovckw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbekfod.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2umtjxjuj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxictabr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjqacsl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2raelxppn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoggrqv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrljgba.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2niohdhvl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwrfyup.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmgemcm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaucqdo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjgrytl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cditypbr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhpujqk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrgtxhv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oulnprjn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rpexmhoj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlearifw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhpqioa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcckegaw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xugqjeju.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrkuwps.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsebhwtb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkfardf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmpvpxn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmfryid.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilceutty.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrbdmkq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fiparklo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jeahsaaq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqlisak.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sepzxqdk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dzskvtvb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2stdzqakg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiassos.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzxgyga.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgawakr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuqsqrm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rzniuwru.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnfxeda.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfmwxyp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyumdjf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmqstgw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcgjcoq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcwvimn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnjtjbo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzylfhf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqgclpw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hliuqnbl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cajihzcg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfgvfcv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkrbrnz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2olmeolko.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gphpmelt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2slptgmfl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyvoorh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2llkzhdeo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdstwyv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhzaqlh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2eueuzocu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2znhpyzkn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuclxzgb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiitxlo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uecsrpzf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obgisjuc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lknjsjvi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjvjocn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2omytwmjm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnsxzex.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sungmqap.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzeuujp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrzzwtl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2umrmolff.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yffvkfeu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2igygxzrn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzesrsr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxvqbyd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kezwkwek.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gslvzlzv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wteqeotf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjihwco.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xldmdsvv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tigbinnh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbhsoqb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdbubaw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhftwifa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgvkexq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zngvqpzq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjuwkhr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2swghvtbj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmgoaqi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjjujxm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wndewuaf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhopivf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfhlqns.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xufeboql.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stgzmtkx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzqqpcg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqlbjdt.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkcadtf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2htvuaieq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hskpbuhp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvndpwr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nemglfqi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfwilnw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjotrkhd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2prjecdhy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pudfpjoo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhsnonz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2frbrmbpb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2conigmyt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkbqibj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2emerqdiy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdzqbte.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sleemgvu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlerndx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mzycwocw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbezavat.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqziynud.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2clihlwem.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrquryj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeskviq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgjpjyk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vozzmhcf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2npzyucgh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xbggllxr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zynvmwuw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaoekng.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjlkmsw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwkbqup.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdskvlcu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2beifogbv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lrupmebf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2emejjggu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eechgbkh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owtttbiu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2adoiwyrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiplstm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhpnunx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dvywsdxm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqhtrmn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sackpjdf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2djkvoefx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2prftmvwy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2owokujwe.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2foxokyob.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvkihqq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wztdtzeh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fugfethq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfixscb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcrpmwx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzwthnr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uafbkamx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vxstfuyi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wphkmshn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzonapj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdjisic.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qakhgmbl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fahczbia.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvjhncx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2knfqutdf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqafdmvx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzfkqif.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2elorpylz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiayvye.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgbyten.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlccobuy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kelquzao.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2guaafknm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2syfrwgxq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeyssno.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drjlform.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ckayjwdr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpifkplt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2majonrlj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjvumhv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvosujo.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2admogpjq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bopjmiri.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxqrvai.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgrplja.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqkgcrh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuuljaa.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2agbhmdin.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxapydig.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqpsirg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzwxyvr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mthlhjbi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2umkpinyo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvxvxhr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uflaxqhk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2swuplcwe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2epvniqdv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiytogj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2syvpkaom.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtfukzj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdybydhn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbkhegi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfvsyvz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjydvnpd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2khizkdgo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tahsifel.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kszuegle.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qdentulu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkpdzpd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbpkqmh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pycdnkhy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xenuziel.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tamuugja.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2udjjpaok.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjfeuxo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvworww.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxogfno.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lscomwkr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2eirbvahu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlslidp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2adewbdrv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2axnlfkdq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyjoydj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrngujg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2epgiupqb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lysgldmh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvwufkk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnklirk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwgkvwi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnjakmv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtteqgp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xabrabmn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wifbyafu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hljjkgfu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkgpynj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2coocuzle.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2agqtrfpg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dicuglmg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qpndlmeg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uglonets.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnjqilu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlozhlf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hsotdraq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzcepve.html


<!-- 参考信息 -->