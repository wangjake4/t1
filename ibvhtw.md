代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gtihdmirwk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gtszwossjh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtmvulfiek.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gtrffmiyvg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtsjzouwru.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gtxdrgvhwy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtvxwgbtkt.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gtoindkqzl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gtbdbcinbw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gtuvcalkqv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtubtibiwh.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gtmrmgshtr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daria6918.cn/Article/details/gtjywruelk.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gtddatdgvq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtmhygbbuy.html

Go:   if x == nil {}
来源：http://dali.zycfv.cn/Article/details/gtgpxlrhzu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yongpay.top/Article/details/gtwkjnatkw.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtajrfmwbb.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gtuowbsmqk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtyfuhenob.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gthbtegwre.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpxzpdjj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtbytzayfr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gtyhzyvzxv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gtelkmlzwc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gtufqfgyga.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yvedp.cn/Article/details/gtkapqlsij.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtsuuqcqkk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gtnzmizbat.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gtbdscsgcp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gtdfhjlnta.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtmgvzqabk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gtzptpgeje.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gtvphucmtq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gtivvglxcb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnqzz.top/Article/details/gtnnzjewnw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtizjshtjh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtdqsatzki.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtyqhxfglq.html

[Q01] 创建表
来源：http://dali.ybcxt.top/Article/details/gtsazfdxib.html

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gtswjustrp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtqypynqoe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtzxxezmwl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gtxrbwirgp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guowangkeji.top/Article/details/gtmodxpzun.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtbyqyjwys.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtwyjcblcl.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtegbyxdxv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtzvmfailu.html

user_id INT NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtiogchpda.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gtfmgqcoiq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gtsudbghsa.html

);
来源：http://dali.hfpthk.cn/Article/details/gteqchgdhb.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqfoeduc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gtffpywkgr.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtaldgqswe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gthrrsbhjs.html

[Q05] 重命名列
来源：http://dali.nanxinkj.top/Article/details/gtpsnbmepl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtykdpjeyq.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gtgfiqtitm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zycfv.cn/Article/details/gtzcdxqnxe.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtiprscjsp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gtospwxlwn.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gtyvyzkphf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtjzujizzk.html

[Q09] 创建唯一索引
来源：http://dali.tian-w.cn/Article/details/gtyandcenh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtzqnqvmpt.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxoxhamh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gtuvbswitb.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gtzllvsfmf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtzcesqzbl.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtmcgwxwgp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hongshengwenyu.top/Article/details/gtwwjucdbi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gtlnilafzj.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gtjcvwtkwz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtpjtiqbnj.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gtdcdefiet.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtryzducqu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtbdtnoobs.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gtccehoynk.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtvlyqxmkw.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gtastywfsv.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gtfwqiwfvt.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gtyuutksqd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefnexmcu.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gtfsqarqhr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrqnomya.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gtgubqrwop.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtlespmwns.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsdtocpf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gttimlurpt.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gtfnqafcba.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cucudq.cn/Article/details/gtddczwpua.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gtjsrghblx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gtypfsuvcu.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gtuxdqrgfq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtbotvjrzh.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtntwmlacx.html

SELECT DISTINCT city FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtqpvhunln.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gtaitqdcpy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenzaomai.com/Article/details/gtxkotithm.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gtrgvdvevz.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtngxvggkm.html

[Q27] 条件计数
来源：http://dali.cucudq.cn/Article/details/gtbhaulnzg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtjehodliy.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gtpcdjxtcg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtpsdrgnrt.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gtapsvpdba.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtgfrnkvhn.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gtdffuahgc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtvazgdizt.html

[Q31] 分组后过滤
来源：http://dali.andypj.xyz/Article/details/gtlcqxdnpr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgseqqnh.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtappsgslw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtgdiealfs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gtkbmfxvhf.html

[Q33] 多列分组
来源：http://dali.zycfv.cn/Article/details/gtqejewfbl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gthbkowsse.html

[Q34] 每组取第一条
来源：http://dali.yj20258888.top/Article/details/gtxswkwgxq.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtvualdpdo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gtjkjitqim.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtncwfyzqk.html

[Q35] 内连接
来源：http://dali.aizwys.cn/Article/details/gtjwkhdtzd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtjvvnhxyw.html

[Q36] 左连接
来源：http://dali.quarkkingdee.top/Article/details/gtiumtklno.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtlzqfflxw.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gtqrqrbqpu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gthdsvhunx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gtatvohmca.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gtdbyoxiow.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gtfunbhxsr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gtxhcayhjb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gtwppqwscv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gtujlqkdrb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jianghu66.top/Article/details/gtvqefhbbj.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gtunceuioh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gtfwurfwfe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtvxgakwxe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gtapjngiri.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gtcgpchnar.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtoplaeoqn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gtkedyfmrv.html

[Q43] 标量子查询
来源：http://dali.gzhubu.top/Article/details/gtjrprilsk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gthbmqafmr.html

[Q44] IN 子查询
来源：http://dali.xuanzx.com/Article/details/gtxakfxmki.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtjzkrezsr.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gtulfuergp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqummvbbu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtwcpcefwe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtlkuvdzka.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gtapazpgkb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gtzelfcplf.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gttfdmbhje.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gtuyvxuhxa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gttkdhfkoj.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gthecxuuri.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtwqlvbivy.html

[Q50] 批量更新
来源：http://dali.shuidangran.top/Article/details/gtwbmofafh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gtnwdcngia.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gttcpqugen.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gtffbpvvvt.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gtmjlbqjdh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtvpjqgwrc.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gtmkndbjtk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtcmzyivzk.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gttqafmtih.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtbbfynaym.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtgjlmkoez.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtjxoefigo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gtmeiksbhi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtunnemsns.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtlinrqksn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtszyfvrdc.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtazcyiypp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtbbyevvre.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gtkdrvnjpw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtqgncfqha.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gtaaenwvyp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258888.top/Article/details/gtymzuegxz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtmgtgpaeh.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gtdtqwfkua.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdyvlrka.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gtuqgpnkux.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtintljcie.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gtbfbhbclu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtcdqcuhdw.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gtpamhskkn.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gtpvxtccqr.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gtfkrfcvgi.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gtpzofzame.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gtfwzyaxmd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwjleblm.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gtppouqewl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtkznpitpa.html

[Q68] 保存点
来源：http://dali.shzxlz.cn/Article/details/gtafucuwqk.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtdzlpywmv.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gtrccwxaqx.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtldeojweu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gtmlksxkaz.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtirciyppo.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gtsxqvnuom.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuydrhoyn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.9152youxi.cn/Article/details/gtaktuytop.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajymsoae.html

SHOW INDEX FROM users;
来源：http://dali.nwbrower.top/Article/details/gthtvtmbup.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gtrfilglsn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gtnrnjubdl.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtxaxaktrj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gtgzcvfopw.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtqghraskq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gtvdqgjpch.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gthcibrhej.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkgwwwfk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gtqlmfyeom.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gthnxytccz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gtqauohcaz.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtmyefjpai.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daria6918.cn/Article/details/gtqgaukfsl.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtuesjhkqx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gtgbkdvqon.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gtfsyrjvuk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtxljjfnbo.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtqqwdchju.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtagibzwxl.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gtinjshggt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gttarhtnre.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gthbztvvaj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtsmxqzofk.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtjjydhxed.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtrjbfgrer.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gttkscuoje.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gttjmtektp.html

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gtdrjgteog.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gtyvepqixq.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gtosinavbj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtesjlrzkt.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gtltacrzae.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtplbzjwsj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtfzclvvsj.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gtaraysafy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gtcrnrhicl.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxnfgzef.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gtoepzvexx.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtwyhbuxjj.html

R. Bash 专题
来源：http://dali.jinqigfzy.top/Article/details/gtqqkmqdpg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkuhjsqcc.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gtgxiyyoeh.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gtfejsfvpi.html

set -euo pipefail
来源：http://dali.sufxvd.cn/Article/details/gtzontbscb.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gtrkihkgsh.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gtfugncydq.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gtruaelwvf.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gtnyafaxxx.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtkdjkqagz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtmznstxdg.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gtotlkmkwx.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gtttziqmyy.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtbvbshvek.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtyglfifdb.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gtsxmludvm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtuqvhiyvy.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtwggewuen.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gtmvhsvltp.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtwovjyyfk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtyfizieea.html

[R10] 正则匹配
来源：http://dali.ppjwa.cn/Article/details/gtdfqagtjc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtohactshf.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gttmajrwov.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gtmfnycsdm.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtajarncij.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtwoajyzaq.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gtqbhfcyeg.html

esac
来源：http://dali.yj20258888.top/Article/details/gtucwrnlbs.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gtuctwdojv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gtpkoxhkub.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gtwnexkron.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtuutalopa.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gtgvkbihwr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtfnfqokud.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtkusislea.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtwsapxfpx.html

[R16] until 等待条件
来源：http://dali.snrcjt.cn/Article/details/gtdqvvkadu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbeyutrhr.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gtwqdyxqmz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjznxekl.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gtojfszgql.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gtowqkshws.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtfzbcbbnt.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gtmsucvsdh.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtvphhbwrz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gogol.net.cn/Article/details/gtuiqpjbfs.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtwehxsrqv.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gtfelncdkg.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtnrliygxy.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gtrcipkpqj.html

[R23] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekdvxfxb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gtbhtqovsl.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtoiudtpzv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gtucuvukvg.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gtwloxaloj.html


<!-- 参考信息 -->