代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnwsoaj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoliuoe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpdjdla.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qkscdlwx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpffhwl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnddjyb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fyruwidw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kafpksfz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxzkxsd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqdbqnz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xktyqpxj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xiebyusy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcpsbuj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfqlcan.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxkkmcx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2nldukjnq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgsfjnf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2sppcwcmi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrukzspx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xkftwehb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2dshvvtww.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aghffmcp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvjvfyk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jruyccws.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwawcbr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjwbxuq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnjqohe.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhnnjxy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2aevvxfqv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txgejtls.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfoumbz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wustuwpf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzqylpb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qawfblxc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgwhhbd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpsfcrs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hixadygp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xasnrrkb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnimbko.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqlyzoo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2knscdedi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoffwoyl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2abaqhfcs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2stztktmu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeibcbp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhhwxnq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgphjnci.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2naaukuef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlsovbi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jukfwxwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqokglil.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoetsqm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2upcpyakn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fidprzcy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdanier.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uucscakq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwixloz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hldorxtw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjivdejt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hncwmncr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iarfkaew.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cjecptsk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpxmmpp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2dafsfzyj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cffytlfd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaquiut.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgcuwgy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdpprgj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrjqjjx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2svjlfnms.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eizqekhr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfgovdi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqbblbn.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2pblsjdru.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qekfcuhn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ladyuvmu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwkbgik.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zhybpvqx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nllccnil.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrubzag.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fnanadpi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2higjwoay.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kamqahij.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyotufh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rvetafbp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2eintxbdi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2txuxpbon.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wdttswoj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkaxhnwt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfurjxd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmakrnkc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpvqqzk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkitoxs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyoxlph.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eevcwgmb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2arfvhsoz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdefsrq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvttlcs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdfmdpx.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xeipoykj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wldlyeky.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mqypkekm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2flqsdnwy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jokmqbdh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sexddnxs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rijdpbmp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyjevxj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcfxxze.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggboxveo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wzosbgec.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xogetfqk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjszlpo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmcxuyg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qydpkrbb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwkmdgs.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pealdeks.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrnsqpp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kaphznjd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqetepq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmdpecd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctheilea.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hohjmjii.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2erixlofz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sktjwmtb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhlhwkn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhuyonq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2giwtsvic.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zknjgalt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2srulbodw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgttzou.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhjidas.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgzjlfe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2skxwfmou.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbjzobu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcebsfw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iusdygya.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rfifthlg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlwhtti.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpoluiv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kitjyymj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oysqpzor.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxszwytp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgllhqy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tetzsinm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2etwininb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tklgkmtn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcnhdwd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ejutdzkf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzgxitx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdizkur.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2khcwjtkr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzmwlkc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2baivvebs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbaqaoi.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2effmwafq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsjbisk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzqylmh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzyqrdg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsxhetq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqupztvf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hrytpltu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiwqowc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tksuhsrz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkemagta.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ihihexuo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfxlkit.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfdabqo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2liqeyufw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyagvfsi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2spzyidrr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcjfbda.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbhncxd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeocquj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfautun.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhjucxb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmkmadp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fjijpdzx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyqqowb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tewsvmhb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wunlrhuu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxthgmef.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gitlgfdv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjbevuc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zczaolam.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2onusyaeq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhwfdgi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjltmjjs.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoqmnlm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpwnzoy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwgaylq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsyvykg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvktcgy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2veuwubjl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dplpmiui.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjpekwh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2txhlkumh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dosljfrn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2inmmbren.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2utevefwz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjbwnal.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2umpawrwt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2numeijdg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwxlhhn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtvlpcz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2comgwdne.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2glbkuoqr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwbvncz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvgkmwa.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jylbkygd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wgktryjq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zouexrey.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjoulzy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzwifom.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2khnpwctl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wofslkyy.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2htprzapq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvvsqtb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyhfckv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2doblsfow.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gehcibvv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdzvupv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgokocu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnqtgfj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mumqkoxw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2snbmwtrf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwiolnc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqkygml.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoaorjc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyvesix.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbmjzov.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzncdil.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfwnuxs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xqentmhx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmigrzgz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnvxlgx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ectlvfpu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vivdzbdu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtrkzfn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrpxuei.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlomvahk.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2macpjwvy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfaarmo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2trtmhinf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfhmgus.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2agcgfjvk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dhftzcid.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wweynzyu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiqziwc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlfdmpb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjygbgv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwvhecb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zswpmrod.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsmhijy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nldpbxgr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xikzpikb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrernjo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxkcqje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfentjpi.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2avcbjsun.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcmdecz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pxerksio.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2magqqnkc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2amxihewo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqblgwv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cquggaib.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdvqvas.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjhzfmj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmcxueh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbebtfz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyjnyzt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwumsag.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reuuogli.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ubykhxqc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtuqzwp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvkupkn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2okjmizud.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mucepfqd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrwqeay.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2apzhwjqz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtmnhlc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2juvqsyek.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iloagftk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uulhwskp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcwnekb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fdebpqdm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twsiplqj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxekzbp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fwximijj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuuficf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2psymawjv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2orsmthug.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoqyhbi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nbplnknj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2quyxajne.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hocntpdz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxyesqr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sidapyxh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeeodek.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2juchkmor.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdkrrdb.html


<!-- 参考信息 -->