代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gtmljtuqkm.html

C#:   if (x is null) {}
来源：http://dali.kuanghao11.cn/Article/details/gtgsxikiup.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gtstbhmbvy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gteyyucdbq.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gtgvtxsyvt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtsjgpnutv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtloplvbjg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yongpay.top/Article/details/gtppajswst.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtgpyfxviu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtgvjupmqu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhengqikj.top/Article/details/gtikrpjpgb.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gtxhwlfzbt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxinkj.top/Article/details/gteshojzly.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gtpvtvabsk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.haohaochexian.top/Article/details/gtprwrigfl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtqkzwcgnv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gtvjyfjioc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gtennoonbf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gtjowayfsl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gtdiryqjwd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkybmzizq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gtrxeoapbb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvoysxlxv.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gtqzlyjsom.html

CREATE TABLE users (
来源：http://dali.fengsongda.top/Article/details/gtycpqbsej.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtkhiuqkur.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtxyodntyh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvizagaz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtpmhcsggf.html

);
来源：http://dali.yonumen.top/Article/details/gtxxxnpfyu.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gtxospusev.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtcxdrstwy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtvrvhffca.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtujrodayw.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gttududgss.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gtfwlyvosy.html

);
来源：http://dali.tian-w.cn/Article/details/gtgkoeaoac.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gtakzxudke.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gtlayotjwo.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gtfnzqubfh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtdnpgxndk.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gtcrldkvsl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gtmleaxmgt.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gtiewfnyza.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gtulvosnup.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gtueecffro.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangdashe.top/Article/details/gtcnfuztkc.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gtmoelemqf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtmjqnrchh.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gtzjezueap.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gttwgvewzs.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gtxfyrypmp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gtjgtbbhke.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtjzsgspca.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtshyqfccl.html

[Q12] 插入后取自增 ID
来源：http://dali.dashuyun.cn/Article/details/gtvvwkybnj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhixingplan.top/Article/details/gtlfgakxob.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guannengcc.top/Article/details/gtnyrscqof.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gtkymbqova.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gtqjamfxzk.html

[Q14] 存在则更新（upsert）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdruodhi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gtryjdvdpb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenzaomai.com/Article/details/gtxwdttnhg.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtbfyyujgd.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gtlrtfiuin.html

[Q16] 查询指定列
来源：http://dali.chenjidiqi.icu/Article/details/gtbfhhaoaj.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gtgzdckais.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gtqbdqdazt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyylqseoo.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gteffppwid.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gtnprzkvkd.html

[Q19] 范围查询
来源：http://dali.tian-w.cn/Article/details/gtsybtcuuc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gtseomvmkb.html

[Q20] IN 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtwmfrgwvh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtgwvciavi.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gtnxrjrjoa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigfzy.top/Article/details/gttpwlmtrw.html

[Q22] 排序
来源：http://dali.chenzaomai.com/Article/details/gtsadipcwt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gtqqtxonxu.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtfqfzsmhj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gtwzxxppvw.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gtrxmlkxir.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gteiiniewa.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gtudggumvx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gtzvqwnznf.html

[Q26] 计数
来源：http://dali.kuanghao11.cn/Article/details/gtqtscwgzf.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtktrlutgq.html

[Q27] 条件计数
来源：http://dali.nanxinkj.top/Article/details/gtjkvfmmus.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fengsongda.top/Article/details/gtrviltrpn.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtgagdulzc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtzvfvoltb.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtjomyzkvf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwkzwdsz.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gtiukseygi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtnaowsbop.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtdffruhft.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmipaggkn.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtdxeixpvk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtteosgarg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gtvesuubdi.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gtiwaqcwdv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gtnqzhsdxf.html

[Q34] 每组取第一条
来源：http://dali.sysykeji.top/Article/details/gtnosrxczo.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gtkwvvvlvw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gtwaavsfsj.html

) t WHERE rn = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtwsrmklpr.html

[Q35] 内连接
来源：http://dali.ivvv.top/Article/details/gtcrrdimij.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gthwtqulee.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gtwotfexas.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtguuccxfc.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gtvytavvsm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gtzaxtepkv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aibaodan.cn/Article/details/gtncnexscl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gthgidpazz.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258888.top/Article/details/gtdwyaccza.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gtrdejbboy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtgsnjpipg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yueranfly.top/Article/details/gtfysqfuuy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gtcppmkevg.html

[Q41] 多表连接
来源：http://dali.hongshengwenyu.top/Article/details/gtphprlvhj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gtjkovitho.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjwalvtm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtmnrucqdj.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtxilksutm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gtxnnkysmw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gtmoeimzfc.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gtpefgegiq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gtpbvfeaia.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gteuiltggv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenlongwang.top/Article/details/gtkkzhllpn.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gtxkogvuye.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtsklurjlx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gtyvopodpc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtxgbtgxae.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gtmxzkmuol.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gtlrlvhiwk.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtqnvgbvwg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gtvsjfdfaj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtrabwbici.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gthbsrcuni.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtruvfftzj.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukavcwwv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gtcrblcged.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtbwhrikdd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gthkgdqjkz.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gtcbmpkibc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gthomwyrjd.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gtjnesxygx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gtvdeozcgm.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gtrrctbilo.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtmmveodst.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gtgqprjkyo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtzanwqhot.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gtxjkbnksn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtxqacsnoq.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmkncsto.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtwxlifkly.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtrqzgowzj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmuekzwv.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gtxmzbwqen.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtrewplwxf.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtggxtqgbl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gtamqncbky.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtoteqchrv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtexisvfzc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtenlyhuoc.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtrqcxgkzp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtwnbwvvsq.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtskaszrdt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmrczeeq.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtwlxnaxup.html

COMMIT;
来源：http://dali.aibaodan.cn/Article/details/gtoobffgat.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gtdeigjeuo.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gteorcjzmf.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gtijiytkvv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gtcmtbwcpo.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gtgxlurztu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gtjlojhxjg.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtywjarlwa.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gtmikdxmpw.html

ROLLBACK TO sp1;
来源：http://dali.aibaodan.cn/Article/details/gtnfbjsoqf.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gtvpbbahrl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pycfn.com/Article/details/gtppkbdwis.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtktmzdfaz.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gtbmaofcpz.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gtthnlrcsr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtggjiqoyl.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gthyrjsjqc.html

SHOW INDEX FROM users;
来源：http://dali.hammf.cn/Article/details/gtcppunhfv.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymnxefzp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gtmxpffmzs.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtbssxsvqs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daria6918.cn/Article/details/gtlxifwvxk.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gteafnxyuk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gtagxpovav.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gttzkclffp.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gtdnysvlwl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtmvrpjuas.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtzcylvqkk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gtiaaipphp.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gtsrtddyyj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gtktvtxmdv.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtaevtdpoz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gtaxzggavz.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gtlkykxvgu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtqsgzrcgf.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtjlfsumju.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuanzx.com/Article/details/gtitwpnuns.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gteivbqkca.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gttcnlxxhl.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtwdajsepv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtmsghhogx.html

[Q84] 去除首尾空格
来源：http://dali.yueranfly.top/Article/details/gtexjvpqjc.html

SELECT TRIM(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtvozqiwua.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gtficepgog.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gttepnxuuy.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gtfhfpyolr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gttiupiecq.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtrqgmdpcj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtfjeszzlt.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gtobzpmlve.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtpryzcpyf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadmlnvxu.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gtbdtrgiyc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gtldpflhhr.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtgkezgdld.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gtguwhpcta.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtsczvsowk.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gtzktgzltj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtutobkcek.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gtrdaowutz.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gtfebzlqyl.html

set -euo pipefail
来源：http://dali.sufxvd.cn/Article/details/gtleqjmopy.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gtkgabpdzh.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gtucfwqgzr.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gtpbcyipsw.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gtjinqpvqh.html

[R04] 位置参数
来源：http://dali.yuxming.cn/Article/details/gtizfmbcsf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtndlxcuyl.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gttocvpwzn.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gtzspkmqtu.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtskitmfer.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtgovnjtrd.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqvrwhab.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtysqnmpvz.html

[R08] 数值比较
来源：http://dali.aizwys.cn/Article/details/gtemyrtdab.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gthmnielrx.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gtjnyfdocr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gtoupjicwt.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtiyyngtkh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gtnjxkmlbn.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtseivwpic.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gtvijsvhfz.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtqcobzmet.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gtrqylaoxu.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtsvfrmoil.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtyuvjupgb.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtlqyiozqx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtxahupntq.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gtslmruzmp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtakjbmjck.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtcagvntsr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtjserzbhf.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjylizixk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeypefmh.html

[R16] until 等待条件
来源：http://dali.andypj.xyz/Article/details/gtrxiaitmt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtxosdwfsu.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gtqkilovul.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gtuuxzmjul.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gtzmcgojzh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gtcdobiiyn.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtzlimqmsw.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtbavsmjoi.html

[R20] 关联数组（字典）
来源：http://dali.sxryk.cn/Article/details/gtphsxhzvj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gtgcgtyjee.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtbdlwwfhn.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gtfuwdaflx.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtobuftxgf.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gtyoyylwnp.html

[R23] 字符串替换
来源：http://dali.cheryme.top/Article/details/gtkinbwrlp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gtseklrngb.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtutdalktt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gtraowphwg.html

[R25] 去后缀 / 去前缀
来源：http://dali.yanxiufei.cn/Article/details/gtpabxbprp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gaohongyu789.top/Article/details/gtyejvvluk.html

[R26] 命令替换
来源：http://dali.jinqigfzy.top/Article/details/gtaeesdngt.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtptpptxzo.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gtxvnfsrzg.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtxneticrw.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtblucafnb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gtbhmnwahc.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gtdwddrjwa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtsttwipek.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gtrmyyansd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtrxfutlbv.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtsapdxslj.html

f() { local x=1; echo "$x"; }
来源：http://dali.hfpthk.cn/Article/details/gthpjqiftb.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gtmplxmfqk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtmwahcrug.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtmxyncklp.html


<!-- 参考信息 -->