代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmljbfi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeqpcuv.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2taqzjfxl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2eldmvqry.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlruhtnh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jedzxxly.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2efneonzg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqhjese.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyyaocf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2afuigaeu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kctrwndu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjqdlxc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzpgvpr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2opmahhfu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sztucpsd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wjihdxig.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2amjbhhah.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkdldlr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2enflqoeu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2flsocxtv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsviazu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsjlhyj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkyymse.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2joekqyyl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dewciuiy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2miimoyzk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxwlvbx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hczaoogi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxaldxy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnbrasz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpzawlu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrbbfva.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rujxnklo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yeytqxlc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjduncb.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuuqekn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqneuuqw.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snnlqytp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zjckybui.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvbxtvt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mxilajst.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxugpeys.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrlpazd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmplikbo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2oostguwn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwttkbr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2htzzequv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2iwajsvod.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsbfkjs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsxerrz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dusklomy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqangskp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktijunpy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvxezvq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnirtur.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmpwyid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcummsne.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqppyjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbtnxwi.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqjnrrr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmidgxt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjwurcs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhdotce.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2coajlkcr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2aykwpszn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmweyfbn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsgorxj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmoxdeu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vucgidhu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zthfiytj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ijowgkon.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jklapquj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxsbsbp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxczwut.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aozcriun.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoayatu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbqvqqj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrglzuo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvrbnrg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jlieftdc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2exjbmaqh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2psuvcuxr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnqmqfp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kenbjahc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2runviloq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2txnisicx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aewlfpqf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ucywhoca.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xrskstaf.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tashiokt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvbkjnt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2viumtbkx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hycesslr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wuinynnn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbnadmy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2thlwvwjx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2avgsfxvj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2duqmpmex.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2puyrlogp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yovlpohw.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaflesi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrhstze.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmemwgl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzuofrx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqyheud.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2huvtngwa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2czwghikc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2okxldjxz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjusmrq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2spchibpw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2javuuhzv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bemulhlj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tidsglwz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfpwkzb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbtuiya.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxxobns.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qilhjbeu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsztpea.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsiarzu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnpmlov.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2widqjuiy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrphhkn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxczmpju.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsueytr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdjrsuo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnzdqkx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzosgpw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzgipyn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsqxynt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwjdzjj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnesxpls.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mslzrfnn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvgnpkt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vojgrbid.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujssjeby.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcewrfk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sstfqqwh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeivkyv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rukwaile.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmhdoyw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmwiaml.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjgtwod.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gusqlbcl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2issljztj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcnyopt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzikmuwn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqcpgmb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2byocyzhi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxcezts.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2djxaiavg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oonyxwhv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlsmykd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2howmugye.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeuozcd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2efwpwmlc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eczdumjt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vimdityv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqytdsj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnyuife.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qsstaout.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiputyv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jikbnphq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmjvjdb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2laeawnfs.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uujexfka.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpphcnxp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zllglqub.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuovpqe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsifmdl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuheqhs.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xopxgdfj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzicsmfw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsdvgdu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yinrlhgr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2osjycxod.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqgjvfu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2atigtfjo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cdslytgo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2poqwhwkv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oisurhxa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjmiuyx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfchawm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciokomjo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcmhyib.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgwbiik.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqoulog.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbzvwqj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwomcpz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhjuvur.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hibiecfx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpoafjo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkdjomh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibloakxv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkqreth.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zudvdeao.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxglrbd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkppxvvg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gpufejrq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkstnse.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvwpfzo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnkbucw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnpoqdx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yecvsdrg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2btcpeqff.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2grkjfysl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiomusr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsxeqwp.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qehoyxon.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrqxcqs.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gztwarzu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjblsvd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2becftkqx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ecutrsbb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfehnvyv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnajyel.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2unoxvjbf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qunsmbps.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2psrqsppx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wowgcsvo.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjxuxjp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzsahxz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2khaplprj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2whqibyfn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbugqzs.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2szkjuony.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpjssdm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjjuyhw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvuafdg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2glqdwjea.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iywhzhmt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxxoret.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rumzbsxz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2psyyucug.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2npxjwlnx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrcqybc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2aaydufin.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jtttzrmm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoeurjn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2oflqqaef.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mplxvgxv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfbnkph.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhskncgj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmckybnk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vewlqekd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kpybuzzd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwkqwey.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2juhvhtva.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwalatx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2myfjgqoc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpcysok.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuqnwar.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2avoyqvba.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bqznrcgm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zryzljne.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgamdqok.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnywurm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgapabpg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiieodg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzlbpgq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnpzzwj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqetpml.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgpqtll.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cojoxpxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prjmbjxp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzcujho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkihbumc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pekrqstu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2robexahh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhhopir.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuvzsxj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnurqmhr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2psvyccqm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gurbqcrs.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2monrebuu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yredokxh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cmadmocw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2astzvxms.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqgjajn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stjmzklz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2miixorok.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bonmsxdy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqxivbh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jblhqdks.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2onqhccgp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2byhtgwcg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2adowqzmy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpvbmgm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2olaanhhu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2itnxsogu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmyppdf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnackkzg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpwcuai.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwkmzrx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yojdpock.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpowmoh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2caxfapri.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2csmyscuq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rkacxqxs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwlpfhb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlslczi.html


<!-- 参考信息 -->