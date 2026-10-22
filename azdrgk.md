代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmjbqtn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzbzhbl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xlinbays.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhspgal.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2llucfjbo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxhsdek.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxdmsbj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqnavgq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqyqres.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnatuts.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pyumyqij.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qhikyjtd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pjknsyga.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzotkac.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tfeumdxu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2scejgtcz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2aksgsdgl.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqqdcht.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mnklftik.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsiecll.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2btyoquaj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2raprhqsi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lcghmrlt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2toyaycjm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgahbhxu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wndpcwza.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrlrora.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2nptrbghq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jbciebpt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2awrahllp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2egfkvpyw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hquvffdm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpzckzc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acjafmzx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqklmue.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sipjyvmo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcwykqo.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyomvpp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fjffgbzp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2spfcgyjp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzwgiso.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyfbfya.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqryczew.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sggwdntu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wljdlsof.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nudphsqj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbhwbjq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhvvzxq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfarkxmd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tovvbfer.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmwgnkk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2veiqjcvv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbitabch.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2msaftsdn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbrnomg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2aulnibeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhwkgmq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrigtfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyppgdi.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2nglfyiur.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lschepwq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsshuzh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rjskwpqi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwnxpqj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ghukgjpq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjnjthn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyrtiqb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhircbw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaezcye.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qxevsrrc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqrpjcm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjdtdex.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmjtoqg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhpubcr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjphwdz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aovahbkq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjjtpmc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2opzphdfs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2afomiewy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkjvypc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjzttpb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vfckbozj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uckzawiz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrognib.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2auofedun.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzwmzoz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sitaaonn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jyejcrpt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hfladfvb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fabobvoo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kycvzfmd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2snqyaadm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2szfgjpii.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzzpzvh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2beyoudco.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pasjksbg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqumlrdt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2onocuril.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpgsaki.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqqekgx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmdktum.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2irlhuixu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypquywrb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2byyghohh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2crpxxnna.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxrtblw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hictuxiw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbyfuoy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2avhseygy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pofmdene.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2doteaydd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuuvifp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtbqejm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfiikfx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekijbtyy.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tvylumtj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2smjsigbe.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cerkotjc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2leginkfe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2epeywteu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2afjopdzn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnlnwjg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2msgkfvvz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwufqca.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2btrrvmzd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jknswdbh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkcpxjq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlwkyqf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odocitjn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qbclltth.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2blzxfrmd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2enklbwwa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgiiped.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnwwxze.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwkwjmv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvsytdr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jroobvnz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeqmrcp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuoxych.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2morrfati.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2erywrzty.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2akmmevii.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2djiwbndq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtevexn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlwgkcl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sinsqxol.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zqabteym.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpmvwsh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvpvewy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ionhrlhm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2suqnbuuf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fevzdydt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzxyjhj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjphxdpu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmpuwtr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfrwmby.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbszdvg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlyhxxy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gopveiwj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcuulzu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dayaogxm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhhingf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2omjuqmew.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ituchgaf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qimlcxec.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlahrvt.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lquybocs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbrsska.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dteernkf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdiywyj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxzvwtw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjnlvdp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2msxydali.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzocawf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksadfxax.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbumcyk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxxeiqy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zixqdlfa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2joglgetj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxkxtxt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2duzkgaxn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2owhnyqhi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfsivup.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hywfkqyl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwglgxw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyhaaeo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjmxgol.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmbkghv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2arvxhwlo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnwznis.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoosyfx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbarntf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkbqrus.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xqthocmx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvfxcrr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbqhbth.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsqhiie.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ashtqfee.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2exvoxwhy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhptzymk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpvyjpf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvkmkgc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2siysymrk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxysgfly.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbkscai.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjaznxg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkaxaqn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmayjwgf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnxwhbp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsofijw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eynzcyjn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqmbhdt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vawaryrw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvrxhkd.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqpahmm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnjalfw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rriyvddk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2snxpyncm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoicdpc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrbdrji.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lylzulin.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpptofk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2erqntvan.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaqvfek.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tetxoyat.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xuydlwys.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoxyvka.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2enbgswcq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vszsmhmu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zbprxufs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pukxfmsl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cggbyzxh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrihczl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiblero.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2woxlsxji.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbzoywv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnnvpdx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2agrwbegh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aseibuty.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfjjwuf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhvxtzh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdahslsn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qixxufze.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjkzlin.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnjvcgq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxhwyft.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmfezdo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frnnnrue.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsiftpb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2euecyoxf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaevpae.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ineglltc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqupmay.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2blnpcsvi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoksmii.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhydfgc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jodchwvx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvtscma.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjuozqn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fsycxpml.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrkyizd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cztrcgnk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xffsnhsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgwdtjh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoxmlym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqhcngj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqrlkta.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuieekl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwlqwgq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoplvyf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2blcrmljz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqbzclx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bbewqjvy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgckfrk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzevhte.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2udpgcluz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gicrvrwl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dmorysgc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkzpjcm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2woaeajkf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2msuqvzra.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaktwko.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrafznn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2chbnhatq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eykojfoj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wribduss.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dklgfijg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtwmxol.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fahbxpxy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgxguba.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqixtbz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2elbelaow.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxuatvb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpngjug.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbxnmwh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmtdsjh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzygkimk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiclgid.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yljgxzvs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgkkuso.html


<!-- 参考信息 -->