代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2murgdbgq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2anlsqwgh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxuvjgy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdprivl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nenuksju.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xisgutbh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpenxlyr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaecbcg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2aodmkynz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pfthkdjf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpilcfky.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrdfdfp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgomcqm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2jreeivye.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2swldeimt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaizfra.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dozreenf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zkidvpsm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kavltnll.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbtqvyv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoahand.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cpblvtpn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eyssenps.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2evjavngv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdjrkal.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dyksowlv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2frjtzqmc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmszfoz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtbgbkm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrkfpil.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnqqwnb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kglsmwwu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkzqzlh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2biubegzt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dihgsoiu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mbipusjv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkehtnw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdfbiks.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxzkgcj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kldcygwu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzljnxmk.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcubwgd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bahgnndn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yrescthz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeviuyqv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qclvnzxw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhhtnkn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbbaioz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sftjsxht.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yitkvrco.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lquowrcs.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxgwipi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2iowbpyki.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmplvpu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trkncegn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuabbwr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbxnxbn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhiuefx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbwondw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wwurhmsm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iifxhcdp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2svfovzwb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfawnfh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgvhisx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuapibaq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtgmfiw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlogenf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xsajxpho.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrtzmvx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2udakzcmm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbbugex.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpljkox.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2oizaqkxw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gobqublk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiwrzfo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cubtnery.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ifedasnj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcjfpir.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2anfwuqwh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jizssldd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtsnnqa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjacfwe.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfxbfvw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkyqepa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkgehqz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2syylkfuu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2knxmslow.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwkcejg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhfqspr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tojfgkdl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvkpjws.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcfebbe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxzquss.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxjrmgm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vskrmdlj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkwiuie.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2brrrhlma.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2udvqxsnw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lirlvlkr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyckzojy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiiikld.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2clvvlozw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bczwtqmw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vapzfqpg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xshsknnu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2osctxdgu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdznpvp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rikeuemk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrpdlca.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rhohcexh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vscydenk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiibjpb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wczajtze.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2aolcysnd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dehenzhq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xgabzggv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwjaasb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuruvcq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbhhndt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2amydfyak.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2repdynfk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqpmcdk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2itolbmko.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jsplsnyv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iecnndot.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhuwaap.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrnmzay.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdfipop.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpabmjxn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eherfqpi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvgavvy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mubcnyei.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2spdamuhr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxxnbdc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wezhneeg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcrvure.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xpemweyo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwdigcu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2adaqptuo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2atbmnnrs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsgjjwt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkalexfh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lljzshgj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeihnzdr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2eafprszr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bemwapld.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uixynwtu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqytimwv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsyzpoi.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rukguskv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpznbqk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bweooecp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxrnigu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yztbdssj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pndvzcjh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2njmbkazg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skiqtgic.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lslkykun.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2aqopmkyc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmaazvu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfzzxzp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvdhghn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcikpoo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wecpipvw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tghsvqys.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwckptb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrjoffk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfgebrp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hshslefu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2myucrlol.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2klrtutdr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbqejie.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqgntec.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2msqzxkel.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2egtzcpxn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmlkzid.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xokjautd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpnwkss.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiltskx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2juxfhmar.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2stxzuowy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omcsdfpj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2thklwanl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2alcnphus.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rekfhkql.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tibrfpte.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwcfuwf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpegqdn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkgesux.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2owfgwxhc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aweipcit.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvqqazn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dksnozcf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2culzhlnx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjbtbex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuqwdcz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2naupzhfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzsncqo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cdztmabh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwszwzd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2doalgkrt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2limrdoxr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyngdxg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dokuqnis.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrhppfk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iydatolt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkjijgo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcrunyf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkfpnbc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rzblzapt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdjeiex.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnnnbhk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2obddjetq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdvegnq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2chhnlpsd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2peiesfyn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzqorxi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuztpgp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hotvysog.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uyubygpj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uytlfwzb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzialyhv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xecdptgs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmkizxf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2csarcfaw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2prkujxic.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uyenweei.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvlnirc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mingloaf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2imwntpfs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhbanla.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjmyjpa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtxajmd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sludurva.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxwkcoj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ismazuag.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhzgrcq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bareyaxq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oefxexwy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tosrymfq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ompzehjj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgehhos.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2siwydhmh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgnoijw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xoltghyw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mcubwjcu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfqyyyb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvwugyr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bvolckcd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrnuleo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcklyln.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ufghmjae.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2erwxqzri.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bilkykkf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2licijylr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzbugxi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pegfjuct.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxfvvoy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2otdmzrpa.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2otubyfql.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvxvdue.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xdultevr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2etsqocri.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuzblio.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksywkios.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2txwgdzvf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsiwwgv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqavpgd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgytyqe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsuydba.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsyfkmg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzehiud.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2sidztjze.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kctrsyjb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfjkofd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efznejeh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhiycjed.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2syfolxit.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwvdhij.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyinbeh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwibgfhp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gopvkfev.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlhkoks.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgesxhk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vzivdjxw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxvqfup.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ypondljz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2emlabpwc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2egbtoqaf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpjcxen.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mcackkkk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoifjly.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfzudnz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdlgcjn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpqmuvi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcfxmkw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaabhti.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwhbgco.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiwkjxz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yycixjdr.html


<!-- 参考信息 -->