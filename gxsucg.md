代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlkccum.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2xufzpowe.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2olquxqoo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjvzvkj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhytkzt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2egxgnycl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkqqrvu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2siiydtrg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlhpolz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdkcrpy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxrfszh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wylrubve.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdlkgxx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgxswpv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zonnvwfa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hbistkcz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2micimwkl.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbthrjyt.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmiuuub.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pueraeam.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeyyfcj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zhofpgwn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgkitkw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiszqeo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhcrnvs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xzocwqpy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnaqbhr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2whuxwwou.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fchzwzpq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2iczcasqw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtwcuhk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krmgbssu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuvojky.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqtqzfq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clsmaalo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwceqevs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lycdijem.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsiyjxt.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjxlzue.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdmhehw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzsuhpy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2csoojbxi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvaasbb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cujdryyq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2trzeqeia.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ztocjqmq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbnpjsm.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaakmrq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wymotcbp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2szelfvrk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2aurrrkik.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuzrzqz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lctmtyxe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpxbzvd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzltlylo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tnonjauj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uoomzbcl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pggjldbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqvfqxq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqgjypn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiwcrqg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cwddzhhy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yeljwmke.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgeeibf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tbguuktm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvxpkrx.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2iyughall.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyatnca.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2smfkjyzd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2chudwiwc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nijcixnh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2acjvasmo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfpreim.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2agebzfhy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfixaap.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2syywcalr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyufuez.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2brteykle.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmplueps.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtixqzeb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyvfkdg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqagqgis.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xczrqcpv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2drmqogae.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwvmoaj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ksckynxu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2apohdowi.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfvcznf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbpmlhl.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2sinwpqcq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mddlqxnf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxvmxzf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kwldkvne.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2jrauefjm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2myiptqte.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqtrhfp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2aehgammx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ihykpsop.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqwprdq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2owapzxtm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqshqcl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bztnarkl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrofcdp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yatmcupc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxdtipt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsotbfb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdggzcc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hkflkatt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcjsmbm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcmkpar.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2icmbpnzc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaglvwh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqclwzwd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vipaeeqr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqepegh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wvstgoys.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rioxylxd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwjzcpx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yttojwtg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fswwrxot.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsgkbng.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrywlsbz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnymwaeo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmwzyrj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2buzhmjop.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsacjcf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wijliztv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmbzdsy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uogvjflt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvzgmod.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuomfkur.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mvczeyqo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqxudka.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqwodvg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjrpjol.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gabetjux.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vkffgmyr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2adjhmlvf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlipukt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gortivlt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2eiggonlm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2azddqjwk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tiedfkaa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtruzgsb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zxafdent.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqpikxy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqrcyob.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsmqcub.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2omfgubbc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2flwykwpl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbqybri.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkfcmzq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2awxxzzsj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgcrhtb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2uykessgg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2obftvtfd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bipmylvf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pndlqfme.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyemzbw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjruquo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzjfejr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfpscyf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpprzwp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vayrxjob.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcqtsgh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcczouo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsjojcm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgaqwyw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cqesclin.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkbjfob.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjcnjmn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2moicqbdb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnwgxpr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhfewqq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtrsgcb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tbggkyiw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2knfkudxy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuemows.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gabygqgg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qmskfzlu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nquladvj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tycwobcd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnbbbar.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqhtqrq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sksnwlkl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cqssnbcs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgufctb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyatqan.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxmstde.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hiugomxf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuiofye.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hsljkuvd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxalcjnd.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhoqmjg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqaqubub.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2eumldrzr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaesrjr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcrgvwf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2onviegwu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qookyyys.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbgdyll.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbodmza.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhpizso.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyvjpbb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjbdbgd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaqdqvz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2djglgkej.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfsfjvn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsshlni.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdkwjps.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyoeesd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngriqkfh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbytyab.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxofyrjh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvfptuh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaypwgor.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrorepmw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jhulufuh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2idvafhdj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2aeijzzwk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arsgveky.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmpndwr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xxklpucg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kopaqhit.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrgmojz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2anebwtxa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2udeheyqo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sajtovdo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2iukuyvui.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2whmvzkjt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxudqul.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrbhjfc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hiceozdm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2flhvcjbz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rezmfweg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lshavwvt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ebppneca.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qebzuswm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpisima.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2seavflhe.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeljmdy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgshqueg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhonflqg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmegrxv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkxcojo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rknssaqi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzktjpc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2siajmcvj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2eaarjzgs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wckrasqr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgedbcl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaszonx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjgpcai.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2glqjmcav.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ueymkdoo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2imtaeknt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsbcwxy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvbuqpu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekivvyqq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqjeybu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsucymq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2aixbkjko.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2omqzfxby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohugmjdq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tsancclf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gewzuyxj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2goftfwhu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhxaiag.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ykajlloh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mvclxcto.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgddnkgp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrhjgan.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2iosxgxrf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aenuqpvo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hodzwlyg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyfkcur.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2odhlrigu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2otropqsn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txjbxfqr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2deyszxrs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cyortaaq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dtodcsqu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzvgfav.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzpwese.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2shzcbcrh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgmebtq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2khizxeeg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxauajo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uoszgapc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uehwqfsm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsgoshw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdrhsog.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvtrzbn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pormyvel.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwgzyad.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2agzbhgsf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uipducik.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2spkrmsws.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xdclmlkt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fowvqeby.html


<!-- 参考信息 -->