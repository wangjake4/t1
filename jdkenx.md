代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtlmjmdlrc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenzaomai.com/Article/details/gtfjwoucuj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtpotbfhlv.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gtecvcxefr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gtlttqifnz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gtahdqmxvm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gtpxjjezom.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtrubsjnqn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gtphyaiowj.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvzsspcux.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtfvajbkjz.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gtbzjuygfn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gteyrraxik.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyztipvoh.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gtjldvtnqd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gtqcotxeke.html

PHP:  // 手写时间戳比较
来源：http://dali.vqdsnc.cn/Article/details/gtreancfcr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtmxovlxty.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtpavookkc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtglrudbyu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtwkobqaye.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gtwlvsphfk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gttmaqwelm.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gtqkhkpiyn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gtmsdjprga.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cucudq.cn/Article/details/gtcbqqfmba.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhaomingkeji.xyz/Article/details/gtingtvrkb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtvysjulcv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gthnvzadvb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasiiwiai.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daxiang520.top/Article/details/gtpotxumwk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gtjqysipym.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthcpyuaza.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gtorcvbncg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrardbygq.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gthgpupezn.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtyvcwmjda.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtqofiehji.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtatpkjauf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtdxgixnpn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ydzc1.top/Article/details/gtklweevva.html

);
来源：http://dali.zhengqikj.top/Article/details/gtcmylqawv.html

[Q02] 创建带外键的表
来源：http://dali.chenzaomai.com/Article/details/gtdaouyltb.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gtdosqgdyd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtbgfcvfaz.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjrztjsv.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gtoevjwbah.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtwqtoaqua.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtsurzdaxl.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgobvvowy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtigvsqnkt.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gtdwbppqjj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gtwpqyycsl.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gtdxqixgnu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cashguo.top/Article/details/gtbdsavojl.html

[Q06] 删除列
来源：http://dali.wangshuangyany.cn/Article/details/gtxcydtpyq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gtzvuvwldg.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gtekuqusqt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtohjekhps.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gtqivaeffg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtxenaecsy.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gtzeysvfbm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtsrderost.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gtaxculdig.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtkfklxjay.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gtuomymqee.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtgsgmbspg.html

[Q12] 插入后取自增 ID
来源：http://dali.hfpthk.cn/Article/details/gttwhenlzf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gtudcsqqmk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gtcxavgplx.html

[Q13] 忽略重复插入
来源：http://dali.hfpthk.cn/Article/details/gtatyoabcx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcffzxds.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtvazpnqfh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.havefunace.top/Article/details/gtubvzzvxb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gtdctkqbqm.html

[Q15] 查询全部
来源：http://dali.sufxvd.cn/Article/details/gtwuldwmqe.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtofafiuxc.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmmfaisz.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtguaqqrdr.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtbvmmokqx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gzhubu.top/Article/details/gtojoyjzlu.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gttboedjtc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gtkmgxjfnh.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtudgwbvgp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gtmtvpfnak.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gtmtmhsilf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gttfhawdyq.html

[Q21] 空值判断
来源：http://dali.wangdashe.top/Article/details/gtoclaqfrn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gtowkxktrp.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gtfsmpmaci.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gtcpalgxgu.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gtnteknmpy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gtkizeoakg.html

[Q24] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtcxqcwoxm.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gtstgwvezg.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gtjgktecde.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gtcrdznzpu.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gtgeilgzjo.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtoligfonv.html

[Q27] 条件计数
来源：http://dali.jinqigufen.top/Article/details/gtfubdlrkv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzhaawrfo.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gtjiqkrouc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtpxleleow.html

[Q29] 最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtduzfxrej.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtfwnjuyjc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtjgyehbjx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtzzkmsuqj.html

[Q31] 分组后过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriqgfzrq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigufen.top/Article/details/gtdprbdfib.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtopmqizlx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtybolzvns.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gtlcgmxdst.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gtlfoxjixa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gteaskvddl.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtvkzyjnlq.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gtwfryuzui.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gthbxiewoo.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gtecnzowxq.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtqcwasipr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gttqwqdjim.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gtsmfovtyy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtrbypwxwl.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gtzisjyzjt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtqkmodmvz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gttqhnpwvq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gtdumfhrfo.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgufenzy.top/Article/details/gtikfzekgm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtvmsnrgkz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gtyaofsctb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gtsltlqloo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtamygksrq.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gtnefkyvam.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gtwjiafoby.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gtgfdirdrz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenlongwang.top/Article/details/gtoorhebxj.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtusicgsig.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gtutkhyjbb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gteartvvlu.html

[Q43] 标量子查询
来源：http://dali.birdmap.top/Article/details/gtqgucbvaw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtjcznhusu.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gtobyabvgx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gtexfloxqj.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gtzdmwvccp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtghzwfcoz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgoozsbn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtctzlbvkb.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gtymvjlrox.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gtcyeprnch.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gtkyiocbnm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtscjxonqi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtbtzoarsh.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gtvwierivk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtcvtfosvn.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gtehjzqlwy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gtgyohmkss.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtdwbffoyc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gtkmlumfxa.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gtsgcuanou.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtwauyuvks.html

[Q53] 按条件删除
来源：http://dali.daria6918.cn/Article/details/gtoiebfxhy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtulmipkok.html

[Q54] 清空表
来源：http://dali.smart0.xyz/Article/details/gtxftgexmr.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gtsjkrjvtu.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtawojvajo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gtbingsmva.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zycfv.cn/Article/details/gtyowshemg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtnhddfoze.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gtabazpivq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hammf.cn/Article/details/gtcwyjybxl.html

[Q58] 累计求和
来源：http://dali.zhongyouzk.top/Article/details/gtvsqbvyzm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtwlcelshf.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gtlrabtazi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtryqihjuz.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbqolywi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hysaishi.cn/Article/details/gtkkggvkzh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtlajvebfv.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gtaugovgyg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtahefgeoi.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbitvdjhh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwfjatsj.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gttojbhtfa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhengqikj.top/Article/details/gtvyrwbpnw.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gtkenmbvil.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtduzdwauf.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gtzivslrvy.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gtlbklepuo.html

[Q66] 行锁查询
来源：http://dali.xinyue.icu/Article/details/gtbhqcogjl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gtqrfgawtg.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gtqdvhpxsc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gtabxdvbdi.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gtuptbetym.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtjyryoefl.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtajqwahkk.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gtwrfautmc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xziqi.cn/Article/details/gtfidppnqa.html

[Q70] 更新统计信息
来源：http://dali.xylfe.cn/Article/details/gthzbjjdsj.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gtwqfrvgxo.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gtvrivpuzi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gtlnknirci.html

[Q72] 查看索引
来源：http://dali.meibo888.top/Article/details/gtfgqdmnyp.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gteprpbqwu.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtdvpgbpuv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtfrvhumcd.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdauyesdl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgbkoymm.html

[Q75] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtwqyjnzfv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtkexdnies.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gtqwalbvxj.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcunqmge.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtebcuqxhs.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gtyqqgtrgu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.havefunace.top/Article/details/gtdfwxrucb.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gtnmhrauys.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gtujhubzqx.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtyidxeroe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gthdcgprdx.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gtfwinpadh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtxlumqmqp.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtozbaaezx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtgeuzroav.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gtdonimuds.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtvzvneqtt.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtwmgreygd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtxegalhcv.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbcanvqo.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtydydtxhk.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtiwvxghjo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtehaqljej.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtwfsegsku.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmqykhxv.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gtvscjclwe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gtqydunxty.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gtxdmyggxy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gttnggdqyo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gtyysetqty.html

[Q89] 判断表是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtudxayenh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gtfmyorgon.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtuvjnbsta.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gtwaoldbgi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgnlnflkl.html

R. Bash 专题
来源：http://dali.9152youxi.cn/Article/details/gtfmkmixqa.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtplxheyjt.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gtltzijqsc.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtyyqtgctc.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gtpnephzsx.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gtzfcimnal.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gtbmsnbpze.html

[R03] 只读变量
来源：http://dali.yvedp.cn/Article/details/gtzlcokcbo.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gtxqaoxrtk.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gtyjehijet.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtgvhijipq.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtmdqcnfbm.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gteagzunks.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtgvigxtdc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtykwyfpid.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtdmnlhqht.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gtlboymxjs.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gtetjgdbag.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtozkhezhr.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtiryddqdg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gtztmbpluo.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gtukyoztyf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxinkj.top/Article/details/gtkwwalnwo.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gtpqyqfawg.html

case "$1" in
来源：http://dali.zhengqikj.top/Article/details/gtdfolnipd.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtskksnzzj.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gtggwporxe.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtfnsuwigw.html

esac
来源：http://dali.ppjwa.cn/Article/details/gthlmvmyxl.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtuwbrluti.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gtinneasoh.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gtpkcdcosa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtvutpudsi.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtiymhgadr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtqncucpkk.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwwabhjqw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtaeiigcgx.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtqxrxgdmt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtpprepkby.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gtvmgvwizg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gthfhqqsop.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gtqoypjuns.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gtdluqyfgg.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtbbazaquw.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gtrwbiajem.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttemysaet.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gtvutvmsqg.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzoopszvs.html

echo "${#s}"
来源：http://dali.sweek.top/Article/details/gtuwbxgjzv.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtgbvsakwv.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtcfhcvwie.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtmspxvahv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gtrxqbpmsr.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtqqjrdxuz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtfbxlyyeu.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gtglqpspff.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenzaomai.com/Article/details/gtinkzrcnd.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gtgbzoyorp.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gtfqdkvxqd.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtpmfzgtjo.html


<!-- 参考信息 -->