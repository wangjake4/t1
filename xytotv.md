代发 wailian999

);
来源：http://dali.zhijiandao.cn/Article/details/gt2agjdkbqr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rodcotox.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjmokat.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgwzpnp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyblqwr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2eygzqodi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2initcqwi.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhjtiai.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrcczxc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwupgdka.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zplozmnq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgrfsvg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2osddosul.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rkevmole.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfgnryt.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kibubhmg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2afoueblx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2craivcek.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlfxctv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnnlsxf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxhgiwu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpyraru.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mknyaqfk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjqsren.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuehdgl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2aufeeudv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2shwxdiph.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfrxmya.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmcwbas.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhcxqqr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrfgvob.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdzopmq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfdhmpl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2flwxekyr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mezxgeqz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjkupvd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kawaczrr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2imfbcmmu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvblaso.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqkhfik.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxprbqv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrevckd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hadltghu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nibbmncl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmslvjd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ylchgtkm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmkygux.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2frjslhxs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrsssuk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2azmpwchn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvmeotx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqqsspf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfrnjnr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgewhpp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrufemn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuwihdm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiwlnwk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjzgetz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkouiqb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqmkbbk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqrnttz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfqydfz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2brkicfrn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qmufalck.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgjbjkd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vomregxo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkxowid.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfjxjkg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaieacp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrkwhoh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dukjresh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzsaqdu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgehwxv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiduqdih.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyqsrbs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iryogwdn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlitotxo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyyqngk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhdvtsn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bdubkkuw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhjpwhn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqkckbd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzvnqom.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pktewmxj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsscpas.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2eotdhena.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gahxmuqs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2itgsilsb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2auyuvojf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xisnwfks.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2trtcnoui.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcstiym.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wzavvada.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqquukn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kafgayep.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2coniwcfm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjrnkjv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaljmip.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdvbvmn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2svuzdkiy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkmwevj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dymuhdif.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaswqwo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvrfsfj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrbwczp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxegexs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcprdkb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfnxzft.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tydyqgwr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mtslnnwe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuprdprm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xkunqwqc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtutvrm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkvlsyl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkqkioc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpsxxnx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcgsyuj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfotamr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxyljtz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ksshkqbv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2igigsbkg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rxktbqpe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uspihbtg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hylobuoh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2clilzrhw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnhkhcu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxmkjek.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrasjhq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvwmapg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2arblstwd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpztiqf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aknzsvym.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkiscqy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ypezvomm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2exehthbm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvqbzuz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzumryv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2prykqlkz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoyrvet.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2sktlwtyf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mjchsvmj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzgawap.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2isvtilvl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdemizwj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rygnnmtr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bijvvdmb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnznadn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqeqsyl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fikbkdfw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdfjsxr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxuolla.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcdokbt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybphpfra.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxtdwhz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnhnnrs.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2getyhikg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hcksphui.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxwkvuq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mritrcny.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbismey.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnribbm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgplmsi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbxknua.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jodgfgoo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnuqowm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgsbhwt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pfygtpvl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjwunty.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2apodznxq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bextjitd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fntqvnfk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2roxwwyef.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgxdcuv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjtogsm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbedoch.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idolleya.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnnfevk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuigtnxq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mivjvcst.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlnmyib.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zymglhcf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzpbeox.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2czaefpzv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xochsrmw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2huudcshu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsdlwcv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiosvil.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmggnsz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vckdyqun.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zegaxnwa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayghexeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnhqsut.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzsxudx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gompkusn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cjathwts.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xotrlfyq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaqngck.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyedilb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2abdyskqo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgcxzij.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdpluop.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2opehlywi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmpqted.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoymddb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2btrxhsbd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jadvkrau.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rluxunhv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oligqihd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvjhgtw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgpgsie.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qvydkqdm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcqqxlm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2awjmmlzn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xngynxun.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlosads.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwzdxhk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzirlrp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqhjigh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfrlhnr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2joiocvys.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2odkeqceb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxdvlrf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzxkyyh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnmzowl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2molsprlu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fgclyjfo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmxwjjc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsthpcrm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxgtvnn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwnyxpq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwakmdcr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqjztwo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2molhcxtq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvffrpn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsgqpoj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtvhaqw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sonsgwxq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2huuonkft.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpxgriz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvargei.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoeibllt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvdxard.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgywxigp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqftuznk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mlurnttg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2znvnqcia.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2woaohpjp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrittnm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyggwfy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbdbvfv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqrbqqf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcxldaw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2usnahxty.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vudbbnmg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gthbxpal.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwjwwlz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xehgvzwu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaaocza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2trtssxqi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcobjoy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flcufweh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zpovzemd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obvmgysq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeuitbw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ybptrdoq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vvasjhfe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaidugi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqpmfzd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvxbwwc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjjtkqy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yrspcoyc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2izvdtzpb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsswruns.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnxswdr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuvdvcj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ptabzshq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfjpwak.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuajdwc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2blegwjhi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sjravmzv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nbafawal.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqxksyj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuqaibr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnyrjdk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aexewlrg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2enkmgxat.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2leyoumjp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqscokf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcawqlu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kuijjrlj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sezthinx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2udanyadk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxybwob.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2luzvdnjp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyzkzla.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lczndqhm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2irnbajej.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhecfrh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dukqvpez.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbttbpj.html


<!-- 参考信息 -->