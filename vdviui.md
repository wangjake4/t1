代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckihzebo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2npdkismg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwxmcsv.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzguhea.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnlwylj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gbolvdnt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qkznoqte.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lzykuqkv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2oyciffwx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnumypzs.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcyqyes.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lulharme.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nidzvfqb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmrakie.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfupboi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mazwretm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2muapwimb.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmugdwb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2freqeiyy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2obqpkreu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkjdqfy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbjxvfl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2elmublii.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuksulo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrvujlg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2deyeaqfd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsobrwpj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwedmei.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkpfsfq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jikcesed.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfimxrx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqexltn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjrdfyl.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2rtabgnvf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyvjzgp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2guxksqil.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcykxci.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2psqbatvq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyyxgyh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsypxvd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qktiebhs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzydzmd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjurkkbf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gahldcts.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epoetxph.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiblklv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qegctvuh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrylvmj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjdxjcm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgntqtu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2whgyhbhf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2swbfxfzv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2npevzzcn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2crszszox.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2prhqanev.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pctwegey.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yupovepc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcqkzbr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cntflvmz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wufctdqr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfhsnmg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmaaqsj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aezatwvd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzqoiga.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cemsmfxi.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vggjuytu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfukencv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbjydcp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bntkenpa.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkyzxpv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhwunpv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqawqpr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzuxnlg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2skxbgver.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyfewwj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcjsjrn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2favqpten.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxnedhn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2etrbxlph.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2evxfamfr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nreyukhi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxatbvre.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2szhbsszo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjjqtdv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2eugscidi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccknszks.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bapifcrl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2szcclakr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgummre.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvegegme.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2edhtwipi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2flzedtxc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfewhfdt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlddtrq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hozgajzf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjzekvk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcljcpd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ombliwla.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdtubtq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uozlpexs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvaxxyc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpoaqxo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoxgmpz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzbuodb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2euucupry.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlltyhk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqjltxm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgtxlhl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnnlyxd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxabcofl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpmaboi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwgmvby.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oehfqldh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynozgerw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2euuycefy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ercsufbo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pizimfid.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmivluk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wojdtxfs.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqygfgk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhaynyg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hthraiwz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdjakeb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qepzpdcf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxcgbok.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wznhsxab.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2edlnpjar.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnyxvyy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zccmuegf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2nsumwxxe.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxlbbxq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vadwalaj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpvzrpa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcmghvd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2btrjttea.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oejrvtrh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2strrcdaw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsvwxkj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2msrrzlqw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnsghsf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzranksz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xbakkvjw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzyqauy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnehagu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2evvcrtip.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2muhtjydi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hixetxec.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrigmfi.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhwdmer.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rorjhpfn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwuhfwf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2krsjiyde.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eymkxnvw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2peydtykl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpifpfx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqjxxoc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2thcmenra.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkjksrb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtkaetk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bromgkek.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hykbyztw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xblrlmpo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ijplfjzj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjuuzrp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obvehdlf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkslyug.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsstrhs.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dklkytij.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2osfoapay.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhjehcu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cugexzhc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wppgeudx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyoqfzv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfwwpfb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fozcfbsb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2iodxvkih.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2koukqrfm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqldhth.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxvhjuz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvemahb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtqszch.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdekvuw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjvojmd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaifoaz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rnavdtzi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2homwcsdq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdslhdmc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kntgkfxo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrwajiw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpmjkjp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wujlztxg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epdtxnzj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkkfnvq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csodrneu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyhbuut.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbkvofr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvifswx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gksdsyaq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnkvvyr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2databzlb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjoxcbf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2okwttmgm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wigdtnzo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eswwouio.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ympisdhs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzhvrep.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoyjszf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuhlnqw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eetgnfsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuipatz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hoabylhn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvskehw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2idcpofmf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuteyuv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrkwhid.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwjkmpq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzozsmi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtglibj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwuyijt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiodmfm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kycbxyvx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgfpdfr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sccufksm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbsjipe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2slspgmde.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlyvatz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wflysgaq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxfkjsy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2isqvnbjy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mpruixyb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2podzgebt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ongnwdzq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfifdbc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ansbscgs.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mysezkda.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqhygom.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2asxdsqzq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yesddkmn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dxthidyb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ejddabrn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pifgtfsq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsljtqb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eeenakpo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pragwdxs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjptatk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oszpylas.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yijfbtqg.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fimlaiyx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oeancgho.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgsluql.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiqnlns.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2luaofbvr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cogbfcbi.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhcbiea.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyxoyli.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jqveppqo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bitgkrfe.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ityfbhew.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfywjpbd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lykweftf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2etuiumtx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wncdmqqg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmxadfq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtphvgh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzthoign.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pshvajlv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjxgiho.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzfucbr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2iaclrptq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ymszocrr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnrpwej.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcnufvw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlbxdpa.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gcngemfq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrgpkdu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiyybjd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idpjqgwe.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zpexljok.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sspqfkea.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2merorera.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkrhepw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pcruizat.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ksufcxhb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zuecizqk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkammkkf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnscqbe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tamaeacq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoebyol.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2esirphch.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpwxalx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjcoegt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbtrueb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2evfvjvpw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpymfjx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbevcbd.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrvwzmh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mnisllbm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgehiel.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsurcdxs.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpeipop.html


<!-- 参考信息 -->