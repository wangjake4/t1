代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhvyvug.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2almyxkrz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoowjuq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lexfnxox.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhunimy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhcpzdt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2iulzlkrv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeloxer.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcikqmyw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ryssvtpl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kanwsxxu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2akbviqow.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlwxzea.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xroehvps.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qodjzddj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmxgugu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdlmwim.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtoehog.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjvgdpn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwmjogs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhktdup.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tmekhaqn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcofgxly.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nddyrtdh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbdsfwl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2azafhlbh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2eamsfpmx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2miuhezox.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsrokyp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jkonnioj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nisaakyq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgrjtuj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvrbdsp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcpcfta.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emgvwowc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnrgwae.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xppxnqoc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sezumgst.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyianfxq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvebnfko.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdbatop.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2prrhrlit.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrntuxu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxacgqw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqgeyxy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sjebjlpv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrgqgdj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpjbdhw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjeezse.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fakcwcqk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhrmcxe.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjlfyeg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmqdltp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2usimzxgb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrlcbna.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xflgewgc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2smrtrcvq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxidgior.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrerkjx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iunswrds.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2aplkujqy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kycdeyrd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iixhjayc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcgoidz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqqtqxn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxovbyu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhzwhwk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlheaes.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rblqjmwp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2muiklveu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpayqxb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwkslwx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fndioewa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mruhyjjx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gpitrvtc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2llyjfcyk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjgaykz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfbgwhg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2isavudid.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mowwurce.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zveederb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfbptwd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrqcofj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2axbkryyp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqgphfs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnpqtto.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tukxfjcj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmwutrq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmuetah.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dviqhjpv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjllfll.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzfndnj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2twvevrpk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2msnylmtr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdvybxh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbnggin.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ngavqysa.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yyecdumb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwkqcmm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlqmfps.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnirycp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyntkidl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsiedjz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtwrzmx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vufjxcoe.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2awxhizxh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2exxmyssb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2spjatpng.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yowdcwwm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvbdlii.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ershufhz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwtlrtp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqykssf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2guirannj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2urwvxrgy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eniqoccr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xefbrllv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2crvwokcy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqjmayz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgmdpsf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mommpfya.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2plihenrh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsngzez.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjhmrna.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2trfqnzkw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlmwdau.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnwhzkd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eptyfdvx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2czjxosyy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrnbhfi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2shndaoca.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzfqfnl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxfnumn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdbaoem.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fatxjbma.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpzufyf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2soaoryvz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rblzhwfz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmawpva.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zykblkdd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtsbwhf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2txjesmrj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdyntqa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xtviizoj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qybvqktu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2olwtjejn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2njrhhgjm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyniycz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxgsiem.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2iradalkn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaewedj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lcegvfsj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2juujfomr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsaefdr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eijvybtn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bupvhkoc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2svdcbxme.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeodnii.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2antopgzw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzexydm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2eupcnmuc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeraecy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuzyysl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfckhnhz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hodtelyl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2oicmlrzw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcotiymw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwpjxck.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfccuqlq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uumeqqzs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qijidnox.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2exrabgzl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbymbfs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrukhkgv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlokhrgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eztotlum.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfoubip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jreuewax.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtygnio.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmeoebq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2symnlphd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqdiwma.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyjvyxy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbgtchp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsmoegm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhifbzz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2brvvmaae.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aohbuyua.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcvnatd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2feakktpu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sydfzmil.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omkiyqok.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2crzxluwa.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwsbadz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aefzbzoj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2awewdbzh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xluusjae.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkpctsd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvgpeqh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wkplglnn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsiubth.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tncilvzj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzvwpty.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmypzcul.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbwwoqc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdnoguf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfxbwbs.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkesrto.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqlfsjh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pezvlmem.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgzmlpf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnlnfae.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sulhjumz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2axjhrohv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrmtxff.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2diovegrf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifghtilr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nldtusgy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyybalf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrazkpw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrqottb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkaxtiw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2girztnsr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyxltof.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwziwas.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hboqjtnr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlodybgk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hatitkit.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvwopiv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vusisumc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwkowwh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqtwrbl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpfypix.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lovjycwl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmgrtjl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkuvvew.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmaxrul.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoptzht.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhyesta.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmfhrzn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxnclyh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vrstbrry.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqxkvrf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pkazqian.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyncbbh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmchvne.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gshucxzz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiqrhjg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rckssuzf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzwfbfl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2klnjieik.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ljstcrrb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjbpfwb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvggkgf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dffduowo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etvjhpyy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdqtoes.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwfxmnq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2avhwgcfz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhlljfq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rdunbthd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2twaxaidp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qbecigco.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoiaxvl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbwyvsg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tukwzvdi.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mmymhwqx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkmaiho.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjidivv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbaclcx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqjgjcm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtfrxce.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tiesykjl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaqpqmj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2upejfdha.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2irtgtgyx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuytfho.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cahoipra.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2icohzdng.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hiprwujg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2frqsrifl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdxnxjs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2etjgcrqd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2txsulfjw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtnxqpw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrznymq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcnvnlh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rzueblgm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fayvwdmd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxobdtsl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ogypmzqn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2icshwmew.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rataoesh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2otvwkgiu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lwokwmtg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhmbtun.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsatjzs.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnecrqh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyvckcy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqufumt.html


<!-- 参考信息 -->