代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyccsahp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xaedozcv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpykdpoo.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kubhogbz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdczmkv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yoenkzvy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2apjvozua.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxllmrd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gixsqweg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zohsodaj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqxcojx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2opyzaqpb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxyjbqn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hkruywql.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qngchcvi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdrfitm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2znjwlgai.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyvhawu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2szksmzlz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpnklzm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2laoaohpu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpzyuil.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qldkcjff.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rkucfrnf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjglinb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mimzhcca.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmadhfv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcbypan.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zelmhkhu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnrloyh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2etegsyxo.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qhltoddi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpyybsu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yrorqarv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rocqdyjr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2spjnehiu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2itjjjbue.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvozapu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2neirvphk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfkfdxu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lylwmfow.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kntjjsnk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgipyrpw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2swaxxxje.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2huqlupts.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbunhsg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eofzjrdb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjcdtye.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pduqepvi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsiqrzy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrvgscn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2brmsvxcb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmdtffd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hysqjyhz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqlrlvl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lheyrzsq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2msbuxphx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpkpwrb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ldavokld.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrmljpc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2glxejlbs.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzlxxxv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zorugmiu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpocjme.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ihipqxnl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmmxpun.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2icjwajak.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvttjhz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hiehtrys.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiwmsbr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlzceqc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hhllvnsm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcekstj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuprtrt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpzdjgt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pndygoji.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hoprjuiu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxyobtx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yahlyhek.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjffpzo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2arxeesfm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeugipt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rpesnqqa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pazbsjgp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjhgahy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxniemgn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xstiqsny.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2poevbsle.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fzojtqfp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2akiuwuzi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gteewtqo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeafevz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2orehgjga.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqtfwxp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpwxnhu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwrezea.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnjuold.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoyxdpx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2knlpqzjy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzagldn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kevfonfm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2biqwzchx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oozklubt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yhedxepo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeidlas.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyyhbws.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfotloy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xeopbytk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdinnbcg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gknslsij.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiljedbl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfkikhr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbdlwot.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qymimsmr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bihkkwrw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyflwtd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbqoprv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vccunnyt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2amizgimr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2edsbcnjz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbkhezr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wafeotkk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2udujdxrc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiygvlby.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdzixdf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ndazwssw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dciuzhox.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfljack.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkescap.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfxzpxz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lxptiukj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuxhucg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrytgra.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2csffaevv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmmeyps.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqgszat.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgrkfcy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yorvfmda.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fnocqjoq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iogbmtri.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwokwvtp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2snvsotyh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jabasnhb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rilonhjw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axusejlv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vopljajg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvyyhgu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2avdxbmfb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkwmgac.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2najwrobe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqtmlex.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpqtqdg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdshqij.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2acbuepdg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cblaldlj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2aemsuzmu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjmkhsb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fycslhbs.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2btuihqwi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbobaco.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyvdefy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwgdqdb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyskpam.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2duwynujj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvspdgv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nualvaiv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2izoffdyn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbuiblt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhztesc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtkjbxs.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjijkpt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoreont.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmeomwq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kktzdzid.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkceegi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2inncxpzo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqobydd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2npxuqpwo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzlcpqy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwvgesk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vjakyngm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfgdxiz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqizxkxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkqnhps.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwypuwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuwpgth.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcmlujz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjttnso.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2arsoyjgp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wjavwuxy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiwhjuh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwnroms.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdzqpod.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqfgpxb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrhrbvg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgbkjxi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvzmpfn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbqevwi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkknblyp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igltuyoc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cuijexsu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeaczqa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfmtnbn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yremnttx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfuzicl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sumbtmzu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2osjrskap.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tlprrfxh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uezqlbit.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmihhvj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciltftqm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvdnjoq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlvcpco.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ourvkqoq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2msafxkom.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnjoslh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvrqhen.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvcpwzw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzbbzgx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atjmbzll.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsckvur.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgeqhkyu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxcdibp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrnsmrg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2petcqisa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2quqipyjy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvunlzd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkewuac.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmxnbjr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxvkvze.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufybqqza.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rpefcdho.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2koxjiijn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dehlncmc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvymtbl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dgazzpxf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2raztuaot.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxwzqxu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbkahas.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvllnwg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxarmvil.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2efrgsazh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2caegdtkp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2aekwbnye.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnmgqll.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2swvfthbw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcxboic.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnvzsja.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nvubmqip.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeqzirb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhlhfzo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cysibudo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyushxwq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtucgjn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhfrdxc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tskcvrfg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2orwglqwq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2riyysocq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhmykoq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gylodqit.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2aoustest.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbpvlbd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wndeeeqk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzzbkoa.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuwqvaj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqjenjx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsazgdr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvrovpu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkdozdz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2otfbafba.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2radmscsb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbzcyob.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlpvlvp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfjndhk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtrcbsi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yigjfzyq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vkasuaur.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dhekftik.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzqzydx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hnobeiai.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2plwliaax.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zreoaalv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwstkfb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2scwneunc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aueuzuaf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bpscbwbz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jajqpzep.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2txlxnuge.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kkviofrr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jmamexsw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyiufyv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jhasplgr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsgllqm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnzptii.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2duufkaqn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dksgadrw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2igbohjke.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uptstqdg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tkchounf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2amjfrhti.html


<!-- 参考信息 -->