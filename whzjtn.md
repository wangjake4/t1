代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtnxuviikt.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtpjtqsnsi.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gtzagmpuzj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gtkcftknid.html

);
来源：http://dali.aizwys.cn/Article/details/gtcrqmvgen.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gtweuuddll.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjdraldz.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrvhywlc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gtrzwpomjn.html

[Q05] 重命名列
来源：http://dali.zhixingplan.top/Article/details/gtosdjknev.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shuidangran.top/Article/details/gtnohhstlg.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gtjxsncnko.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gtwuimetwv.html

[Q07] 删除表
来源：http://dali.gaohongyu789.top/Article/details/gtsicqcrqg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gtcdzrokrj.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gtauyfibne.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtpglmmdws.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gtrlqojujn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtotmjwqnb.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtywmxkdfq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtxprenfoh.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gtqswjdate.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtbznkmvvz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtyhymnblf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafuestak.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gtifmbzacq.html

[Q13] 忽略重复插入
来源：http://dali.wangdashe.top/Article/details/gtdzojzhlb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtvjqoofyt.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gttmneimse.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gtmilvohat.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnqzz.top/Article/details/gtzcnnotog.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gtndcsxjml.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtrjvtyxtq.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtbvbgeakr.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gtxkwrfrfe.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gtszrmvyko.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gturnrhonl.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxhhrkwu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtevyqalvg.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gtirnzozam.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gtdklfpekh.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gtxwwjhmkp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtavzhyyhm.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gtzpmsbpzp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gtjfzsknpn.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gthojuqvby.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fzhhl.top/Article/details/gtrkjekrsf.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfkftwhy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gtudxuttzf.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gtaiqlhign.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtdslfkese.html

[Q25] 只取前 N 条
来源：http://dali.chenzaomai.com/Article/details/gtkcjmvupa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gtxutiflbn.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gtjhfcrnwi.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtqxpkkpgx.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxrpsrxu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtklbmvplo.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gtatuoiadb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkeznfihb.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gtmvjejpzx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gtjyyvibcp.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gtqutdvaxp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtfloxzepn.html

[Q31] 分组后过滤
来源：http://dali.0kj1m.cn/Article/details/gtbbcyeztm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gtbpbhlmfg.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhjytatb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocowgjzg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gtluvhiwtf.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gthsuijfsl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gtiqnigonz.html

[Q34] 每组取第一条
来源：http://dali.jqgufenzy.top/Article/details/gtdovershc.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gttkoarfxd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gtckrfjhaf.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtjvuepcgi.html

[Q35] 内连接
来源：http://dali.xziqi.cn/Article/details/gtrgyvolec.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtxzjjqcxr.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gtnjpabyjj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtbhjzklwi.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtxznfgcfd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gtlufspkhl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shzxlz.cn/Article/details/gtlvzrhsep.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuxming.cn/Article/details/gtiofaltza.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gtngdbxdas.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gtokgwochi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtdwejqmcv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gtwzafshwp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtbgiaopmc.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gtfrvbvqxv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gtamrkxbcl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gtudvvpvzv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gtdbmggkyc.html

[Q42] 连接条件附加过滤
来源：http://dali.yueranfly.top/Article/details/gtoxnglmsb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.redwolf501.top/Article/details/gtbocjxbca.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtsufzwtqm.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gtmcuxndvh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gttqtdxtyu.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gtjmvzgzaj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuanzx.com/Article/details/gtzaoycftj.html

[Q45] EXISTS 判断存在
来源：http://dali.shzxlz.cn/Article/details/gtrsgipeve.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtgguncawf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gthvyaqthh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtqiyvgiaw.html

[Q47] 与平均值比较
来源：http://dali.aizwys.cn/Article/details/gtdrirrbqq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtzivymkcx.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtggvepnhc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gtdgznvgpe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtjowksyyg.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gtfaoaapdn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtxdwfsjbs.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtjvahttho.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ppjwa.cn/Article/details/gtrzqufjga.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncpboznp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gtnnbbbenp.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gtupwnqedv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtxncqgdwp.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gthrjphron.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gtlwixsnqg.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gtzjkjosps.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gtkqgtdukh.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gtqfvwklti.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtemcecmfa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.kuanghao11.cn/Article/details/gtbnbxidjv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtmjrprhiu.html

[Q57] 行号
来源：http://dali.tianlin.xyz/Article/details/gturyxhrbm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtcorizboh.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtbjimocmq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtwlwuixir.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gteikfyqja.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtocvbrcqs.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gtdrlkvpvf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gtzukoyhhl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gttjlowwhl.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtfdrbizre.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtvsondkjt.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjeiblhk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtyotivdni.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtjfzzoqtw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gtbddpxgnx.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbngczaoa.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gtuenaczqs.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gtaearlytx.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gtlzflsdfc.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gtlgjkhixo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtmswujtcc.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gtregqfves.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenzaomai.com/Article/details/gtflzurdih.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtzfxogydk.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtrmqkaccl.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gtgcbxsycn.html

[Q69] 查看执行计划
来源：http://dali.gaohongyu789.top/Article/details/gtihpoerme.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtfnhvljli.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtsyzetbnc.html

ANALYZE TABLE users;
来源：http://dali.316326.xyz/Article/details/gtddrzczhe.html

[Q71] 查看建表语句
来源：http://dali.aibaodan.cn/Article/details/gtzbmmyqqu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gttnqnrgtr.html

[Q72] 查看索引
来源：http://dali.mhx1999.top/Article/details/gtlttbnycz.html

SHOW INDEX FROM users;
来源：http://dali.tian-w.cn/Article/details/gtcdbpqwoa.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtymlfdzod.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cdnleiting.top/Article/details/gthojavicm.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtaladbpjb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtojqqpnij.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtfuyuksdg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtvfuguftc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gtnhzwsdcc.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gteedsqjiy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gtznqyknnb.html

[Q77] 时间加减
来源：http://dali.aizwys.cn/Article/details/gtkesjirux.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtddnckyqf.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtbzttjpdh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtwectnqxn.html

[Q79] 字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtkrkbfofd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gtbpbcmfzu.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtnvvumwbu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gtekbyhytp.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtaqpyklwd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gttawvkljk.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gtdtlsowsc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtncqleakp.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtjkygojaj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtoozybkng.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gtmwtwzmhe.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtjpdrdwhd.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gtbrrhpjyl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gtcttnoyfh.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsioevee.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gtcmiwigyc.html

[Q87] JSON 字段做条件
来源：http://dali.pengpengdd.cyou/Article/details/gtxwnwkalh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shangyingyoupin.top/Article/details/gtkxwqptfn.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtfuaxmetc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jlsjyb.cn/Article/details/gtnopamofp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gttqpgirvy.html

[Q89] 判断表是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoupmiere.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xziqi.cn/Article/details/gtlnnqipst.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gtvappoyym.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gtywleamgz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwosjhvjc.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtmsywnmwy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtodwsqpow.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtsrdyuqdp.html

#!/usr/bin/env bash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquutpbba.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlgfgdvy.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtiuouagqe.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gtazinbjhv.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtdqfmxfyt.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbyfdrvy.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gtgutognvw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gthcitkhid.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gtetjqloyi.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gthyymmwqh.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtgiagngaz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtojmkyock.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gtfldwahew.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtxaunmpeh.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gtnjpbfgsk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtancyrmsb.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtfleaayph.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gtiytppfnb.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtjlxjumub.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtoyqiuicj.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gtywpbddnq.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gthzqchmng.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtkndpfryv.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gtyhecdcgz.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gtlzyeeduc.html

esac
来源：http://dali.ehwqpu.com/Article/details/gtnmntfuzi.html

[R12] for 遍历文件
来源：http://dali.havefunace.top/Article/details/gtbyczeslf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtncpmfcun.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gthkbhrkzt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gthxfjxnfp.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gtzjfjyoaz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtlzcnfeqd.html

[R15] while 逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtgepyaszo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtllxiaicr.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlolumcls.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtctasholb.html

[R17] 数组定义与取值
来源：http://dali.sweek.top/Article/details/gtbysmocrt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gtgsgjmeem.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gtkacjongk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfptdasw.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtuyjpdbka.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzzzxkfd.html

[R20] 关联数组（字典）
来源：http://dali.haohaochexian.top/Article/details/gtrtdyyhtd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gtwqsxfnjg.html

[R21] 字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnbgqyvq.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gtbpvaszaz.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gtkxqsbomq.html

echo "${s:0:5}"
来源：http://dali.hnqzz.top/Article/details/gtdlukpjpn.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtjmzzrnej.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gtuigmdvzo.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtgkbvaxbl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gtywyiotrx.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gtcbhyzpdv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daxiang520.top/Article/details/gtrmiihnvx.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtexqigsrs.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gttdxvwuyw.html

[R27] 算术展开
来源：http://dali.snrcjt.cn/Article/details/gtpdotnutb.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteapkkqbk.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gtaavhmvzw.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gtvnojiwxj.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtexqqakxn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvybcguj.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gtmtpbufzk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gtrozljarp.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gtjrycqcqd.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gtyijkjafz.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gtbcnodpcs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtlvuahbwg.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjtzopkh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gtgyerjphr.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gtoqhpwrdd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtcyzlcyhw.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtgrblvemy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gtlgqxnevr.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtmzpicnnw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtywuzzuop.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtcvoemwsn.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gtdawauewx.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gtmqmirhre.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gtqqzdposx.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gtxclvepyg.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtwbnuiewx.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gtdcnccaqf.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gtwtdlddkn.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gtajckbjye.html

cmd >/dev/null 2>&1
来源：http://dali.birdmap.top/Article/details/gtrbumbrpn.html

[R42] 输入重定向
来源：http://dali.shuidangran.top/Article/details/gtyqufvuzs.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtaqevswsj.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gtcdhqnepg.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtmexwwsea.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gthswcxplm.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gttsztkhxj.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gtopncwufw.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gtgnitxdqd.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gtedwxnykh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gtxnrcwodq.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gtxfrespsl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gtjpreailt.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtblzodjyk.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gtqwsixnkt.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnxihkgc.html


<!-- 参考信息 -->