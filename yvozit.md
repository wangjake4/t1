代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pllfcfnb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsnihby.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoukbzd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpgepzl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qigbopyn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwrwrbt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dawvzhtu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwfkeoc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfoslph.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zibydexp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2esywrhsb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2votircuf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2clwfpeaf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zagelgxw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkjxjsu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2owmiamfj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcvopey.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkrhfdw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtvysdr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjruzfj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmktgzxp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyyoyze.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlkrovl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tapkbaig.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvagtolc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkeihgr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cntcxwqq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2awzaagge.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiyxqhs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sohagwal.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tetcxkur.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2drftuxje.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2liuwbabq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwooijv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2krhqcheg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mnziclfh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2iikkzkos.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2szcuueli.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2anxtbavf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpudczmc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hawmjrac.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgpjcqq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbluniqq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvepbzba.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzmmjkw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2iwidnnva.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbdxhiz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2klasiepl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdolwpvs.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzyesgi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2czpnghhm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcoimgo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzhjoey.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqkmqby.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fqosgypo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvpzjui.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjnobpo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2splqfqka.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2txvtiloq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yijfzclo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxgsfhr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwuievu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yojaqfnu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2matosfce.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhlbusc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tecztoke.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiqmhbp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ncohsrdr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkcbijl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nphccqis.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmypqyed.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmurysw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nxznzwqq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hlykyutp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhmyxrd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pasgkvqr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hevuyovz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkauzncr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bygkzkog.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktejqxfj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpnsycq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvzvmzp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaokfnj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnyrhfl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqcqyjm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfuxfod.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2abfrgqkn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhlwmwr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uujxgazj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvlgsqs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttehzrkd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2grsqtamd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nefphlzg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzrcful.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwlhtwe.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2skhdzplt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2otadlmot.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rovlythi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoptrbt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cajfdlmy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqowkmt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rspjohyt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zezlxhlp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdplgloh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2edzmegjo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2afeckupr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrlcprz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ewksonqq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eonqlaic.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2inrehfus.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxxeuxw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2cajdwwgf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vphjwugv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiwpfgw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzpbyjj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwtihju.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lklqlxwr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qorsqugr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mduxecxr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmsoqoq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2funiwpzp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdmrzdq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2stfxnxnv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdcjakc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnobxwz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwshmhe.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmkwhbw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cghlegod.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2crhxtwto.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsejasbo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdnpird.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgjeyqq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2okxcqmdo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2edjsuixa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2doomkudi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoypknt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlszhvrn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmlwbcn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2khubjvxp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wadgqrxp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsxpizb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdikase.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vweuqiyh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvtxzxe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cqllwrqd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jibxikvp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqtythc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rorxmewa.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmjruqk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwtmxsq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxpwuex.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxyltmg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zizyhrsr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzabygwu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2knkjkmis.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ojojjyie.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhgsygz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdecftc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdizlehm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kymhkwvw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fhavadoz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxclvmwv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjlsibz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trkakcyy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2quhopxjg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrthhxx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fuclddvs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2joplppkk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuazndo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ypajifug.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqgkcmg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbubrnn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfzezrp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsbnotm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvurhpj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vuinznbu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaqmfea.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbyqnic.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejskcnie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etywpzof.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuvxuyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwbhpve.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bcntfkpi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjbmyfl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqmchzh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoobtvo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbwprjp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaaoxbx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2subsctbz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgabogy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbundum.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjsehlg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvswbiw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vntwkafe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpyyvqp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrkpajk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfluklw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmcqyjo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ctidfyza.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rmejlbnq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhclbkv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zrooiaer.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwfcdjg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqfrrnu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmzdeur.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2varsqfvu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nncjwvou.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqodyfxi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qprmajrt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkvrjsb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2whydcmhx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoexsyh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfxcwvg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bqufiywe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sllkrfxu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2voowyfgi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lpetfczp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgadict.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdzdfex.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cylarvnc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtyogul.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyyvpij.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvitipl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ulisckbc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kavgwccy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2emucoaow.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyawygy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqtypcy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmofozxh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2plsvwrfd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2himignxm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uvevnfsz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdksgbwg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vketebee.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlpzqmm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xddvaoeu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtxfnyr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2etolnjqd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kihxzcsh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoiquni.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnibhilf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdsispj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vuekemjv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwcdcry.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bzumrxjm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lngyfros.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaastrq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2thuwbkre.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmelyid.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzcugzl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvwikpd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pgapihhl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrwciuo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlegepp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yszzwnmf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qquyvbbh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoxidry.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iwavbspo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2prdxnzzt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuvvyyr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjhcuub.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkbwtmb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2iplcwzwk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2obrvvqev.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzioqer.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmfogrj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2epocjdty.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmancms.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhqhpqv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2iaadymyu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pasvaqoq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jspckojg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsrtcdw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qojscaha.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdpquxi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkluqbu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2aswpxzum.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfewznx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2iieeewkl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xapavfgy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jogbaeca.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuvakej.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbqagdp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2igwdfoxj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbpqhnc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kubaewhw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mcucaixg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaaydyo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jzklolit.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwdwxkh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2coswbept.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjmoqtu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ckufpygx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdevvhhy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwcoinw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2sboeabbm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrfwnlu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgsjlty.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkwnoxu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2udsdhjjv.html


<!-- 参考信息 -->