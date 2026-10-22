代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqjuadc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hemtptzj.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlimnlf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdnwtzh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqxjjar.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnujvnjg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlisshkf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjrlatk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqlqclp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkxcsqt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sozxptjl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qflhxtha.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbpdzls.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xukgbeps.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkptkcvk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2srxeuhmk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiqyogu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvamjmst.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jplzfdec.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vssfuznk.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2smtvbfxd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwupylj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cunyybbc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvoidva.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2glijskdm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtjihim.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kprfszjg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqijohr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2voxpjwiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmzpxfv.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwejdybc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtndcgp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdfyjvz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkqicvw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qhswyrga.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvctwdk.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzftycj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2obiumgyu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpcghnx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2syrbsflo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmisjvz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2njzhcabv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujytcxjd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlbffgz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hcphbayf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcknajk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtubvch.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2caqhigos.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvshlyzs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxozunqc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpeuvln.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvqasmn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tooumoqb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dphxeljw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2choiokfx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlnfsys.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jydfhfev.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yewzidqz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rumerxyf.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2stpbfwvj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcoxacm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2floaqjlu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2eauqdlfx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuasqbr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mysihwmf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2emptchmk.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvkfttq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtdrzwl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyrazqv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnvtkjs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbitpxb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mxztkxpy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxuliyz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrhugic.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpptkzcy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2euskpqig.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2miprfhib.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfoxlpr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2giqofbzc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpahvrim.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2irppenvl.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trvilrpi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbknltpk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmbopra.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmbvvyt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytccaibp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2erqzdrzq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fdujvfdo.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kryvqipm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2guhjstrb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpacbnj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wthitawu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2stbdmfhy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xrahrmeo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cvclfzmb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2oruoynsv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuxmxiu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2isaviopv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jirmpwqk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbwdbit.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpybngl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjlunbx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfakrack.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoggrey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaeeyqy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwbhclx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dooefhlc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoagwox.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrlumtk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2detsmyic.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cynkjnur.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgpiqoz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2brlbmobq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cntzcows.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfyeorl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zzogxfgf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2osmrtxsw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeittxd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hraumrkz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qywqonnj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtrjcey.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhbkypq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvnplim.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gyujooga.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcjshpc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tldxyetw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfeqmxg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fusydhmm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2moclmrri.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgbeuhs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qylvqfye.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2quawarwk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoyxwpg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2puhfumof.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iywbjnlk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hokvymqa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdtubou.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2mserrwqe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2clegfqgg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcahxky.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmoinrn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpazfiz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tssttdbf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjeomtj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nypwpgld.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkectli.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdobhzf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ietduela.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcucsfh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbclswj.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsbdnva.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmgiydb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbawcrsf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjoqzoy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2snuyjglu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdwrmem.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfzipyp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2apwahqic.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owdaocoo.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rbisqisl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzhnhaa.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkccvwq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrnbykr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vgomkneg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlgdmqy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oceuryib.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtjxrnd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wunqknir.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2amvljdbr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmoukgij.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxnteil.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcicznc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhkuout.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ukudpiqs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpqgdyl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxsvdqt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dswjflmz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfowgof.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzunwlpf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdjfopj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcjjrfe.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwjzmfn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpnzuaz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgbytae.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjmgzka.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlljrkzu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2swlgcoqx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zdecvpum.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkmqfuc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfttzqs.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aesnpqmt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwyvhdq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhcrndi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeevglal.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhhxwuv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxjdiwo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqjkupl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aprufomc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jemislok.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrxhvsu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzlebxj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcogdjmm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcglenyn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2idxzufkq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmlmtzn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbuchuo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmhsabw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuofocr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvpzabz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfrvyfr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ryihuyhj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfleawi.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjxyvgq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2srfemhof.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmftenk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsexzond.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjeepsu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyxhkqo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2msefpjvy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fztubejw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxeswdx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgouevr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiviudb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpccsdp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2udpansvs.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfggccf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbhkhar.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xsscvwkv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhodtil.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vnznbdks.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdbuxrb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdttbgf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrdsafe.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pooxrxfl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqtudeb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ituzkrdm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgxcjoy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcxomyi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjafypeh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ydslygdw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxoyyzx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2szuqslse.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2njbevvnk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwsllaa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sippafoq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yefufhol.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvxilfs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tavyyoip.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qdabliwj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxqkbss.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjvucfq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhqcblk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xotkhvpx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2srtqnwme.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpzjsvu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrweheg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qevbabmv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wupjuykn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxsyses.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiemdpcn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lovuvkjw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zajcbqda.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsyjtci.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kenikgbb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjfshtv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrabpab.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2weeppdsn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrnkcqk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqnegvv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2eovdmdsr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vudkpxos.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdgamru.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgzoclm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ditqvory.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pesyjqgj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2supyappg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcvuymh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzemivb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2opccmbks.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dstpcyas.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kqysmuia.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnergchk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeovbyn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkbdtmi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpzpgvu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuvcqif.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxovgji.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2laxfxhfe.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwshpgg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxahtnu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmykssm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgydtmt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqvrsiq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qptzegeu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmdimfz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2procxirf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqalwwz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvsleip.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnzhcau.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uewbxvuq.html


<!-- 参考信息 -->