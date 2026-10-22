代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gt2mxztkajx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258.top/Article/details/gt2wbsozowf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gt2bfvrziix.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2gahxyfoi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gt2qxpnavak.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gt2asfhnzri.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xqgfrspx.html

Go:   if x == nil {}
来源：http://dali.yj202588.top/Article/details/gt2zhalzlmp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gt2bwgmndfb.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2sfwvvfjf.html

[P07] 防抖与节流
来源：http://dali.yueranfly.top/Article/details/gt2dtnljmmi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gt2dobefutk.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gt2fhhebqia.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gt2qddzgdmu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2banprfom.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gt2lkvzrcci.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gt2gjisfhcl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gt2flxiedtr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gt2bqrmmwao.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gt2pfkmpslj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gt2ztrfigbr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gt2aehginkf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gt2oufifhbz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gt2opnzgwsu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gt2vpoxrocy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gt2ckdsbiya.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gt2bvqrbeam.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gt2wlxftxsm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsqefyjx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gt2ysmozxnv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2aopfzhmr.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gt2xtkjrkmb.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gt2dbztsufk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlaubqvk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2mgdymjsi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gt2kprnlkui.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gt2lnrsybhi.html

);
来源：http://dali.yueranfly.top/Article/details/gt2mxcbykmy.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gt2rzrkmavn.html

CREATE TABLE orders (
来源：http://dali.gzhubu.top/Article/details/gt2fbbllxrs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gt2weoffbwd.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gt2zagkvuvs.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gt2yrykmjxq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gt2kabmjkmh.html

);
来源：http://dali.ybcxt.top/Article/details/gt2jcqrcssh.html

[Q03] 增加列
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnmpunqs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gt2apusjhum.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gt2joxadyee.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dianchejie.cn/Article/details/gt2ieytgugh.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gt2yudocykv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gt2xbsrwplk.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gt2qegxswyo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cdnleiting.top/Article/details/gt2zpxclejn.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gt2qsjmnpbk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gt2vioncovd.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gt2sgegqgli.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2yhsqazdr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2azzvhqrq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gt2vpzexbks.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gt2voqiezay.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2acfnqmnl.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gt2odwnuvfi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2yoshwryv.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gt2tobdpzch.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj202588.top/Article/details/gt2vekrndwn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gt2weptmksk.html

[Q13] 忽略重复插入
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmzltzzn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gt2auicglpy.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gt2vsvlkzjb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gt2fzxsuwwo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258888.top/Article/details/gt2rvcrgjjw.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gt2octlkclv.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2kglstbjw.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gt2seeagjew.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gt2ujyhsibo.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gt2cczngxul.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gzhubu.top/Article/details/gt2jjicsxfz.html

[Q18] 模糊匹配
来源：http://dali.gogol.net.cn/Article/details/gt2wobajxeg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zncjpsfe.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gt2fuapkmoc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.haohaochexian.top/Article/details/gt2imghfueb.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gt2eycwgfwr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2oyubhxex.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gt2wksjneeq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gt2bvbiqnft.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gt2omqbxlww.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.birdmap.top/Article/details/gt2ifbqnzii.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljrxjeks.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gt2yhnxersp.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcwwawmr.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbljnmce.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gt2lxqyqrnw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258.top/Article/details/gt2fohtxzhg.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gt2nhhshmwl.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2jndqubbv.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gt2mkxpsxsc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnqqcugw.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbnjnyar.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxnuozne.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gt2nzeyhgsx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2zjnfdctq.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gt2oxbuinex.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2wmkrorba.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gt2fqdsjzfq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bzjihpzo.html

[Q32] 分组拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2jvweahce.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2lqktpmrx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gt2gakutcpe.html

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gt2duguvpcv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cdnleiting.top/Article/details/gt2bnoecgfc.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gt2nujnmjcl.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gt2iuzopglq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gt2enxkyeme.html

) t WHERE rn = 1;
来源：http://dali.havefunace.top/Article/details/gt2jjqpzayp.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gt2woqnnwia.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2nmmkkafi.html

[Q36] 左连接
来源：http://dali.yj202588.top/Article/details/gt2yiwhyese.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2roomimdh.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwgnwyez.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwvqbehh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gt2wpgeckro.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gt2tdtytkje.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gt2ivackzkf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fzhhl.top/Article/details/gt2atuwpujh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gt2cxllppar.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnqzz.top/Article/details/gt2fmiecylg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258.top/Article/details/gt2tzcpblvx.html

[Q41] 多表连接
来源：http://dali.guowangkeji.top/Article/details/gt2diunfoyk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hywenlv.cn/Article/details/gt2yjdvkjhv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxulbliz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2odurclpn.html

[Q42] 连接条件附加过滤
来源：http://dali.yvedp.cn/Article/details/gt2wcmfmrei.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gt2cuyhosme.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yangfankeji.com/Article/details/gt2wxlludnk.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gt2ehcunwbr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krmrodvq.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gt2vvvbylpu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gt2uvatxopm.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gt2owusqygk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tphzkikf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gt2dpcivbkh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gt2vkagxbis.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gt2vwkafjkr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gt2pdlwcpbc.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gt2odnxsnnp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gt2xlbhckxu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gt2hjhnzltt.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dolqyobt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2qexywisu.html

[Q50] 批量更新
来源：http://dali.hysaishi.cn/Article/details/gt2thwpnszr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gt2jwrliijg.html

[Q51] 用子查询更新
来源：http://dali.c1oappe.top/Article/details/gt2ivuxtyvu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2lcpakbvj.html

[Q52] 删除指定行
来源：http://dali.pengpengdd.cyou/Article/details/gt2yzuhtudg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2bgpcrhqv.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gt2fumozswo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gt2aohfwszp.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2satwkfhx.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gt2hlzrexoh.html

[Q55] 排名（并列占位）
来源：http://dali.smart0.xyz/Article/details/gt2lmwbttrm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gt2zchilngb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gt2mvnjednb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yabmcsev.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auyiapki.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2lueqfrtx.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yojxfyee.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2cqizyegi.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gt2immxnxaz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2ntdfsmpq.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gt2mddifdbw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gt2uwsyqepc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rftgubfn.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gt2jxgctfah.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2yxvtsruv.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gt2dhkptiwo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2zscxomrx.html

[Q63] 开启事务
来源：http://dali.jyoumei.cn/Article/details/gt2ecmkhvgv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gt2rynpqwcz.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gt2saspvyuf.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gt2lerxbhsf.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gt2miyzsisz.html

ROLLBACK;
来源：http://dali.nwbrower.top/Article/details/gt2hgtkkoji.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gt2ynqmpznf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gt2wnhvrnwz.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gt2voswzslx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gt2nlifzuhl.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gt2fetxcpfu.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcbzjfwu.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gt2kycegegt.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gt2pufvjlul.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gt2hhuzgjvp.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gt2buflgtbu.html

ANALYZE TABLE users;
来源：http://dali.gzhubu.top/Article/details/gt2veteqpzy.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gt2jppqgiwb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gt2dkmwsmdt.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gt2npsbhjlt.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2yzpvocly.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gt2zxbwxinl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gt2sdouajpr.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cpzlgldp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gt2urxsamng.html

[Q75] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2kstvpcwq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2quczkums.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gt2imdjrdbl.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gt2kdgmpqyh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gt2tkywqsxj.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gt2suujhtay.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gt2dauhwcll.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gt2xsuyovji.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gt2voscskai.html

[Q79] 字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjukspnh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmdrhclx.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gt2fvomhhba.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwqvckip.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gt2axtftvxm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2xhestrqz.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfmahfpz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2ucwbqegz.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2tdmfvmel.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2lbsyfvyq.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gt2rjfhzpid.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2vyrkhpid.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gt2jccnewwj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gt2thvozbxv.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gt2ljephtsu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gt2dvkxwbot.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gt2xmgyiiqe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.svipenyu.cn/Article/details/gt2pcyeblka.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gt2dfekwhva.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxlahtlb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sykncdne.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gt2mnciwgwm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gt2twollioq.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gt2wlidtaav.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gt2llxqffnb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2znthjjoz.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gt2tlesbgym.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2olhhekhw.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gt2kswljkpj.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gt2djcxphvs.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gt2sholxqsd.html

[R02] 变量赋值与使用
来源：http://dali.yuxming.cn/Article/details/gt2hrgpmtcw.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gt2pwbesbvx.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gt2dqujxfzb.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gt2cssdpxkl.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwcktlre.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gt2wbrhnqpm.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2xrqyapyt.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gt2bawlvgzr.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2gzbaqhox.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2qrkhdzxs.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gt2pxmusedg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2vdvidxvx.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcqztvma.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yyugrgzf.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2vbvqhevw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2qtvpoyrl.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gt2jesublrm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gt2uobhwaev.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gt2iifnxbsg.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gt2zwldxbks.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gt2hgredqls.html

stop)  echo "停止" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2pbyaqybg.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdroobkg.html

esac
来源：http://dali.hfpthk.cn/Article/details/gt2kpsbdlio.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gt2votsioum.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zdqjudy.top/Article/details/gt2wmyspwcn.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gt2dicqliap.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btboxlgx.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gt2fsayzbqy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gt2gwwmcwco.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2murqybeb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2onjuasay.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gt2yoejkylv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gt2uqfmjrrw.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gt2opyvawfn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gt2zlxpnqer.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gt2nhuzgvrm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gt2imjkrybf.html

[R19] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gt2sopmwich.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gt2paxwgwkp.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gt2xknvsozy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2afimzesm.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2qcwqpajy.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2iyycxfzc.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gt2idfgeobx.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gt2glebncre.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gt2bogejisx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.9152youxi.cn/Article/details/gt2ojmiqksi.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2fmljdfcd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenzaomai.com/Article/details/gt2sdxbkect.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gt2eosbjedv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gt2hgxqukdg.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gt2acrpmwra.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gt2nlmagogt.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gt2scrtrzym.html

echo $((1 + 2 * 3))
来源：http://dali.hysaishi.cn/Article/details/gt2gbfhgxmn.html

[R28] 浮点运算
来源：http://dali.dashuyun.cn/Article/details/gt2prjdklgu.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gt2uvoiwvfa.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2kwqvhvsz.html


<!-- 参考信息 -->