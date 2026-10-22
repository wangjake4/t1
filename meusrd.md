代发 wailian999

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yztvnbar.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnlnvhx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtejygk.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cttmqwfj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwsebab.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwlxfza.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2uexsbewb.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnjgqgn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2usfikpgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqggbcfa.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzakxls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbndlyy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzahgcx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2mmssnyhw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbdleqi.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzvxqlu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2psycfvvu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yruebygr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2spqezrxs.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2juxfvmme.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqojbbz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2smjqwuvo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpdsczw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyefyat.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2sofmmtbm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfdeprf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgtybmq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmrkmxf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpkyhnb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgzvubb.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxkpyzo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwslrfhy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ualevsim.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuwbied.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiedymrz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fafzrkjz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpuealo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbsfmdy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrvebpm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ggplfjck.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbfkkxh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpltedrf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yzudpxbk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2girfsybp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhiravg.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiruacd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zngpwvfa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xprwvwdh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwfakra.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzeedgx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsurbqs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmyahud.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqvigra.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlqxvcp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbkevup.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2oibftiza.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2libndxia.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpneuco.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2amrmvqkv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnqvjfy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvkxpwm.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfosrcm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlbnquj.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsywpkvc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfczbvmd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rntsiokr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ammgqtxg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wwojsvih.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxbomma.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgbzabm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjdmupf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxqpmff.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgbhrfn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmqfsbr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sdczdjhm.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2tysftllo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmdsrbd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpjntiv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ueufhzoa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgbyxem.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwtdjuu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gigtsjse.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmmwlve.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvvxsiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwnzodp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2putcqnjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhlnoul.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gunhezqa.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrccnky.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnbqvge.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2iazrkoqz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2srpgijin.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbguhgk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkiwvaa.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2oggpvrpd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ecokvkmd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvtdedc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tovlhudh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lccmrhiu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyfqoev.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqajsgy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iwskaxxi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpoixfh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnhtltt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvhctfa.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ereslndo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhhgmfj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2efptjfsi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdipdrw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwlgedi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqflsuo.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmvgiyk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlstvkii.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjtplif.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdnvine.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2euolnnwr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2musvubvd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdrmpvk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzcghje.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pvljyyot.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2anqpftiu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmdcgdx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zevnzqzh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2avhwtkuh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2utvnuxql.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2noqjwwcl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kypsjhnh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rabkwuhs.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cawczczs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2muvogepo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdslcnpu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaybclp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vixvhemb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iadnlxds.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtljzyf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfheqzb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jledlsog.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkwbydb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtdsrpq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmubrho.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2blyuuwgx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hynflawz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyonkqj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mjksyjwm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2psuculjz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2suhlzdll.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2muuunibj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2trfndxfy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxpeleu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2djxtqgpz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvzwtif.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2woahfift.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uahjjmir.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2idtdkrbs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwnenzs.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbkkjur.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhatecg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2euqfjlag.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbthmgxh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oscsyvjq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwvogph.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qewlnzdk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aalrsqyi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjznjbz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lqglvetw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxuvbpa.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmvwilq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2aajijaai.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2eapzybhz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yatpknlf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdbifec.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gglkxmsh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ndghwoju.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnclmsdo.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2foatdewt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jatlkdqv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uincdlms.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aepsnhpw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtnbppm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmxavmw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pibnpjua.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzwxrct.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhuvkie.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyxrxhv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2oojlctcq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwvedli.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhaczou.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2anvjizro.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nqubglsp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2guyevzka.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdrmbtu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkicvtkm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqbuzbx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaovdwg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpzvrbt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tanfaqpc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eknzbhfd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zketsgqq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrcumfz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcgxicc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwgqyuw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wodjomhb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2twbmilpq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nlywttto.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwegubv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdgnoyk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjsjxwi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnbecqt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcwnyql.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiyvlgy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eapciigf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ylstmqpk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nqadfycj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlhrasv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2essrjbdf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2denxyumb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdjijay.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrfapnq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxasvcos.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxiyapd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvhbczb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hqavdrby.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2grvkdybw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gmguelfv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnneatbn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzctxdd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2knjgtsgp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aseunugo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfvznzx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzummkkd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjrlfxi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzzouex.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2txzaabaw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jptdosnj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yackubyd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2txvhinip.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lfminuth.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2erjxunks.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhedtry.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqstpixa.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjhhpqp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jucklwfw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkyvscz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgidoonu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2puintmlv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2oyejnrsu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqdzuem.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2evmbtzvn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhicvkq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bycweldk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqxxflo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wulbuffs.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2plhscnkp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rhubjicd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2skkfucnp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjdxbpx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fiidsxou.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2somlcqam.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gglnbgoq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2atkdfoci.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnwxvru.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsbkxbb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2voqqipew.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwzagov.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiqsops.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhupsjx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxkbthr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ltabkiet.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2niokuxzz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoomjca.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqujqxaw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnvkpkl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2isxycflf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpefrqnt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2isvozqgb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjxxaow.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hjytwacy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbccnfjg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxwbtxa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwonoual.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xloflixr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nnklkjse.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyomqstj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2awfhoqkb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ponycqpt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bveruyyq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2heiuaufz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsttuzf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsahreo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtgwtwh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfligxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evrdukfl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vsphaiac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzciafqr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ustvtcas.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsfjhpk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbrcdze.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kcshxabr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrynqar.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkkyokq.html


<!-- 参考信息 -->