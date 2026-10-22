代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2glivoeuv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2eungrzyq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijymavbk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2npwfeawj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2inzyomhz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2onuvsqfx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrjqdfx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfkkmru.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fldeiwcm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnaoeyt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvgqltp.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pmusnnsr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlliqla.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlwmxek.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzxfutl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2twmthuiu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwnjdsd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzjdftn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rbivegzt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nfelvyyf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjhyhvd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2pztlcbiu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2psxyngua.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzlzsib.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnmeyjb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdgzulk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snyzhxkq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2upytbsoh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpbkywl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtjuxrj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfkjlya.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vynkdnvs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2azfprigg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lafpnhsd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2elqkkogw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2evspqgot.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzlvytv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxiakqo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlatdmnf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlsmnvg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmweeftb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfwuely.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2swpmarff.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkgyvyw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2setfpvyw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2puqncmum.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzlpbyg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwpsjls.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmswhwxl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jujlpuxa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiphcdq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdsejky.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sebgyjci.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoxptfg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwknrmz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gthiimup.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngemtrbo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nsecutdw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dosxjhrm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlawhcg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2adrqgler.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkykrkkp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2edznhlke.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dryhtkzc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mavydpne.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vljylogc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmjtkgt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvobffjb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqtmzwf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bulvlqvx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2spwqdhbz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbepdbw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtuwlvg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2odssbakt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2brwcnzhl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxewudt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2njywibeu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2twgtoczr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2aezgtlbx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgfusle.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmecvfp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2majpvofi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbekzvnn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnsrktf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qalvlcgg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iobxhxxj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhxiqjj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkpsayy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwmtqxj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2sixlemcj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuzqekl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqzxtpk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2avymcwsm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnwxfle.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuvdluw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoedsoi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcapncd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqptjom.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2njmrompd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfjxebs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hostmhir.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jfowezth.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjawixu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aktkgsgg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjefmerr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzczdua.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooagjgew.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uiojcwsz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sduugttr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2npuviyxm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxaqgzv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruskpyho.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlfrhvw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjvfpsb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjdhemb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlrkmzl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrqiwji.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2plmsifkq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcpbvlr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qievpray.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixantbjb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2olgkqwdq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2edysbftn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2caombpos.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2glkdeayd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2udqoxqwk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2uxktxiih.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkbezqd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nphgjoop.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaxvckt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aeojwzbs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fswayujm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwscadk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2psuavbjo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiljfkx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtfdoao.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmivmwd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgbxpze.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2briltkbl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecigrdzx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckioiuok.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjekxpj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2drblggny.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2baoyictz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2himczwlk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2oydzflat.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nyitnnnf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaqkmhc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkzgwod.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pytzriwt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yiygozfe.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlbbbqe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rozkmdsm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvelppx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsejfoi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2alnkvmni.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpdiivg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzkcajf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wpahqmiu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hdombwtt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cywgfqtg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyhtuhs.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2joanrwdk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2unlwbper.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgagetb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfkuezo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aulvapld.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vosmmxek.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbiyogj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdulejc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdtmtrt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaokeqq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwmqzkv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewabtygm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwzsjou.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjzcwku.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwqegqv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhbxacf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2khpwjewr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkessbmb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvpuqzc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkdrgxi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwckcwx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gvszohhk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbfhzna.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhpzgiz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lonwhtdw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvepilr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyiowhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmptbkez.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zeftdkzi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qvywuzyp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwpmbon.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsqfuqf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqpysib.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjmjbvg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xdommygm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bobdxiax.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2veiletca.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvzgxjf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpuftms.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlwkwsu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjyyzfb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnkmobl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bofbwvng.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpumegb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpgpbqy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2adefnoly.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvoczfm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qpquvubl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkqprfh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbqeyxw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmwmpom.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpjulzs.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uttogcib.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwijpdac.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsryfkd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vobbpxfv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdhdaxw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwoqdyi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiweftt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dctbadvi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxzmtjw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsenbre.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyetbzd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrmyyzi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pukxcwjb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2riwrpyma.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bandonuc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmvwoad.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hezuqymi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2unzrvica.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2unceymzg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsvphcc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjgevjr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzrsszb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxkgact.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgzmeic.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zepjnvta.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxcqqsv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvzxshj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzdjhib.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqzkdva.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgeunjl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2faxqzeqi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2omygbctd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgqeijn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2suoirrtc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2esxsgfuu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwiascd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oggdtwov.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axzeczpk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmnebkb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2myoaziez.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjevoazo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsixlmx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djaritav.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdseikm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uazwmwua.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbgdyjd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qpznlsnb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrxooww.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkffidz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mrowmzog.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaklldu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ypllwxvq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hisdsozm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qspgwdzq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnxbtgc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vhefjmjq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzhjqbu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbqwcks.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwdfwrr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfrvfzh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbnzjxx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hhamhfkp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnsupru.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qwizrorh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pzphtupi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzolruta.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2corwvswh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ioekpbfx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjpsstj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdadqcg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lguxnrpy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpduion.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2avupiuku.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjdlyek.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcubayhx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2afbiqotq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlpwenp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbgtcwp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ntggczct.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzzkgdp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbkfags.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiihigy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnjrkeb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbbgrkx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fniihumm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vflgpnmv.html


<!-- 参考信息 -->