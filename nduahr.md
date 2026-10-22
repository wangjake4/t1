代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gtdzfeasex.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtktsdcxyt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtbjyxefdl.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtjgbbfkrd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cashguo.top/Article/details/gtpmoowqia.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gtdkvcoook.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gtwcouhorf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gtmyvdluie.html

PHP:  // 手写时间戳比较
来源：http://dali.0kj1m.cn/Article/details/gtkpbxwxzu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtrbdmcbtm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtqhikdtjp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gtjybpoban.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gtiznrafay.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ppjwa.cn/Article/details/gtawvdxayy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tian-w.cn/Article/details/gtzwmfwxjm.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gtjeivsjst.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtyxmmpgnf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gtkrppxgro.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gtdujryrzn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtktnxjxwl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nwbrower.top/Article/details/gttlldfvok.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gtcxseupxs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwkrgxio.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gtowivomqg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gteocgthve.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gtcrmekqwe.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsydrzxgz.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gtgdygpvdo.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtrwxuxrjd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtqlotfcqs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtvbfyxuwa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gtfhhsnmtc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.9152youxi.cn/Article/details/gtlrzknjvc.html

);
来源：http://dali.0kj1m.cn/Article/details/gtisyeoiup.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gtqwscripe.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gtrsqecyuh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtmoxcivbr.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtcqvisfdz.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gtktojtdxh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gtfifupdth.html

);
来源：http://dali.yj20258888.top/Article/details/gtyfppuruv.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gtjlxvicoo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gtozperupw.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gtswxjvvct.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxinkj.top/Article/details/gtbhhlhpnb.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gtaqvqnlia.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtoudqpjql.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gtwrcpgmjf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gtqljkgywt.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtkdluelmn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gtsufnjguo.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gtsbczzkwk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtvzvkjkky.html

[Q09] 创建唯一索引
来源：http://dali.guowangkeji.top/Article/details/gttwsfsuzv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtvcjwihbj.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtenrrieds.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtzpztsseq.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gtxotswjsp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtaauovfxc.html

[Q12] 插入后取自增 ID
来源：http://dali.zdqjudy.top/Article/details/gtqlovaerd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fzhhl.top/Article/details/gtpduccjqd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sxryk.cn/Article/details/gtvqxdqjva.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gtqerstzgv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtthdzvrpz.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gtsfdvwqck.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtwxaqmpcx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtswycyiqs.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gtjedzjfum.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gttdqrkrkt.html

[Q16] 查询指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtxoivrqae.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gtrnvtankq.html

[Q17] 条件查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrppwymln.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gtedcgwdmz.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gtsmgnloyk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.feifeiyinyue.top/Article/details/gtmjgqmotj.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gtkgrvrodu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gtwxfeumgk.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gthbqltsxa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gthbhretiv.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gtqlmfvjai.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gtfxjoulcd.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gtkpbktsbp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.smart0.xyz/Article/details/gtdvkksjyg.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gtobllwbgt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtabuedkqs.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gthziyulou.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtmzveziov.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gthvdblfrh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtyzzzknyx.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gtcwxllpyi.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtajespefk.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gtfdzllhiq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtxolkycwl.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gtvlapknol.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygiruawg.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gtjkudinul.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtczeogmso.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtiwgghtmb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtkudnjjir.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gtqkqehzne.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtvjhuozmr.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtmwjrdnhe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtdyrxfweu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gthuvigivj.html

[Q33] 多列分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhvzxebg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gtjswnnlfk.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gtbcfffrgo.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gtyeiacjad.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gtpuvpsnut.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtidbdoaea.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gtfqkkltsl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtielcgyrb.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtseiiosoe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtnouizfwb.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaemgjill.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtbszgitaw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiujmmsmp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gtsrssajoy.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdezoifkv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsblxjclp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gtefvgbztv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gtbnshvggo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gtzeftdrhv.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtpaxgpgox.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tian-w.cn/Article/details/gtiqwzgvov.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gtwmhoejdz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gthewgsagm.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtnjqkjamx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gtidvbkqha.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gtzexlapnf.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gttxqufpft.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gtombxofjr.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gtqkllibpt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gtwjyshjqo.html

[Q45] EXISTS 判断存在
来源：http://dali.ehwqpu.com/Article/details/gtcnnvicgl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtckvpdpod.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gtsxosgckj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmyigwsp.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gtsoddaymx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shzxlz.cn/Article/details/gtigtkffjn.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtpsgysrog.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gtdqmnwgah.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gtmmbnypaj.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gtwjhdmwfn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtogqjbnrq.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gtezbxkbnf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yongpay.top/Article/details/gtineucdbx.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gtbakqbdtv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gtceufjiti.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gtnheouarb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtilydieec.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gtbntgvyjt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtnyipxbgg.html

[Q54] 清空表
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrjzjrji.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gtwqtdawmt.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gtdtyxavkb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtkxodyupz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gtglbzwttc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtgxhimptd.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gtwhopomcr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtbklofqjc.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtukfvtljg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtalbgqgjv.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gtwlyljdyv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtvjjpbikh.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gtwzhmyknn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gtylnkaslm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gtjtiimlcd.html

[Q61] 移动平均
来源：http://dali.cdnleiting.top/Article/details/gtulecuobp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtytywckgq.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gtktxpbihv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtgygvszpe.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gtlbwfjzic.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gtayjsogyf.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmumlozer.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtfcdamtkz.html

[Q65] 回滚事务
来源：http://dali.cdnleiting.top/Article/details/gtmzuywamw.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gtvuecbmjr.html

[Q66] 行锁查询
来源：http://dali.shangyingyoupin.top/Article/details/gtdtkcmobm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhyqaujd.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gtnpemqtfa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gtmkvihrrt.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtizwehche.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gtzydrmhzw.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gtswpqquez.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gtnknmnbgg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtzhqizyau.html

[Q70] 更新统计信息
来源：http://dali.fengsongda.top/Article/details/gtkshgcsff.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gtzakynnfc.html

[Q71] 查看建表语句
来源：http://dali.tanke756.top/Article/details/gtjoemijpa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gthlsqgcyh.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtrlpaamrq.html

SHOW INDEX FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtfgifojnp.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gtxuiemrly.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gtumxhiofm.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtgbtinxrz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtpicguzia.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gteoraossx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gtkrjzrawd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtgktwjibi.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtafkwlrxu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gttnicdldn.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gthgbusxgz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gtdlgsvudq.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gtedxfazjc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtqgnqdnhc.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtoxnibjep.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtnhtekatc.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gtpyyizndx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwflfwwjl.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtzgpphyai.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtxsimgoka.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtssnjzgrp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtrjswuldn.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtiytmkdza.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtyhxsalgi.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gtqbknevop.html

SELECT TRIM(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtmfrpynpw.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtwqidvlod.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gtgtlducml.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefdndhfr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gtornbrzoc.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gtcdzanvgd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtuddptxvf.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtizarcfxu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtmaqzfjvt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtynuvnuyi.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtpuarkucs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gthmgeeqzt.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gtjdmcgztf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gtptkaqnxb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfgqfevvp.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtzefkpidq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlyxeautg.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gtlqymelga.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gtymyxszca.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gtiltzthig.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gtdctjossk.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gtaomznbgo.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnsoceee.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gtzyiiwqur.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoswwayc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gtybooaygv.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtvdtgbotc.html

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gteprnymby.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gtbcasfsvz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtwfbgfwni.html

[R07] if 判断文件
来源：http://dali.shzxlz.cn/Article/details/gtsfwtkchm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtwujqxnyg.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtblpmjcnc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtkclqdvaf.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitjdtskf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtxwnjhwzb.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gtjopbseqg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtkywyishl.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtgyeegmpc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gtysthxtlw.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gthzyrvbny.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtkuiazgmd.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtjmedefcn.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gtysxcolwe.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtekokilny.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtswyzdfiu.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtpboxofvy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtiebievzr.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtgkrpocsu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtwmzykabe.html

[R15] while 逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtkhylvntp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gtxotodqxk.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrylraauu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtcrgahumf.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gtbqytxzno.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gtdbudthcy.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtatfwitsw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gtsparfxcy.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gthvceuuoy.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtzmwuuqes.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gtniczevbi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gttlvtrgmh.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gtdzocjora.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtapeeiybu.html

[R22] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtwqahcogm.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gtrequzsin.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtbastglmc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gtpblmxgir.html

[R24] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtpotfxkdz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gtvfktuhoz.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtiitffrxf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gtkphfdrby.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtnknyhnoq.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gtjcsypaan.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gtmrzzgkst.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gtlumnilzv.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gtlfnubgop.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gtcdbzvqhn.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtpxhzpkak.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xinyue.icu/Article/details/gtgszznoil.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gtjtnidlai.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtxbdprcqt.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gthyyafygn.html


<!-- 参考信息 -->