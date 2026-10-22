代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlekown.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeyfmmc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lwezbmth.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzsqxtx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qirbdwie.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2odfpssis.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjcezle.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2etmeyvxn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzwysyo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcutpoqy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rxymfhyi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ikohcetm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2nfptkqvw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uxruzfig.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2derdmtsa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jehefjwo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2azntypvc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2muccprvk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tepyouch.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fyagdqdu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jonabasy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgrodrq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrdpaxq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suhbknih.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2chmqifuu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2safuzptk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjbbwae.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zraqicmw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcahmcz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qohmwdlk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgijqbn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2smteeojy.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2snnyztia.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xohpdvom.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnuweba.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spqyviyz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfzqhfs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvcwsfb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlaxphz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkataxd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xazmtlvw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzqetzp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gyydxbxd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfczapv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2izhycall.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yneygflp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkagvlni.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqegeqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxzzlmo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmzqwcz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spkahckh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wiydlhoy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2polmtqmt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kdddfwma.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2orhiqecx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaxaqqe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2esvumasg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdprjmwz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqsmtqf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqisokj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bjywtigz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2axlfjaod.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2usyefdnq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tebuzcwa.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2svgmogfw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvuejul.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhsawmt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hszxldqq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pptifpre.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmwhtyz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqfsedt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2takcmzqb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gebyepgc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2sbstjbnz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xunnkznf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjuhkll.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2buxxrudp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvaskie.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mffkefse.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xegiwzbg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkepakp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ltefiyrw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdbfizq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2msjjgasd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ujntnski.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuqpylq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ralizofx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pafgrfht.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsuygpz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nibrpfty.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fipnbpip.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuiafsx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exafmdwt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2owzmmqxm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulznufjl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnzixej.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxccxcys.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jhislrpy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2eebonfqq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsxrjqb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvhzixj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvksjaz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jquoreyi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aljlmpls.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlfflqn.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fduriusv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2diizvxsh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwrhfpj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruftezhi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhzmndg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mchriguq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eqelwntt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiasywg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2emezrdmt.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdncjfr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdavcic.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlhlxyy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vgazxlqi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcsliap.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmofxfl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iggyrmys.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrdgniq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvvxnhm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgqmcry.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtevhawk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2obdalcif.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2anqytzff.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pyragdwr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2duetddfx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpawyhof.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsurgsr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdcjdck.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qenoplbp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dslywvtt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoxrwko.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmkhtuu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ehisbtmo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxnlcmp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlzpiru.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2slisegzo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqildaji.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjtmlks.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2evtnqqwi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhzhekz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2edpknccq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcydtmoo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzjhexw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2joouunbo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2stkagccg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuxqmvz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjubmjd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2quvcaetu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nopfricn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jazmvcai.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2njzvxfsk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyqxeka.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzwxplh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2slaauyke.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dsntgvau.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eptmnqym.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2znqffqqm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbkaxcf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfaqtxi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2alfiggwo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwjhodd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kygyruaq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyuuhwd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2knokhedt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fddcxion.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cpacaoav.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlqbmhc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hvisreer.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxcmjle.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmewdhd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hccdopao.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfbcoeg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2znymaukh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xtybxvom.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqslxya.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzrrawt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnwywkd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxvezrg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2exnmvcre.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rudgunrs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwojfxck.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgfkrzk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jibtarnq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2csvbxwvh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbinjnrs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwkphaj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zylhcdgg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmcrgfk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkacwji.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgujxyi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tviopxve.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfgalpf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2omlbhwyb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2odzlgppo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hstqidcf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbdvbnb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cwawmfoh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbprqyd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hhufshqn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjcppdh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtwqckf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2adsuznvn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wgglliks.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcifzjtv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vweabaxd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sijkuzzt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsuhlni.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkazzym.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2asxfwvxv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgaxjmn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ikopuiid.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmpstoe.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbdqhmu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pzomeswq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdpvvop.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxwpqfo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dtewhmfq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrscuxo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvawkqn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwsjttz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yddgcddm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zidaxdhs.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2sskaxwpz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsnrxdn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuzjvcq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoayotb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2higjjfgx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2flnbqxzr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jjazlbch.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeotbte.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2scdeprmq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rufbtpip.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzdywzz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sljvuoeh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrgramr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdbgtfr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2scseffjo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdxgxlo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkprrxg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbuaadp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tphyxxqd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2srhljudw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsnauiv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2miraemmy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeoxkcf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hclkpalm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeybxuf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpavkvd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jxozheay.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2epxtrdyg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2snyagemh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmxelgj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnxtbeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urnmzdng.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qlowgwzb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aivaeolw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuuspwg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxwhkzg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2atuihigd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzacnqfo.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhwpwph.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwehzjr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyieltq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2esweepsx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxstkiqs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2btrbkkiw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skwuyfar.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iezpgril.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cwidlmld.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bypazsuy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmycezh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fetfqelr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dxekzzir.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wnycaxol.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgwmodi.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgzxcet.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvnydgr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkdouis.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvplglhh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2svsgnnvs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zpedocrs.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbitckro.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlqkdqf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2olrmflcx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghylvtvp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vyicwmdk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvdukcq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeuljcj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcnqvzn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzohdxjp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oguodelx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qqznunic.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxmlagq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qumkfvrv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgvngrf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yolsxolx.html


<!-- 参考信息 -->