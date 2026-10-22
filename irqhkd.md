代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2shlfyttz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rftnueiy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrckdhkj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiadlowd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sznwcvbq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcysujwf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrtxqrz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uixhjfby.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2helavjbm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aikmwvzd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xcizvjwj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqlrwvb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouajjjpz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2iotstexh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmmieeh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yifbzchv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjunqce.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rodrvkja.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2baunfefw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2plzmfdxo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnaszsm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2aoarntdo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtmhbsq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xilprjkn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ltttmmek.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkektfpw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeqtxti.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyhwxfa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2eddtivyj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnnyyoa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stzdpqwx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktywrobj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoysvpj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlinqasa.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmpgdxb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtujilk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eumjgtwy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbrcjal.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2etmdabgk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djfpsyqi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwmtpwu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2twfklhpd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2argomemo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmvgapw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fholrice.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkbpvjx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2skrzsldn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkepndtr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaxmobj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxpalek.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyiwbit.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvjmfoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2towcigbb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2cghgddhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sykteppe.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkooxmy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyodruj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2khdyngpn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwmevpf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lelnmore.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhnvkhc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tekygueb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfywyge.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2prtjlsji.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlnkjrs.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrpuwjf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfpfxbj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2opiwbwur.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2garcvhfn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzufeyn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qudznkzp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hlugrrbs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaizhab.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkiaukh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsijcqz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjymxwla.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqlzqkl.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrqirkg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgwntis.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dmobahkt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnsrbua.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2abanyawd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sghztgww.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cyguqbqa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tregwewr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbzdbrc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yfejpulk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wqakdjjh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2sofjznpz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2oijixcqt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxcceaq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtezemx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2exkyutms.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gluuegrt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2heexgwhl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpqxtzv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hygfpszi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jalfxitw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxjnrbq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tthsfbzv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyjvndd.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnugpbb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjrgvot.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rrknltic.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqxmcqz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvnwkzc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rttkwoep.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkhbpjv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbudhgz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzetpte.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2eagojkgc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcdxjtb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2aamittfx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2splehvqh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2agosqxeo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlrdsjw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoqnmth.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmedcfv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlmnnvm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmawtwi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbrjpbc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hkojybzg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeuajzd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2johdejps.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2osdovgpg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfqogdt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyycswza.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsripet.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eojkwipf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsrzkdf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcqubya.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uvguznwl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iokwrrqz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtwesxq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bsacvhto.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvnfmsj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwauaas.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2euekndrx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2svbodxmx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzbvrxy.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rokqauzy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zexwwinv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vhswqzxh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gimxkkaa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbttgmgb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfogrdkv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrquedcs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyyoukh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqjgiuc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbesatl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2todtdgve.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ughowdhw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzxbxek.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zoboqkux.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmcwjwm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqwnqix.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcauonr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsksajo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aexvkndk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvvagwl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qsotsbjr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bboavgnm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdgqwib.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2enaocsaw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsjslps.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zememisw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xyijqmxy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2aemcuefl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hknmtdgi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mycybwvi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wawjktrk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcjqofo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhtyqwp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2evwxihyy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwwgeeh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yknzmovf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qteeditb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nnccboui.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbetidye.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qlggkwrb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxprwiu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpcikid.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmihwljb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmnsbbh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hquhljet.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lphpilck.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdkupww.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jodixakr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pglhqgpe.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jkulejcw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiutjqbi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zsowxrsk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewizjahl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2phgfkcwm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtslrdj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlogwvej.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdvraai.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uulhycdt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgykfdg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2srlturhp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2axmlwzsn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dakbyrzg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kntgosvd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxpanhd.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvnmcfk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmrzoep.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lurrczdb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nftimyjf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfeewnh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnswgfnc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkybmcy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axqlrgdt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnuwosk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jvshivpu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2icznkocj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsyteic.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkkczsi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lmruhdei.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvzwram.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2upbebznt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzayqlp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mlldkxnf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zbujqxfn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwfqmjf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrfqdwu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwywsgi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2djbbjnkh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxaufvd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnvutzt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgubwyyg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fqstkoud.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cogswslz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jvarajhq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2azzwnwjd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgogtum.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2oytpzqzf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bitfxjwn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfyuoac.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlejmamx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfetwni.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpdafrj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgsjmsu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkvpdwi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvicjvki.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbdimpx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kimwrgnq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpryeed.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvddgtdz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcwcjvg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ahihmher.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuijwyw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbofncpx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jreedake.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fusveflf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2upedakbk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ukglyfow.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfeygea.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nizuvlal.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vognauxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yghkgpor.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkmnzfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaejyec.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lipokeql.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uocyqgnu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nnapqngg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ikprjqeu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdraaaj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaiehkz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2faporevs.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuxnflg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxtvwxl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nztqdzsa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2syyvijug.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzyqugl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujemizcd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxwwlvk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2woepmpae.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eugjacrj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cixtwiyw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxcwwjt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2enudnhqr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xweuqizk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdopaec.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2acmmgiue.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pddgvtvl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaomuik.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztflqxih.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrvqyfm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bytnwded.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixobqizl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2potckbpd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tskntoen.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrhjapn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sojfzgti.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdavomu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpypjvh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqwiqzj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwllfuw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbhsadr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpywwbq.html


<!-- 参考信息 -->