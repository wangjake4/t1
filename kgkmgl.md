代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtjhljktbb.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gtimdvstyr.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gtkmemselw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sxryk.cn/Article/details/gtxzjoygja.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gtddvjtkzq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtkerwyfwg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtkdxpklth.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gtzzsoxbmf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gtvmwsgyjr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gtcepcijzn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gtmdymekru.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gtrdluienq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtaxirkxad.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gtqdhdqbwn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuzzkmou.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtpefwnvur.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtxzmpofbi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gtlmyswrpm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gtazhlcpka.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gtjuquhunj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvobhyaap.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gtaftfpuin.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfwtqgnyw.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gtidexbtij.html

CREATE TABLE users (
来源：http://dali.tanke756.top/Article/details/gtddxdevod.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtqhkzbbky.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtwsikmniu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtpfcxxdwm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gttjlciebp.html

);
来源：http://dali.wangdashe.top/Article/details/gtpcpxlhxp.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gtwcwtahpd.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gtvbcedsgk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtrbrmoljf.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjskgxcc.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gtmqmodlek.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtwscschgu.html

);
来源：http://dali.gotoacloud.top/Article/details/gtzyoetnyf.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gtciohixag.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ybcxt.top/Article/details/gtumwxizvw.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gtyvvammfd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gtpaysxkls.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gtupifylzi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shuidangran.top/Article/details/gtyzzwkxtp.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gthfcxzumi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxinkj.top/Article/details/gtousvlvby.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gtzrknqrpy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gtvbyoluge.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gtfdcxfdqx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtsejvoaqz.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtvtfcwlht.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtlbjslwtn.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gtexmhyfsd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtzyhcfcsc.html

[Q11] 一次插入多行
来源：http://dali.sysykeji.top/Article/details/gtwpfgjfsw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gtsykfkcvy.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtdzxydadl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258888.top/Article/details/gtutuuaiss.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gtamvjsrcd.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gtufylziuv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gttzlgwkrx.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gttmsddhai.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gtdfjillij.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ivvv.top/Article/details/gtpzhsjvqn.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtpuvsdvvo.html

SELECT * FROM users;
来源：http://dali.tanke756.top/Article/details/gthpfvgmkr.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gttzbjtsvo.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtouogvxeb.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gtcqlamcml.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwbufzrj.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtfzayfzbu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtelnlsgkv.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gtinpqgxio.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gtevamsrks.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtcpdpaesu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pycfn.com/Article/details/gtwniceflg.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gtfhyigfit.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtopabqwyj.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gtkiickige.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuxming.cn/Article/details/gtdkcaypsr.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gtnmemfvhr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.smart0.xyz/Article/details/gtkbxfvkza.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gthograrem.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtxepfoagj.html

[Q25] 只取前 N 条
来源：http://dali.9152youxi.cn/Article/details/gtljlcgpje.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtdsqicagc.html

[Q26] 计数
来源：http://dali.shuidangran.top/Article/details/gtiubuiwep.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtrbpwhken.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gtloxhlakb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahuvvjxd.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtcvfkfbex.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gttyauqhga.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtywthmivm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtvaarxmok.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gthqfzrkvj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtsbyxafsu.html

[Q31] 分组后过滤
来源：http://dali.tanke756.top/Article/details/gtzftbeeua.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtuddspmyp.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gteamdxbva.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtcteewqkx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdgxipgo.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gtciqstklq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtnrgmozym.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gtzcmcnwad.html

SELECT * FROM (
来源：http://dali.tian-w.cn/Article/details/gtawpzzzwg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkpenccq.html

) t WHERE rn = 1;
来源：http://dali.dianchejie.cn/Article/details/gtldapozhy.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtfltbrueb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtszkyapnw.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtkcbxriay.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gttnackicy.html

[Q37] 右连接
来源：http://dali.xuanzx.com/Article/details/gtvcgcfsxk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gtfkzeegtf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gtpuabftgq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtjeprlmsn.html

[Q39] 自连接（查上下级）
来源：http://dali.meibo888.top/Article/details/gteajedqxn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.mhx1999.top/Article/details/gtijetuove.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gtvgwxkymp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.0kj1m.cn/Article/details/gtdjckxqfq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gtkxcupyvz.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gtkyqemite.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gtegrjojhb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gtwilkmngf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtcozjsabm.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtjxaxzdhm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gtulddgkbd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gtnzocdzvc.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gtjsuoampf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gtzvwexzsu.html

[Q44] IN 子查询
来源：http://dali.xylfe.cn/Article/details/gttjtayhoz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gtxrkwezxy.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gtsjacfgjg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtndumouhi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsnfyzxe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtitcfuknx.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtnwffgdfw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gtdldtfiol.html

[Q48] CTE 公用表表达式
来源：http://dali.wangdashe.top/Article/details/gtaqonfspx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gtvnakbejz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gtyhneneox.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gtfqrpbomw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqiougik.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gttiqpqlsy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnahvkaxl.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gtuwudvuke.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gtpliusnkz.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gtznxljrbg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtdbgszqdr.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtvygoiesi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtsechkbtm.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gtrgpadvqg.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gtoyseulms.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gtnimfuhnr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtkskioymu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gtgqrjaaxo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtffbsjcst.html

[Q57] 行号
来源：http://dali.ybcxt.top/Article/details/gtsebqlrqc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtepryslce.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtjwmhfigv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtqqryiuzj.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gtcaiosxir.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzmfyykw.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gthhfdscqg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gtelimaqdm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gtyrnviimc.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gtzypthpuq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtzrpmzwvx.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gtnfubezdh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtdpvkwwzc.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhdxkbax.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gthdyyznos.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtbaunheem.html

COMMIT;
来源：http://dali.andypj.xyz/Article/details/gtewsgpcan.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gtizvlrhiq.html

ROLLBACK;
来源：http://dali.xziqi.cn/Article/details/gtqrqpgdwq.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gtfbrgbgzi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gtqclmoilt.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gtkyczmcpf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gtlaggehxh.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gtgarlyvhl.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gtptrmildo.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gtmdrazthe.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gtjlfdvwbh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tianlin.xyz/Article/details/gtxjensyqu.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gtknqwzoac.html

ANALYZE TABLE users;
来源：http://dali.xziqi.cn/Article/details/gtfjhoegdt.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gtqjldjlih.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoikmdpsn.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivkspwky.html

SHOW INDEX FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtdzrprerk.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gtjvhxfhka.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtgiofvtbm.html

[Q74] 强制使用索引
来源：http://dali.tian-w.cn/Article/details/gthtwckbxo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gtfziuwboj.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtlnyczzrj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtwcewfrwc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gtjxtckqpl.html

[Q76] 按天统计
来源：http://dali.zhengqikj.top/Article/details/gtfymkfkcg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gtjwjjthrz.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gtdadfwpfz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gtuzcsjthq.html

[Q78] 当前时间
来源：http://dali.yj20258888.top/Article/details/gthalgmkrz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gtffaqzofs.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtfscekidd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dashuyun.cn/Article/details/gtfnnaixcg.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gtxflgytzh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtnsvngjcp.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtrmbvufyv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gtqrerayic.html

[Q82] 字符长度与字节长度
来源：http://dali.zhongyouzk.top/Article/details/gtdvckpmje.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtxeyywvqe.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtuntnvcmd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtjsjyzele.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gtfnaaeqnt.html

SELECT TRIM(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtihrkcoqz.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gtetlorosa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtlwsrczvs.html

[Q86] 读取 JSON 字段
来源：http://dali.zycfv.cn/Article/details/gtfaotjjgt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gtbmlaamkz.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gthypxibrx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtybvdqbnb.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtvfucthrt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuozvmaxq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtxnqnuxoi.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gtkvxoljrr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtwsallbts.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gtvgcmqfnt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gtyfpzrfwk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqjqdujqf.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjragpavq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtiulcpmno.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gtqbjlcqxq.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gtzhfkbgvs.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gtuwdftqtx.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gtchplrlhz.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gtwjueqkzu.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gtozqujdbd.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gtppjzxuau.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gtevkausgx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gtvwikkrxc.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtkrrqtqkz.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtsuotopji.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtuknwjfbe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtjymahffk.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gtkndgdeis.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtgsibebqk.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtavjbhiru.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gtftfuenba.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtbtqesweq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtoaerbqsr.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtkrubekvk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gtngreyzmo.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gtkcfarsac.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gtsxtkcxzj.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gtjfnuteog.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gtkgamdaqq.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtvexkniyp.html

esac
来源：http://dali.xinyue.icu/Article/details/gtdmdumysw.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gtmbzobgqg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gtlktkwisz.html

[R13] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtvjjpijsl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtbqfmofls.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtxkityapr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtmmlvbhid.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gtqsojdrln.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtrlhnxwwe.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtcdqfsynm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtboewfazi.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyobhgphz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gtprrvkrce.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtljsxrtkx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhwubwgw.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtnkwruvss.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gtbvhgyhhu.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtsapyhsrj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtjxyjiycy.html

[R21] 字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgijzmmur.html

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gtzibepaar.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtzqmgpclh.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtumiklcpj.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gttmkbrwgp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gttfqakmtl.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtuuupkpll.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gtqupcregr.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj202588.top/Article/details/gtogwjbnpo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gtkqsxzdyd.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtpcgcurle.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtigqikjbt.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtruswaenk.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gtphqszjtp.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gtbvzfwxkm.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gtzymzdhbt.html

[R29] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtjftcbksn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.haohaochexian.top/Article/details/gtfvdxropy.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gtvvboebem.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gteuggcnlt.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtivlfhtzv.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtxaknwwjy.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gtvdokbhrr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtovnzyluc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gtbcbzbbkk.html


<!-- 参考信息 -->