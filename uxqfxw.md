代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ydzc1.top/Article/details/gt2jykcptav.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ybcxt.top/Article/details/gt2duziafic.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gt2ktwqydhb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzwaozxi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gt2mqtyyamx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gt2adfqlonz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gt2rkcveuau.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gt2mjallwqz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2vdvjhpxh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhoulong.xyz/Article/details/gt2vksdvcfu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2kppvuxdw.html

[Q01] 创建表
来源：http://dali.zycfv.cn/Article/details/gt2swlylbur.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gt2lqeziict.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2jtzjyqnm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2gzhelmmx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gt2kfdbdndi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndtsdvft.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdylibsw.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gt2hakunsks.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkcrltps.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2czahicun.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbepzczp.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gt2shfbnhft.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gt2xhhbjlqu.html

);
来源：http://dali.ydzc1.top/Article/details/gt2juxjnuay.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gt2ystujnzs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gt2urwlobga.html

[Q04] 修改列类型
来源：http://dali.jqgfzy.top/Article/details/gt2xqzugsue.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gt2gcsfsvdl.html

[Q05] 重命名列
来源：http://dali.c1oappe.top/Article/details/gt2enqvpbrc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gt2tofzcjhh.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdjukaak.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gt2wfszqtro.html

[Q07] 删除表
来源：http://dali.xuanzx.com/Article/details/gt2jjgfwxij.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gt2ldizzekj.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gt2mzuolcyy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gt2bwmgiafa.html

[Q09] 创建唯一索引
来源：http://dali.nanxinkj.top/Article/details/gt2jzhsyspr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gt2jyiqnknc.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gt2yfovfgkd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzrohxpa.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gt2fdgbvlxr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2ztfdvzkd.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gt2szmbdyfj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gt2nwcucykt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gt2afwyibpc.html

[Q13] 忽略重复插入
来源：http://dali.yj202588.top/Article/details/gt2uquuqxip.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2zlegjrda.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gt2ocbinktp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gt2krfzhzdb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gt2xxunyhaz.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gt2sfmxkkyz.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2wfirzkth.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2analhini.html

SELECT id, name FROM users;
来源：http://dali.sweek.top/Article/details/gt2vjxwibbg.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gt2gnixkqti.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2lueqbvvh.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gt2svwrxtdc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gt2djbwengn.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gt2slgealtd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daria6918.cn/Article/details/gt2sctlodfh.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gt2obmalmtq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pycfn.com/Article/details/gt2itxvfjez.html

[Q21] 空值判断
来源：http://dali.jyoumei.cn/Article/details/gt2hyxgwola.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gt2cjjtpipn.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gt2xdfymbjy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gt2yxijqbdl.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gt2zasrhpdi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gt2efdsjaur.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjygojqw.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gt2efttgejb.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gt2gjisqkrl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gt2sgwstqzm.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gt2vzigxkci.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2yloilzhn.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gt2qkftfdcr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2vlbonvyi.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gt2vbispiqi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2naksvjia.html

[Q29] 最大最小值
来源：http://dali.meibo888.top/Article/details/gt2jiacwxuz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gt2vwgjigin.html

[Q30] 分组统计
来源：http://dali.snrcjt.cn/Article/details/gt2rtlgwnro.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2bqeejllf.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gt2fyhexmjc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dianchejie.cn/Article/details/gt2shvfvkwx.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2fkmblisw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2zhjjmxfr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gt2wnpkodxd.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gt2ckmtgkqm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gt2jticnocx.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gt2fcrzyrbh.html

SELECT * FROM (
来源：http://dali.jianghu66.top/Article/details/gt2dilnokgr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.9152youxi.cn/Article/details/gt2damhcmxk.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gt2jzggskre.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gt2dsmzqamh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gt2ovmafhjx.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gt2stjkdwfi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2xfsvbaxv.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gt2njsyncao.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jyoumei.cn/Article/details/gt2jqjbavpy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gt2qjffxczu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gt2iizazmfx.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gt2vwkalgbr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvspzxkt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnpobpqd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gt2hlycbcsn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gt2hoeffpkp.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gt2wvtnldqk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gt2ufcvneum.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gt2nhmohmfz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tanke756.top/Article/details/gt2gveyzire.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gt2vpmrwajo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gt2xfgeknmg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gt2fwuyjqzg.html

[Q43] 标量子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbtkisjn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gt2tfltmauw.html

[Q44] IN 子查询
来源：http://dali.316326.xyz/Article/details/gt2zbelbyuo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gt2qkyblisu.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gt2hezmqjad.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gt2rhtqrscc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqoeisjg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2ewtfbjcm.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gt2soxogxpa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gt2sjgieyxi.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gt2fgtcyoqz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxnmlvhf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2zpkmoggh.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gt2gjbxhinm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2pkpwkkwi.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gt2ysuckbva.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gt2wymzsiyk.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gt2fcmpnski.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lapegzdm.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gt2gnpiwtzv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2bmhdqxeh.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gt2acrsmsge.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cqqwz.cn/Article/details/gt2kvhsajgn.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gt2dsluogsc.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gt2lawhkftz.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gt2rwgvjzqj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gt2avmzxywd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gt2smmkccsa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gt2ejagjzra.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjomxma.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2eutltthu.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gt2cifobwye.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2bbmfurys.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gt2kvhaotwv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2pyrrhyzl.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gt2yfspnycz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uaapyxpu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2qgehefnu.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gt2wdjbqkkw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2vqinojux.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gt2nuvirppb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2riirjcxo.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gt2bwooqkqi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gt2vonvhrok.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gt2zxhfarnp.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gt2evfqbhdb.html

[Q65] 回滚事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2wedohhtq.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gt2rwduuyqx.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abziimgc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gt2jwcrjybb.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gt2meofczhj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqxvqamf.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gt2uarcvbon.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqoshpex.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gt2wyjgqlhc.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gt2ivjfekmg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gt2gtdsjtpv.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gt2szxfqpca.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gt2hhtqoonf.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gt2izqyspom.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gt2fvbdnpji.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gt2gvgquoqe.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlvawcau.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gt2akfkbqip.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2eowmeudf.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jobpmpbt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gt2vsgjgrax.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gt2klwfffoc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2msuitmvv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gt2zidwbwvd.html

[Q76] 按天统计
来源：http://dali.cucudq.cn/Article/details/gt2ickkhuhr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gt2fqwikskf.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gt2ueitvhjb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gt2kmfjorul.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhxvhkoy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gt2tdtepfig.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gt2uktpnglc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gt2adpmtqxc.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gt2cghyfbjd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2twpuudyv.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gt2orcwrrcm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2qulmhymh.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gt2ldskikwg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2tbfvumuv.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gt2wehazxxx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2dyzmsjet.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jubrcngl.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbsncrfv.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gt2zhttfrpw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sweek.top/Article/details/gt2iqvlqict.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gt2xmfhwshm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gt2sdhhqrui.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gt2giyjihit.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gt2gvlmodad.html

[Q88] 行转列（条件聚合）
来源：http://dali.xylfe.cn/Article/details/gt2qjduareu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tian-w.cn/Article/details/gt2ocverthf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2wmhotlzd.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2cjiekrsr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gt2urjldbwe.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gt2jvcdwnbh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gt2uztwmvrr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ljksnsah.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gt2fubduqwf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ptouqisj.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gt2pkbhbtur.html

#!/usr/bin/env bash
来源：http://dali.hysaishi.cn/Article/details/gt2unkojicw.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gt2vhpyatvr.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gt2pxnypczs.html

name="Tom"; echo "$name"
来源：http://dali.zhongyouzk.top/Article/details/gt2bjzlcoqu.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gt2kmerormk.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gt2yjjicjcy.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gt2omrksyig.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gt2kvmouybt.html

[R05] 参数默认值
来源：http://dali.shzxlz.cn/Article/details/gt2gguqeijw.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2tansrnbw.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gt2bmkzyqvc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gt2lrroevap.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gt2rabmrapk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gt2fqpoqeeh.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gt2iftbzvvi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gt2hlirfrox.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gt2cvnwonuh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqkspaoa.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gt2oydrvuzl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gt2cypmhubv.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gt2uarisrrx.html

case "$1" in
来源：http://dali.sysykeji.top/Article/details/gt2psjaervt.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gt2efvjwvyh.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gt2tohcqgie.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gt2phmqcjgn.html

esac
来源：http://dali.shuidangran.top/Article/details/gt2btkfqmtq.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gt2xwwuatkt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2ykglfmsg.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gt2porvfyof.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2oobpbpbr.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gt2czjnztiu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2ddqkxlwr.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mflhiyjd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gt2xdywiyvj.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdrrhlrd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2qqbmqckc.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpatolzp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gt2legqhjwt.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gt2qzpkpvaj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2srxakgei.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2rvuochqe.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gt2grdxiktl.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gt2yfvpkpab.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gt2kgbhckyt.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2wbzwbviq.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gt2jmbiiiog.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2ajgivdbr.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgvijhko.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gt2ldswdaaq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gt2ufvmdgxs.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2kycxcwjl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gt2jfsiyzbk.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gt2ammrzuko.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gt2hhkqbmim.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gt2gdgnlvxm.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gt2cvylvmhg.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gt2tpjnqwcn.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isfctrer.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gt2xpburyve.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gt2owmubmbq.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2ctywrimt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gt2fqrvhmio.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gt2qffmypud.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gt2xhsixxkz.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gt2csyfdrrc.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gt2kntdlygz.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gt2drkyqiro.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gt2usvnclal.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gt2ysccmrdm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gt2qmiznzuv.html

[R34] 退出时清理
来源：http://dali.yj20258.top/Article/details/gt2ipcuzznu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2nrtjhqyw.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gt2msygrczb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gt2mhxnqoyc.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwvahdwd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gt2gdfotpap.html

[R37] 把输出赋给变量
来源：http://dali.kuanghao11.cn/Article/details/gt2lryajinm.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gt2xcabdora.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gt2qkkkucxg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangdashe.top/Article/details/gt2vlfdqhmh.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gt2blzjmcxn.html


<!-- 参考信息 -->