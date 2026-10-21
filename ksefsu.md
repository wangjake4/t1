代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nwbrower.top/Article/details/gtkyahsnhr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gtzxqopyrb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gtdmwoxnsf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtjjmaabbr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtkrxvtusk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.9152youxi.cn/Article/details/gtquocziyf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtctsabgff.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtahxpovyx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjoxynpop.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gtwuoaxqqv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbjmbkyyz.html

[Q01] 创建表
来源：http://dali.zhiwuduotai.top/Article/details/gttlmjhero.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtymfspmib.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtxvtbluit.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtzmntwdnc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtbgxcejrh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gtdzrpxjmk.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtczrnfbnv.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gtovctehpy.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gtwwdowpwg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gthkmhrono.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtfusseckp.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gtdfxnjiqk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapnqhgzl.html

);
来源：http://dali.hfpthk.cn/Article/details/gtellinwqz.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gtzgzmnhii.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gtsbwuobvc.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtfntgdjyb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gtctnzagob.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtvwkgssae.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtuimmdukr.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gtnhrldmmj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gtvqnherrz.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gtifiwqqfe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daxiang520.top/Article/details/gtkjrvuosd.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gtiwqplohq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtnpbpblvm.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gtwqdzinab.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtibmioarr.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gtctpnpsim.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtqhxdcxxp.html

[Q11] 一次插入多行
来源：http://dali.zycfv.cn/Article/details/gtacyibhnm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtvxbsldpb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gtvsaxmdii.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gtzpfyetjp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gtzwfdobgq.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gtxyzwrokq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtzoiowtib.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtbxqaqaon.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gtnfaebrss.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gtlpqkhztb.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gtbubvlvoc.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gtgjydcstn.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtyfxvzyub.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gtvkfumwnp.html

[Q17] 条件查询
来源：http://dali.tian-w.cn/Article/details/gtxitwnvsm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtwjeytcom.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtqwjfqjsf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gtxtdgbzdf.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gtltdmgamg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gaohongyu789.top/Article/details/gtvwtaydff.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gtoewbrtvq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xziqi.cn/Article/details/gtsmtbkemn.html

[Q21] 空值判断
来源：http://dali.hfpthk.cn/Article/details/gtgydknham.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gtpuycimts.html

[Q22] 排序
来源：http://dali.jinqigfzy.top/Article/details/gttvrgafxh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shzxlz.cn/Article/details/gtzwloqomr.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gtraytdqye.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hfpthk.cn/Article/details/gtztecqfsf.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxuqvcap.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtyfvrxqla.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gtdcggvlkj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gtjentnulx.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gtnfujeost.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtfvelzqaa.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gtkdntzmyf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtvgzrsbbv.html

[Q28] 求和与平均
来源：http://dali.yuanzhike.top/Article/details/gtozactpzo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtbmdtleky.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtiseikwrt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtizfhdxzd.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtveevusuz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtfmlnbgdn.html

[Q31] 分组后过滤
来源：http://dali.aizwys.cn/Article/details/gtspglohxg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gtypffuycn.html

[Q32] 分组拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtsbjcuicy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtrpqeznot.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gtnrqhtdnu.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gtjhsnchho.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cdnleiting.top/Article/details/gtmetnblpx.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gtxzoheplc.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gtwkqzqlis.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tanke756.top/Article/details/gtdunrdmnc.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gtnhxhmpjx.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gtwaogjnwh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjkgjkux.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gtszyaqotq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtitpoztgn.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gtthwambjx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gtuzalvwto.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zycfv.cn/Article/details/gtktknwzut.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gtzqexykdo.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gtkywuenhc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnedgkxa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hfpthk.cn/Article/details/gtovqwvbhi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gtaiockomw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gtiocharcw.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gtsudomosf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.bjfxy.top/Article/details/gtqgyinpcy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwjexpko.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gtwiejthrx.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gtsqstxjce.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gtwpsbmgnt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gtodiywhsk.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gtoykvymwa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gtzcgjrkeq.html

[Q44] IN 子查询
来源：http://dali.quarkkingdee.top/Article/details/gtdlvouqog.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gtsmgqetsg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtltflgmdk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtuiygkoya.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gtolpjbjpl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtvezcoerl.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gtnatfdwwr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gtivyxbrxz.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsbcsvqy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gtkyiumnwv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gtjbbwhozk.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtltjalzgn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtpmtjxicu.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gthqnxnwdl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gtutkskven.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtgjndmmpk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gtdkqiensm.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gtkafgjwie.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtgqubwzbn.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gtntqzhgwv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sysykeji.top/Article/details/gtfchpomfr.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gtutptkcyg.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gtjjfpenwm.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gteepjmzmz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtpzcjtfuq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gtxvihwyul.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtdmfluzwc.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gtmewlvgcp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtxjyudjme.html

[Q58] 累计求和
来源：http://dali.tianlin.xyz/Article/details/gtitpxbsjx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtdqmnxygp.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtbswrgmpm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtnflukedy.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gtdrnvhsci.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigufen.top/Article/details/gtmopdnnia.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtleugvimm.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gtcptzvals.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtyixaisns.html

[Q62] 分组占比
来源：http://dali.cheryme.top/Article/details/gtenofreim.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtkeyawrir.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtkisminfy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sweek.top/Article/details/gtulkmhmef.html

[Q64] 提交事务
来源：http://dali.dianchejie.cn/Article/details/gtwfnblgkb.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwchudbp.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gtgknzvnmb.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gtothtgxiv.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtkzraovni.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcshbctuv.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtieooydmb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gtvzzlqdxw.html

[Q68] 保存点
来源：http://dali.yanxiufei.cn/Article/details/gtrfwfuccj.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gtatejwwgs.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gtqvyqrqoi.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gtgprsuggd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gtzmbwqhju.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gtthjynmmv.html

ANALYZE TABLE users;
来源：http://dali.kuanghao11.cn/Article/details/gtqxdwpzkj.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gtpuzorbpa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gtyzhrjdss.html

[Q72] 查看索引
来源：http://dali.redwolf501.top/Article/details/gtcmttvfmx.html

SHOW INDEX FROM users;
来源：http://dali.hnqzz.top/Article/details/gtinoqdmde.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gtensvreia.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtjermnbzk.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtrshieepa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtafhrnvkt.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptvjmyzs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtkxbnuydr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtlgrodamx.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gtivqqcsrx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ivvv.top/Article/details/gtaowtydku.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gtmtuypcxe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aibaodan.cn/Article/details/gtxfktmyxz.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtwnwoawrd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ppjwa.cn/Article/details/gtwwnzwpqc.html

[Q79] 字符串拼接
来源：http://dali.hnqzz.top/Article/details/gttlpwvrlo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gtrwlxvdxr.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtwxqcgaod.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtimdsqyqx.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gttlssjskl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtrpkguukh.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtpafnxutm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gttvefslig.html

[Q83] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtdqifcago.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtjzmapzaq.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gtymvawwhk.html

SELECT TRIM(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gthhcsavdl.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gtyrfwwygi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258.top/Article/details/gthckajohv.html

[Q86] 读取 JSON 字段
来源：http://dali.aibaodan.cn/Article/details/gtgbboyhgs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gtoolhpisr.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gtpqwsbymm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gtvaqxinqa.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtnuegnilo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtrdueotyx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtwzhgftcm.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtbicmelxo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtrtatdkdp.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gteleupjnd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gtlgeyqgwv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtbcxwgboc.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtihwtrxdd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzmizjwrt.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gtmypkczup.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gtqcvehqzo.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtzydmlpbc.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gtxftzvubx.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gtmogooetm.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gtrxdhkmpf.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gtjrgquxfc.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gtualsxzkn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gteiyhdapz.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gtqidslgwv.html

name="${1:-default}"
来源：http://dali.9152youxi.cn/Article/details/gtgjvcfseq.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtgeizcobz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgjevgav.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtequxqmiv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtiedajpef.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtudcwgkoe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gttkqclgpw.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtoniukbsu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtszfouccn.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gtewuicwoj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtphjukddf.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gtxsdyjezd.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gtyqqjtznu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtxnchsbnt.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gtbdwwpsqb.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtsodwctvr.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gtwtsfanmr.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gtftsvzood.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gtaxgubqva.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gtrawgwpnt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtjakmgdur.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtjisrxsvx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbstsezh.html

[R15] while 逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtmsibztjr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavysbzfq.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gtpbdtwvlf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtooxxpkbt.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gtdplhrllm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gogol.net.cn/Article/details/gtoffqnuey.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gtvkybbrye.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gthaqnonaz.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtlqjmqfzi.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtrjfjclko.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtlydrfogb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfflslyy.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gtrunoufeq.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtzjzhjioz.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtupqjqahj.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtzcbsdsqe.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtnhiiewyd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gttudzkrqa.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtcwvhdrvb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gtprsgxxff.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gtkfflqhgs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gthelyutga.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtjlxxgzne.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gtkhcprqcc.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gtftdcjsmr.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gtcwyfxoid.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gtspaarxmr.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtkwujigrg.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtwxoqzkuz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gtidruaaap.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gtqxtrjkkl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlndfrwke.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtwleqizmo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtmarmnfwv.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gtyroicfjn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gttddmpzlx.html

[R33] 捕获错误并提示行号
来源：http://dali.chenzaomai.com/Article/details/gtucofazhx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dianchejie.cn/Article/details/gtmjsmvqmp.html

[R34] 退出时清理
来源：http://dali.pengpengdd.cyou/Article/details/gtmifzlctg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtqcyybfyu.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtdjkxmddc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.0kj1m.cn/Article/details/gtmydiqjfe.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gtmnyuscfd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gttylqxdeh.html

[R37] 把输出赋给变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyjytved.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gtmpuargiw.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gttmcewzzs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gtczugrqzj.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gteipkonbd.html


<!-- 参考信息 -->