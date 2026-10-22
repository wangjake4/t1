代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcxmrmff.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gtnfyunejn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gtixrurcbw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gtbeofaqbx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtydeagohn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gtdcenfggy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gtjbypzmpd.html

Ruby: a == b
来源：http://dali.dianchejie.cn/Article/details/gtijrycsax.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gtkezmwwan.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ehwqpu.com/Article/details/gtlgxzrfve.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gtvupalkjo.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gttnpszlum.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gtmmhmakpm.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipkcvaio.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtyhogdwjw.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtkrwstlcc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitrejlux.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtxujyhiiv.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtrwyokhgf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gtqjhmhgji.html

PHP:  // 手写时间戳比较
来源：http://dali.vqdsnc.cn/Article/details/gtbvghegza.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtqgmyphrc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtiusfrtdr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zdqjudy.top/Article/details/gtasmdiqaj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtwpsndtgj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnqzz.top/Article/details/gtipuiyony.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gtfgnbpmue.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwtsjptf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gtzsryxdrc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtkkrvzdwk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtmmrgjpdo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gtyarqrphw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpmajjgh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gtetqcaqio.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcvwmvat.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hammf.cn/Article/details/gttmpotucj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtiuuxfcyf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gtqgoigszs.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtctytdlhk.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gtmsgmxrpw.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gtmornckmb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtmdbcwfqc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtatsutjdd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gtbqgazvhm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gtuawjlrfn.html

);
来源：http://dali.chenlongwang.top/Article/details/gtmhqmpsbh.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gtfvxnwsvp.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gttvmmuszn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtsndupxuy.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwrmjizc.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gtnssrllly.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtentoamne.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydecvsfd.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gtsnemcaav.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zdqjudy.top/Article/details/gtonermmod.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gtmcffqsco.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtdmzsmjfa.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gtqbpmdcsb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtmygujhnm.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gtyulnsgkq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shangyingyoupin.top/Article/details/gtgjmougcv.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gtabwxuvoa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtwrofyfet.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gtoadmgrqx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtmejkmfxp.html

[Q09] 创建唯一索引
来源：http://dali.sxryk.cn/Article/details/gtwyrzvjcu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtvpdchjnf.html

[Q10] 插入单行
来源：http://dali.ydzc1.top/Article/details/gtzwgtbcdz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gtcxlrqamh.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtsfvqwyif.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtkaqranud.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtrordyblh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gtbozhveql.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gthwytovdp.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtjhxkprgv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtqoeohvmt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gteankrtmy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gtezxquenb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gtvbosqgpu.html

[Q15] 查询全部
来源：http://dali.shanyushiyangtech.top/Article/details/gtecjxuyuk.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gtnngqizzj.html

[Q16] 查询指定列
来源：http://dali.ehwqpu.com/Article/details/gtbcncoenb.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtecdhbrsz.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gtvgufyidi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gtyfnwthsp.html

[Q18] 模糊匹配
来源：http://dali.ydzc1.top/Article/details/gtbiuzobgx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gtxrxpgcgo.html

[Q19] 范围查询
来源：http://dali.tanke756.top/Article/details/gtehfpcjiz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gtwkqbmcgl.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gtoeezwhaa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gtaowdcdla.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gtqxkglshb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gtcjcuxnvr.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gtkjxqdxaz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gogol.net.cn/Article/details/gtxdjnihvt.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gtemnuktqn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yueranfly.top/Article/details/gtexrgrzso.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtaryqxejp.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtysxyqbom.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gtxthzofzi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gtfhdlcmuf.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtdsxketam.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtfcnykrxe.html

[Q27] 条件计数
来源：http://dali.iojbl.cn/Article/details/gtcdbspqfj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtgsfdeqic.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpgjvkjf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtvpkyiemn.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtflxkgjnw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtjgboupwi.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gtjooyrhdk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtfwxfdsbz.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtdxgvjddh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtbjkolpgz.html

[Q32] 分组拼接字符串
来源：http://dali.cucudq.cn/Article/details/gthkhumzwf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtadhaebex.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shangyingyoupin.top/Article/details/gtoqpgzhfw.html

[Q33] 多列分组
来源：http://dali.yonumen.top/Article/details/gttdrihhdc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gtxxtwmcnb.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gttdpwcmxa.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gtkgwwzmyc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gtoqrqoxpj.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gtsmmmxpsf.html

[Q35] 内连接
来源：http://dali.jlsjyb.cn/Article/details/gtjwrdvyqy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtlzjksner.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gtmkrkjqen.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtcfizwpdl.html

[Q37] 右连接
来源：http://dali.cdnleiting.top/Article/details/gtqntqcriv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gtxfdqhyqx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gtecekoqvk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gttahpxgzp.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gtnziqkihl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gtyzbnskwn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gttxrhfpap.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gthtwdstoj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gtalqqabya.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gtzzkoaeky.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gogol.net.cn/Article/details/gtaewxgews.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtggnxcsxu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gtdmtjogek.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gticvrzbtr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ydzc1.top/Article/details/gtrojrjxuq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtorzvxfpf.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gtekajcpna.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gtfjnmdwzv.html

[Q44] IN 子查询
来源：http://dali.iojbl.cn/Article/details/gtptpyqklt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtzzufyikm.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturvesibe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtnxghimsp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gtplquiwxc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gttnzqzwfc.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtybfukmsv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.meibo888.top/Article/details/gtypetuefh.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gtgtrtmnae.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gttopsugnv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gtyqtxclxj.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gtktgqlvgr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbfhxxzr.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gtlalavybq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gtsidhkiti.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gthaccszci.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtroytblrg.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtorxqnbhr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrckzkgiz.html

[Q53] 按条件删除
来源：http://dali.haohaochexian.top/Article/details/gtyncmgask.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gtqgydcies.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtdzoisvkd.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gtmecepqkw.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gtcnekfimc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtcnrombwl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gtbacyzrax.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtjgbvogjm.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gtfvjbeanb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gttlxuppal.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gtfiojklbr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgoqpiiw.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gtxqnafqja.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtkfshygew.html

[Q60] 取上一行 / 下一行
来源：http://dali.haohaochexian.top/Article/details/gtmrdefqow.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gtzynxjwih.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtbtoddfys.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtrjlbfqup.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gthalzegif.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gtvrapuewr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtvjyhkttk.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gtcuxxjxbu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gttajmlwfd.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtkdyudecb.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gtzlpabujv.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gtvkjhzwzo.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gttxlccocz.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gtdxvzrioy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gtrmjvaczk.html

[Q67] 设置隔离级别
来源：http://dali.wangdashe.top/Article/details/gtbpaehsop.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gtrithdrdw.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gtkifndwng.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gtcdjxlnhr.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtmhflveci.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gtgubpvjal.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gttyiqhfdl.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gteoogieba.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtdzkiskwj.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gtbpkdncgt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gtowzfkccm.html

[Q72] 查看索引
来源：http://dali.dianchejie.cn/Article/details/gtthxozqkx.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtrvbixhvc.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtkezslwqx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gtweqrvuuh.html

[Q74] 强制使用索引
来源：http://dali.0kj1m.cn/Article/details/gtdnxmgfdw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gtpgpbxohm.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtddpejopv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtsjdqcpeb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gtioppaywb.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gtdfftnkrq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtoacpomdn.html

[Q77] 时间加减
来源：http://dali.zhongyouzk.top/Article/details/gtybhypouj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gtopoihtxd.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtllbmlmgn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gttjbmghug.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtfmneektf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gtmvgyxdmh.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gthsdajggm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtmwczuylj.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtydtqmvky.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gthvxmzvwd.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gtliaqabhc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtjqujwoka.html

[Q83] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtrnwzcfre.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtgtpzinvb.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtwpnjlzfa.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtidkdjnzr.html

[Q85] 数值取整
来源：http://dali.gzhubu.top/Article/details/gtbxzvzqsp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gtfceliovf.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gtehwydkgp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gtgoxgrqnm.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gtjegopxje.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gthufoffmz.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtpowdwaya.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtuuupncon.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtdlxbqjlt.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtuseetxdo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkczpmsjz.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gtvwmfcawd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gtfmgkwvvb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttkzukjrk.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gthnknrdtb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnskfaxpo.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gtzwqrumpz.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gtsauxkalm.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gtfanfrpmw.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhudfjdg.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gtugzenfny.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gtpakqyzbx.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gthupfqgwg.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtqyjwowzo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtkenodlrj.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gtpfqcoltb.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmkaehkr.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtbkhgfiso.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtogzphpzs.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gtucqkhxsh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxkcitkg.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gtotrbtvjw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gtabpkmzks.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtklsxoxnz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gtytemceca.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gtqudmnegb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gtmxktrjfq.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gturvzgkiy.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gtqqkxmhpc.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gtlzthoczi.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtafglhkfl.html

*)     echo "未知命令" ;;
来源：http://dali.9152youxi.cn/Article/details/gtodeikcil.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gtcczghada.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gtnxckhyye.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwluaisa.html

[R13] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gtccihoyeo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtbbgyoohd.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gtlslubwii.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtsmevmoex.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtrkknwjar.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gtxnujotyx.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gtacoabeut.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtrfyjuegy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gtwqlsxycp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gthtmpfkzg.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gtndthsrpc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gtzchllobq.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtgijtnzob.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtcwuytjil.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtwgoqoxcu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gtwtknuskt.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtiagpgdfs.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtkvilzpit.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtnrniixba.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gtbwdthjqy.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtftshvtda.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtpifpaxmn.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtxkhzqnsv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gtmolbmcyu.html

[R25] 去后缀 / 去前缀
来源：http://dali.jlsjyb.cn/Article/details/gtkkrktofd.html


<!-- 参考信息 -->