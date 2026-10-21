代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gthykgffpe.html

TS:   if (x == null) {}
来源：http://dali.yangfankeji.com/Article/details/gtdribnvaf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtcmkpceqk.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gtkpmiwext.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gtvkasybqk.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gtshmjigir.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gtrlkyvgni.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gtmtsbyijo.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gtkxbgymgr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtqxxngctv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtgqcgqtdw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gtsoangytd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xziqi.cn/Article/details/gtjtqfkezy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gtqsmogllx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodblzvjv.html

[P08] 处理浮点精度问题
来源：http://dali.ehwqpu.com/Article/details/gtyrnzeoxo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ivvv.top/Article/details/gthglacjcz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gtarpvzhae.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnxiangtu.top/Article/details/gtflusizzs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtxkzzzruv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtusldiohj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gtlkeptuej.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gtkrkxczmy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gtfzkqwabg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtnwpweegf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gtxgndfkpm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdmgjerbe.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtzzvxefjp.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gtnldclynd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvkbzwbv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.havefunace.top/Article/details/gthhinsjrp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gtvkzpxjuj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.havefunace.top/Article/details/gtqsicwscv.html

);
来源：http://dali.yuxming.cn/Article/details/gttjatiath.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtvksyzqfi.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gtlkakbgoh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwotcsmie.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtiezeghrl.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttzjeytx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gtyhxddkyl.html

);
来源：http://dali.sufxvd.cn/Article/details/gtkiecbech.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gtnjyqolgf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gtznkujfuj.html

[Q04] 修改列类型
来源：http://dali.nanxinkj.top/Article/details/gtwnpnekku.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gtbnikgxvy.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gtrtsymfie.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gtfodqibrx.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gtnjlcmqov.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gtipyzfoit.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gtnxthejku.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gtevyjhjou.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gtdbkwemfh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtrmgkzoky.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gtnooyaexi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gthgdexbni.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gtyuqhpqzn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtgfmqjzqq.html

[Q11] 一次插入多行
来源：http://dali.ivvv.top/Article/details/gtlreefvre.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtkhzfexhr.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaszuxarz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gtckgszosn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtxyyelivl.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gtabpbmnzg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gtkwtpjskj.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gtmrmmgeae.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtxzzcinsk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gtgkmljfyv.html

[Q15] 查询全部
来源：http://dali.zhiwuduotai.top/Article/details/gtrzwhqqzo.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtnkeajslv.html

[Q16] 查询指定列
来源：http://dali.c1oappe.top/Article/details/gtiwioveqh.html

SELECT id, name FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtvbvqgthi.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gtbjcfxiab.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gtrnnpgcbf.html

[Q18] 模糊匹配
来源：http://dali.yuanzhike.top/Article/details/gtfmeaulky.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtkbubfqgz.html

[Q19] 范围查询
来源：http://dali.andypj.xyz/Article/details/gtavxysgwp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtrdorveim.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gtsgicxuou.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnmkjtho.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gtdnqbmwfh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gtanyiyyza.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtlbehqwgc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hammf.cn/Article/details/gtdapygbdi.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gttocjvsni.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gtovrugagp.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtjrjzwlpd.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gtfshjkhhz.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtotihctbn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gteyqvomvl.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gtyhttwwmp.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtwqgjkrmv.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtyxgpnpuq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtnrpoeohh.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcsyzqyh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtgvgjbcwe.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtlnvznobu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtvfyyssmu.html

[Q30] 分组统计
来源：http://dali.ivvv.top/Article/details/gtfyyjmsqx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtgbzctozj.html

[Q31] 分组后过滤
来源：http://dali.yonumen.top/Article/details/gtbvwquyha.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gtwukegssf.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtbluwysnk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gthhwwjsdv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhongyouzk.top/Article/details/gtlxjcdemd.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtrtbzrysj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gtekquigxm.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gtkbobxprf.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gttquctggy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomrtujyu.html

) t WHERE rn = 1;
来源：http://dali.cucudq.cn/Article/details/gtqolzjcxc.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gtygvutcmy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtbhbeoysd.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihwrpzcj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtsxpvyquy.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhlndekv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yonumen.top/Article/details/gtegmscqhm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gtxjzllbwu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtbjsroiaa.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gtprolsqdt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gtdfcqeqzf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gtpdaocuzm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpowjabse.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtufoidici.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtcfhbyyaw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hywenlv.cn/Article/details/gtkaomsabb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gtgvqtphcw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gtxzkhlrnd.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gtdgzhgjyz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gtgvxuwdcm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazrwvjff.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtgcjmubvb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhluggos.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gtdqyqeccm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gttafalyzp.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gtbxaiwlsf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtrqucrtjt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtchjucxdw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtqdqivvoy.html

[Q47] 与平均值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdkblfxw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sufxvd.cn/Article/details/gtdcfghsib.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gtvdibnaqw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtjapntrzu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gtxxmtbszn.html

[Q49] 更新单行
来源：http://dali.daxiang520.top/Article/details/gtoplxolqd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtlnyotlrl.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gtujjjlnhu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsirktzgz.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gtapufbplo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtoildvgiv.html

[Q52] 删除指定行
来源：http://dali.yj20258.top/Article/details/gttelcsbsj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtpgpdmcla.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gthiscmhuz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtruvlkjem.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gtjedbqwwu.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gtpgipievh.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gtahacgfzy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.redwolf501.top/Article/details/gttsjdhdna.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zdqjudy.top/Article/details/gtutfueqvo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtdosdmzdz.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gttegoufst.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.havefunace.top/Article/details/gtvaeokany.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gtkwtxgbax.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtzgllulpc.html

[Q59] 分组内累计
来源：http://dali.dianchejie.cn/Article/details/gtjnjuoveb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtmsnlmugd.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gtaupyfbfl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gtjflaziyf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtmqhjzbeb.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftipyipm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtspzjszfi.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gtimstswyq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtxnvufixv.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtuaamxdrl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gtuyqmbdyr.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gtgkiykjks.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gtqkjpbifu.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gtzaionphu.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gtqtyhfbjl.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtagykaulk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtcskmvsma.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gtwttxmdml.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gtzjzngjkj.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gtkxutiecr.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gtrtdwhjpe.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gtcdddgsqm.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gtgqcumdli.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gtdeahkczc.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gtxzqeobkn.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtlisybmlk.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gtntploroh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gtynsqxuue.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtmaszqpvs.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gttuzdkzhh.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gtwfvazqny.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhixingplan.top/Article/details/gtytkedney.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gtxfiayjqc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gtczrtmnyb.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtiuxakvyy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gthnhdwcps.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gtjxlmbnah.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gthefckglf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fzhhl.top/Article/details/gtimxwbkei.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gtvpdzfcue.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxuanxn.top/Article/details/gtvkxhutbx.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtfykeefhi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gtvlxfwnnd.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtxawgwuhv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtzgkhufnm.html

[Q80] 字符串截取
来源：http://dali.jiagoushi.top/Article/details/gtsgdqrugc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthrwsdkcp.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtfnwwhzkh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyandkst.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gtvpuwbwpl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gttreanmdr.html

[Q83] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtgupmdbef.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtqxmsnaoa.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtopznqqsc.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtrqnolwqf.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtzehuwxqy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtnhzzqrjf.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gtwpxxdzai.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlznakss.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtscdncdmu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gtanxtkydm.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtxifbwoel.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gtihxiprbp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgezhmyon.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gtgyuaycsg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gzhubu.top/Article/details/gtksuvpdls.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gtqwxbpilx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtjayylzjc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtczmwrqfe.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gtinkpqnqb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdxvbtpwe.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gtpucfiuos.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gtnvejtzpq.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gtbhzcjqtk.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtyovupihc.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gthrfitpgz.html

[R03] 只读变量
来源：http://dali.yuxming.cn/Article/details/gthsndomty.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gtktorttpr.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gtzmfdhfbu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fzhhl.top/Article/details/gtyxwxgvpw.html

[R05] 参数默认值
来源：http://dali.hfpthk.cn/Article/details/gtttoabpuo.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gtzoaeyxvk.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gtewqmqgxr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtwzbijcjx.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzyyetur.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gtpittmrcl.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtipwkkabd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtgjewiyak.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gtoptunrgw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtvswjrkwt.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtdnifcrel.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtzdfnikyo.html

[R11] case 多分支
来源：http://dali.bjfxy.top/Article/details/gthtgxpodi.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gtexhfbjas.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtidlednjt.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gtsthdgwjh.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gtygnuumjp.html

esac
来源：http://dali.sufxvd.cn/Article/details/gtadarkdav.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gtpkegzkhq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtpplmtamg.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtkuxomzmd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtvaprlxwm.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gteuaukisk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtfzvnorrv.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtkrshevct.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cdnleiting.top/Article/details/gtlymyzonh.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gtwtvywofw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtqaspyvwh.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gtdwcdubpn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gtcblwzbew.html

[R18] 遍历数组
来源：http://dali.xylfe.cn/Article/details/gtepzqrbtx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtzsiculxs.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtnkiwuyee.html

echo "${#arr[@]}"
来源：http://dali.jqgfzy.top/Article/details/gtaqwazcwr.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtrhgltsko.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtcturmvzh.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrvrfyjs.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtlfbjpdmz.html

[R22] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtaaavzfyh.html

echo "${s:0:5}"
来源：http://dali.yj20258888.top/Article/details/gthczfosam.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtvetmxezc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gtdvydplqm.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtphjvuwby.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gtbqykemzf.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gtdmmphqxn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gtugcpamjz.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtfpolofad.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gtgmngqejv.html

[R27] 算术展开
来源：http://dali.hongshengwenyu.top/Article/details/gtbmwdscev.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtwpmfqotc.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gtsfqkujpj.html

echo "scale=2; 10/3" | bc
来源：http://dali.andypj.xyz/Article/details/gtovvhfsar.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtlhinikwz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.haohaochexian.top/Article/details/gtbdagjnte.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtpglrtqay.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gtvbxddlvm.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gttbwilwpn.html


<!-- 参考信息 -->