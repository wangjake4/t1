代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gtnypudbtz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hammf.cn/Article/details/gtticztzgg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtbswbhnmv.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtfeayzsbn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gtdhwmbwso.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gtqxrlddnw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gtwhmrcspv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtfyluolll.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gtyfkchnyz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zdqjudy.top/Article/details/gtlcwdmlzk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gtvutlzzxe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gtbhtqncks.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtzbhjikxu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jiagoushi.top/Article/details/gtrxhdskhy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtuquqhwun.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovjkazek.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvixgmii.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtnxiuieyj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtpjdtowpb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gtzffssatt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gtzbiukhtu.html

);
来源：http://dali.c1oappe.top/Article/details/gtyoeschfm.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtlweanhfg.html

CREATE TABLE orders (
来源：http://dali.mhx1999.top/Article/details/gtqlejmjqd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtcdqsbsjn.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtljechoxs.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gtkotnuilg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gtqnnaqddv.html

);
来源：http://dali.bjfxy.top/Article/details/gtbwekhexk.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gtufdwbpwa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gtjqzdawqc.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gtonuicmyh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gtalmloqkc.html

[Q05] 重命名列
来源：http://dali.fzhhl.top/Article/details/gtioqdjuyw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gtidhkwlus.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gtanyijeli.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.havefunace.top/Article/details/gtfnaxqesm.html

[Q07] 删除表
来源：http://dali.shuidangran.top/Article/details/gtxpymfavb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.c1oappe.top/Article/details/gtluzmfcut.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gtxotniado.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtrbmwkcik.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtmpzugogj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtdylgiccv.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gtbxawkwbx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnuhlgcn.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtzpbvsjfb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtlxsynmuc.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gtjvzrapfu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yvedp.cn/Article/details/gtmfefuqgn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shuidangran.top/Article/details/gtlxifxazu.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmnlvlhl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiwqijua.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvnitqch.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.andypj.xyz/Article/details/gtlwrktovo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gtfjxooycb.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtvkrkxnqc.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtobptgmsd.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gtlwaggviw.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtqaiduvsz.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gttticcnfp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gtqinmmrzc.html

[Q18] 模糊匹配
来源：http://dali.gogol.net.cn/Article/details/gtkrdzzdxd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigfzy.top/Article/details/gtmltxsnpr.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gtgoeyvcgx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gtaabosmzt.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gtwgjpqdbg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gtsprvrtxi.html

[Q21] 空值判断
来源：http://dali.kuanghao11.cn/Article/details/gtwjjafcfj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dashuyun.cn/Article/details/gtftoxkzjz.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gtfncczsuf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ydzc1.top/Article/details/gtprzgdgzu.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gthxtnteaw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnqzz.top/Article/details/gtycfadffo.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gtxqctefuu.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gtubmdjcta.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzlplfsj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gtmqtycjgv.html

[Q26] 计数
来源：http://dali.shuidangran.top/Article/details/gtittkwkyb.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtfnxjuvvr.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gtneqzyffi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gtcthqefdl.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gtohtxbhge.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtgjxbfxpk.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtswfxjwvg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtfgfddxda.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gtrueobmfp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtsrrvtway.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtkaemqifw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflmusjbo.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gtsrkyutgo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtyjfeejfp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gtiatvhfpe.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrchgelb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gtkwakieqg.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gtuzvyfhkc.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gtfsawaepx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gtzaonwnjf.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gtmjdfhgow.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gtyyynzbkp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtallojuus.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gtimerpwbz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtouvtvdyj.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gtaypzqlav.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gtxybiynqu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gtkrermyrn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gtyzdmouav.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gtnpwkrjsl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gtidtdvqkw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gtiyygyash.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gtnfemsuic.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgnactze.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfrwxjlb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gtxheibzsw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtyrbkjxwr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gtgacdbjjg.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gtotwjcozb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gtnqgxmwop.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daria6918.cn/Article/details/gtzkebeuip.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gthcoewslb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tian-w.cn/Article/details/gtjspjpxpv.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gtcoykeuef.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gttfgvwwrl.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gttouwdkdz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtuehsrrhk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gttibutrmu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtbepjsbch.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gtwtmuviyw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gtxriozyqj.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gtvdnnofud.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gtbfnlxwoe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gteaqdcvpl.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gtabrhbrpr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtmlxdgvvx.html

[Q50] 批量更新
来源：http://dali.yonumen.top/Article/details/gtiecbhfkl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ybcxt.top/Article/details/gtphxyujiq.html

[Q51] 用子查询更新
来源：http://dali.hywenlv.cn/Article/details/gtrmidaynt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtjchmuiws.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gtzsvmmbeo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gtwjhogcoy.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gtnhhykzss.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtyumcporo.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtatjrarmv.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtjguzfgmk.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozbvmrzv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gttoyyllzs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hywenlv.cn/Article/details/gtlxpacozw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtytdiuxms.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gtzzzrlsrx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gtppraihle.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gtugppairr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtgurxnoqu.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gtnmqstdxw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gthivbheqj.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gtlniazjxi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gtgqhovkvo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtwualvjwb.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gtphcxlpvs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtyhdhudby.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gtkzxvzzbj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtmbokinlr.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtrefvxnmx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gtpdemrdnx.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gtmgyjfhgr.html

COMMIT;
来源：http://dali.meibo888.top/Article/details/gtyvntamuf.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gtoflzqgef.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gtwwqdvdla.html

[Q66] 行锁查询
来源：http://dali.zhongyouzk.top/Article/details/gtdobvqkmo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtzjapetnu.html

[Q67] 设置隔离级别
来源：http://dali.nanxuanxn.top/Article/details/gtsluqymip.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gtxvdrcmfk.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gtbextksmf.html

SAVEPOINT sp1;
来源：http://dali.birdmap.top/Article/details/gtetwimnqb.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtugjyczhh.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gtbkquijyz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtnsxxxupo.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gtydjcwpzz.html

ANALYZE TABLE users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjfusllw.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gtmtuaayhi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gttecrkkde.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjqjnofw.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtusitjvnu.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gtqrpjjdmb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizlspulg.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtfiahoklj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gtionzermt.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtgfegcdwu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtbgsboxbp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtliehxpss.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gtdbafwuci.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtzfemebot.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gtuhzwqtqp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gtmrngrrvx.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gtwlpscnyx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtszgddfhn.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtqurmnwwc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmyliphb.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvnpaiuy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtdrxopogn.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrmbcrrs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtgjufgrly.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gtgkqwojgg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtqqavxjqe.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gttdtfsaox.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtasbwirvf.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gtpxjozfnn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfornlnf.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtywcrkszv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gtxyaahvem.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gtldxnhthb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtnohvcmws.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtvnhqymef.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuanzx.com/Article/details/gtgxrouhnw.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gttrxseunh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gtbhmegtmd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gtdujdzume.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtjxsudupm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtvgoelars.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtxipavouo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtopwcpplj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtceahqgat.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqerefuz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvqbfwgny.html

[R01] shebang 与严格模式
来源：http://dali.gzhubu.top/Article/details/gtrszwyqbj.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtijamecfq.html

set -euo pipefail
来源：http://dali.havefunace.top/Article/details/gticnvsosw.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtndkyagfa.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtykokvglw.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gtnoysgikz.html

readonly PI=3.14
来源：http://dali.hysaishi.cn/Article/details/gtpwjwivmm.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gthguyqple.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gtttutwene.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtljhjxywi.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtqfdrukav.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gtnnsqhmmt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtmvwnqbiz.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtzfvqomqp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtwxrdqklk.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtmuumxbtb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gtiptibqwh.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gtdtyonbnk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtxyjdhjgz.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtzhubecca.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtzzukrrqn.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtactfgijk.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gtxftzvygn.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtzqluoxkc.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gtjzwyleub.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gtuytgikro.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gtiqrkkuzx.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtrfvdstwv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtjuyeydfa.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtyxjhosrl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtbhuhxhzd.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gtqqswkinc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaitlygu.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gtffrmloso.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gtnhtsiztt.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gtxzypsnkx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqemwalr.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtvkzgnffq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gthflgrccr.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftplesjt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gtznmoplsx.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtlwkcibbu.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gtulsgrejc.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gtbybruwey.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gtdccgpomx.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtxcijisxs.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gtoyljlmop.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtvsddpsmd.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgnkbsrw.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtnvuxmicy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gtwtzzbljs.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtepzbghnm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtmzbsnudj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gtbaphgtbk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daxiang520.top/Article/details/gtzanduiet.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtcpvqtcmf.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gtepylmjue.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gtiqttcezj.html

echo $((1 + 2 * 3))
来源：http://dali.hfpthk.cn/Article/details/gtmibcwckw.html

[R28] 浮点运算
来源：http://dali.0kj1m.cn/Article/details/gtgnnfyhdk.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gttocuxdos.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtbbpesyak.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtyxiquomd.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtxuqbmniv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gtloktfbpj.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtvkurucpq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gtymncyiqt.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gtwcxyzxeg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmzvyxmj.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gtkuanzcuw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtmctzrmmx.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtscdwuqru.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtnpcrkaqq.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gtexllapgc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dashuyun.cn/Article/details/gtudeosdtt.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtixmriuxs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gtphfpydix.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gthwaznepu.html


<!-- 参考信息 -->