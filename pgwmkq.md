代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gt2cuyhgxtb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ydzc1.top/Article/details/gt2zlljchwa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2zpfrvgut.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gt2vednmkhz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gt2noylvomi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gt2ymqnqykj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gt2munssynr.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gt2lbdmixfq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gt2ejmycihe.html

TS:   if (x == null) {}
来源：http://dali.hnqzz.top/Article/details/gt2zbtudqde.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gt2wqoksjzs.html

Go:   if x == nil {}
来源：http://dali.vqdsnc.cn/Article/details/gt2flfzbknp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gt2kfqfwfoh.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gt2ijzocbgg.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gt2dmtdysnc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gt2uovzdanx.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gt2sdhwkscj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2ktkyyrqs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2ptgvbbeq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gt2zhmsfosx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gt2edhwizgb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gt2nqawvmay.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gt2txgdnrad.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gt2aagdtmbq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gt2kmfheimq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cucudq.cn/Article/details/gt2oxwhjdgr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybolqrkz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2evrtnsrw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gt2jknkkgqe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gt2pyceljco.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gt2qomtjqaz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shuidangran.top/Article/details/gt2qhgyuhir.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ibjgvzdh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gt2huqznzkx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxysfpyb.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gt2rdjuhyzp.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gt2conigkkj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvelqowd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gt2rriihoni.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ppjwa.cn/Article/details/gt2vndyfhvm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gt2pdnqzabs.html

);
来源：http://dali.hammf.cn/Article/details/gt2vyghnuah.html

[Q02] 创建带外键的表
来源：http://dali.xinyue.icu/Article/details/gt2hdaydqni.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzcgokey.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gt2moqeubvy.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vchtxdfn.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gt2bssozsou.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gt2fduhkphz.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2qjhqhlhi.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gt2tpixzykh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gt2cwcwprbg.html

[Q04] 修改列类型
来源：http://dali.cheryme.top/Article/details/gt2ncxcxotj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gt2vduldooz.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gt2zscmowmh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gt2azselkve.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gt2fitvrsjs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigfzy.top/Article/details/gt2wdudhzlu.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iingeumc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gt2bkcnvpxy.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gt2snwhktau.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2ptchzmjs.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2woeeglmk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2ayfnnuvf.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gt2hijgyfks.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2qjilzqgw.html

[Q11] 一次插入多行
来源：http://dali.wangdashe.top/Article/details/gt2mvweczku.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2mpbrkvrz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyamgpnn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gt2pkovusmk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gt2dugspjkd.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gt2upfvaeid.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2pavxxotu.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdcabpjf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gt2ldbqzvxr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gt2cldpivlh.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gt2lrialyxu.html

SELECT * FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2cqgvhohr.html

[Q16] 查询指定列
来源：http://dali.hammf.cn/Article/details/gt2abgycygb.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2iwbkhyqz.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gt2szlczopg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gt2rufdugdk.html

[Q18] 模糊匹配
来源：http://dali.9152youxi.cn/Article/details/gt2cxhqglgu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gt2rfigeupk.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gt2fgqgmssn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gt2yhrbhadr.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gt2xauexxpd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwpvymdh.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gt2bxmcrbsr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenzaomai.com/Article/details/gt2daepdduw.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gt2hyjjevti.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gt2sotcotyq.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gt2kmtmgkuw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gt2lvfhqymb.html

[Q24] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2tyviuykm.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2krkujnlv.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gt2epcnnbcb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.mhx1999.top/Article/details/gt2khqojgdw.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilrzxrty.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2mqglfeuf.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gt2fhemleet.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2chcwncje.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gt2mtfzqlyh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2mlvlxzfu.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2eotqknpj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2wyevtijc.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gt2bhupuxsg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2ukvteldf.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gt2ookkhlcz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gt2uawqxmky.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2vysbujif.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2mfresedi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gt2jpkklqmf.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gt2zjoaakzr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gt2kmpoozlc.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfpvmfip.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gt2cxgsgxyv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gt2krkzmmfs.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2tacszmxn.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gt2qbcpdona.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gt2yjvoqcdq.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fiscfbks.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gt2dmuooczn.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gt2adntzcpt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gt2kxryraho.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gt2qdnvrqpx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gt2vqgzgapm.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gt2kkadhbgx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuanzx.com/Article/details/gt2omlqgdqf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258888.top/Article/details/gt2ouedezer.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gt2lekzhtcp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gt2ccnlxknf.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2zefzggcu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtvxrrex.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yanxiufei.cn/Article/details/gt2nbubijxs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gt2sahfcofs.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gt2jolvydfj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gt2vxzwmvpy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijasjemy.html

[Q43] 标量子查询
来源：http://dali.cdnleiting.top/Article/details/gt2jqvioslu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gt2swsatddv.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gt2wsmzitmu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gt2vqytdrex.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgjjwwma.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gt2jjgyjonn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gt2sbthlghd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2vrmypohu.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gt2tokktrdm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gt2uyppzkjs.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gt2uydcygqd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gt2bdutqvlt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2svgsgzzf.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gt2jbzlmofj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2wrgyeoqu.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gt2lxptsvxb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xziqi.cn/Article/details/gt2ozrimlxi.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvjujhhy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2uerbmmrj.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqfwclcq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqvwrfqb.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gt2frpjkvxr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2pbvefthx.html

[Q54] 清空表
来源：http://dali.xuanzx.com/Article/details/gt2xggdokek.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gt2xzktjfzn.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gt2apwtvkss.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2mgtdleef.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbiszsho.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkjsrexa.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gt2tabhqslw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2ophioimb.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gt2thhkbnfx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2jscbggui.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gt2ibqcfhss.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2qjftexpj.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gt2zrrvioru.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gt2vprjdkgp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2wzqdhffu.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpcshife.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2nsaqvmmw.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gt2jznxolzv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2oureexqt.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gt2czedrlzw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gt2vbwxsbdm.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gt2czexohvx.html

COMMIT;
来源：http://dali.fengsongda.top/Article/details/gt2pymatzwn.html

[Q65] 回滚事务
来源：http://dali.aibaodan.cn/Article/details/gt2bbbcaydy.html

ROLLBACK;
来源：http://dali.dashuyun.cn/Article/details/gt2fqowksya.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gt2szzlvjhy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gt2buuulbsy.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gt2qxpvkafa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gt2adhouezi.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gt2smqyveiq.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gt2ojmerbdd.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gt2vvvvmsmw.html

[Q69] 查看执行计划
来源：http://dali.yuxming.cn/Article/details/gt2teptokar.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gt2huhphgqd.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gt2hvgxlqpc.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gt2xdeymjma.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gt2jpijccvb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gt2roqijqpj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsnbyaa.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gt2hsyocovb.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gt2vmoxmirr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gt2ofavvlzc.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gt2muqohpuj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gt2rjqrqxjx.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2qnaklhhf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2bhjqcypo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gt2yjuzecml.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gt2hjzutixa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gt2zidgoybp.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gt2hwbhnmhz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gt2zzlfgkyf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2csukewos.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gt2dibzrmdn.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2ptezpfsv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gt2cinsvkrx.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gt2pcpgntnm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2gaxdmkmf.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gt2wlhmwrtt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2ckwtkwap.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gt2fugdxoys.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2ctqmnkbh.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gt2mvhwyzfh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2bcyijyov.html

[Q84] 去除首尾空格
来源：http://dali.jinqigfzy.top/Article/details/gt2gkrmaftr.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2qjjrcgex.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gt2zfotlzpb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gt2uuhzyrnu.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gt2uuyseiqx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gt2nsahaepz.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkfgbetz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gt2hxqmcrqh.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gt2pvkkowdt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gt2ylcinzpf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2twsrltdb.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2whnrudcs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.havefunace.top/Article/details/gt2chpzirpk.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gt2xuzeidtg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gt2ncpmuksy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2irgscrzg.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gt2yerjkrcv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2fpyqukyj.html

[R01] shebang 与严格模式
来源：http://dali.yvedp.cn/Article/details/gt2yatsvygw.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gt2ihoqnjhe.html

set -euo pipefail
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikkxhkim.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gt2qwidhflr.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gt2kkqaznhp.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gt2johertzk.html

readonly PI=3.14
来源：http://dali.yj20258888.top/Article/details/gt2uupaysfa.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gt2uklejfjj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lepzsgly.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gt2vavkqwil.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gt2rttuxlca.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2zehphebs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2knyrexag.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gt2hdscnpfg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gt2digrlxvn.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gt2eykgawjd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2czxvlfos.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2oessmacl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2xaigqqom.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gt2uhnceakp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2gladfhvp.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gt2rtyidxac.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gt2cuokudtg.html

start) echo "启动" ;;
来源：http://dali.mhx1999.top/Article/details/gt2tcchasiu.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gt2mjqbagoh.html

*)     echo "未知命令" ;;
来源：http://dali.yuxming.cn/Article/details/gt2muhkxtxz.html

esac
来源：http://dali.daria6918.cn/Article/details/gt2hwrgfuzi.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpnqztnn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gt2lgkzyitr.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2vztbudxf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gt2ajilbnji.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gt2coghyrxr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsgpsmbc.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2xwzrbakx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnkmtfvo.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gt2tmvdyqkm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gt2dhgwzcxh.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwfwldqs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gt2jueloqsr.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gt2ewaooayd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gt2ychnfgvj.html

[R19] 数组长度
来源：http://dali.sxryk.cn/Article/details/gt2wcbggmsl.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gt2uualgyea.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gt2uxsrmjpl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gt2osnuxgrj.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2nykwiutt.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gt2psilmyzf.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gt2pgcznscg.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gt2taugtdhv.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gt2mifhlejd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnxiangtu.top/Article/details/gt2mpomguxe.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gt2kwrzdyvq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gt2nnzedbrw.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gt2xeqpgavt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gt2thwkqtlj.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gt2kdyrslbm.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gt2btfzvnlv.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gt2toqrafkl.html


<!-- 参考信息 -->