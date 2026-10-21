代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigufen.top/Article/details/gtstyurskh.html

TS:   if (x == null) {}
来源：http://dali.haohaochexian.top/Article/details/gtnqyomxrg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtceaoasnj.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gtjivnfmwt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ivvv.top/Article/details/gtuyxcmido.html

C#:   if (x is null) {}
来源：http://dali.yueranfly.top/Article/details/gtouucsswn.html

[P07] 防抖与节流
来源：http://dali.nanxinkj.top/Article/details/gtifzodhpr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangkeji.top/Article/details/gtposoaszl.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gthkufrpdv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtxaifjxyq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtkeymaonp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdyjyoixs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinghuilouyu.cn/Article/details/gtskxwoaxl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtafuudnjj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gtktbtsmhr.html

[P08] 处理浮点精度问题
来源：http://dali.nwbrower.top/Article/details/gtvibqqtqw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gtyednwgri.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gtohirqwry.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gtanycmpmm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gtlqqdhfmn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtntpspxic.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gthygtohnz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gtdzwtdgfa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hammf.cn/Article/details/gtmwoemsen.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlysnaapb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gtfrvqcsha.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtayzyyoie.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gtmvdjtvwd.html

CREATE TABLE users (
来源：http://dali.shanyushiyangtech.top/Article/details/gtegyrgiop.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtdpfhgiyj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtfvmvfecf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gtstuclsdm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gtmhyopexf.html

);
来源：http://dali.yanxiufei.cn/Article/details/gthlwjxffa.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gtasqgvkty.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gteabolhwm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtacpkeapm.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtrpsehamf.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gtwqbmbfaf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gtkmzisvak.html

);
来源：http://dali.shzxlz.cn/Article/details/gtezmqemyb.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gtnqigobgu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gtmukjxgmy.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gtcwppxyma.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gtwowsiqla.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtcvawvdfo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cqqwz.cn/Article/details/gtiquxzxpv.html

[Q06] 删除列
来源：http://dali.zhiwuduotai.top/Article/details/gtluajxkti.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gticytjglw.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlovlquvy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.c1oappe.top/Article/details/gtroozbywz.html

[Q08] 创建普通索引
来源：http://dali.tian-w.cn/Article/details/gtsnrpmqqx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gttpwxtigw.html

[Q09] 创建唯一索引
来源：http://dali.ehwqpu.com/Article/details/gtpfjzgfxy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtcsqzkbal.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gtbtiypgup.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtqpvklqgr.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gtuckdaist.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shuidangran.top/Article/details/gtyxnyshfn.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gtryxzjmbd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fzhhl.top/Article/details/gtowujhbsb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gtycicwjby.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbhojrtv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gtvwmaawrp.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gtuiwaiwyp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenjidiqi.icu/Article/details/gtuomvtpdx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gtdkhfdwtc.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gtswxxrdcm.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gthydchkci.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gtgknztdgk.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gtiqizndit.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gtqnrcwmze.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gttizkanly.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtpsyraaru.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gtilokktih.html

[Q19] 范围查询
来源：http://dali.jqgufenzy.top/Article/details/gtwbdchrcg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gtqzevqasw.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gttylpxkjj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gturxhypwf.html

[Q21] 空值判断
来源：http://dali.snrcjt.cn/Article/details/gtglzwlnob.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gtcvonnorw.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gtslinttkz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gtlnbalowm.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gtkcmrwjqt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveqrttpm.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtvllsrhby.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtbfjqncuw.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gtmcaqzsaa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gttldrcmvi.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gtqbbvsbio.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtcnllwqqs.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gtapcetzvk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtjtdbyetd.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gtqokjxloe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtetvjndch.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gttdohjbxs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhnchshp.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gtyrxjxpyy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtcjrefmdu.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gtfldhcixq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqxzmqcd.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gthbmyavse.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtocdyuker.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhongyouzk.top/Article/details/gtueaiigdx.html

[Q33] 多列分组
来源：http://dali.hysaishi.cn/Article/details/gttwhelvfa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gthwdwnmpm.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gtkunujhrb.html

SELECT * FROM (
来源：http://dali.gaohongyu789.top/Article/details/gtmnylrrfx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj202588.top/Article/details/gttomwpjlq.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gtohhooayh.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gtwfurvuvw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gtccctisni.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gtcdgfngxc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtfsvnabga.html

[Q37] 右连接
来源：http://dali.jlsjyb.cn/Article/details/gtdlnknnoq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxinkj.top/Article/details/gtflberbrc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigufen.top/Article/details/gthgybstrx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gtyhycudri.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gtazwarfac.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gtpytfhsbf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gtckhvlxsv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvgndepq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtqyolkzio.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gtofuihuum.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gtwzvammhw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gtsncldfff.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gthyathzcj.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtwqldkovb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtmbtxsvhn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gtrysugtjg.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtwdzkwpxt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gtifpxcbgj.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gtjhivntjo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtkxapubeb.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtwydvcvjx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtkvgmwaqj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ybcxt.top/Article/details/gtmfbpnsrz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtionxnyuq.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gtvtrnuqxp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gtdafqoidh.html

[Q48] CTE 公用表表达式
来源：http://dali.yangfankeji.com/Article/details/gtnjqxestg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtcrmimsja.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gtmawcmscg.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gtdowzyffi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtgnukimbi.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gtvbvuqixv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtflskiopc.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtrrmxstox.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtabostiwl.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gtkwerrrmy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtzthieuyg.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gtntbdwfwa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtnvobrzja.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gtohossnoh.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gthzquwfho.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeigaipv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtvkaubrkx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gtomnddevw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtlulbvvbq.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gtbodupbao.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtskyqdhal.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtpqrmzjvc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtolkgywfq.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gttxzpixks.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtskfpsxyx.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtrotduzxj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gtniidkhme.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gttfnlyssi.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gtwxjmcjdi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtqecvcghk.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtjsdfsznd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtwlnoaxel.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtimozbytd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gtukvdfohr.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxqvtfjp.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gtgaioeqcf.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtenybyzbe.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gtxmatkikv.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gtesypyljv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gtmxrafvvg.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gtikxlepcr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gtojoikicl.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gtiugnbexq.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqhcdtpt.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtvhxudfbi.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gttqfghfqf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gtxzalbvyk.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gtiqfdrhec.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gtlfdhhfwe.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gtiqzrqrxp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyffthlb.html

[Q72] 查看索引
来源：http://dali.birdmap.top/Article/details/gttssbccni.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gthjyhbxth.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtgvktdhao.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gttuajmnjz.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gtfkakcpwg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtixanrbxv.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoarufxae.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtuajaifzs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gtzeeclvse.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gtuesllvyo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhengqikj.top/Article/details/gtfocciacm.html

[Q77] 时间加减
来源：http://dali.wangdashe.top/Article/details/gtwwopwdbe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gtylndmtjl.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gtzwqgzyrk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtzdszjvrc.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqucwgzo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gtizugkryv.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqveufejt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhgftchc.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtupjtikqz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gttoqzrlhf.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gtksghhfxe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtavdcqgdt.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtqdkabidw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqvkphuj.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gtgnsunxno.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtmklwsarj.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gtedxoyxla.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtkjzlemof.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gtquytmjyk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gtzuoxrffp.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtotvcchno.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gtoaoovnct.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gtkivnefrs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpcvevko.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtfilsxlxq.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtdywwrvcw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtehtyadgp.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtjulpdsvq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.vqdsnc.cn/Article/details/gtkfdefwhi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdwiuyawe.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtuazdjcyd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gteurqmhhu.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtreweqilg.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gtrbywfpjl.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtdumellxc.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtmsjykqcj.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gtjgbscibw.html

[R03] 只读变量
来源：http://dali.xylfe.cn/Article/details/gtpamokntv.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gtiyyznipl.html

[R04] 位置参数
来源：http://dali.yanxiufei.cn/Article/details/gtvqkusesa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gzhubu.top/Article/details/gtgjdssbdz.html

[R05] 参数默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtbwmkckej.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gtoqmsravc.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtedefsevy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtgrjlfwbu.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtlusxvant.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gtifihpjnr.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gtjovjdzin.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtfvjakaom.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtwpwkovkv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gtadqktxoy.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtwsyfqegu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gtcbbmchdr.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gtmxeytwru.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gtmawyjvgt.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtxamzypxx.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gtizfydgkl.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtruuzvzop.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtjlnkxiod.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gtopsmbsbj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gtjjyyidow.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtbrlplbvj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtflecvakl.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtrsacorno.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtjxsfdqop.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtsphmqyab.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gtklsurdmo.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gtnkztoffm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtlqlauqyg.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gtzpsfvwkp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtyroaxxgk.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gtzgunwuij.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gtseepcpxe.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gttqraepuc.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtddfxxphc.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gttdogzctu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtyvcfsnwq.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gttbqmopmg.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhxbspso.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtnrdpiklo.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gteooapwoj.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwmbarsb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.quarkkingdee.top/Article/details/gtkconeyiz.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtprgwzpsl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtmyoydurl.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gtsmsbmpaq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtwkqbxfbs.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gtybdafmfd.html

now=$(date +%F); echo "$now"
来源：http://dali.yanxiufei.cn/Article/details/gtwgvdklch.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtstllsero.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gtvcjohrpb.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtwycyjcyv.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtceccoekz.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtmmqyafxx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gtkngwbsoo.html

[R30] 函数返回状态码
来源：http://dali.zhongyouzk.top/Article/details/gtkjdjsmnl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gtysxczpme.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gtyoyaosnv.html


<!-- 参考信息 -->