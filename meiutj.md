代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2phphpqaw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fztzevne.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxmqegh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sabthgec.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrruviu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwekjuo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhlxlem.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpmmuxi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkkztpo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2untxcfcn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lguvnplj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2sekcxrgr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmdicfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwvvpkc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfqfxcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvvkomw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjxpxlv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wjstdlqs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvoxgvr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyejwcrh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrtgauc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2irlpnptd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2leythany.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ponqfyjq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fymxcdzh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rnndvepg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqyapej.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvldbvw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrjvegt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhuttbx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2olxqzzhs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbavolwz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgddooze.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgcnxbf.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2evjkqfpj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2syvygycj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqjkfkq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwtlkat.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hghdovjj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaszbclg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uivsxbec.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoduhxcj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aylxzllw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbjkofw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2llwzylzk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2oudnsrad.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyxyejz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzwtlhu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2adcoczqy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqarfbbb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qzakjxms.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cuybciip.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxlcmwc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2spiikjwp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxkujqn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzchtmz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrpkrop.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvwosxs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrbbmoi.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yechymcw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxgrrra.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaevafe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmsgfic.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoncoyq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmyfvhz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upqdqsxk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iixfmqdf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tblvbnii.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nywmjemz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2logkxcur.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rcquyuvw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2aesyanvn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yktlvnxb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2giylyamb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2leefnspb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqjcmji.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnwnevn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rellurgl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpbkxyk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbosxja.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2anbmxmec.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxixdzvz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2qvukphvw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgoetox.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqepfvf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2euswxrhc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfykbct.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2aofhyfpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtankbsh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2irycsnnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxisrak.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuqchda.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zzumsutd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhfsovl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2csczocph.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hamxvccg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2osnsnvnm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2grptyddp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnobuxc.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lndblkpr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdngqnz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cqciqnpf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2eszeaslu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlncerix.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsrkyzs.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbehtzx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgswmev.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kigpyiwe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2npjwkbpq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvumozkn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbaajhr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zifwstqn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjhmyws.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiyfygm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oykulcye.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jentdtgj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxkgvmn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2igsbiogi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifixejxc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuxqsmp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlpqafd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2txhlpvpz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpdixbr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfmnbka.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaivtvs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrlzxvc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2giayzkin.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lwysbyyl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnisemny.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxujcnz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2oknvjkon.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iejpcqnu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxlhtqq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hihqinrv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrvgkdy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gdahxcdd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xenjzsty.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgfdqqh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2huryfxji.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdusivs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnisptmq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nnelwjmi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yorsuxyb.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2olpgrwfs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uninfqsb.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qmftnhdm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qukngfck.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2aycjewcw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2huwwbrmg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwbdenp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmywdfn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrzgnlv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkcmpwe.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkuneqj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2byemeqxi.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhakphpd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbooxrx.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhpaphv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcxbmbw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aajmbfvs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxfnjrz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2thzdbuxl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxqjimr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzsoxln.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaykbrg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iayazyfa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cptnlqck.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzkrdjo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2izhptccw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrguwjv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqcvlan.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjeicrx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhrraqe.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmkoynq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqjkjyx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vybfqpkc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2egvtehha.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfffebj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxurlur.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnigjcev.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2noxudoet.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2geysfrcx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfbeksx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcbfold.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbjhxsi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2crtilgbv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeuuscp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wgutxota.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqqvsth.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ricwwvqm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypygmzuq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wylffpkh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2iahproxk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2shzyujjq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvsluoq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhmgxjv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lntielct.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwurlcn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2orzvhalr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiyykkv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhshunx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtqfmba.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2exwumjxx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2htlnwiaz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yybzxuml.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhsvswt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcbdpkr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fsztmufs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhzqkwy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2etdueszi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtisuyx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnpgazx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2veeipjzr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwkjgud.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtvgstl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2utvvclog.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkinwut.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cagsyzpe.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2stgouswr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtttjjgr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlonmjr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxuauum.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hilzxxfs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpmjwnz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjeejja.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdjzedb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylarrzyf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzqrgqw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2llsxmtvu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2voksebrf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qndrtfir.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzwaeve.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhvwjje.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyemlyyg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvpihuv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2phzczcxn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfjoxur.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rckjhaay.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdfrzgp.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyyejxs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2onyatrvz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcwnprl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkqulxw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2osmopdou.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2egfgogvv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rijonyol.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sodxeaar.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvwesoh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrpchxx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrznvri.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtlszuc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lciqfqtp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oijfbfje.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zkblzqws.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcgbizh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bshrlmsa.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2swaljltb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxxronm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tzofwgqw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqvdslc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpcnngy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwdqneu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzzagfm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmqngef.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pltyleaa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hskrxasm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wpltrefp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2spsczooi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeayaer.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzwziwx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ohstkyss.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2oihihgbo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yuahyckk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfjmmre.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifamkgtx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyuvghw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqrczaa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aobhuhqt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuohymw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgztydq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2oepjdutg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2spzehvfb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2oljtaoji.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kndbulyz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2spmraktd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2euwfkvnq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bctyvlav.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhtbupf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjfvblz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pukexnhe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxxwszh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pjldixqj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2faagppze.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2liudqdfu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnsrfoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2repxgudi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2unzngjps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnoudur.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxacaki.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jejnmlwr.html


<!-- 参考信息 -->