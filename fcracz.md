代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfignzcf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzggrsh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbtntrf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tetxydnr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbixgwm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxnalsj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2haidnypu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsprvmux.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwsjzlu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbxongz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhksebl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdxlqis.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbliftc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwwnlxk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pwctsnvq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2swwkwtcs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2phzeeagx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2awcclruw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwwtohe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxdtlvj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bspnhems.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2puesthgt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbbwejr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdqorgt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2evrplqgw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvgqwai.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wljvaxmy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jeazlxyl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2guulbmnu.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksypqasu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2irbuxijh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpaingp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mnagihge.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oglqrqbv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfuwiop.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2oocqtwom.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgshufxz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tocdvunp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2torxfzwh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ynovvfvd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bngizfuq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nohpwrtr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tgteoigs.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spcdjyto.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2synemxnw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erkeydqa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2manjhrxc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoqfblq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2yglpyauz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjhafwk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lidamwko.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2pddnbuve.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfpujtt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xczjbwmv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgywzykn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gulmtejj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kbreilbw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ahybilpe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xytfccha.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2pduwtoeo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpzbmsu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyyrfef.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2lajmuqri.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvmeqhu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmlduti.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqxcdrh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xldnpaoy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvybltz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2reaaulhw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2sukzfhlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpllrqd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2okevrngu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2fbclrbcz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuufsiy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2oilpfjhv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kswqmfja.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2aficmzet.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsckqwcv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ltriinjg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hilkcuiw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuoekki.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2brrhmyde.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbsephc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjuqnet.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fozkkyae.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dejlndjx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhhrsir.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvkgipy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2taplsrvv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeqoxja.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouowlqks.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdjrrbh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfljpbcx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bnepsmsr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkoieut.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbpwwqc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2viuhecth.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gibwirvz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxdoilh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrrnkfh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lewzxkoj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nawrcwks.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ritevxwr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2puxnaeww.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2eweshmod.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmsozhg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2oximthzs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwzjccp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dofneemk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gybgpxeg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpibpwg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2syztlnke.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrvotfr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pauoyhha.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwvpixr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbnqlls.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2puvedssb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qofgtouz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mllytjem.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2apqfdidt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fepbdofu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2axrgocgu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzaknfh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrowxrp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaegjwyj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2axcjhfdb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2uayfwbxh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2sepmiwzz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2petkrsmi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sacvkqgu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2olblfeci.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bvscxhbx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hflewejy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2faiejavc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trbbdcmz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2adsjgjfr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hggthqzu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwmcjnx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nguqzqik.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2shzvheaq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxexxkll.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqwmnyy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eckhsmdd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpynapd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2inlcmpja.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuecpnw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2otaxwklq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtseqfo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sihdxjtj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzunvlz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2imalbaqg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2criytnoi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mlocqfmz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvuzifx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxyampl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rniyxuen.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2njmbeshl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zibrqygq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmwpxtq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtmudhl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzobwley.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnikxjtf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqryznff.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qibnbmck.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyhklmz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjiibxt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2catpmgoj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiiwmfb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2epwkcobs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtordqj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmncuplk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwihfcc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqnmjhz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvymmav.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2evptgnaa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmtnpud.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvgdsrm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2uznfrlpu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aoarazqn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zetlhzaj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kuorious.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrmvxza.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2suxvalaz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqmxjcr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpievxf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2siriajlj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlehzope.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhhmjgg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwdpnhn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2euiacmsn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2abbhczyy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tswhjvvg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifojcris.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2inqezowl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2peezkpce.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2agbyousc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtifawm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsvfvwm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mltxwbkt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzqycft.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojexskhe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2liyqnlel.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvhaphg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhhsvlk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdpgqmq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nrofyjwe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqirhrt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvtmkfz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lslvxvbp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2efnipdwk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbyzczu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtbgtix.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2znzcyhmn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmelkqo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzeendv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ossjghig.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpopcpq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2udghdnqx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbjxrig.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcjjkip.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xryzkkrm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtehyiwh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeitjwd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcbhfzn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqutfve.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzxhxyi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wmutmxif.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mobdfaha.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgditiv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqhnypc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rstuztmd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2egdfxugw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsmtfco.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxaprxr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhceqhn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dvczhcop.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzywkaxu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2flqclizs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwkkrbq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fejbbzyn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dzucnutw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kutwykws.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2viufrizb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlszbxm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2szlnawph.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqswxnd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2quvisjkh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbjgzyb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eweyyrxj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2szfeeunt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqwwygm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfrxolo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqmbtfc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtwayla.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2huevlsaa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytubkhzf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sletrsyq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcviuak.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2illaofmo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngflqzxk.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjwoltx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxozyjkh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhuuske.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2axlrmrgi.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmodili.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyqnaqp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wcronvqx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2riedpgig.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2njgbguih.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hqasawmb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xybajgmt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaumsre.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwlhtfz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyzifwm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmmkjtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdufutls.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2umbrirks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbuukrj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjkpoxx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yagacdvs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tdydfuhh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2iefcipsb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkggvalh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxglbpcm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvqkuca.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcoceum.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqudceei.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2syhglsfk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2espfesiz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzmzfvw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akjegbik.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoqmowl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2krvudemb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ockaxkfs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eiauitjx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ketpdmpm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dscmuevk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjgzkgh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2brcsxkyr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvkmiga.html


<!-- 参考信息 -->