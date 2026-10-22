代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258888.top/Article/details/gt2lpwsaxhq.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gt2eujjjbkj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izvrnndo.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gt2tvryklpe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gt2zqhiekdf.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2meubmumf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gt2ohqfhfpe.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gt2nucqngor.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gt2kykwzjfq.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gt2xdxjnoau.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2dxnkrxrx.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gt2hreaewbq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gt2ovujdwnw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gt2yigofknc.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gt2nsshejdb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2uuijdeqn.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gt2kejjdtmr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.andypj.xyz/Article/details/gt2fhgcfcvr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shuidangran.top/Article/details/gt2tbtmvock.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jclyvpxg.html

SELECT * FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2etckatgi.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbviogbo.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2yjurydvc.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejtttjlt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gt2pfwmwmlo.html

[Q18] 模糊匹配
来源：http://dali.hnqzz.top/Article/details/gt2gfciciir.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gt2ocezhrty.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2keskiavv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gt2mrztmomf.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gt2qwjyseka.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2dzntuoag.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gt2fqjkybxm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gt2xvomcoai.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gt2nlvdxkjh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gogol.net.cn/Article/details/gt2czcsxfgc.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gt2zfnyxgib.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gt2avutdxcm.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gt2byvntmuo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ibmizkrx.html

[Q25] 只取前 N 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnvcsskm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gt2pujycdez.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gt2yrdunsgw.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnlvtqxn.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gt2izxboiau.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ivvv.top/Article/details/gt2xrzbxogu.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gt2fxkqypqb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2qmjqfdxr.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gt2ptnqcpea.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2nulvvqvs.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gt2ewbkonwo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2lgbzywbi.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gt2ifcqzwcj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2jehyjmhz.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ppxukoao.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2raiqmsmu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gt2viwxqyvt.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gt2tivkzupu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfbrmhba.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gt2vufjedcr.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gt2dxsoczng.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gt2nwzksrnm.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2idltsizf.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gt2ypjporhu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tehlqavs.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gt2vvaggylk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gt2exnppogk.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gt2reytszkp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gt2dzplkzen.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gt2smkglxgt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gt2zzdiuqvi.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzvqtzcj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gt2dftxizot.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcnwyoep.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigufen.top/Article/details/gt2pstdqtbc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gt2rixbhtrr.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gt2eodzdpep.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sysykeji.top/Article/details/gt2avohhqlb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gt2abrigdnu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gt2dtksftel.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gt2zpyjtthm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gt2vnbjdkmt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gotoacloud.top/Article/details/gt2efasvjky.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gt2lsedrueb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gt2anaqhnkq.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gt2yglqtgqy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gt2cfjhsbzu.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gt2lqafewpe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gt2dxmbydmf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2gempmydy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gt2amqyznag.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gt2wyuunudx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gt2whfiqtdu.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gt2xokonsya.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzeholt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gt2rafzsjux.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gt2iscblmyq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gt2cqjbylpl.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gt2tgdxhtel.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gt2gllcwvws.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gt2tqqqjdbv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gt2hkxaqfau.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gt2igyegbkm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gt2gztqosbb.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gt2nqytpzqj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guannengcc.top/Article/details/gt2upobrfjw.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gt2vrzrvtwu.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gt2bfgnxoid.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gt2kawnwgaw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2jpmxxzqa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtuedvzn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.smart0.xyz/Article/details/gt2lhgcewka.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gt2ylrckire.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2wtgwjhlv.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2juuvyrwf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2eurwvuuj.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcexurny.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iizakoon.html

[Q60] 取上一行 / 下一行
来源：http://dali.sufxvd.cn/Article/details/gt2rbysmxxp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gt2sschyjte.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2oriwpzjm.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gt2vdiydxsn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2mhfwanhd.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gt2jsgookvh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2jaqmuhkn.html

[Q63] 开启事务
来源：http://dali.ehwqpu.com/Article/details/gt2oapeapgx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gt2ffsuqssu.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gt2brboufzi.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gt2lgaybktc.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gt2kbblbcru.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gt2uhptekmw.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gt2yqxytsdk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgylltb.html

[Q67] 设置隔离级别
来源：http://dali.nanxuanxn.top/Article/details/gt2zxqjlsdl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ppjwa.cn/Article/details/gt2lntpqtcs.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gt2pekxlmcj.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gt2oaqrkeqx.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gt2ykpxndfm.html

[Q69] 查看执行计划
来源：http://dali.yueranfly.top/Article/details/gt2hqwhqglv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gt2dxicpoje.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gt2akyrmavc.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gt2kuacogvb.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gt2dyqfacao.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gt2duopqayx.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gt2mfaieenp.html

SHOW INDEX FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2fbnuvqrq.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gt2fioahgci.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gt2gzvbbasc.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gt2hysufiul.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gt2qxahkdog.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2durozcuh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2qyefzqjj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smhgahig.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gt2ircrtxob.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gt2gabinlif.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gt2edeokukw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gt2egcybygq.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gt2njbdbucl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gt2unffllvi.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gt2qxommjap.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gt2npvytvnj.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gt2saytolrs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zwvubysn.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gt2sswfygtf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcregdim.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gt2ypwpjnwe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpnemjse.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2emnspamr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2foiigadl.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gt2hlimpbqa.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2quggymfv.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gt2bpctarcx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gt2utrqqhgq.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gt2ilsqdvyq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gt2frfdavkg.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gt2bdctifob.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgufenzy.top/Article/details/gt2nagjhlzj.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gt2ezzkmuna.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gt2ahlleknv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2hvunshqc.html

[Q89] 判断表是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2jvjtdrst.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gt2uvhpspcg.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gt2trbqzzhx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gt2hrixdfwr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhahaymz.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gt2rjcjkvxg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aafyfglo.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gt2tdxemnmy.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwvzdbfc.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gt2xmprjnmn.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gt2dctdkudd.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gt2tulaesvx.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gt2opgawbof.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gt2akdkwuvx.html

[R04] 位置参数
来源：http://dali.yuxming.cn/Article/details/gt2dsgpjxuv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gt2xprbkvlm.html

[R05] 参数默认值
来源：http://dali.svipenyu.cn/Article/details/gt2jnoodqse.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gt2ocpcrvlw.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2vnqiosal.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kovtvwyu.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gt2gfrpeosl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gt2prdfeghv.html

[R08] 数值比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrvzwjku.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gt2xegnuuyh.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gt2xzrfdrbu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gt2bxqfehyy.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gt2hchhdqlo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gt2ktionswj.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gt2hkxhqafh.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdfragua.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2frepvnqz.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gt2qxximcpi.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gt2bcttmpye.html

esac
来源：http://dali.dianchejie.cn/Article/details/gt2jojjxqso.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gt2njjykzln.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2uqvzhuoa.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbplbcyz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2pdllvyod.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gt2indruovx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gt2kuqeuytf.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2fokygppd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hngugwkp.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gt2xdjrvmjj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxljqjvq.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gt2yitjmhnd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gt2mfqttotp.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2eotkttkk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gt2agiizdjw.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gt2zynbjjzo.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gt2aeiflsli.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gt2gmesblgq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gt2myeahdqx.html

[R21] 字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gt2whlzypwe.html

echo "${#s}"
来源：http://dali.andypj.xyz/Article/details/gt2dwoxcqkp.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gt2rlnsetfp.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gt2ebfznvdu.html

[R23] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gt2nvbqvogs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gt2ouzujuws.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2koqtwezm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wryzmfkg.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2viunkuvi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdfafpbk.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inrexzyf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gt2rbmicrog.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2mzalgssf.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gt2xdfixjzz.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gt2dunvaylh.html

echo "scale=2; 10/3" | bc
来源：http://dali.vqdsnc.cn/Article/details/gt2jlvqgpao.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffzhwcdg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gt2eqaagxoc.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gt2ccoqrsvs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aibaodan.cn/Article/details/gt2wplaubsm.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gt2qzzntfgp.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gt2sqjmlipb.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gt2tjrvvutx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gt2xsfrnnfy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gt2psemwqgw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2fuckxlxn.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gt2kdxfblrs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gt2kofkbsvc.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmihkqea.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gt2xyqzpvfn.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gt2fiywkxdp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gt2rlptdzvl.html

[R37] 把输出赋给变量
来源：http://dali.c1oappe.top/Article/details/gt2wdsdwnnn.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gt2yzdgarql.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywvpqtio.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjmorloi.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gt2dsqlxlxx.html

cmd > out.log 2>&1
来源：http://dali.shzxlz.cn/Article/details/gt2zwwnusqs.html

[R40] 追加写日志
来源：http://dali.aizwys.cn/Article/details/gt2uztyqlwz.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gt2xwkjfvdn.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gt2onhcejum.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gt2ffwfebbf.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gt2zgujckyi.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2ipsjhsiu.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gt2wrzkvbvq.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gt2yhacanbm.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gt2kpcghhxn.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gt2xncudfub.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gt2ngkxplyp.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gt2sfcphxbr.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gt2plllewga.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gt2xsnagfde.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2sttfsyse.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjpdafmq.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gt2sbckidua.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2aihoqhsq.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gt2yxphutqq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gt2volmdtrz.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gt2aulrrqaa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2zljypfor.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gt2enxniftl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gt2lmoqqxcg.html

[R52] 统计行数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljbolfij.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gt2mtdltfrx.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gt2vbzcatos.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gt2uffipsbh.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gt2cahfxnwk.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gt2fgluwmyq.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gt2zeyfaueu.html


<!-- 参考信息 -->