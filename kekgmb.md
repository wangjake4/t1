代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzuaibq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsgmrew.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2naborudr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2iciukfbo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vckgxtts.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgqvyvq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyybivz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xniccgfh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2olgjfdnq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pxelezrm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udznkill.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiljwjz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwinevvu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2pkimclzb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ododovhc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqulzqf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtzrjcq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpffaqcp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxhsksv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnmakah.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjytyjo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2njtyhwrh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zldoffbs.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2smauyren.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2smwqjjbo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lbherbqr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzodmbp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2yqprxzbn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jdraaeer.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqqvvct.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eratwvwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxudmlr.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpmoadu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpzzvcz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwkxttk.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdcfyba.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2glpvorsn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjkxqmy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lddzmqbb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2harwtryy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2njvyqzog.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bennkaid.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsbmvag.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zasyaewr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2eijmwhuw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxokvrn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2btqhutmh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fisexekm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmkaymy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2eolsxlqm.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hrucysrt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fodzogjh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgdhrdb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojampizn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqwhxrf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2edvdezmc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2waevaaga.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mifhwjrq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tiycoeqh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwliesl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlbymem.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxdaaan.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtmjisp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2srzrpkue.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcbqikc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmkntoc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrwgzow.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgsinav.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2qatosglh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bduonbrk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjggypg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rrddzvab.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wciazymm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2udgcbfky.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nytzieme.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2grwuqcnc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bubibfgz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxgqfiu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlbtmmi.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apfuxjpn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuznhut.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sikhebdn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhczioe.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwfvmes.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqvunrb.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flbxqwvx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hibsayff.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2uujhodep.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvimygx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2agdmjowi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2grjqwvtq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epttltui.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2asslgziq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pavstfpk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaohmjx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfnqwpo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnianvta.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkztxnyc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dssatrsu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuffnld.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzidguy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2pnordftf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2podmitlv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxwsejb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkhewtn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2atsbrjuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shujtwwy.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqwcgem.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2eunaanro.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyhcqib.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2onijwrsg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuxoxyb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvycjzf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekooxbvk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mdifuagt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2uirmveaa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjdwgaa.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eessppfj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wefogeso.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjdesvn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lctckypd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iforrwpm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmerysqt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsoeuhc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfzzsjd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgwzcqd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2boihhdos.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ersbkgtp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuxjwds.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wbctymmg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eszohhid.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxodntq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sranwrrm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrlltvw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxevkrwr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvoiotv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhtrgie.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtlpmrn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aiencsqd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jowxqvaq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bfinsjpb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqxvibw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lkssrsmf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xhttloqb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2safghkxr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2yugroukc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2udruxsph.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2famaaidm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlxlrjx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ooskpuuw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpakkqpr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qigdlppg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpcgnju.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfcxrgj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgfacec.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2earttnzb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpfcgnq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwhvaib.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfpqqvr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2scofmmru.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2chzixpia.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzcprfw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2trqncjbk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmxnlvw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbldqvy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2veeguxkx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aksijejt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vplobtti.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpyccus.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyvalaa.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aldkpfzh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hequhaqo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pymimgdy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2niywsmiz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dttrydfa.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2adiktywc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2natkkgnc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gzstumil.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxvskix.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrpqnlm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqykdns.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2npgtbhrz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzvtlsd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyxkhag.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2buuytdcp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrciwlno.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gjypkrrj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2akecbadl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vknpvgge.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmrgelo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2suzuolyk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaczisrx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fyutoagc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxkheuh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lbofmxgd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvewglrl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jczkafmz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgtwves.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrfgmrn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dceiyxzw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hocvhjvk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnwuwxq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsqoaaf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2itnsnijx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lswgewvx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2aldyzduq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxauwbfz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oubfvtbs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2craaleic.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2irrrbicg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vgevmsgh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxcolby.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdysrkq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhsjrna.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqnywco.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dttemwpl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2astudieq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhtbrkv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2veyyhasu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2grnzyndr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nlolcawo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yedghuzh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuawusp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlstoyf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gywztgvz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdjxbbu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuciqoh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrnmumv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxouruq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmamanq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2semdluix.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxftktq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzsnfsd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbozgww.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2urizzvbq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrpegkw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtogsnx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtxqmlm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kenymacv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2liahqucr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvuiqlh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tayibjdv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxrlfph.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mftyttao.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgvxlkm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2suywaqpw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2oruojenw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbmygxg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2htkmayhh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2inezwcyq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2albswdtf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yixhjbci.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uifydaqc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ndygvzfc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmhqxvz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiisvdk.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvkkoun.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jihkjxwf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzbjdvh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pewhraku.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcexcqn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jubzyzlj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcjpalx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtiqtnq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvhayjb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2obfkrutr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfjbpwe.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjbayhe.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkmvngb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdcjwcs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhtodmf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sluvrmum.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoletdpq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzxaegu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxvomlk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsjaafy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2csmzyjfu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qryqshue.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbafvcu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tywfbefy.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgicefp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dviguoks.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gsasgmna.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjamauo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sibxoepx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2llikbxul.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmcgvkh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgjjyhv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2iaylcrol.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrnochv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iitqjdwi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhddndx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbjxwrl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmcicgl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lfusdaik.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjsnhjv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpuxsmh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zanexxgv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fninrrsz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhomiey.html


<!-- 参考信息 -->