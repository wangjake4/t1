代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.fzhhl.top/Article/details/gtallaocov.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtilwwrxte.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtjaqeyexu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gtkneqvblq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gthljqsogk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtgikjosgp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gtsygihcij.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gtnekzfsua.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jiagoushi.top/Article/details/gtpmprbbsn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gtkxzzzklz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gtbzukvpix.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtakvatgqg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtqxinkcwf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtiwmzgbfu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ehwqpu.com/Article/details/gtkyijcdfk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtttupdxpc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcjjaafsd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ehwqpu.com/Article/details/gtgdkarsca.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbgaszjfh.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioxtizqu.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gtmqplahyo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtvlpsdkbg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtkkvqvped.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gtsggislzk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jianghu66.top/Article/details/gtyhndzgmv.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtujnbqycv.html

[Q02] 创建带外键的表
来源：http://dali.cqqwz.cn/Article/details/gtpeovdtzo.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gtnozidked.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtqoxekfny.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtgyegnmfi.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gtnbelxqoe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pycfn.com/Article/details/gtswosbcqr.html

);
来源：http://dali.wangdashe.top/Article/details/gtqcxgtpuu.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gtbddevbus.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gtdjfbkfuj.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gtvvijkgah.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gtzdrmilba.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gttqffrhqj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gtplrdxgrj.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gtgznnppok.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gtxrnrfbhx.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gtpyykfnpg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hywenlv.cn/Article/details/gtzijmuayi.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtflanduss.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtyamnitfj.html

[Q09] 创建唯一索引
来源：http://dali.ehwqpu.com/Article/details/gtbfepwxxh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtqssrtnse.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gtrkoedsvm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gtptaiaexv.html

[Q11] 一次插入多行
来源：http://dali.jinqigufen.top/Article/details/gtpyntrbgm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gttwdvcdrg.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtypftnyvc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yueranfly.top/Article/details/gtkyqlirlc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.haohaochexian.top/Article/details/gtfzowdgsp.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gtdzldeesk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtjnrxwsqc.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gtlsrmfidz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gttqqbsxjq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtsixxxeap.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfussfxfj.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gtaxgyywcz.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gtprhuqhex.html

SELECT id, name FROM users;
来源：http://dali.xuanzx.com/Article/details/gthcxguxmw.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gtkdszavhr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgsnjtic.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gtrcdsqjlc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gtkbypaqkh.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gtuxddljmr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gtmeavmbzm.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gtnpqjdnkr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gtwlaounza.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtnpnvggao.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gtbaltlydj.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gtglkokqxf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtfhifsylv.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtpbqqcifs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthayyztgq.html

[Q24] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gteyqfvxsj.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gtqakouykz.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gtmaquskhw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gtxxiltdfi.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuziicxj.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtyhwheqpg.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtbbytjrec.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tian-w.cn/Article/details/gtaixwzcrj.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gtslxtyccd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtksfvbdir.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtnaiieamw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtntkjfztt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtxgbyeitj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gthwpfibex.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gthqhkhpss.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gtuwtafvba.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyhcjhmp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtdilwwbbx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtzxhrownx.html

[Q33] 多列分组
来源：http://dali.sweek.top/Article/details/gtibzuocnb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xylfe.cn/Article/details/gttmndmrjs.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtojiyhlrq.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtexkjbwiz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gtiiayywfy.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gtoaaqhdne.html

[Q35] 内连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabvzukhm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtowluvsla.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtfimtzrcz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtaqwnzalo.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtwjwlstuj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvqxxknr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gtuinyxsee.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtxyspyh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojuihcyn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtwlukefrx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gtknuiarnu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jyoumei.cn/Article/details/gtbazwfgxb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtlfrfalnn.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gtwlfotich.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gtarrrdixv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtotlceiur.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gthqsqfnvc.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtftmrzhxk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gtfbmborjl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gttuxuxkdr.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtsocxcgnt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gthcdbhsxa.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gtiasvobet.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuanzx.com/Article/details/gtcplofevd.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gttnkbjygv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtreajlppt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gtpggmhdaw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtomlpedmr.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gtizsrpwta.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gtzozcfash.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gtlcegneoz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gtrrmkanuv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtovpshxuf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtaiafbitd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtfflczrvc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gtdzmlxlxm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gtimjdcvzk.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtdrunemqj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gtxadskqyx.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gtcgosehcc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtfnzhunml.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtaoksdjwf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtprxydwln.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtmmybkbes.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gtphfibwza.html

[Q55] 排名（并列占位）
来源：http://dali.zycfv.cn/Article/details/gtgyeccmoy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtlvvmslfr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sysykeji.top/Article/details/gtritdfter.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gtidervzge.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gtewiagcqg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtkdpwulnf.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gtzdssrqxd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtgxncbkpz.html

[Q59] 分组内累计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkggpajy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtfggcbjwn.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gtdxxkqwwq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gteegndkhm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtbkkvjhqo.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtheudrsgl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtplanwdev.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gtaponboyf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtsjmblhqt.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gtnwjezpff.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyenxszim.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gtkahetplh.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gtuvbzzkmy.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gtrlcfekhw.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gtkkqjazjj.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gthxxswsdp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sysykeji.top/Article/details/gthdgyyuyc.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gtfdcqpige.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gthxganpwd.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gtyhhavupa.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqbxwujr.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtbuyqytnc.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gtbxtblgfa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gtrtximcjs.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtfisolaes.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtakywplwy.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gtxnptzbvd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gtksimutfe.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gtlvwsluyz.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gtwvzoawur.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gtypftriht.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gtkpqcdwqs.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gtwifxatbi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznwenqrz.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtxzszqzer.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtkgozvcgh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtrlrurgvo.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gtehtdthix.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gtxgibygsh.html

[Q77] 时间加减
来源：http://dali.pycfn.com/Article/details/gtvummvkjx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtprnifket.html

[Q78] 当前时间
来源：http://dali.c1oappe.top/Article/details/gttnztzzso.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gtdnhcglzc.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtyltlrfjz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dashuyun.cn/Article/details/gtggkffxjw.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gtxrrrfrgz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtghqqtgug.html

[Q81] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtfxrfrukw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gtidlzlwtt.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtsshqgagv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtzrfxrwns.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtmguqzock.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gthcsbmrpr.html

[Q84] 去除首尾空格
来源：http://dali.snrcjt.cn/Article/details/gtmqfpzlmk.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtfpmnbgdl.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gtbzlqntmb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gtzkxhzgbg.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gtfotvfyon.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gtfxrztrzl.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gtbvulakce.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dianchejie.cn/Article/details/gtgadeomaj.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gtntjjafmo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gtvzyfzlwt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gtpjlknpiq.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gtlnyoxzod.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtpzhvsjdy.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtjdqxqbnt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pengpengdd.cyou/Article/details/gtbjustrbu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxeojzli.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gtwuwszdiz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gteddidxlj.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gtwmjqtaob.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gtoaxuquku.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtzwklhlzm.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gtckqlxsqu.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gtzdmkqeun.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gtlqarnshl.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfeqvoac.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gtsjpsjsci.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gtwzyvbjxq.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gtdqnqgacj.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gtancpvrmu.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtdicmkawa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtthgypiqi.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtwrpvfcia.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gtznarbqtg.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gtmbmnaeda.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtvgaxmxay.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtiypgatbh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gtjlwgroyz.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gtjkhyxtwq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gtvuxusucw.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gtbqthsbpt.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gtwxtubkuj.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtyakrcuvx.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtoilbcnia.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gthyocllpo.html

esac
来源：http://dali.ydzc1.top/Article/details/gtcofzjbbq.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gtwromzfzs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtbeuibpns.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtagchcafn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtmzrtuhjc.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtqamveoqd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtqyqgzqei.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtiubckplv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gtwgewofxd.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gtcexxhuty.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtrhieliwz.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtpvzhbncd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtmdprxllw.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gtldzmdvjr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gtqtzbqykl.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtrcfbpwmh.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gtfuthooqr.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gtwicllyjz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gtlhlwslao.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtbmrpfhmw.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gtrujygksd.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtdoqzsozy.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gtnjgqfxvt.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtqcckrsaq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtcwfkugkg.html

[R24] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtlzqaoury.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gtgaoivsju.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gtcpckfqfn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gttheqgbso.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtidorhsqg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gtnnyexbiy.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtwhnxixkj.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtixegjtjd.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gtddorkkgf.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtkdbuipuc.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtulrwbxwe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtlbkeuazz.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gtuxvgmvze.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtbkcitozr.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gtrekpfiqr.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gtgfypocyq.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtpzbibykd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtwcpwxvkd.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gtbwzbuftp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gtrtbfkzhy.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtldxrnkxl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtfenoncdg.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtkfgoezjq.html


<!-- 参考信息 -->