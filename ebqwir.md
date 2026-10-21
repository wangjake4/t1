代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtdpifbplv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gtupnuctnx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtzmzvorms.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtszidxuxv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangshuangyany.cn/Article/details/gtngxalhkb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cashguo.top/Article/details/gtbnfeonym.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gtygjqhytb.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtgkdghclp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gthrisvtwq.html

TS:   if (x == null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtedqwymei.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtqntwebjf.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtvodczggi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtpmbweuuc.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfiduhzcf.html

[P07] 防抖与节流
来源：http://dali.nanxuanxn.top/Article/details/gtvslituhi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtbyqvzvhp.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gtirdqrxxy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtdlvdswjp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtmgbqneii.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtncgokeez.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gtbapbeary.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtenwaphge.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gtzuqzccsa.html

[P08] 处理浮点精度问题
来源：http://dali.xuanzx.com/Article/details/gtlesacqub.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtszmusyxd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gtktitphtx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.svipenyu.cn/Article/details/gtermvgahb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtygmtqkew.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtjntqdnfb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gtfgplrlug.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtvyuvsfbk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cucudq.cn/Article/details/gtywwdmurx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpholjdkq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gtgltsravd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrzjnsilp.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gtvtqyjqpb.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gtjzzibblg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtcletmtie.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtscgwgjvo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gtokdetbgj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhengqikj.top/Article/details/gtwjmkufso.html

);
来源：http://dali.zycfv.cn/Article/details/gtrqomjkfq.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gthxqnrotm.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtrpnitxbn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtsdkaistl.html

user_id INT NOT NULL,
来源：http://dali.birdmap.top/Article/details/gthkikehwm.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gtkudamydb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnqzz.top/Article/details/gtsgmifuhs.html

);
来源：http://dali.nwbrower.top/Article/details/gtsefwifdy.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gtuzrojylx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtmthmhfxz.html

[Q04] 修改列类型
来源：http://dali.nanxinkj.top/Article/details/gtyokwpywa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gtojmqvabk.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gtwddigkyl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtragzktdg.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gtuasuihjc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhongyouzk.top/Article/details/gtawxqznwj.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gturdnkigf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtrpkegggo.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtqbyxiyai.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtlomaidir.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gtyrnqkrvl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gthkwovzjk.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gtfllvlopd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtqnzczsoy.html

[Q11] 一次插入多行
来源：http://dali.dianchejie.cn/Article/details/gtbvrsyywv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gttkbwdhio.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gtouwcxqts.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dianchejie.cn/Article/details/gtozjxilbe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gthsobtlri.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gtsweoweul.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gtssikrwvh.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gtjgtxodsq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gtzchjwziy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zdqjudy.top/Article/details/gtfyinwpsd.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtdqqlgnpo.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtfhzdhwdg.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gtboircaia.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtxmttpqys.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gtspwmvuwr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gtkzqgfkel.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtzkzsdtvk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gtejwcccls.html

[Q19] 范围查询
来源：http://dali.jqgfzy.top/Article/details/gtglrfdnzm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gtrtodnsll.html

[Q20] IN 列表
来源：http://dali.zhoulong.xyz/Article/details/gthmqfkoke.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gtqokxfsmb.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtixiuyhlv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gtzwrpqvdu.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtczldedjq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gtcsdodcdb.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gthxfspcfy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shzxlz.cn/Article/details/gtdkptkive.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gtykkhfbsq.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtjgvclcbu.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gthcjeirsb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtmgdmbtwq.html

[Q26] 计数
来源：http://dali.hysaishi.cn/Article/details/gtgetmpcfb.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtwcbdysgz.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqiljsky.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtekapwtai.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgxdakeh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtjnfiekmd.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtemywvmpc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtngmqbzwa.html

[Q30] 分组统计
来源：http://dali.jlsjyb.cn/Article/details/gttnopovlr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gthrwdbbzm.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gthzvfxcki.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtgaetqhfd.html

[Q32] 分组拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtgrlnerzv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtppvouuig.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gtxpfvdxqx.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gtcpjksykr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gtnjsfktmb.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtfzbxrjay.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gtfcbimesf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gtbpxlkivz.html

) t WHERE rn = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtiuxbkwtw.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gtmbohgdyr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtdrmulnlw.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gtxsesqloy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtyxbzmhcf.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gturbakmgf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gttjhaemnj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gtlevragyu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aibaodan.cn/Article/details/gttbqamgcw.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gtzmwwlezu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fzhhl.top/Article/details/gtqpemxucf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtfboeackq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gttkljlont.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtunsdqwoy.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gtduoomwfi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.iojbl.cn/Article/details/gtgpldhfdw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gtaxcxiqql.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gtaywchzww.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtgbpsqqnx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gtorwwhlfa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.0kj1m.cn/Article/details/gtpidqslmh.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gtbteptkcm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gtctyoyxah.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtfmbnlghl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gtmhiqausd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtscghdigx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtxovbryzt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gtuhzprobr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gtfankfdkv.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gtjfplnemm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gtgunnhsqf.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gthvybsjye.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtulquyido.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gtylxuzfnb.html

[Q49] 更新单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxfqmejc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtniohzwdx.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtzloipuri.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtuflsecwx.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gtolhkpyku.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojuydtgo.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkjxfacw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtrqteqmyh.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gttcxkbvqm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtutallldd.html

[Q54] 清空表
来源：http://dali.hfpthk.cn/Article/details/gtddeqecoi.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtovadxwys.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gttiwrqztx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyumyecx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgoavcsy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtfctyrffo.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtnrnuucrd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gtogopfovh.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gtqkbyxbvh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtfnoqkgbm.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gtlcknnhfa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbabknag.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gtrtqvzhqx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gtgqmfummz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtejknzciq.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gtsyenrlpc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtojtijbml.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtseaeyzgn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtyvmkvvui.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtthphffvq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtpxujmfct.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gtaqpuywof.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdbsnmtt.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gtarjlowua.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gtdgnxrzeu.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtwunykvnb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtbppbfkyc.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gtbvmebmlb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhixingplan.top/Article/details/gtsnqdmawv.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gtppkibjwv.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtyigswekk.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gtvkdfhlaa.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gtdnnndors.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gtdhfrancx.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gtuuywfrcn.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gtlbwxhzwg.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gtvbeahaho.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtxzrmigkh.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtrmdgcrpf.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkplolwh.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gtrzlifmfs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtwwhrebkm.html

[Q74] 强制使用索引
来源：http://dali.chenzaomai.com/Article/details/gtuwwwoapi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gtkbcrtpyz.html

[Q75] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtrejghapa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtafgluphw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.snrcjt.cn/Article/details/gtxftgibke.html

[Q76] 按天统计
来源：http://dali.cdnleiting.top/Article/details/gtaittxdqz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.redwolf501.top/Article/details/gtiysarnav.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gttgxzuuqn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtjxrstytf.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gthnbollpr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gtjogddnsp.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gtkanjklsq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gtdhjsvwba.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gtgpqqhlzn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtlgpkzafl.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtckkasamu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtxhcoblyl.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtvddemfsv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gttnmouhlx.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtovxhocvz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtrmzyvtji.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gthxifdssh.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gthxsnljpd.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhrczguk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gthzcicmfb.html

[Q86] 读取 JSON 字段
来源：http://dali.dashuyun.cn/Article/details/gtnccrwpie.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gtibatlkvo.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gtyzketmjq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gtmfykkgyt.html

[Q88] 行转列（条件聚合）
来源：http://dali.gotoacloud.top/Article/details/gtpugxbpew.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gtbnfidafn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtviyxetbw.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gthstjlbxz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.c1oappe.top/Article/details/gtxefitbqw.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gtxdwuopmz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gttcrvatvk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdwlaouqn.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gtzuktpzdn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbygteqpb.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gtlirexbcv.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gteedjfiaq.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtyletbjbn.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtjnoasczw.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gtrmpcyoxo.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gtwqoiqoey.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gtlddiobtu.html

[R04] 位置参数
来源：http://dali.yuanzhike.top/Article/details/gtrguhvyob.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guowangkeji.top/Article/details/gtxhawqpwb.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gtkqhygacf.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gtjwjpjggy.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnnklzgc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtbiewsbpo.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtqcouziff.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtpchjaxxy.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtfkpqsvhm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtjwkgdhkj.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtkalfsfgk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gtgkfgxtci.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gtwftojwiz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gtypxfcdwj.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtnxjrjkon.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gtbladezod.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gtpnbyaoct.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtoghzvzbj.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtkhiopots.html

esac
来源：http://dali.yj202588.top/Article/details/gtxspbkzvi.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtfndwwgwe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtvwscdvoj.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtzejmgdcy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gthrboeejd.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gtitgueyuz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtbkhpgllp.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtevhcbrjy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cdnleiting.top/Article/details/gthuttigtw.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtuyeevdet.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtwvdfrzou.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gteperxvtq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gtlfpjryti.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gtazwmekkl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuxming.cn/Article/details/gtapihkpiq.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtbujxfjkf.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtfhyikpto.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtkljtqgsj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gtltvtvhgs.html

[R21] 字符串长度
来源：http://dali.chenzaomai.com/Article/details/gttslbwkri.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyrlwdyi.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtuotestrb.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gtnrnfbmzk.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtzpajxymf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nwbrower.top/Article/details/gtybaicass.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtclembapf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtvdnrybub.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gtvlkzkpgd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gtcalvtysp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtpzyzpmps.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtenrbbzha.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gtrtsuutdy.html


<!-- 参考信息 -->