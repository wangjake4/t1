代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gt2lechrewo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gt2fziuamkh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.9152youxi.cn/Article/details/gt2xhoynbfc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gt2onuirunz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tpvdmdmh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.iojbl.cn/Article/details/gt2krbplnbv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2rbuglzgt.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gt2tqhxppva.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gt2ljoigtgp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gt2xkgrwegy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gt2kzebvzpl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gt2nsirekcu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gt2uhbbkyae.html

);
来源：http://dali.sweek.top/Article/details/gt2ernpkchl.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gt2njskaifz.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gt2oqnstfoo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gt2vasvuvww.html

user_id INT NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gt2mhxrxynw.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gt2ppeesixd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gt2kwxymkxf.html

);
来源：http://dali.yvedp.cn/Article/details/gt2eljtglny.html

[Q03] 增加列
来源：http://dali.guowangkeji.top/Article/details/gt2fzvkyokc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gt2wxkgdnlw.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gt2vtbnpauc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tianlin.xyz/Article/details/gt2ajqygpht.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gt2kqultptg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqxshwkb.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fayqsamw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gt2hauphukz.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gt2qsurvxyq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gt2yadtbhbd.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gt2atackfue.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zscmzezx.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gt2iepjvjce.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gt2yjbkjwza.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnidqyjv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2wxvybyjn.html

[Q11] 一次插入多行
来源：http://dali.gotoacloud.top/Article/details/gt2osfdupea.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gt2qmtuqtcj.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gt2bhztusgz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gt2rciccgzl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnndojpj.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gt2kenfukkx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gt2qfhhdwoz.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gt2jkasermi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gt2lryftqbr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.birdmap.top/Article/details/gt2jpamcoha.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gt2cfszzjdk.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2iskncjzz.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2ldcrfdaq.html

SELECT id, name FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynheiqup.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gt2mxspfdnx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.c1oappe.top/Article/details/gt2aijvqcis.html

[Q18] 模糊匹配
来源：http://dali.fengsongda.top/Article/details/gt2agrwlvtn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gt2wubhlnwa.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gt2klhieyic.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gt2qdvwigos.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gt2cscvyvqq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gt2aytkmene.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lerjcjdm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gt2knifefmz.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gt2cdmippxc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gt2gqmgxvlk.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gt2wyxafqvl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akfqeiva.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gt2vihhndhh.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2ucxkiiik.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gt2opfzsmgg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gt2qemfvdze.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gt2iirashqd.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2rqktmqbl.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gt2aeoqkluw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqinqyag.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gt2ikvhmogb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2fjzvkrko.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2tyoxbvlu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2zrsrbxlt.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gt2uwzisoag.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfbbliwq.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gt2tbzpkdmj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gt2vuiqqpaq.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2itzifysh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2zytpodad.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gt2ecvntfxb.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gt2vfzfodlx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uivjwgjq.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gt2msypwuly.html

SELECT * FROM (
来源：http://dali.jlsjyb.cn/Article/details/gt2ffoklwut.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gt2mygftlpt.html

) t WHERE rn = 1;
来源：http://dali.cashguo.top/Article/details/gt2faeicryp.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gt2kggxxgsw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2qfasycrh.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gt2knxqqwhr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gt2tumxrcnq.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gt2nrqrsxjf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mfjqxhoi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gt2glwnnowe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efogzfdl.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gt2hllnlwos.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhongyouzk.top/Article/details/gt2dziidlws.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gt2ezxesuxd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gt2rcfctplw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gt2ypldybjz.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gt2dlvqotpb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gt2hyomiaac.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pengpengdd.cyou/Article/details/gt2asvrngzq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gt2twslihil.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2aoitfcta.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gt2jirbwygy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gt2bfixcwsa.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpbfpmph.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gt2vhqgyxxf.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gt2eqdtkepx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfqltdbd.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gt2nugsiagg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymqmnrnd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gt2elempiyg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gt2urwbqfvb.html

[Q47] 与平均值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndhungrq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gt2cjvqytef.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbnrfjn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gt2xmzivhoe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hammf.cn/Article/details/gt2padcjgjn.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gt2gavmxjku.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2mcfficun.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gt2rbsrqqme.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utlaukpo.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gt2dqfgzwdw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdpncunp.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gt2mlltdwfu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gt2ksxbzpuq.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gt2nbrdcejs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gt2esnrzawp.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gt2pxfsovvm.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gt2zvutnehv.html

[Q55] 排名（并列占位）
来源：http://dali.tian-w.cn/Article/details/gt2cysmxudk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctqcvspl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gt2tpkoiwcj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gt2rzmjvwvy.html

[Q57] 行号
来源：http://dali.cashguo.top/Article/details/gt2kmngoqqc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yonumen.top/Article/details/gt2cbxtjpzl.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gt2rwvzljxa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2ordxspvd.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gt2ddqteoaa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2uyjjqmdc.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gt2kjsbdfna.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gt2zkonvoog.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2smoogiew.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gt2ctnowepd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2cxfotmqj.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gt2bdvhgsqy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2yysekyjr.html

[Q63] 开启事务
来源：http://dali.dianchejie.cn/Article/details/gt2irqktjdd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gt2ibuuurqs.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gt2ynqzulvo.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gt2mqjrckgw.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gt2dnbocvcf.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gt2affzahxq.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfustgfg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gt2oveoyesb.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gt2fueoodfm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gt2xlyimvvx.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gt2pvmxjstv.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2eajizpzs.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gt2mwjawphg.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gt2nmplqvjh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gt2zzkbhicj.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gt2lqaylaxp.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gt2jesrkvyc.html

[Q71] 查看建表语句
来源：http://dali.sxryk.cn/Article/details/gt2qkwqaieu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gt2wrwhooyd.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gt2cqukksqw.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2hnljycix.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gt2zljwzyoq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gt2jsdfpubl.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gt2navvzvea.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lierxlnm.html

[Q75] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2iyileqmd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2gppuyjsy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gt2xiehffgj.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gt2ancjzbkm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hammf.cn/Article/details/gt2lupiznku.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gt2owuqocwq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gt2ryfpcthw.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2wdfhlmyz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcxueqib.html

[Q79] 字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gt2hxhupdlm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2yokonlue.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gt2qdefofxh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2iktupdtv.html

[Q81] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gt2aiousznq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kklwohlb.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gt2oduqmihz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyukepow.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gt2dcxvgtrz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2rkebswlo.html

[Q84] 去除首尾空格
来源：http://dali.snrcjt.cn/Article/details/gt2yyeyohww.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2vrjbmwfd.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gt2frifwzvi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gt2hunfihzp.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gt2omjawzgf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gt2zlqfqtsi.html

[Q87] JSON 字段做条件
来源：http://dali.hnqzz.top/Article/details/gt2afruuacz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvzxwntm.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gt2dhfdrfxm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jlsjyb.cn/Article/details/gt2swovcfrj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2etyxlqtv.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gt2bdnvcnql.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gt2httqzhtw.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gt2djspuykf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gt2wyvempmf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jevtqqpo.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjbmivdf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2gbqkbtsa.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gt2muvflnpn.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gt2lmbpsiul.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gt2sevotkgz.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gt2hzodctwa.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gt2wzbesavr.html

[R03] 只读变量
来源：http://dali.yuxming.cn/Article/details/gt2mzvmgyby.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gt2ffuashbw.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gt2eogilzro.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cashguo.top/Article/details/gt2sjlqxnqu.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gt2zqscvjht.html

name="${1:-default}"
来源：http://dali.tanke756.top/Article/details/gt2yfaovawa.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gt2rdybtmrm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxnjmyfq.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gt2rpyvxjjd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gt2dfkxipwz.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2seelzmmx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2lfmucwyb.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2sumxyxqz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gt2osstdito.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmorchzn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2dwpvwiva.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gt2wmmazvdw.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gt2qftswmcm.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gt2pyvrkxfz.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2isyaaxuw.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gt2otnnwuig.html

esac
来源：http://dali.dashuyun.cn/Article/details/gt2hxcapztu.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gt2fobthivc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2glhnbqeq.html

[R13] for 计数循环
来源：http://dali.wangdashe.top/Article/details/gt2ptqrigmb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2yvyqhxyd.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gt2xoztwcvl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgkocaav.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2fncfvoix.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gt2qyydolmn.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gt2vvzrzoej.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2cslnfpty.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gt2auhnanhn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hywenlv.cn/Article/details/gt2bdhpzcea.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gt2wrnuxavi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gt2dqcvibvl.html

[R19] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gt2dvuykbnl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uugkwqqe.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gt2iketjuxr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2lcjqyskp.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gt2fncltzcg.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gt2hyjetvbw.html

[R22] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gt2pysxzvzx.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gt2xxmrezgw.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2cuqwjcpz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gt2guzexjnk.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gt2wsuisalk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gt2rpcacdmr.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gt2yzmfyqlu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gt2twkxfiqj.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gt2oqbaigbj.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gt2jtvebton.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gt2opjeqajc.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gt2fzzoiiyg.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gt2sfkcqior.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gt2djovjwge.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gt2vepqtzax.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gt2uruhcrab.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gt2vrygjywk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gt2uiwkhkwz.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gt2hqzeupgd.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gt2klodlnfd.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gt2sukvnsjd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2hyjygbpc.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gt2bipsijdv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gt2ivgtrwzo.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gt2yodpqhsb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2qoqhnyeu.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gt2xetmdvvs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shangyingyoupin.top/Article/details/gt2mldekdov.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gt2mvgjzwyb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gt2mrsnovzp.html

[R37] 把输出赋给变量
来源：http://dali.kuanghao11.cn/Article/details/gt2elkolrsm.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gt2veqwqppt.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gt2ihfhksoi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gt2ihpfebga.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gt2zvmsrhja.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdlgvwtb.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gt2vmamczit.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gt2hfinloea.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gt2fvnikiev.html


<!-- 参考信息 -->