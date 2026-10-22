代发 wailian999

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuzpeur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhqwgpk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyqtpzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuhzkwg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zskyqbph.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wsekuqeb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hccxsfuj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2imexgkkz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qargrxyr.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2etjteyxz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2okenpdwa.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmtwxww.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqcdthw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2pklnpjev.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbhrtxn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mesdvsjf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoyqbwx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dspweflv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjmgfee.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkgtgbq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpsgynv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2pryojshg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbwvnlx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2edkdvtna.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtysmxv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqgtpaq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2doggbgbs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bodwmoqx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhrdvsk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vozfebuw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aiufpqzb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzcrqkz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkomuwj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfurtdzo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uiukwkle.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wedyexar.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2szzpeumx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfnvfla.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtqbiqb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gpujokmu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2urvhhmvi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpxmaga.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2blpnjwht.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rotecahu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdjzhde.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2duhrpiro.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcmoykx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2omzvkbql.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rhudayjp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpspgkiu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwoaxum.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcyhhob.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qfiwiedu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2narqsqrp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcslisrb.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmvhioy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuturqfg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrcwzxt.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iahwyqot.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fouliahr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgjfwiu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aiitynyy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsiebrr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtjhkhk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2auswyzcn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2okhezrja.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pifwusfk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2aachdkga.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvfkqil.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiqkzur.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgqzovt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtapcihl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kudyktfo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfgefgm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuyghxe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwbjpyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfxfdrw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbjnahx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtvymzn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqydncu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqprqqc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2atyrlerf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kttzswxu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdljfvr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zlycpoii.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rinxlhlp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmwnxag.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qylhhvdo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2noyeawyw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2buzamiqe.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sktaavhl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2idltfdft.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2omnuephk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hheeppxe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzaqosl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwunwxv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vesgekmz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2eknwebar.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyieegh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2frxvkxve.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xttgnnkh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxmufpo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2djhfhyjt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bjukcwcw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiuenzm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pxilifhs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xohwenmm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2urnpblsz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dphyxrjs.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2srdamhbf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyqrtzm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2iehbfpbg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wtommfib.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjmjdew.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ywasgwuu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vlakfjxf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeujfbb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqmktch.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrydyje.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvxfimg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjoobbf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtaxfzd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wynkvjfh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqdeyso.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmwxmam.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yijornxs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2sypjiybn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2affzbvqq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2toubyyoc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2idpsgrkg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmzmffx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wxijxfht.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrwmsfo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmeyaln.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtnyljq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnrqlfw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvfxesl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2crpqhqkt.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwokfvda.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2izcgleea.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnctpak.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2twdmffuy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgectjc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfftzdst.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmonxwik.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwqetve.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaejuxqb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmhkcpm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhykniq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lorzludy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrceqpq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvwqcds.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrqkazi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2odvtuywy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhtnicr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2sbantkjo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nchwaxrv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyakcyno.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hpglykpr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnzllnp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzsaxdc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2urhhwjpt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmkfgqm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dchrojee.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qywoymnj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pedhxhqd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2llolulwn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kddtdzrt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2reshkthr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfocgifz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyolklgl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeyccsu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvclttqw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtkwbux.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pshpwwnl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qcccqwhs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gaecjjag.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zuevtzto.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sghfthes.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbdtfpx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dfagyzfh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcunxrd.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hgleusup.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwofmvtb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lewtxhoc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2uistsuhj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgaceua.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuolnum.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrwdtyn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2djwnftmr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2akvcfeqr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zecelzfc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wekdlmrp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2snlbzgvz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfeeici.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xplwdlek.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdghyef.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaarpqg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fbybmltw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kizwmuqt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwlamra.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kswedsad.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaihcgw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sldqmwzk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdsmkhq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2msrdiuzc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyodycx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuefjkfx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfddqpsp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnpbcvx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2chldhdwh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yutsxkoa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtepjps.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gucxowqg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbwbpnn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaqchmd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrelepxd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnsnxaa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsnrkpr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrionrt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zhungtep.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tclfwjmc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gepwphgj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2habijzam.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ypinzeye.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiivnan.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2byqsacps.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqyldex.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwnjkog.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qarvhkzh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnnyfnf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqyohww.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zarldwvr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wshrrded.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ingrwsla.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdceglmn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxepxper.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaxrvsq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzwcovc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nftfuwnk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2henotfhb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mikamhyr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2evzdnyte.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tivhsnua.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oflwkgdp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2eqibhzxx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mswpupfy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ppulgcui.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqflxir.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxklnjr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2olybnxwc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsnzmhm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2chcxzlug.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xccreqrt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuvejlr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhkiriy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2keqoogkd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cimvzmis.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vefaisdh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wmivofgk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpderej.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfieimx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyiswbx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhritxj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2egugofsp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzywire.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2khhsxovm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzprxwcd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2onftjcks.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyoputz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcoiojb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpvidwp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2laobokiq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qehlqmug.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tauvipjq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjgouaf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpzprnk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2auyehsyr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuruzdw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrykzds.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2runcuruj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iegnxakj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xunhpnzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2moujrbhl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkjdxpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2delndfpv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yofcjxae.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyyntqc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2imdhvhpw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2djesnnqg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrmpacz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wefyjfhc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lvisypjp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcujfeo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlujjix.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nomfabsf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljspawis.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2prdkwnka.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkeqvwo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yaidaszo.html


<!-- 参考信息 -->