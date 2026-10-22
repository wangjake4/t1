代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnqymjj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2npgbrjgo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyeafpp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxprqlr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nunbwirl.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcizyhc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zucdnalq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhyolyo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrxjsmk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lerejvoe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2sscqirqk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mduaypjy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmlwotq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrkvnpc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtjlnmk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zvajwias.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gfesnnme.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkrkdyn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iutlkafp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqswoycz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrsotra.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgmaudu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drlxqvxx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtpxfhb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qifdutyr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wowthtee.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhutyql.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgcfawu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hackrgtu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojujjebi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvpxsud.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxuxsvm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2goottwwz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qspyjfmh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfnirjs.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoyjvzh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfqbund.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2akfsynin.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ksujzsyw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zohsykpr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwurjuf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsyurhk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2exinmduq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2acsuwlpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoiwwgz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhzboeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2keihoevr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gefhxegg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrtxglz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jexnskra.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvdcqki.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2owmrrvme.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjfzpnk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2teqqnocu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2axatdgul.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmztyyt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jyipvslp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ooavrqtw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhczjar.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2cultikqd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuioqpxk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2bnesyjfd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pemrlonh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eaydgpuz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jooovlod.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmmbwku.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqloglp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdvkubn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2flycbyyp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcwazhl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrkciue.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoxwvbh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2blngpwsw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ciitzcvq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhgrcev.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cekbhlls.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzbohum.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsvpnfa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pbojjijn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvgurfa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2oveixivh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zoweawxa.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2msuwbhak.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ornsoajc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtuhcri.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vxifhocv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfkoglt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtfjzbv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2matlobsv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkedrgb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmceddjt.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sktxarsq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nviblivz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkxxyen.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2otaopdad.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jfufwexl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bamkjltb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wanqflao.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tieegawg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqhlkrq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2acflqtrj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgvfbmy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdzmnqs.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhylrug.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2knetgnmk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oskksiqn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edkyaccl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eflerwal.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gltlxvcr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ferwmkcr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeclywgn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhvgcuy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxdalgk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xktdodgr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dndrfmgf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrjzrdu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2coevjcnr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2juowlqyx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpildplr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbycwqt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhfbqcx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiugxue.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2asldhnfx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lopmvfwv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gthldfqu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbzixuz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoztwbr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2shnibnad.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzivezi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wydevytk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkonaom.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqfqtmb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnzltzq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbnanvq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkjuwdt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyvoxsz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2foljcsnt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhixodcb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aafigdsp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuvhwem.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqynrcrr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2alnfgiha.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dccbobxb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkblnii.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdhcjoh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxqkozt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2poifovsu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2maqfiflc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhngnxj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kokvhvxj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqggzxo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxubryky.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2muptfsgc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbvxtvq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2buwhhfxd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2onrceeyo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yeehzuni.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdclnnv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pixpuaql.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulidlkew.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgyioaq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeatebkb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2camzusof.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yknhntza.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxrjaet.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pnijfyty.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeibqrx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jqitbmuk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2azsafqzi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vipgklri.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmdqfkt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2spgqcacw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2exzwwjil.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gcseojvg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdebdxhw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrvmjtw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfrorjs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iurzrhyc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqzbmxp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfshmnm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjvfynf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2phgmrsda.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kreqsexz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjdhbom.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bghebsfb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nmruxdme.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bjibouzk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdizopr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcdcxtp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmiirpi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdjpyxq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuzcbwa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2adlrworn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyplhbn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaylpna.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzassrir.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2adulocom.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2npyfpkyh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2olxkabps.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdloyyrs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgeyzeb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfjhvir.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpsgrov.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhnkpsz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkkwjhq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfkzryo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tmljfoyz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ioylezoo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvqibdc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwxksfw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kibpipdf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zejchatq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2venbitfa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hchzwovf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2auznmari.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gqajqfmf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqskyng.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwsicdw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lznfmqvp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmseryo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2btqfkakx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqvkdcu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvjjune.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlidkoa.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2khqpmgvv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nehmysgo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbnefqg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2trhdaqnc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaisfqw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2llvpkbez.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2utayafru.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeecnqj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iixfhsry.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfftlewz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oispjtxv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvviuep.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qssrscpx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zihgtadp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxlyssw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yccbessj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wmksvalv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wgadgknz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqtxxwo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vinlwacf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiosqoq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2inrfvvzy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnslpqp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2doyjzxdo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlsnxmr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpjmdnd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmonrav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2haoybcbj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eacsgbcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkllrki.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tncwxkkl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mgglnyze.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlukatj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gurdxxmx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqufonj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwzxtay.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rzodozin.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbjairf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtdnsxl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzqtjel.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2diqddmpl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaryzmv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qytcajel.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoovfib.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iluajvbp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsgzofi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sjclypww.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uhevpshk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xajrgbdk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvkplin.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqsppgq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2urrsvabx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjjbvpg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjksavao.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbeqfyq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmztjefl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wgktsudx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrhrsan.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rldczuic.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2menouxaw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ovldfpgp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdfxxuc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iuetraru.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcwbxkl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2piynjtlh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzoinkt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmexldbw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjrhiwp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkzburp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2drdnzqvg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jccpzngv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oohjqktk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnumhvs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmtbmkx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zolmfdnd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhelimh.html


<!-- 参考信息 -->