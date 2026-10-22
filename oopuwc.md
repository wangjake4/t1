代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gthwnofjsn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gtitjsgkgi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gtvztznkjm.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtkakfrewi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gtstnsgseb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cashguo.top/Article/details/gtbxbsjckx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpdvscfn.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtzmkjepfu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtwfbemtaq.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gttytsobvv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtioasfotz.html

Go:   if x == nil {}
来源：http://dali.vqdsnc.cn/Article/details/gtpvfxefcu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtmeyckdgu.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjjzfljm.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gtmlpbrfll.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gtuvrvnnqg.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtixfdnqdx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtarwzyybh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtesyawqcg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gtadumxnnt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gtltdxvaig.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gtzndswewr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.haohaochexian.top/Article/details/gtcpzozgob.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gtuoerklxe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtkhcqhiie.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gtjcvidamu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gtkxhppttj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gthpakbphc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cucudq.cn/Article/details/gtfzyzcuvv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gtggxykbpp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gtvgrfwoax.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gtycanawas.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtggewbuul.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.smart0.xyz/Article/details/gtawqjrmlb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtehopryhm.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gthapkhavh.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gtsggxgtxz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtcyepbjgd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtklvolzpg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gttikjgouo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gtzdjqpnij.html

);
来源：http://dali.dianchejie.cn/Article/details/gtjxnyttxv.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gtoobgjrtr.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtfnwyceoy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtzdgtmvzk.html

user_id INT NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtiwozpuaq.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gtssszegax.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258888.top/Article/details/gtwlxhjqce.html

);
来源：http://dali.sweek.top/Article/details/gtsvovsqga.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gtywselgqx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gtyuayhjuc.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtmkvzderq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gtffaxbmck.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtymoqtqzx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gtpfktngdf.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtonyrhwpj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yongpay.top/Article/details/gtjicqzsux.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gtmtovdlmc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gtgefooqqz.html

[Q08] 创建普通索引
来源：http://dali.mhx1999.top/Article/details/gtplxdcfky.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtmgxrbmdy.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gtnzbxucdk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gthcendvma.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gtraezojeu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtxgdcggvr.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gtdrflnsyo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtguwtuoin.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtwgyqpbvm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcdbwpmz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtqygzjsbm.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtzsycchof.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gtulopuxyn.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gtaqbjpfkm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gthdfbksbh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gtjvowtfve.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gthwetjrtx.html

SELECT * FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtoyfjaiqx.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gtoygvvzzf.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gtkitzhvjw.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtghharwql.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gtysisygwf.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gtibggpxod.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.redwolf501.top/Article/details/gtnnaoytvk.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gtblbvzcji.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtdpplaqbo.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gtkshtwnif.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jianghu66.top/Article/details/gtmjvdiqlr.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gtndqoksmf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gtqlkoilgv.html

[Q22] 排序
来源：http://dali.sysykeji.top/Article/details/gtbkwyclzr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.havefunace.top/Article/details/gttduwugha.html

[Q23] 分页
来源：http://dali.gogol.net.cn/Article/details/gtgyowvvnl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gtuwtifjmw.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtdzdyvitv.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gtmopppwzn.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gtkywqenry.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtygpiiqdl.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gtkttzqjtj.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtickvtyqh.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gtayglqwhi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtoajlyumy.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gtrfetmzpt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtiozskmhd.html

[Q29] 最大最小值
来源：http://dali.yuanzhike.top/Article/details/gtdfwmqcly.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtiakwvgyx.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gtevewcrng.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtrhaboclo.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gtveglcpdo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtufondgij.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtykvnqxjd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtciqnevtp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gtzauwoftn.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gtqkpqabaj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gtddmxwwwl.html

[Q34] 每组取第一条
来源：http://dali.ehwqpu.com/Article/details/gtldvbduzt.html

SELECT * FROM (
来源：http://dali.svipenyu.cn/Article/details/gtsjsecxrc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gttgtcfzib.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gtdcsvyziq.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gteqvaqvaj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtifzbzmaw.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gtgtlbapas.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtxzjyuzuy.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gtaofbieng.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gttjmamish.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.9152youxi.cn/Article/details/gthxhgiyqf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtlmbshhvn.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gtthqkxctl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gtmffigejs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xinyue.icu/Article/details/gtgvkhejzh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gtfiudsnhu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gthjlutbjl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtwkyuyzmb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gtlvsmxvji.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcybkvnwb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gtwpdgiomc.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtqoelpkki.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gtollexrch.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gteoqnctpi.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gtlhsmapdv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.mhx1999.top/Article/details/gtaslaxycn.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gtnuflqklz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtztkfumff.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlzfqetz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtnliispep.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gtvqwdbtpl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtjiekxiwx.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckgpxqex.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtpenlukdh.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtlhzlbrav.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gtqhpofdoo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gtlepaszkr.html

[Q49] 更新单行
来源：http://dali.xziqi.cn/Article/details/gtxtotcsxg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtumtdnvpo.html

[Q50] 批量更新
来源：http://dali.hnxiangtu.top/Article/details/gtqcmioaut.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtsnegkzfk.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztgllyos.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gtawcasxxh.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtzxkujigo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtodrxnazh.html

[Q53] 按条件删除
来源：http://dali.aizwys.cn/Article/details/gtnzroenbe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gttjxxesqo.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gtovczavjf.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtosmechmz.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gtyfdohxtw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtsqyvworg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gtdrpotodm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtaumjoazy.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gttktxremg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtuhigcqfm.html

[Q58] 累计求和
来源：http://dali.ydzc1.top/Article/details/gtrahimura.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gthrbpnlvo.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gttuxmilyk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtlwzniuge.html

[Q60] 取上一行 / 下一行
来源：http://dali.yongpay.top/Article/details/gtqqbvdtds.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gtvdgoufmx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gthgeuofrb.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gtnaysslhq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtbvcqgwpw.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gtkrlndcla.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtgvymbyfk.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gtvgiwvcmm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gtizobcauz.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gtepzmjofr.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gtsmdqwvwx.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gtutbevpqe.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtuffkpviw.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gtvcwsrywa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jyoumei.cn/Article/details/gtvwalevcr.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaleeaktv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtekujwdwb.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfrtuysy.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gtjjjiprrw.html

ROLLBACK TO sp1;
来源：http://dali.gotoacloud.top/Article/details/gtgdsnwlrs.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gthkgnnqzo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gtzvoklank.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsuosxyk.html

ANALYZE TABLE users;
来源：http://dali.gzhubu.top/Article/details/gtngnmzxbm.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gtxyujhamg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gtvcdaexwv.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtculxkgbz.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtztqvqjro.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gthtkaqprm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gtinmeniwz.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gthkimgpxp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gtxsnoybqb.html

[Q75] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtkacvnytg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtstwkdarg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtdluudiib.html

[Q76] 按天统计
来源：http://dali.sysykeji.top/Article/details/gtmrboamcu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gtqcihkbwl.html

[Q77] 时间加减
来源：http://dali.guannengcc.top/Article/details/gtvqingrjv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gtnktffjjl.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtkkrqlebp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gtpwqvmfkb.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtuzdxiyzs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gtfvbjihpz.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gtkrusgeix.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gtiudwfqzq.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtgalvddgs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtbbkkzcfk.html

[Q82] 字符长度与字节长度
来源：http://dali.pycfn.com/Article/details/gtdhkajpnv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtdntsorlf.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwemdvwdb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtpqckbpbu.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtjhuinepz.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtozzgmsmr.html

[Q85] 数值取整
来源：http://dali.aizwys.cn/Article/details/gtgdrxkvnc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gtjyoowxih.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gtvkgdnswe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gtlkqnyeyv.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gtgxqsvrkg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gtnssgdzps.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqvlvced.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gtghyumkfp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtknucsdqo.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtgjoecgiz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtthwkymlp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtkejsvnkg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gtnsdnhkfw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtskochilp.html

R. Bash 专题
来源：http://dali.jinqigfzy.top/Article/details/gtfdfphkyy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtownmmcjn.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzbeakwa.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gtlufqbxkc.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyocgqjnz.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gtklqyebfg.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtoydcxxgw.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gtathmkwvg.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtgvwaopab.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gtfwspxuac.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gtqzjmnvqo.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gtkjklsxww.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gtujpwkpnb.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gteiynkspp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtaobajsqs.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gtafpakpqb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gtirqozgsw.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gtccvkeghz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gthghnzomg.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtullndguw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aizwys.cn/Article/details/gtinqpctzc.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtcelpssca.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gtuygwzixs.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtbwmeqgmo.html

case "$1" in
来源：http://dali.sxryk.cn/Article/details/gtnzvcoxin.html

start) echo "启动" ;;
来源：http://dali.dashuyun.cn/Article/details/gtuooorwwu.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gtykelqkoq.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gtzyvtsnvx.html

esac
来源：http://dali.svipenyu.cn/Article/details/gtgavoyeas.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gtrqytoktx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gtuvudonxe.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtenrwepnk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtssiufjtb.html

[R14] C 风格 for
来源：http://dali.daria6918.cn/Article/details/gtectkpjgd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtgzwybqqk.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtmjsxftij.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtyutsflrr.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gtdbnvyxer.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtateofzdy.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtezfdxmpc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gtilgsssqk.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gtrwpluiqu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.kuanghao11.cn/Article/details/gtfipeomak.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtmxjhoxdj.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsjzzeep.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gtpgbpvmyk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gtypofeotf.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtplczavgh.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gtlhinulez.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtaiwtbaxr.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gtzljezpbp.html

[R23] 字符串替换
来源：http://dali.cashguo.top/Article/details/gtyrpwyslf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gtehenrwsf.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtljmspnii.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtodyfwpje.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gtldgqyuuv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gtutukzsvv.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gttwqtlnyv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gtyulcpmhs.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gtpvuovrpm.html


<!-- 参考信息 -->