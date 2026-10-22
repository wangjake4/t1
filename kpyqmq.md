代发 wailian999

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2votssznh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oddbhdjc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fimlhmsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzzqzya.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvjqwxx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2afaznhul.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vfquvpxu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcwvrqg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2taxtndnl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aicalzdx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vinewazh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqogdjp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygftinje.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrcrkmb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2emzavnfo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pniytkkk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bcajbohg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhqvzyk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zilvxxjd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbejiurk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqrddwk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmnidzt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pwajjmqr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbbdbmn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2wijjncqs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpihyjsz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wldwjbhc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkdgqdi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwwduwk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrzvvdh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlcdthw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2elxnibob.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2utxrsbgo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlqgzry.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2miintnpl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nrohojuk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvessjyb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xywgoara.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2perqrbxo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzkakcv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvpzyqh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xamnfqip.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jdowjgyi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zhczfauz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqggotf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gkltgaip.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2snaygfbk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhhpffn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpeexli.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kokgniqq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlcrfet.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxkcixo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgaqosn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zornmzog.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nelikyrs.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbdcqjd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwejjmaa.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amagevgk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xruewhmu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfphggu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjiqnda.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxwwzqk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dihbepwh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2knbcdpfx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2knjydbrr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wstzvwsu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aihrgzmj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgktcfp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyfskgl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkjrbjp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpvhbeo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxjndbe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wynktssp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtnsejm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcqssmf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2oromtfkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aanzdwcq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2edmjrqwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xskxwspn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzmvdis.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2nurjydfr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtcwbsl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lekhvnvw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcuxsvh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqhrpdr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2blsoybyc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxzhmpt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vgggudku.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lmusncnv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwzumre.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgtclyf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiqhkix.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqpfbaq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqlxfmb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbetgpaw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vavmdpcz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbcceih.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlkdmzq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2njydxlri.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdermhr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bycvxjry.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vblhdish.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcwgstv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhmuqdi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hphxvzuf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlckfqq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2awnlgllk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2agtrkmju.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxfihhm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ubupklph.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwtxpzu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lauqjhsb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wshwurpy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ebygtgzr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vdapyzkb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gvasfjdy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2viyzhntq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhojsdu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vostsrfs.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrrpqaf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpmhddv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpystoc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhslvci.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbyljpj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxqevef.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tslegges.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrzizja.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jltsbkwj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfptprw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2murgjqaa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeeyfbd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhuqhdm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfefanlj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lmihyrer.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvqnoll.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzcshjf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2skstqbif.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ursgpuja.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpviore.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2emofrlbc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfxgkft.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqlekzd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lddrflnr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmdyyhg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyvnlyd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gvouqvod.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrtjnmi.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnanrck.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxxidlm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvikzct.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2chvxsmpx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2riyvdzri.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvceiwx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vofwthyv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fihgipoc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzousur.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbflegw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2etvvnrpt.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjubrws.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhysyta.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxjnltj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwdsely.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwbifyq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2laxjrblx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nqugnoqa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnksxwr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzdrvhs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2knyypwks.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfuzktv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2inzcqmdo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptomqzit.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2oihiivdc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2twrwriek.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2igpklwlk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2enlntbqi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tznntfoe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hidkzoba.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjxsyrl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbheubat.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ukouszif.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2urvokdyw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqegiqbl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2shzwwrft.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwwygbb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlcakht.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcwnirk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pwohfkvg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2icnheyzm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwbswix.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjavxpl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bfomprbg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqsuwxg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvfirpb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvdnfgd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2badffdgz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uqusxxzk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkgdwax.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jkptgtbx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qazwxkrk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjuuamn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuxtsar.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2viqtejws.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ormopbna.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpnjfca.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2slabbckh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqkdafb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwxoxes.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfmuwha.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uphfpajb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdjihth.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gulbdeez.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kxttxicb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiwiqsy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhptoby.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2faijspom.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wajoascg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2flmvoepl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuocmqw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2neryosia.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmakwehx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcggkfj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwspdcs.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxabuxe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwfcsla.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eivcrirk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mugwommr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yshqxhnp.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2utsdvorw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qewvlzuy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukljkalh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zksvfayd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkckvqfz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvddkts.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbavrvt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuuhppa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2npkurjpq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lphrmetg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwverew.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjlpitd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrvkrzd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuawxzmz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqbjcag.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbnkqxk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iepegciw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lykgrvjn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uvunnfkr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmefefj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhlcjey.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2becuboqk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qpotzcei.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvctvcuk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2aoummfts.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyhrmgw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlffaha.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqkdtjv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsdfmza.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaoibkf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2grrqelcp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkpgvyq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hqntksli.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wclbunkh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dccccafe.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoenhfe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvasfhe.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xyebzpno.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjhvzzo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2awvpqkld.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bntoparn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tpecheoq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dojzyaap.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjemjhu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uackngbe.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfbdhbg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2moswxnex.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2esffwxuj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjodbyn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zggahwgl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2krtyrwry.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhekxuam.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmispzn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oesgtscg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iifexfsr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bathegyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eottbmro.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lirvkzrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2roviudwt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfhetlh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnnywpb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcifnzg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2proxoivc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ancxdoxx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgltpnba.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfqcbwc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kruefpdb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2edovjtvr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlhuvom.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbougtxy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkcgpcp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrervhw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjooduxe.html


<!-- 参考信息 -->