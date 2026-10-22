代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmsdycb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmkghnq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcvrvsr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvklpkd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmbgkoy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2losdvrxi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2synajzsr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cigextxx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcznobv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkfqfst.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bugopunc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ssooiwcd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2baxdwiaq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2goubdgzr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ctarkvfj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2znaftjcl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjtjdrf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwubspu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wetawlky.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxodtnt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsjosgc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2znixnavu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhmnqbf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwmeqlm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbisicp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkuevfb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tehgzwck.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vswzmzub.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2komeasvh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjdjbmm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umuuhtee.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jasuxqzb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xagofisa.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfbgupf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnpocqy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpdhvhv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwidvlx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfhuhnj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kcohbyow.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkunytf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqpyfqz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aazbhayh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bprbzxke.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2emvfuiym.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxelrdc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjrlntn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nhebltsv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpcfatw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjmrfqb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vuolaubz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgtiwbe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtrecmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjesoaam.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2uofhhekh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmcrsuc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gamzjbbo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2papiidst.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2skbbjjui.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2myxurjam.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvthshu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmkymcr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdusuksf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpmlwyu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgwlcrq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpseath.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2inntgvfd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyztcqt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcbrqom.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoxjswl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjbkdti.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgzjdhp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvfjtwb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsvxges.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiyxinu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mticaowy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gglrwjzm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcidtzn.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmavrnq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nagdpjda.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lddkywhp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2abfktqoe.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fxczcmzt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxleapif.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ztowjlag.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlqzaha.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2sfumjaxp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cprokzej.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2siriutgs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yssxwgfz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lflfuiqv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuzcyzt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fugvnoxj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbuwslf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2psnwzclr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyuugqq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzbrggy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2barwrhuo.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fohiayjx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tirhahor.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmqtwdh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvzomkt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfmfkcp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmsanai.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hkiiklhj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyniqos.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhtelni.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmklsxtm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cljlxtzg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjuqody.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnixkve.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofztqtrj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrywzjc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbmcyyy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aarvlbqw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoaheze.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eyljfiyu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyuazdd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2egmcruzn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzavpbna.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ismrgalt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yknitapt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdnwsjp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2amezsass.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxfixed.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2btajljlp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpgosza.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2peiwgvcm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cqblhztz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwfzxkv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sygvjhfc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbitlnv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2krjefehv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2illlcrpy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfixnvv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2quklkoih.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwqcauq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxuhqbn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbbvwqw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2noflokrm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2olzbimir.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vpikyojt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2djvfznnt.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uembxzhm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2juxxjktw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjsbtyk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfizixn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmeohvo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hawwdyih.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cihvwurh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sofrznxv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhghuqu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgfudnx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2msflxxzx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqyyysz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2agyroxka.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ylflngcj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeidoll.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkxssfr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgkdpwt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhzapcl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vucmrrny.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2etfzeifi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmbyqsd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgaeryr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaknvrp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhiqtbk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2buexsyps.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xofrizod.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2biewvchh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpklaugs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgevekkj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaxuedq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2srnxvsvy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tskvxnfm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvqtayt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2khqgpnlv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oitzxknn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvnadmu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhupsucv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwiewgq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfkgnqb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzptqqw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqxkrke.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqosavtk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxqmnqn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeqhnak.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvanqmxv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcrghcb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnfsvar.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbmmfem.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqvvnry.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2oemakoqg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpuhjzn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oeedissi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2neikzoxu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bckuyila.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qkltbcom.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvsghni.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrrcbmz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuujnup.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqqsmfi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lvakoxef.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwauhen.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiletwkm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gajvuquh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmebllx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2meaxbohx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuolflgw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyanyun.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vemtqhad.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2soqublsf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2izlbeqdd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqdngkm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdckkip.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ciduytgz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuszcnw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsfkxiy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsoihqi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdocbos.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnyuhaq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpghxnl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cafbwnny.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkblnfo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rbplolld.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2csguyode.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lssgpmjk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxkxywp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcwrwiq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcutbkj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxthdpve.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuoyfed.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zqisrprn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pndvgmal.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2chkkvkww.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hrotsyng.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfsvgzo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwuwbil.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgebpnwi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzyfprl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2krhlbpkf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wjywrmof.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2psesvhyq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmkheva.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zipnkkra.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2khrbxndv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xihbigoa.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuvvbos.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2shrtmegp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2etcbrbzy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpqwzqt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqumfzoy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbzkdie.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiiglho.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrwxeqj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkukufyw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kiurnpga.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mpojuljo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdnnfxu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sagibfvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krntoawj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkmxiku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqbgxrt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwmvvlg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbhchgg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlnweso.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vebjyqal.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2diwpkxdj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwimidg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnhvzal.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2okjaurar.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdiddbs.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2avnemcqr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nosdnwwo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiuhnyi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzridihv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkwxfmm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2usjvbmim.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyglwbg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2irlygqmj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwhcrtu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qjldsirp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxqtgfa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dsextsrz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gefdtanq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qvukpsxe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsudkir.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aurizzot.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmgqalw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrupztx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgbvgez.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2guvcddyc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zsclpqdx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdohcdi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lygkdbdn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fdblgsja.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shpgbojw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfdrbzv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2akuoocwp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kshzbmcq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrswiel.html


<!-- 参考信息 -->