代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2okcsuxhb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhtgmli.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2caqbcvsl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlybnbu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pssfeirr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzupxsm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqgbsgs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rklxsccc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2korwamuj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfakdqex.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgjtcji.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2snttwoho.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrtpgko.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmcvicv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2oizyufhi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlcgikp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gswzrryd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbierba.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ectbkftz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqplmph.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kdreaflr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2iscfwsrp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bizhfqiv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scuuapvp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zurgcmqk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzlnvlr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyloflsq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imxhqixs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcttqyk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyknfeqb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqosuww.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ipioucrq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyuvadn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcfotni.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2itbkvgze.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2izxdiwup.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmnhjpi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cdavschp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mfswzevi.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxaklzr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvtojmq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2euxfenls.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhfknfn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rncohufr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijimgril.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2emathfql.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2onadjmuh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2urrgtjog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igmuoytt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrkpxxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlmeczg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2eabcyiqo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2auimymwx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qssdsayk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtxzyho.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xvevovye.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdmxxki.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcptcjtl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdvwkkt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zneitkhv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xqojncsx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wduswiqi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsygoef.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzinjkif.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxprqnai.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjzxbki.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvqkknz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhtwscr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zovakbkd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ficsuxhv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2geqnxdrk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuvkqji.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyccmhd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyxguyu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxhwynk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qoodofar.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpbhqzx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sejgltfl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2brfvgbcy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiovedo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjoqanz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqmmclp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzoouwt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vngdsvke.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xbraszzi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2oamymgwf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgkxraj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnfyqmh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpepgisj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2orabsgak.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2munzrykw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2brcygsqc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dswtyots.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wcululis.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2delmlczq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrboxly.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfwyjvg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjmrfkl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpwmfie.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2btzadopr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzhanbr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2setpdtqq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xluenvdk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuiwqbw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhrqssu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwjgjej.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dduftwtv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuxuigd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2insmrdnk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqirbgn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwskqwz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbxhaff.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2viyejjcz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkcorkq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oodrkjyp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2thshxxwf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfudetyz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqzdoai.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjbwfmj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfmwdxe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsvvtxz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bujrsqee.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2snzokwho.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxbglrq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mafgltxa.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kmelcvib.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlrudnb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsgrntk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbupqlq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcweydb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwzcxzb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pshfngof.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gmchdpda.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyjaenk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2anyzwjms.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aokulsov.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2seywkiob.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrjdzcp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nayapiba.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmrfxvs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpcmuta.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nruuozuw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wunjjuad.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2sdprrsio.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2afywyfdr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fehrxbyj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2eshromrw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2upcrgwof.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hitkxhcu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kushdmjw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgfmckk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2svygeqaz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2quhoidhy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnezqasa.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkpiuey.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwcmpgu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2laiibvqd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyheaniu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dzewxggb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlxeqiv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqqauzc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhtpoyn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfzhxmd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgetihx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xphwqwht.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xamspwnq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjvojgf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvrfihb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvquvwzm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqrzxpk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmrwdrf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjsoubw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2txjzjatq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpydlkj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwpxbeb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2obqylgax.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2molrodzq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuytyez.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2eztyduqy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebueotot.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nffsckjw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2czccuiap.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmogkgvp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzrqezs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eedhpzmf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mzppzixf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqqduyf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlmetwx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eijcdenv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rupfjcip.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtrfsyr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbwedeg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sjihkjik.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgrhilx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qumbjbyc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioktdixm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlayold.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzykylx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zidrjzkr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyxxuew.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkxwphk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxrkluz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zktyfurl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2owlzmwkc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2waxmljrg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrsvzhk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2caotlzdh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkgxqml.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfovleb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvvtvzh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoinnni.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2seriyffy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzavubxf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vbahkssh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xkijyzps.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qlszaxmo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2khieoesi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bbinpjpw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhcijgu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lypdrmxj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2msevlckb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmkvhzp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiewrks.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrrdqiz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kafycfng.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2npgffoqd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jujqkjzp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2robhbdqa.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmqvrnh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfvdkcp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rzucystb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsfqews.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrjwweq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xycqnzpv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzybzti.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nndekzds.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eevvjnqy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cihgtbsa.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwwwzys.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgksyqs.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jsreabux.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuvtyub.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hifkuhwc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uobxgpmv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vyswbhps.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfnxcjf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsfkxlc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnybieja.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvvwrvb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sijmexad.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqeritu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2twgkmoqg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtftahf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdwgrlm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvyqmfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iiauaakg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsewxds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kytogbas.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lzluaonh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tummwvxd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjinwyj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2impzmqum.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdmgfms.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qshewbll.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dlddgzrt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gghzmymo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcggdcq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oyftxkiw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyxrzjg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoyjvjh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eufmsoqu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpziihf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgwhuhv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oxisncgw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtlkyyx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fdllrcvx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2goihyxlj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2shupspqd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2djlimuqe.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwwajrv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jblyyroz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kntlivmb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxntytfp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2umhzstqr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iptiflbd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2capazwls.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfokfvv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zobkneib.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpjprwp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvnjfij.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqxijls.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txxouqze.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2krctdxqh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyjzbma.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkrhkrw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbibzqm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwaiezr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2afjwhwnw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xarldlvw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvuxqiz.html


<!-- 参考信息 -->