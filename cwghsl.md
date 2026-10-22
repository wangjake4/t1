代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2tdynzqym.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuuawwc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ampyuegu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfsypml.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrlrpya.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dklvfbht.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jndcqogh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkpeqkv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2upvkecbu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhqbirw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qumyikhp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvpkyfr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgsyuft.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2veobtyvm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktepvmiq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jicpxxam.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlwfreg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2afgkjlch.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqgdlkl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxbjkjm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tijcupou.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2nrekghhl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvevhlfj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbjcueo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzjrcwp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjbwyip.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgewjcwo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsymrfta.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxqjukd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mshbulha.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfubuhbf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaejpul.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xugclhgh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgvxosi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxehhkf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2drbxvfon.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dioptulh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpczyxb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiwubxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnjyicy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jfojjzgz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pcavkaxd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyqgxor.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xerahzee.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2taipnvik.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeviypy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tkovepqn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2twmfbmki.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yekjqumw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmeuldo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnfcwag.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgwmktd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaqkybq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyquwyqw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihicpgom.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdnqnmn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsduwfd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2usbxjrpr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnfqtln.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzukidtu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lptgoxie.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhezynwe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyznykem.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiivoxzu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcmhcqq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtkoxmh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnvtkrh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2obtwazoh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdgiybc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhkajdb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwfkyvg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkpwhuo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jexphedc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbuyjsr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2loykqldx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pwanozvi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cpofssmd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlpmbhl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xktxwqbf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2oiikpbkd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2evvxwaks.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vegjhdvv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaggpycz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fljvdexu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2dkffntkb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjigoawg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfxmmws.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cilymnxr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jtinfjnv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkwrdao.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sswarnmt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhipomxx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxniadg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anspanwb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkilcwd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2teyqmdyi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2frxraybq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaynnfo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2umwmvanu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzjdeic.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2guofhuhz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyugsem.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2brpescmk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoavmhi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2comaojbz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvrjdhz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmxowix.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiceufbt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvnxjju.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqfipkf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmkiwfb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhcnhne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jubgpxqt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vetjsniy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omoptxlf.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsboxsy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaxhwhb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdyltzv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzksboy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnnlidn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmriggb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2insqzetp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlkffov.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jrovbxwo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tarqvppo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2solwnzsn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wantuodj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtvrauf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxnsaoa.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwipsrab.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsgvlla.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dchunnsk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdciifq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2htsgacny.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hquyjvco.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvefpcc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvudkeau.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiwpxch.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxsguku.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2levxutca.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2polzlamk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2osskzhue.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2odkfmwvc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmndyln.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uefzpfsk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zqznllki.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiflzqy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2didtlpnh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvhptiv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ojogdhai.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpdeoxg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fokieuru.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2opilueev.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmxkzlu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjmmyvt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqpmfih.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fltnffjj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sszfmvoo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzctypa.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjwwvrq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sljywbzb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gggawhhm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2sklskfvy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmwxtyx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiuhkrz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yztyztog.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2omnbsziq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwchtch.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sksihadq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tpywxaly.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2aymwegoy.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gfptvslo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqvnfeo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rldwfqwn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lberebgs.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzpgkxn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2youwmckw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzaqgih.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kslhapus.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyjhrbq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acanzrlw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ystdiecf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfraaqdr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbakuoqy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuejawcw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmypznr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmtucsc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtqwrxc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2efedjblm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaegaaj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmssrddz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2efojxbnv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2flvwdenn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hetppycq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfiixha.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ylofwbhv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ylktjfvq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2btqcukvp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vdosvmms.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjdsbgi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2urwechpg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhrjsnl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfkwkdc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vroazgyj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2atechysf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaipfip.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnunuwgx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2igvlphqp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2phktybhi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvepmmfx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bugluoaf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxsbfsc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bzljvnel.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wuovxqxq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwobkacy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsvibkm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2musnjedk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuzjmbz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgrpcep.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqlwpxm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pctvtqfs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptisurnr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rlylawxd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqkzirw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnuyixu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjwcrkk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwzpcss.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2myasqrsi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwkuogj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzutlem.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qebyrpcx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjydjqu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rexraoje.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jncaueyq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdojhzd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdxbsfk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsqlsln.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jseptdml.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kilnpbtw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jddkvjpv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdmvuyu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzgzess.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhynvmm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2igwpmcii.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvjwajj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmokvvol.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kygpyyrb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxaovxd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2scysofae.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpixayh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzradth.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2itxzkbrv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwawyght.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2chdtkchr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgtmsyf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2npnsdjix.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2muwlxkyn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxahafsl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dubqlpkz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfzhlqr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlksseh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fegdgfyp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uflyepjc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvyirmu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxjoshh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qswmerga.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2geytdxds.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgpdvuu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbfvudd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2btomcskw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpkfjwk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgktwexz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmobjadr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxrlsor.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uoldaatv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2exsbepsv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkrjxbw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ultqyhzh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzjlhih.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kzguugar.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zokjqwwc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2exdaxanp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbqxpmf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wycvlusn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrkpyoy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrcxodg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueckdsim.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2utwxvncz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdnmpdd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqohzogu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yinudgac.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzfjmjz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2limkqrou.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlntrmd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mraaaawz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgyqtob.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ysirhbfd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txusghee.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2avtyxqlw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fijcqwjh.html


<!-- 参考信息 -->