代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gteidnathf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtgoabfiid.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtozkcvgpb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gtausnfrtr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gtisuiwbqk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtpjdyatta.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sysykeji.top/Article/details/gtulqrmgoz.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gtcnelqvsg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yvedp.cn/Article/details/gtdzbxksfj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtmbtzirlb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtbkqjhwzt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtwammriyy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sxryk.cn/Article/details/gtlgccwahp.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtsdffvpdp.html

Ruby: x.length;  x.size
来源：http://dali.cdnleiting.top/Article/details/gtpwuczggq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gtbetgfbky.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinghuilouyu.cn/Article/details/gtwutnavai.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gtwdjmrpgm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jiagoushi.top/Article/details/gtmilybovl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gtovzclouw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gtqtjazldj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gtzukzggyo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gthnggatzg.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gtucqmvmlx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gtynlbibtj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gtsjssasaj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gtjwdlreor.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gteptnmfww.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gtrdzfbdzo.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtjkerpihn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuptehodc.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gtslemzutj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gtoawicreo.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gtelrrjyiy.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtxsnnuqfk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtfqqabzqi.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdzmgytx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtqmywlpmi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwbiblbw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvmmekbyz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtkldycytz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gtpqvpcnvx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gtdcxoyrdy.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gtgqihywzo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gtluvsnern.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gtztqgewye.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gttxpsishm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtextxyikx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj202588.top/Article/details/gtbhltrdry.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gtonywyouo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gttqooqrae.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gtiphdkgql.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgekhzlpq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtolhluqxy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtaaphmdze.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gtagxmeogx.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gtndtkxbcb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtbmfyoktq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtdgtbtlyf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ppjwa.cn/Article/details/gtsscgwzeo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtbtbisajt.html

);
来源：http://dali.yvedp.cn/Article/details/gtnnhdumjn.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gtmdckdije.html

CREATE TABLE orders (
来源：http://dali.mhx1999.top/Article/details/gtxsrvalmj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzldjeeo.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gtcobmuxsg.html

amount DECIMAL(10, 2),
来源：http://dali.shuidangran.top/Article/details/gtnhhjkera.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258888.top/Article/details/gtervcuzst.html

);
来源：http://dali.gzhubu.top/Article/details/gtgngxgeww.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtsrobmjkm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gtimfqdarp.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveolrqzv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtcdnypdxc.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gtilegnhba.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258.top/Article/details/gtpeampmav.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gtvzieehnv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigfzy.top/Article/details/gtdroxrzxk.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gtbtcggkxa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtqepumehb.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gtarziohor.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtxpsrkiku.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gtnvrlfhes.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gtgmrcdjdh.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gtyxomeaea.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtutlfzqxy.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtmwodkzdf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gtpwmisyjh.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtrktzfsku.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daria6918.cn/Article/details/gtmmdbgznb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yangfankeji.com/Article/details/gtoyhaugfn.html

[Q13] 忽略重复插入
来源：http://dali.yongpay.top/Article/details/gtlvmiriru.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtesadnnxh.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gtujigfeaw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gtlbtanrpp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shuidangran.top/Article/details/gtuatgeipy.html

[Q15] 查询全部
来源：http://dali.shangyingyoupin.top/Article/details/gtvtbtwocq.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gtkeopdzfv.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gtcdkywqln.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gtdljhwsrc.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gteibnvrlp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gtrvchasxn.html

[Q18] 模糊匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugddamfz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gtqhdpqswt.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gtqkwfryrn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sxryk.cn/Article/details/gtylhlokqn.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtvsifayfw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gttsyherha.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gtjcquwkac.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gtikfhhrjw.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtpbqersdv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gttxakemeh.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtzailkgvv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.haohaochexian.top/Article/details/gtzstjgpco.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gtneeiuvsb.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gtkmacghvb.html

[Q25] 只取前 N 条
来源：http://dali.shuidangran.top/Article/details/gtzmscqloa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gtaglcukbo.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gtjpgqcuuf.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtsvifzkkx.html

[Q27] 条件计数
来源：http://dali.svipenyu.cn/Article/details/gtxgpgxwad.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtgispyhva.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtpvqkucvw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtawpuafrc.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtwsdheyqs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtuygmzdaa.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gtzptftfvs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtipcsqtjl.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gtmuwcyadt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtrlsekysn.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtnwygbzhp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtsyejlsjv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gtzqnvqlgx.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gtfccpovvi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtlynyvggt.html

[Q34] 每组取第一条
来源：http://dali.jianghu66.top/Article/details/gtayrsvnrp.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gtrgdssvko.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gttmnrxldm.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gtbqnuluis.html

[Q35] 内连接
来源：http://dali.jlsjyb.cn/Article/details/gtxlefekrc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gtslkmmjem.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gtqtmcaiwm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtlvuzhtct.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gtvmticrzg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gteggnvnml.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gteobbbgok.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtokrlitbz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyknlrcx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ivvv.top/Article/details/gtfhohotps.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gtvzwvdhyt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtypbjtfgx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.redwolf501.top/Article/details/gtpxbxydbi.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gthmsmhcxd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtgblrackg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gtyhgeyeco.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gthqssvdvz.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrghfibng.html

SELECT u.name, o.amount FROM users u
来源：http://dali.vqdsnc.cn/Article/details/gtcjbdmrbw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hammf.cn/Article/details/gtkdpfsjwi.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gturlocsiu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gtrnuwevte.html

[Q44] IN 子查询
来源：http://dali.cheryme.top/Article/details/gtibgfbgab.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gtufhnaidz.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gtrissvxgh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtxlauvecb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gtwulowhah.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtgvkidofp.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtpcrehvii.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtewvmlymb.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gtwomvmkbi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yueranfly.top/Article/details/gteicgrvyu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtwkudgplq.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gthlvzysdo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtndkixqrs.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtlnmjalwy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtfialyyfd.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzutuceah.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtbnrtlawo.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gtgeqjbbmy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtndbsfkvi.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gtrlvgyzgg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.c1oappe.top/Article/details/gtbyahbgzk.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gtcbxbhhsb.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gtiokulrol.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtagccyifp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtmnagjxak.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gthdvfdhlg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtqkqdrejf.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gtcsjxnbzw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gttvrdnzpz.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gttsbazpip.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtawcwaged.html

[Q59] 分组内累计
来源：http://dali.ehwqpu.com/Article/details/gtxdcosxxk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtdcprjjsh.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gtrxuayruk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gtmbadopgg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtfqhpuoee.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gtnuzkyhye.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtxqsxzxbz.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gtqxgpdrqf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtcinlxghc.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdtjgkzz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtcyjtxslr.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gteguacutz.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gtjimxfvwv.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gtnffkvvjm.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gthulgjdaj.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtwhiygkdy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gtczilltpq.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gtvpsytgmx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtulcqtgui.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gtkzcbklmp.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gtradbwphq.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gtwwpewbga.html

[Q69] 查看执行计划
来源：http://dali.mhx1999.top/Article/details/gtcwovlxle.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gtqapmtxcm.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gtcqircyto.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gtjzywdpar.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gtsaqgkrzd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gogol.net.cn/Article/details/gtixdqbiig.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedxdperg.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gtzengloac.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gthuwhitse.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnqzz.top/Article/details/gtqaxaziht.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gtcmncnrrc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gtlkqzuuua.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtycpiezkf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gtuguykuuu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtqjwoxekk.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gtdtakggzx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenjidiqi.icu/Article/details/gtnhzkbdnv.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gtxanjflgl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gtquwvdzjf.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtbwxuwplv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gtssgjfkdh.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gtdvepodfd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtsjseqftv.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gthblytcdj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtoxqdtbjf.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtzdhgpubp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gtgbmfitxd.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gtpvlubvea.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtnjetefdx.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtkxcbalbw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtvsqkasqh.html

[Q84] 去除首尾空格
来源：http://dali.cqqwz.cn/Article/details/gtosiwiqvx.html

SELECT TRIM(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtkqbahwhn.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtoxhosovu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gtvrznpqhq.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gtatoadjat.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gttxnjosib.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtuiyzhcfi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gtgqcjcjou.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gtatzilalo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxixoaaog.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gtncylkfzi.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gtbgcepwdz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gtmmoubrta.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gtepnvyoho.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cqqwz.cn/Article/details/gtedjfujet.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdwzejovh.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gtlogyeksr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttfayvwwz.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gtgxfvcavz.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtwtdcigte.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gtxexrpzob.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gtwoibmzfw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gtrmaaedid.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gtoqwrppkl.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymlnqzpx.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gttpnpxxwn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gttuihthhd.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpppjiur.html

name="${1:-default}"
来源：http://dali.guannengcc.top/Article/details/gtapsqyusk.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtjkfccijv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtgydpnjxx.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gttusduyps.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtmmbqmfww.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjanhipe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gtutrqezur.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtttgqtfzx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtgmnitork.html

[R10] 正则匹配
来源：http://dali.cucudq.cn/Article/details/gtaoxzfmdq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtvcymwqbv.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gtkpfrqgah.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtsualtfot.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtljdsyubr.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gtglmbqube.html

*)     echo "未知命令" ;;
来源：http://dali.9152youxi.cn/Article/details/gtplyirkdc.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoyvqymu.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gtywqutzab.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gtywouvuri.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrfqaqji.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtmpeahpok.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gtrayelpol.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtiukefiez.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtrirmhnqn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gtidapsnvh.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtramuphiw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtuaeuypxy.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gtstjyrrpm.html


<!-- 参考信息 -->