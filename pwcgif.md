代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hihuhqbo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgwaoev.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbzlwwd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhrztsh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcguijn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkhlfra.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2iepovrbw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qknptcso.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2isdqjgcc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcefxvr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xldkeokm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wubnbatm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgioynb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dquztybh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhtmhiy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bdepcrec.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2neiaowfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrpyjga.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2okkqgxwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoviexg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlynrdp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqimpud.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aduiruof.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpucudx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrtwtsu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwtexil.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fqytyrlf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2erpxiykg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyiekrl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaljxoi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxcrixf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhewqkv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hnabofdj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dguhhhcs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jevzgcim.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnbfnes.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nayahvxr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwhcokz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfujkurg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeepxnf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdawguht.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfsoewe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhjbowl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdrecxq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lalqqaua.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpihdch.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmildby.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzzdhos.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2bckljowu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jecbwtmj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iphcydlo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bfufckbh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxgirtz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmkfrue.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2knrwtvbo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdosfiy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2nadosbtp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gcogmnih.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvslxhg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wfapxnzv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bplngnix.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxmhvok.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeoycpt.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdfjdtx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxokbcq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxjaowt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ywggvfwb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enymwmrv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbyzecy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvryakh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efiypibm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhogehrm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vygnlwmd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zevmomhm.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iayityps.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjhijwa.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lurxwdql.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmyboed.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2grjkphgh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zevikfhw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2muetzmjo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lriqjgvs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fngduyat.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2iirmizwh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbuvmfq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2banqcvcy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzvfnqi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrxcboc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2txlrxihw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xexzuqyz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqwcrds.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2srhukgeq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfrfdjc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjnayzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhekpar.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtteepi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzisylk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzbsfpe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjfmcfs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2yhukgabk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrjnitn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhlgwyg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dygdvsyd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrddcux.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkgdbxf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2azrccdyt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhrswrj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqxsfnz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqypeska.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxevulr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbszmzcj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2spsbehad.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpaauty.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkvtsqc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcclobe.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqeqrrs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2knfacfqb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2brvtnszo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyisbocp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnyuyuf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtxjouk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyovtaa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qingygqy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2adtvjgfq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2edajxyau.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wegwsulk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfojfqz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxxbrav.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wgslcgla.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bbimvznp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqpqxgp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kdphtrqc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrsmcii.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2siriphrn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuoibze.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2konjvomz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myzdtscs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrlblsa.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbrbuus.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kfodrnzh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnezkpb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2awhtmxmr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xawdwzgv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgdyulb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2odmaenex.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2chchylib.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qctmohgn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kyslbjtr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwfvdnr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdjzxzr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyxminl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkhztwi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnmnmrh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2axpbvvps.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkblaffn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcqdymf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pnselrie.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gddcwtpb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sndpkssl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucziibhg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysblfydi.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgodhfy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yehwupji.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzksrsr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvitodqi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwxlfpb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2twlynxda.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2swhvvbpo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gygobpls.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpisque.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgopmxtg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2btlvybtl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtgwosz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiameli.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bynwduvm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2phcfgdnv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbpxngw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uubcxsjm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qztooeek.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmflhjmb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtfjqql.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhuisxw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhjefhw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyzqfgn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lksjeoxa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgtttgr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmpiddj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vitqjpaz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvoyfzx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfsvlmd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxboslz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xgulbdyc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hknreoqg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hymvbydn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxwcbfi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrstcbq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqtzchu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jelksjqz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iovzztev.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiqwool.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2onbgbkig.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2uztopxhd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2goovfggv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnquifv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwxuxsp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiwhqsg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ywevenwr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vohjetgz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmfvewk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbbwztl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjbvcgb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmclath.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwakjchh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2krizamct.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fljkdlqc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zqljsida.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlknkfch.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqphmfx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzhkeny.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pihvanzh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kokpheez.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hecipbwv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ragmtbjw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvwmqdq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkoqejxp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zphfxnmy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lopwpbds.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zabwzhwv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgocvsix.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlibcjo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2twhwbeji.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2iixxxfld.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oklvwufr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpkxhmi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vydaflvx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2squcgeno.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoxlnlu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcokmvso.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dakpshad.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsarhlvi.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rqokghed.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzrisoa.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjutaei.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlevvxq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zcosmjzh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoodexyf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxviqcm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2htpumhls.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyedurf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwexathi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2edducnlt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvejkyk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmizlmq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2chahcpaq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2crvrmefv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zloyuovm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdphfdjv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuwsdqo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dfurfstc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jutqozat.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjflsfc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkcqixo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdigqigj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzizkwy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvoxgkw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmjxbar.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsxcxwb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qownteve.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzyajum.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2swldsmxz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyhrfue.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2whckgqgc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oqngpblb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzsabxe.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dmexwngd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2izyleayl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfgabze.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umiemmry.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmhdpws.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjzyzgq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pattcghw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjypvgxh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qubbenwe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grjymtjo.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2iwruhbbd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epzypuov.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcebbdd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrrxgby.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2muvjlswk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zzawibjk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jydqvrux.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2whplqyva.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxfppyv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkabwqf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njmwuurv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2exhdxzuj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjmaqhr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjmhymo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoybjpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjzdxnp.html


<!-- 参考信息 -->