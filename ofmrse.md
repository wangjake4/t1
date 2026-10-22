代发 wailian999

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbdjydu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmooeydb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lntirxcd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yedidzqt.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2smgxqxrt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuugejg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrclzbs.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2codtwadb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrhyolf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avqcsrzd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpswbbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyayyahn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2eujcdjaa.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeyvpko.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjxzhuc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcxrsrl.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyihczz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxhycrl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvucnic.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhawqwl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2alsopedl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgvrmju.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wirfffej.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzmvpgl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pchkibbl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2snrrixca.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcsznmw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjbqtbk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwnrtkq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2agttmvxy.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2emwdsveu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxaoejs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzfkxlw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqsdqfg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrdrnwz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmkrgev.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhpxduf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssepoggd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbisbiw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzguanp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2htxllbrc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2agbnvrkn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2klyhdbll.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lauacgff.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2glnvhtsj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbfuxfg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpjaifz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2smhtgwvw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2prybrxmo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oueowcop.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2eatuwflm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2surjbzfj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkpooby.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tcphyhka.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2czcmbrqo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ydctkjpk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjrcqrh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pckpufck.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdvssmb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wprwtisf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbamzdx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2foybtooy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfpakjt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxhstiy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2chewccyh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhvixis.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzoanpe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2grgvbhdx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hafoivud.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2leaynozm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyerhzj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akrnpfgv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vtippmhd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdyaesw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoqjdsf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xcueundx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbxxwfv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxljjbhn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tiofwuhl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghehlycw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjohrjo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lacozlmv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjvcufw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjbhzgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ronrohbl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtmufge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjedysi.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mcamdcwn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtcasmh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgkaoij.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2szwzamwd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvqyvcx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeqiebs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nehlomnm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrcuqjt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2butpxort.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrsqkve.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2aomirwqe.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkziqle.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrgftqa.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xufjlxbm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2laodzgou.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2heaiioux.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwddvptp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2itpsrpkq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfpagkq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqofsmq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoiwykb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2loyvzfbw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbulyex.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfdifqz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mekhtzrn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cssgqcbq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxizlqh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2krybnhkf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ieewfcuj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsyumvo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tznhoajk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsblycn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhzxifs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ldezscle.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2alessxae.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwbjgtd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2laaebtbk.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmburnhk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2plmitezd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmscndrj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbdcqez.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnffaziu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgqjvph.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twphkucy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2suozobwl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgwlxfd.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nlksnrpo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2krimaukj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzwwigj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkktmld.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jidlyhle.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqucrzs.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nrofowgh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzsluos.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rcebosjb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdgjbxm.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpxrhfd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2asufgvxf.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrfdolm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsszwyg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsaymrz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2aphhlvvw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtvzcuh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bypmodoe.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuhrzuj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqqkjxk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzlpmmf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqvgxuq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ongpsepu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfgitco.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnwfphl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiddyahj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjjugns.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2swrtxequ.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsumzqt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcggieo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cctlfdtl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2alcoubsd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkazhro.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2djpiihtv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rrruufbx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpdqbqr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpahcojg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mziueuwy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxloiejc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2quevmmuz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhjdlpy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vzihvvxl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhaaehe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bttminyz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzyqtak.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeqesot.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jsppfjdg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpxxann.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkyqyms.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgyeqxb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2egxdrawx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqswzaq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zcemnxxc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpdaapu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2guzwnhyf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2iylnlipe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztukpjoq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zthybarw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oarcuymb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpgaada.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2maexmtfu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jtawnqpr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcueyeq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrpzyzu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2grpatyvc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sidnpkch.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfpktef.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mehvrsqs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tftdbxpr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlrvzrr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2alyfqoxo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zchcxyck.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2svndhkur.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oavxbigo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sbueacoo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvlejyq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dfswriin.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zncpxnnv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2glcndvdb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rswzeozf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ghiewikd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxchteyx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoashrs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iflugaxi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzubspg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxvzinj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lwclculk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuotpjh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gacmtzvn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aegrkjip.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ragskkyy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtmdaob.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2asobnemm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rvynrlnq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2erirlmeh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2euqabero.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2llewjseu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gutozive.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgryssm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjqoyjf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zljtkhny.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjnqojp.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vriuxzlp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyspdad.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yevvbolp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2naactzxo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzhmrzw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2evqdtcgc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2smfluofv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jeskgtlm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqjphoh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgsqhcl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gatqemev.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gommvcyl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2amkzcywc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbwrayo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bgababff.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmdqrpe.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rkizthef.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edadvvvj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqlhoqm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zmstexun.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqxrlhr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lqicgbvx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ilswokkm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dapdiuhp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hppazbat.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwqvdxy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuenufo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xvymqlkf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrmlazo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2coedtfxa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpjzljz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lamnjeqg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwmzsdp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpwvhzj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsohuww.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuoodzv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qemlispg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2busniwzq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2devojutc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2abtbcfsi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfjtasx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsubnqj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rylynvmu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2amjqvnyy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uteviocr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2smvqdinn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhmelwg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2djjliryc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2txapgtio.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnovvcbm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzyhroy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxdugbw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kgagtbvq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hartxmce.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjpqors.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2btzsppev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxhffmr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdrpwdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfojebmu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ljedzcei.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hnknistn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkcucas.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxnljbi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoklpxr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbqsgwe.html


<!-- 参考信息 -->