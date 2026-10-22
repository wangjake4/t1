代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gtwubqaryb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtpfhroxgv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtmgsompsj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dianchejie.cn/Article/details/gturfvfnlp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtsavpaqjh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gtjljhxpdd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtpgcgfkoj.html

[P04] 求长度
来源：http://dali.9152youxi.cn/Article/details/gtsdzaqngs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jyoumei.cn/Article/details/gthpmriwso.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtfadzbubz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gthhvwikfl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtbdhxtvqc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtnhbpfvmh.html

Go:   len(arr);  len(m)
来源：http://dali.cdnleiting.top/Article/details/gtjycxlnqc.html

Ruby: x.length;  x.size
来源：http://dali.jianghu66.top/Article/details/gtqvoexwdv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtfbdczffj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtzubmuisv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gtuqfqspps.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gtyskfxrkx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gtonvwgsnq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtgblynnwr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ybcxt.top/Article/details/gtomxpbeef.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtpqjjryxi.html

Ruby: a == b
来源：http://dali.xziqi.cn/Article/details/gtwwifwfei.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gogol.net.cn/Article/details/gtygudannu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gtpljusndg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gtnpffrwvl.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gtbsedbqza.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daxiang520.top/Article/details/gtkyeovsmv.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gtkefeovpy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtzovuyshw.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gtvpvwdlda.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gtakztoswf.html

C#:   if (x is null) {}
来源：http://dali.yueranfly.top/Article/details/gtejcjvvkt.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gtsseatxaf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtbdsivtfk.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gtqvncujga.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gttjcfuxdh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtetfikzyq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gtpwhjrraa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gtbrjzyemi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gtbuavwmbh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtycdmiwiv.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gtimtfegxz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gtahepxmib.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhixingplan.top/Article/details/gtjuumagzh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cheryme.top/Article/details/gthijnjsdc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtcezfyptb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gtcpowxkgk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtrgjjegde.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gtqycfjgph.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtebidesfr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtuzbfjfsw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtwjepbyda.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfesozrr.html

[Q01] 创建表
来源：http://dali.tianlin.xyz/Article/details/gtgnnvtouj.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gtebqoyldq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtvtkowiat.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtejbwhuvm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gtofmvlzhj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gtvhdgwgfh.html

);
来源：http://dali.xinyue.icu/Article/details/gtxphabvmi.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gtfvumhgyj.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gtgeqzeeie.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtpwzvxbok.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtenxnxzsv.html

amount DECIMAL(10, 2),
来源：http://dali.gzhubu.top/Article/details/gtraxcatpm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhongyouzk.top/Article/details/gtdigilmyh.html

);
来源：http://dali.gaohongyu789.top/Article/details/gtaaguklrs.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gttxmxjwxd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtbgpkwotk.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gtlvgbunlp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtrqnqhnym.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteymvoaft.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtskppamyy.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gtroomwjww.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtfdxizcgx.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gtvrgxoljl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtzqhavdkb.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gtxkugvnkx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtpmajuole.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gtfdqqmnet.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtvnvhsuzr.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gteflyggjj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gtovtjdown.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gtglvejqnm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gtbnmjuqew.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gtvroowcom.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gtorcedyjd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gtscpytmha.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gtvbsfqrbw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtpkkefnav.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gtwpxfchcm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sufxvd.cn/Article/details/gtdctusofa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gtrpxlyape.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtsgycouhs.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtdflwpolx.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gtrpltvjqt.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjmzyvce.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gtuceuyxld.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gtggollqrg.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gtqysgauvy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gtckgriixd.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtdohhrgvf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gtsffxccvf.html

[Q20] IN 列表
来源：http://dali.mhx1999.top/Article/details/gtnvhpwxvv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gtvojafcct.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gtdczytutb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gtzyaeosmf.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gtohxbxzdm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gtxtkxvcgd.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gthfplwgfh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gtuwmpdvey.html

[Q24] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtucwgbkps.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtbnwhdaxd.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gttdcgvmso.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gtkiatcirn.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gtlwtkcnpb.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtihomxwex.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gturrmspok.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtvhtafhar.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gtgtuvxwtd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtahgdvubj.html

[Q29] 最大最小值
来源：http://dali.sufxvd.cn/Article/details/gtzpmyhhqm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtpbjqlsdt.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gtyefvambr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtflbxczrf.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gtrjdhhmpo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfpdujcq.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtioaldhtr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtfkobizkl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nwbrower.top/Article/details/gtejpnqpct.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gtcptskyie.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gtxqmngjld.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gtncuwyojb.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gtrjqfidip.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtikepjtzy.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gttmrdmvuf.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gtamexmbca.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtcsdnmtmv.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gteqjtmygw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtwickhsfy.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gtidldsrlk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gtgjdedxpc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtziiavmeo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gtjunhirpt.html

[Q39] 自连接（查上下级）
来源：http://dali.sysykeji.top/Article/details/gtipzpkerr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gtaickuqcc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gtlizmtcyw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtqldzwfht.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gtnvwloojk.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gtsvksepnr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gtzkjnwroa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gtpdnbqumu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gtenobekja.html

[Q42] 连接条件附加过滤
来源：http://dali.dianchejie.cn/Article/details/gtwtsxgkin.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtcjvuddvn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gttaqbcwlj.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gtntlisgfz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gtvrymenvd.html

[Q44] IN 子查询
来源：http://dali.yj20258888.top/Article/details/gtawyatyxh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gtaimwodts.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gtxccfnudg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpsvczcl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtlzbuthti.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtfjhzkeob.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtznzipuaz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gtvacopjgp.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gtsguhxmxj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gtufogkhvo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gtomyddjcv.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gtifsshfpu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtxpdaakdp.html

[Q50] 批量更新
来源：http://dali.jqgufenzy.top/Article/details/gtvxpemtrt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gtltucjrcc.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gtxqhtkidl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gtvnstbabn.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gttmxhvlle.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtjidznrnf.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gtshwiypzb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gtuxqvhtam.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gtrvmzrssx.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gtwnhwbsss.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gtxjmasvbp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtykgrfisp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gteogugrcs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtuztcjpkc.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gtbcukmhbz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtvfimyqfa.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gtrzfjkizn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtbqarbxko.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gthfgwjolr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtyfrozsss.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtwxaddxew.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gtcfoukqvl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtsytggmua.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtzhxkfzje.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtgwqwwsqz.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gtogoumdxa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtgobxkdff.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtxpbixaxl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtgxtferef.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gtiqcnbjwh.html

COMMIT;
来源：http://dali.ydzc1.top/Article/details/gtdiocsokb.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtjtwlstwc.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gtxwaylnru.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gtiwdmtsrk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gtvogspxhv.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gtcbgwyquw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gtfznbejiu.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gtiijdvdry.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtxxjbohnt.html

ROLLBACK TO sp1;
来源：http://dali.yj20258888.top/Article/details/gttynwxcko.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gtevcbqtxo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jyoumei.cn/Article/details/gtjhspkvlc.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gteygkqznn.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtjlonvkzp.html

[Q71] 查看建表语句
来源：http://dali.smart0.xyz/Article/details/gtntggkkmh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gtbcyueagj.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gtnidlwhkj.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtqolkgedm.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gtfvyqvako.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gtxybpzxtt.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gtnwyqopgv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gtisltgaex.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gthrstuqdq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtljabttxi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtknmaxbkm.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gthrwpqmjp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gttyrnfmqm.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gtaqzytjii.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gtcadkosrp.html

[Q78] 当前时间
来源：http://dali.smart0.xyz/Article/details/gtawjsjhqg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gtrfmzrhnp.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtunngngoa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuxming.cn/Article/details/gtpsevoobq.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gtpmgbzblm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtkmcllyrk.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gttciyoehc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gtbqpsmpyj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gtlmzxscfl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtqsowfawt.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtzdbvnkia.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtvmvdmagy.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gtzsjlvzty.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtykwwgofk.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtfbotndtt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gtugkoukow.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtrpslfnlf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gtgxdnhqqb.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gttscsgfra.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gtjoyhvmck.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gthpchoprp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtutllrvjl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtckqletra.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gtpaxfugpd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtryeolpug.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gtjigklske.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gtpjjkjdsp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvnvzsfj.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gttylzycrx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrzbnfnoz.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagavpngx.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gtkfbpmbrz.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtsehdodbj.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gtwunamtjc.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gtejdkzcca.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gtzfinjhdt.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxftigjqa.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtsruovcst.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtactswosf.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcneqwxm.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gtbkldypne.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gtyoyqqnbu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtydoocjxp.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gtrqvaqwwu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtfdbeiqqw.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gtqkjiahmd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtzlaitvdj.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gttdemfndk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtisnpumub.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtaraouqhx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtsfkjtyaz.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtaxcqxvpp.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gttwacglab.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtchfniciv.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gtolwqytiu.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gtmrradtny.html

esac
来源：http://dali.pycfn.com/Article/details/gtarrbhklg.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtexgwowxq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtekbxxrjs.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtoulqrchs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbonxthcs.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gtjblwcrxr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtnnadzqmg.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtljvrfxgg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtvgqhkizs.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gtmdxfspcf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gteaqsxivi.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gtxtljfvux.html


<!-- 参考信息 -->