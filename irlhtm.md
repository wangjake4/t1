代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhibado.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrapvov.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiexmgb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjmkrer.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyughol.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuhgied.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lckhibqq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2twtahzmg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yuabrykm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlomejs.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuwhigw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnrnvga.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzbxgzl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzwjhwl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwagfqc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2stqfffrj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abncvqxu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkotyvo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nptjpxuu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wvesybae.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcobhky.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zegmjfhs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsgzxzf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2noskstto.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzozkzhd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2apodxmpk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjgiswq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rukecjla.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lowanamj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoqwxbj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcpfuqr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ouszomfs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2swztrnxo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfbzttd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2anooxfzc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ksenkntw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dnomiuzz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxjukhk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdebevl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbbpevr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuyjrtu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxvsqmx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iahkchib.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnxennc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkvqoza.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2whslhngm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lezhjfom.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tfadnxlr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsupjmo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2arcbudzd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pffnouvj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfpiqru.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hummzxsg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdvqpgx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnlelwj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fmafcucu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2saqzoiii.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2luftbqli.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2obdakscp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkifkie.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2edlqigfv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fapprzmp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nqivxkzs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2osnqhbar.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrgtisk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgjzdgc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wohnerqv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2srvhrtxn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2desxufkg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxazwyq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gamhmzwg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdwqlgp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tcctcwzm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2eftadtqa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvwkvwv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfougiy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnjviyb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsvwdoc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrnsafv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaqcnpl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2txaeiogj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gusvrgyb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaztezg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpqtzmc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yljgeosc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2okvsmzkm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdjnvnq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcbcrbo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtdxfsc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyljtex.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aryfpfti.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rujecspq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjncigfi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdcstvj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmzfwkk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uclhteto.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aicjhwhp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqlqmlz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nshwtitr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2asltoudx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nluguyxz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2radhmgll.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2inxyrbpv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyznkrg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2murhkbve.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sidgszsp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoxdgje.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqiguav.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2keldwpyu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cswuydyz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnkjjgc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvmlzjp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpyphpb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xilckzfe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzfzbmo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xssxskoe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvpzztg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bskvpugq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyqvcxw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2htakvlqp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrbbpxc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvjjvgr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2afxfzrdc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2slzkipwh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhpapni.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfstvyvt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrzvdkt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbczakfy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxcefve.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtlwxdf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ytijnijg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xraubwcr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkvbjox.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtzeejr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jumozcge.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiammdy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfhwiha.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuvjzkc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuqjarc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mvljhqct.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eklpoqpj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsdefmh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcgdmdh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmzppap.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrtkpou.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkkftjo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2svcfenij.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pctktsxo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdlfkdk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbudrfxu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmdsohh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzakmnv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtdtqnj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2uncisvvc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrltrwb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pivqnbtv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkdkqrd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rocjbtfr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sosvtprf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rurpsfnm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2itdrhcir.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnfhtkt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zanqbyra.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grchvamu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ghngabao.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqtyexg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ripzltge.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcogznhd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvjbcwq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bzquvcra.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhhazyn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2laaqybkr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkgxyui.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2psboombe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsvxncc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsjmvhf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwmuljh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfffklww.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2efujlhoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olmdqifc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xunrtxnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtewpym.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlwwgcu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtustcw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwjuypt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyahjef.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mebzpspg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwtawgb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxpahtx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgzksxs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjdyjmk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tekzvmxl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgycnbar.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjdfqql.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuzoyqq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scmaomra.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2grxoryzh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2monivdck.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2goqemblm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuhbine.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrfjknl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfhgfgt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2irrccrxt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2myrfgtrx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uftzjexb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuodblns.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxncgqwx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxocezq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnwhfwc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whmoelur.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxpjjxr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kuipebwu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uuohuuee.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjticmj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkzqvce.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpxjoty.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vblwsijx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwucgwb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cvanhifx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ustgxjdd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvrblxv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2betczyzk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxiumhj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gkddzlqz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sigaqbkt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yitsuruu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrstytg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2edaulark.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2egibbmbx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxnccxu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owamehdu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfysxxs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhbufra.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jupimbuw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmegtuj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpgzmpq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utwcpzwj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wweccctg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkodhwcl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zqziafud.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfcracs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jowqfbpo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2krfbpeai.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwcrczj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2befyetid.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtjtdgo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebffgvle.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2thopbyyx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqygbfam.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2clgokbrm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htkvxrcw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbwdccb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhjjyhh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fdblysdv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpuvocr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoprtpg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtrmery.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2stpxjaek.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvwnahx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoylucy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2quiedcjg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbtwcdo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrgvgaq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jvluodaz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpynhzi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ykspyksi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2civrhsmh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gojfnlvx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2krgtatpl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2oshsipzk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbalgly.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mifaaimv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnlmjno.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kuurwhwo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ioczpmdx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lthsqgsd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqmubym.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vetvcpon.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2snjyznok.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gikeenei.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhneige.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjewduv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkqsoyz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xavyfmtp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gynulecs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgjebjx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgnhkgi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cikznmxi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpgyfhn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2szwxlveh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ftypstdg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dxghjlif.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcqefyk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwseeff.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2djbvggot.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2eutzvflf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qucdyham.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrpmrgp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzbesox.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ziagrice.html


<!-- 参考信息 -->